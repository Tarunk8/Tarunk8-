# To check the nodes and pods RAM-CPU resources utiliozation 

error: Metrics API not available
means your cluster doesn’t have the Metrics Server running, or it’s misconfigured. The kubectl top command depends on the metrics-server API to fetch CPU/memory usage.

✅ Fix: Install Metrics Server
Download the Metrics Server manifest (recommended YAML from Kubernetes SIGs):

kubectl apply -f https://github.com/kubernetes-sigs/metrics-server/releases/latest/download/components.yaml

Patch the deployment (common issue on bare-metal / AWS EC2 / labs: TLS verification problems).
Edit the deployment:

kubectl -n kube-system edit deployment metrics-server

Under spec.template.spec.containers.args, add:

- --kubelet-insecure-tls
- --kubelet-preferred-address-types=InternalIP


Or patch it quickly:

kubectl -n kube-system patch deployment metrics-server \
  --type='json' -p='[{"op":"add","path":"/spec/template/spec/containers/0/args/-","value":"--kubelet-insecure-tls"}]'

  
Verify that Metrics Server is running:

kubectl get pods -n kube-system | grep metrics-server

You should see something like:

metrics-server-6b87654c8b-xxxxx   1/1   Running   0   1m
Wait a minute (it takes ~1–2 min for metrics to start aggregating).

Run again:

kubectl top nodes
kubectl top pods

