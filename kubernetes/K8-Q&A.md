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
 - 
 ## Cluster IP mode:-
  In Kubernetes, ClusterIP is the default service type that provides an internal IP address (cluster-internal) for a Service, 
  which is accessible only within the cluster. This allows different components within the cluster (like Pods)
  to communicate with each other without exposing the service to the external world.
  
 ## Node port mode:-
  In Kubernetes, NodePort is a service type that exposes an application running in a cluster to the external world 
  by opening a specific port on each node of the cluster. This allows external traffic to access the service via the 
  node's IP address and the designated port.
  
 ##  Loadbalancer type mode:-
  In Kubernetes, the LoadBalancer service type is used to expose an application to external clients
  via a cloud provider's load balancer. This type automatically provisions a load balancer 
  (e.g., AWS ELB, GCP Load Balancer, Azure Load Balancer) that distributes incoming traffic to the 
  backend Pods running in the cluster.
 # What is the differnece between node port and loadbalancer type service.
 - lets asume that my node is 172.31.31.4 kubernetes associate, service get associated with node port.
 - it should be 172.31.31.4:9000 this would be node port type.
 - advantage is to access the node to application.
# what is ingress in kubernetes.
- you can define a traffic rule to the kubermnetes cluster or your kubernets application
# what is the role of kubelet
- kubelet is basically responsible for running container in your pod
- whenever you create a pod in kubernetes,so kublet basically talk to the container run time.
- and it make sure the container running in the kubernetes cluster, this is the responsibnle for kublet.
# Kubernetes Architecture
- Inside the kubertnetes cluster we have 2 types of node one is Master nodes and 2nd is worker node
- A master node controls the cluster and manages its resources,
- while worker nodes execute containerized application and tasks.

## Worker nodes:-

Cubelet
Cubeproxy                                    
Container run time

- Inside worker node something componenet called as pod 
- PODs are smallest deployable unit in the kubernetes tester and the POD can hold opne or more container.
- A single container have one or more than one pod or it can have a single pod as well.
- Deploy and manage pods iniside this worker node we have an agent named as cublet 
- this cublet agent is running on all worker node and gets information form ther master node to decide where should be the pod running and how to manage it.
- along with this for a worker machine to create and manage containers we have to have a container run time interface or software like docker.
- so worker machine will also contain CRI or container Endtime interface such as docker here
- Also to enable the communication between these two ports or to make these pods or application accessible to the end user.
- we have another networking component in the worker node is know as cube proxy
- Cube proxy is used for pod to pod communication also for load balancing service proxy to kae your application accessible to th end user.
- So these are different components inside the worker node you have cube proxy for port-to-port communication and expose your application you have container runtime interface to create and delete.

- containers you have cublet an agent that is running on every worker node. which get information from master node
- and handle the workloads inside the worker node

## Master Node:-

Kube API
Scheduler
Control Manager
ETCD data base


- The difference component inside the master nodes, so Master node or control plane has four very important components 
- that are responsible manage everything inside the cluster
- The first component is the kube api server, this kube API server is like entry point for everything you do inside the cluster.
- so lets say you a devops engineer and you want to create a new pod or may be delete a pod or just get the sattus.
- If you want to do  anything inside cluster you have to talk to the cube API server.
- to talk to cube API server either by running command using #cubectl command line tools either using\
- Or kubernetes dashboard or may be using sdkd or anything so you will talk to the cube API server.
- cube API servre will validate if the request is OK if the user is authenticated or not and if it works then it will get the information from the other components.
- Next master node component is called Scheduler.
- scheduler is used to assign pods to the worker nodes let's you made a request to the API server to create a new POD.
- Once the pod is decided by scheduler, scheduler give the information to the cube API server 
- cube API server give the information to the cublet running on that perticular node and thus it creates the new pod on the worker node.
- So based on the resource capacity all the manifest file that you have defined for your cluster.
- Now what if there is an issue inside the cluster or one of these ports shows an error or gets deleted 
- that when the kubernetes master nodes component comes into play 
- so next kubernetes compnent is the controller manager controller manager is used to monitor the entire cluster and it makes sure that everything you have defined inside your manifest file.
- Controller manager is used to monitor and make sure everything is working as you have defined 
- It does that by compairing the desire state with the actual state of the cluster 

- ETCD
- where is the cluster information or cluster data stored it is stored inside the next master node component 
- which is ETCD
# what is docker and kubernetes 
- docker is a container platform where is kubernetes is orchestration platform'
# What is Auto healing in docker kubernetes.
  - Auto healing is a behaviour where without user manual intervantion your container should start by itself.
# What is Auto scalling 
  - Replica set is a new name and replication controller is a old name.
  - Kubernates also support Horizontal pod autoscaller
  - CNCF is the community who conteniously developing the kubernetes.
# difference between kubernetes and EKS
- In  kubernetes you need to manage the cluster in kubernets, you have to create and maintain.
- In EKS amazon will provide the support for kubernetes cluster. that is the only differnece betweek kubernetes and EKS.
# What is the use of KOPS in kubernetes
- KOPS is nothing but kubernetes Operation
- Installation, upgradation, deletion the life cicle of management is managed by KOPS
- Auto scalling  - it automatically scale update the pod and scale down the pod.
- Auto healing  - it automatically up the server without human intervantion
# How do you secure some Important file and credentials in eks..






































