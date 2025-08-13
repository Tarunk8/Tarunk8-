# What si the difference Docker and Kubernetes
 - Basically docker building in and runnning single container
 - where as kubernetes is a system, its a group of vurtual machine.
# What are the main components of kubernetes architure ?
  - There are lots of component in kubernetes
  - In kubernetes we have two major things one is Controlplane or master and other one is the node.
  - Fastly that component run on controlplane are cube API server, its responsible for everything.
  -  Then ETCD that kubernetesd store the object.
  - then schedule, its take care of the scheduling of POD in kubernetes.
  - then controller manager so contraoller manager is responisble for the contraller in kubernetes.
  - then we have the cloud controller manager , these have the component run on the controlplane.
  - then kubelet is the responsible for running containers in a pod.
  - then container run time, so kubernets support multiple run time like docker, continity. creo
  - which are responsible for running the container again.
# What are the main difference between the Docker swarm and kubernetes.
  - Both of them are container orchestration evironment, one is designed by Docker and anothe ris designed by google, which is kubernetes.
  - Advantage of kubernetes is the , the scalability of kubernetes , configure lots of monitoring with kubernetes.
  - Kubernetes have something costumised resource defination with which we can do loadbalancing and advance loadbalancing.
  - kubernaties also has support for integrating ith like the API gatewy.
  - so ovaral its a complete production grid system, its a a greate comunity also the lots of company contributing on keubernetes.
  - so i dont say that docker not but kubernetes is the big dimmand.
# What is the differnece between Docker container and kubernetes POD
 - Kubernetes POD is call one or a group of container, all the container deployed in a POD,
 - they can have a share storage, they share the network resources, its also have the specification how the container have to be run.
 -  what port is ths to bind the host, what volume it has to use, the same way you have to put in kubernets but through yaml file.
# What is the differnece between kubernetes deployment, statefulset and daemmonset
-  3 types of deployment
-  statefulset is something which is used for maintaining state full application.
- If application is gose down or again came up with the same data or it has used a specific volume. is called statefulset.
  
- Daemonset is basically a controller typically run on all the nodes on kubernetes cluster.
- daemonset has configured each and every nodes of the cluster, that has to be monitor the nodes of the kubernetes clusetr.
-  it has to check health of every nodes, is such case that you have daemonset.
# What is the role of kube proxy
-  Kube proxy basically take care of Networking in kubernetes.
-  It can be configured in multiple ways the main thing is Iptables, whenever you deploy container or pod.
- then iptables get update and basically kube proxy take care of this task.
- Kube proxy is the one basically that key component for handling the comunnication in kubernetes.
# What are the different types of services within kubernetes
 - In a kubernetes the service can be implemented in multiple ways, the common servuces are in kubernetes 
 -  Cluster ip mode, node port mode & Loadbalancer type mode.
 - so these are the most commonly used service within kubernetes. 
  Cluster IP mode:-
  In Kubernetes, ClusterIP is the default service type that provides an internal IP address (cluster-internal) for a Service, 
  which is accessible only within the cluster. This allows different components within the cluster (like Pods)
  to communicate with each other without exposing the service to the external world.
  
  Node port mode:-
  In Kubernetes, NodePort is a service type that exposes an application running in a cluster to the external world 
  by opening a specific port on each node of the cluster. This allows external traffic to access the service via the 
  node's IP address and the designated port.
  
  Loadbalancer type mode:-
  In Kubernetes, the LoadBalancer service type is used to expose an application to external clients
  via a cloud provider's load balancer. This type automatically provisions a load balancer 
  (e.g., AWS ELB, GCP Load Balancer, Azure Load Balancer) that distributes incoming traffic to the 
  backend Pods running in the cluster.




















