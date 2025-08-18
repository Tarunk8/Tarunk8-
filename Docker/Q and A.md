#	What Docker technologies are available to support communication between containers?
	• Docker connect and bridge networks
	• Docker linking and bridge networks (Ans)
	• Docker connect and alias networks
	• None of these
#	Bridge networks can be defined in Docker Compose files.
	• False
	• True (Ans)
#	What command can be run to download an image from Docker Hub?
	• docker images
	• docker rmi [image name]
	• docker pull [image name] (Ans)
	• docker ps -a
#	Docker Kitematic can ONLY be used to download Docker images.
	• False (Ans)
	• True
#	Docker Kitematic provides a way to visually search for images hosted on __?
	• VirtualBox
	• Docker Hub (Ans)
	• Docker Client
	• Docker Machine
#	What syntax can be used to create a volume that Docker manages?
	• docker run -v /var/www imageName (Ans)
	• docker run -vol /temp:/var/temp imageName
	• docker run -v /temp:/var/temp imageName
#	Which of the following options can be used in a Docker Compose file?
	• env_file
	• container_name
	• All of these (Ans)
	• networks
#	Environment variables can be defined in Docker Compose files.
#	What command can be used to “link” a command terminal window to a Docker machine?
	• docker-machine env [machine name](Ans)
	• docker rm [machine name]
	• docker env [machine name]
	• docker-machine environment [machine name]
#	Which of the following statements accurately describe a Docker volume?
	• Can be shared and reused among containers
	• Persisted even after a container is deleted
	• Are not affected by updates to images
	• Special type of directory in a container
#	What key concepts does Docker rely on?
	• Virtual machines and LXC
	• Images and containers (Ans)
	• Images and archives
	• Images and virtual machines
#	What command-line switches are used with legacy linking?
	• –net and –name
	• –link and –name (Ans)
	• –com and –name
	• –run and –link
#	Docker volumes are persisted even after a container is deleted.
#	What tool can be used to visually work with images and containers?
	• Docker Engine
	• Docker Kitematic (Ans)
#	Which of the following tasks can Docker Cloud perform?
	• Create nodes
	• Create stacks
	• Start and stop services
#	Dockerfile contains binary instructions.
#	What command-line switch can be used to define a custom Dockerfile file name (such as node.dockerfile) when building a custom image?
	• -t
	• -customfile
	• -f (Ans)
	• -v
#	What Docker Client command can be used to create a container network?
	• docker createNetwork
	• docker build network
	• docker network create (Ans)
	• docker ps network
#	What syntax can be used to delete a Docker volume and a container?
	• docker rm -rv containerName
	• docker rm volume containerName
	• docker rm -v containerName (Ans)
	• docker rm remove-volume containerName
#	What task does Docker Machine perform?
	• Create and manage Docker images
	• Find and install Docker images
	• Create and manage containers
	• All of these
	• Create and manage local machines (Ans)
#	Docker Cloud provides a browser-based terminal for services.
#	Docker Toolbox can only be installed and run on Linux.
#	What Docker Compose command can be used to create service images?
	• docker compose
	• docker-compose create
	• docker-compose make
	• docker-compose build (Ans)
#	What syntax can be used to publish an image to Docker Hub?
	• docker create /imageName
	• docker publish /imageName
	• docker move /imageName
	• docker push /imageName (Ans)
#	What benefits do container networks offer?
	• Allow local containers to communicate with external host containers
	• Allow local containers to communicate directly with host processes
	• Allow containers to communicate with each other in an isolated network (Ans)
#	Docker containers can be started and stopped.
#	Docker Images consist of read-only layers.
#	Which of the following best decribes a Docker Image?
	• A read-write template for starting one or more containers
	• A point-in-time snapshot of a container used for backups
	• A data volume that can be mounted inside of a container
	• A read-only template for starting one or more containers (Ans)
#	You have two services running on a Swarm, but they cannot find each other by name. Which of the following could be the reason why?
	• They are on different overlay networks (Ans)
	• They were not manually registered with the Swarm DNS when they were created
	• Service discovery only works on bridge/NAT networks
	• You did not create the Swarm DNS
#	Which of the following is a loose definition of a Docker container?
	• A VM running a shared kernel with resource limits applied
	• A unikernel running on a hypervisor with resource limits applied
	• An isolated area of an Operating System with resource limits applied (Ans)
#	What will happen if you start a new container or service and specify a volume that does not currently exist?
	• You will be prompted to create the new volume
	• The command will complete but the container/service will fail to start
	• The command will fail
	• Docker will create the volume for you (Ans)
	What are the base requirements to be able to use Docker Secrets?
	• Swarm mode and an external CA
	• Swarm mode and self-encrypting disks for the cluster store
	• Docker in Swarm mode (Ans)
	• Docker
#	Which of the following are top-level keys in a stack file (Compose v3 file)?
	• Version, deployments, networks, volumes
	• Version and services
	• Version, services, networks, volumes (Ans)
	• Services, pods, networks, volumes
#	Which of the following is an advantage of Multi-stage Builds?
	• Multi-platform images
	• Better image documentation
	• Faster image builds
	• Smaller images (Ans)
#	Which of the following is a recommended number of Swarm managers for high availability?
	• 4
	• 3 (Ans)
	• 2
#	Which of the following best describes a Bridge (NAT on Windows) network in Docker?
	• Token-ring
	• Multi-host overlay network
	• A single-host network (Ans)
#	How does the HRM know how to route traffic to the correct service?
	• iptables rules
	• It inspects HTTP host headers (Ans)
	• DNS labels
	• Custom load balancer rules
#	By default, where are Docker daemon logs sent to on a Linux system running systemd?
	• syslog
	• The Linux event viewer
	• journald (Ans)
#	Which of the following is a major goal of Docker volumes?
	• Data replication
	• Data encryption at-rest
	• Object storage
	• Persistent data (Ans)
	• RAID
#	Which are the two major kernel building blocks that containers are built from?
	• Capabilities and seccomp
	• Namespaces and kernels
	• Namespaces and control groups (Ans)
	• Capabilities and control groups
#	Which of the following is a recommended best practice?
	• Keep your images small (Ans)
	• Never use the latest image in a repo
	• Use large images containing lots of tools
	• Only use Docker Hub
#	Where are Secrets mounted on Linux-based Docker hosts?
	• An encrypted volume mounted at /run/secrets
	• An in memory (tempfs) volume at /run/secrets (Ans)
	• initramfs
	• Solid state volume
#	How are Docker Secrets created on the command line?
	• docker secret create (Ans)
	• docker swarm secret create
	• They cannot be created on the command line
#	Which of the following is the best high-level description of a Swarm?
	• A secure cluster of Docker nodes (Ans)
	• A tightly-coupled cluster of Docker container
	• A secure cluster of Docker containers
	• I tightly-coupled cluster of Linux nodes
#	What is the atomic unit of scheduling in Docker?
	• The service
	• The container (Ans)
	• The pod
	• The stack
	• The swarm
#	Which of the following commands lets you deploy a Docker Stack called stack1 using a Compose file called myapp.yml?
	• docker service deploy -c myapp.yml stack1
	• docker stack deploy -c myapp.yml stack1 (Ans)
	• docker stack deploy stack1 myapp.yml
	• docker service deploy stack1 myapp.yml
	..-33/> 
#	Which of the following are true about Docker volumes?
	• They must exist on a SAN or NAS
	• They are decoupled from containers (Ans)
	• They are higher performance than graph driver (snapshotter) storage
	• They are RAID protected
#	Which of the following commands will list all of the Docker volumes on a particular Docker host?
	• docker system info | grep volumes
	• docker node volumes
	• docker volume ls (Ans)
#	Which of the following can be a Docker Secret?
	• Just SSH keys
	• Just .pem and .crt files
	• Passwords less than 100KB
	• Passwords, SSH keys, service ports and names (Ans)
#	Which component of the Docker Engine interfaces with the kernel primitives that are used to build containers?
	• The OCI layer (runc) (Ans)
	• The REST API
	• The Docker daemon
#	What currently replaces containerd and the OCI layer in the Docker Engine on the Windows platform?
	• The smss process
	• The Compute Services Layer (Ans)
	• The Windows Registry
	• Hyper-V
#	How do you tell Docker on Windows to deploy a container as a Hyper-V container?
	• Build the image with the isolation=hyperv tag
	• Use the hyper-v container run command instead of the docker container run command
	• Pass the docker container run command the --isolation=hyperv switch (Ans)
	What are some of the features of Docker Universal Control Plane?
	• Docker Content Trust (DCT)
	• Management of containers and virtual machines via a single web UI
	• RBAC, image scanning, image promotions (Ans)
#	Which of the following explains the relationship between a Docker image and a Docker container?
	• A Docker container is two or more images that share a common execution environment
	• A Docker container is used to start a Docker image
	• A Docker container is a collection of image layers
	• A Docker container is a running instance of an image (Ans)
#	Which of the following commands will initialize a new Swarm on the current node?
	• docker swarm init (Ans)
	• docker swarm create
	• docker init
#	Which Dockerfile instruction sets the default program for a container to run, but can be overridden on the CLI at runtime?
	• ENTRYPOINT
	• RUN
	• CMD (Ans)
#	Where do you specify the default logging driver for all containers on a particular Docker host?
	• logs.json
	• daemon.json
	• The Registry
	• config.json (Ans)
#	What underlying Windows technology, used to build containers, is broadly referred to as control groups?
	• Active Directory
	• Job objects (Ans)
#	Which of the following Docker Engine components is part of the Open Container Initiative (OCI)?
	• runc (Ans)
	• containerd
	• The API
	• The daemon
#	Which component of the Docker Engine implements the Docker API?
	• The Docker daemon (Ans)
	• The Docker client
	• The OCI layer
#	Which of the following is needed to deploy a Docker Stack?
	• Compose v2 file format
	• Kubernetes
	• Compose v3 file format (Ans)
	• Docker Cloud
#	What is the name of the configuration file that describes how to build a new Docker image with your app-code inside?
	• dockerfile (Ans)
	• config.json
	• docker-file
	• dockerfile.json
#	Which of the following is the worst number of managers for high availability?
	• 1
	• 5
	• 2 (Ans)
	• 7
#	Which command can you use to get a shell session inside of a container?
	• docker container login
	• docker container exec (Ans)
	• docker container shell
	• docker container ssh
#	Which Docker EE technology performs layer-7 (application layer) load balancing?
	• The ingress network
	• The Service Mesh
	• The HTTP Routing Mesh (HRM) (Ans)
	..-32/> 
#	What is the preferred way to deploy and manage a Docker Stack?
	• The declarative way via config files (Ans)
	• The imperative way via commands
#	Which of the following Docker Engine component is a Cloud Native Computing Foundation (CNCF) project?
	• containerd (Ans)
	• The Docker Remote API
	• runc
#	Which components constitute the control plane aspects of a Docker UCP cluster?
	• UCP/Swarm minions
	• UCP/Swarm workers
	• UCP/Swarm managers (Ans)
#	Which key combination will disconnect your shell from an interactive container, and return you to the shell of your Docker host without killing the container?
	• Ctrl+Z
	• Ctrl+C
	• Ctrl+esc
	• Ctrl+P+Q (Ans)
#	Which of the following network types would you choose if you needed your containers to be first class on one of your existing VLANs?
	• Bridge
	• NAT
	• MACVLAN (Ans)
	• Overlay
#	What type of storage takes care of a containers union filesystem/union mount?
	• Graph driver (snapshotter) (Ans)
	• Volume data
	• Copy-on-write (CoW)
#	What happens to the data in a volume when the last container it was connected to is deleted?
	• The data remains intact (Ans)
	• The data is deleted along with the last container
#	How can you inspect the unencrypted contents of a Docker secret?
	• With the docker secret inspect command on the leader manager in a Swarm
	• You cannot (Ans)
	• With the docker secret inspect command
#	Which of the following describes how Docker manages a deployed stack?
	• It constantly monitors the state of the stack via reconciliation loops and makes sure actual-state and desired-state match (Ans)
	• Swarm checks the health of the stack every 60 seconds to make sure actual-state matches desired-state
	• Fire and forget. Once the stack is deployed, it must be monitored via external tools.
	What are some of the benefits Docker Trusted Registry (DTR) has over Docker Hub?
	• On premises, image promotions (Ans)
	• Public and private repos
	• Image scanning
#	Which Docker command lists all of the managers and workers in a Swarm?
	• docker swarm info
	• docker swarm nodes
	• docker node ls (Ans)
	• docker swarm ls
#	Which of the following is the default network a container will join of you don’t override with the –network flag?
	• MACVLAN
	• Bridge (Ans)
	• Wifi
#	Which two docker container run flags are commonly used to create a container you can log-on to and interact with?
	• -ahl
	• -it (Ans)
	• -ssh
	• -telnet
#	Which of the following describes data that we need to keep long-term?
	• Immutable
	• Persistent (Ans)
	• Ephemeral
	• Non-persistent
#	Where does a container’s graph driver storage usually exist?
	• /etc/docker (Linux) and C:\ProgramData\Docker\windowsfilter (Windows)
	• /var/lib/docker (Linux) and C:\ProgramData\Docker\windowsfilter (Windows) (Ans)
	• /var/run/docker (Linux) and C:\Program Files\Docker\windowsntfs (Windows)
#	Which of the following describe some of the OS-level constructs that each container gets?
	• Process trees, network stacks, and users (Ans)
	• Virtual CPU and virtual RAM
	• Kernel modes
	• Kernel rung buffers and syscall tables
#	How does the Docker Engine expose the Docker API?
	• As a versioned HTTP REST interface (Ans)
	• gRPC on a Unix socket
#	Which of the following describes a potential advantage a Hyper-V container has over a native Windows container?
	• You can run a different OS/kernel for each container (Ans)
	• They start faster
	• They implement open CNCF standards
	• You ran run more on a single Windows Docker host
#	Which of the following best describes a Docker UCP cluster?
	• A group of Swarm managers and Kubernetes minions
	• A cluster of Swarm-based manager and worker nodes (Ans)
#	What do Swarm managers and workers use their client certificates for?
	• Role authorization and cluster join token
	• Mutual authentication, role authorization, and transport encryption (Ans)
	• Transport encryption
	• Mutual authentication and transport encryption
#	How many processes does a Linux-based Docker container normally run?
	• One per image layer
	• One (Ans)
	• Two
#	How can you login to your local DTR so that you can push and pull images from it?
	• docker login (Ans)
	• dtr login
	• docker ucp login
#	How can you make a Swarm service accessible from all nodes in a Swarm on the same port?
	• Create enough replicas so that there is one on each Swarm node
	• Map the service to a port with the -p flag (Ans)
	• Create a global service
	• Create an external load balancer
	..-31/> 
	Images contain the entire user space, in other words the entire file system for a container. How is this not horribly inefficient in terms of disk space?
	• Images are layered and common layers are shared (Ans)
	• Images use state of the art compression to reduce the disk space requirements
	• You only pull down the image layers that you need to run your application
	• Image layers are highly optimized to reduce unnecessary components.
	Say you have the following output from docker ps:
	57cf9c689955 docs/docker.github.io “/bin/sh -c ‘jekyll s” About an hour ago Exited (137) About an hour ago grave_tesla
#	Which of the following does not work as a container identifier (CID) when running a command like the following?
#	docker stop
#	docker start
#	docker rm
	• 57
	• 57cf9c689955
	• grave_tesla
	• gra (Ans)
#	How do you terminate software running in a container?
	• docker stop (Ans)
	• docker rm
	• docker terminate
	• docker kill
#	Which of the following Windows Features do you need to use Windows Server containers?
	• Containers (Ans)
	• Hyper-V and Containers
#	Which of the following stops all running containers?
	• docker stop $(docker ps -q) (Ans)
	• docker rmi $(docker ps -q)
	• docker halt $(docker ps -q)
	• docker rm -f $(docker ps -q)
#	Where do dangling volumes typically come from?
	• Containers that we manually mount managed volumes into
	• Images that have a VOLUME instruction (Ans)
	• Containers that we bind-mount host volumes into
	• Every container that is created has a volume created as well
#	Where are created, modified, and deleted files stored in a container?
	• In a volume mounted in the container
	• In an R/W container layer (Ans)
	• In the bottom most layer from the image it was created from
	• In the top most layer from the image it was created from
	In the past, to launch an installed application, we would run an executable file. How does Docker run software?
	• Pull a container
	• Install a container
	• Runs an executable (Ans)
	• Create a container
#	How are image layers coalesced to form a container’s file system?
	• Files are copied out of layers when creating a container into a union mount point
	• A union file system is used to create a union mount point (Ans)
	• Container file systems exist in memory, in a RAM disk, aggregated from image layers
#	How can you connect a container to a user defined network?
	• –udf NETWORK_NAME
	• docker connect
	• –net NETWORK_NAME (Ans)
	• docker attach
	• docker disconnect
	In traditional software management, we uninstall software to remove it from a machine, what’s the equivalent with Docker?
	• Remove an image
	• Uninstall a container
	• Remove a container (Ans)
	• Stop an image
	• Stop a container
#	When you extract an image with docker save what is inside the tar archive?
	• The contents of all layers flattened into one folder
	• A folder for the entire image and also a layers folder with each layer nested inside
	• A folder for each image layer (Ans)
	The docker history command shows output similar to which of the following?
	• Dockerfile (Ans)
	• docker ps
	• docker-compose.yml
	• docker layers
#	What is the role of Docker images?
	• Used to execute code at runtime
	• Provides virtualization functionality across environments
	• Acts as a blueprint or template that is used to create containers (Ans)
#	What command can be used to start a container?
	• docker run [image name](Ans)
	• docker go [image name]
	• docker rm [image name]
#	Which of the following tasks can Docker Compose perform?
	• View service logs
	• Build services
	• Start and stop containers
	Services can be organized into __ with Docker Cloud.
	• groups
	• stacks (Ans)
	• roles
	• zones
#	What Docker Compose command can be used to start multiple service containers?
	• docker-compose up (Ans)
	• docker-compose start
	• docker run
#	A Docker _ has a “thin R/W layer.”
	• File
	• Image
	• Container (Ans)
#	Each instruction in a Dockerfile creates an intermediate container as the image is built.
#	What syntax can be used to convert a Dockerfile into an Image?
	• docker create -t /tagName .
	• docker run -t /tagName .
	• docker run -t /tagName . (Ans)
	• docker convert -t /tagName .
#	Which of the following tools are included in Docker Toolbox?
	• Docker Kitematic
	..-30/> 
#	With Docker for Windows, what container types can you run?
	• Only Windows
	• Windows and macOS
	• Windows and Linux (Ans)
	• Only Linux
#	Which of the following is an accurate statement about processes in a container?
	• Container processes are different from machine processes
	• Container processes are regular machine processes (Ans)
	• Container processes run in a VM
	• Container processes do not show in the Windows Task Manager
#	What does docker-compose help us avoid? Excessive calls to ________?
	• docker stop
	• docker build
	• docker run (Ans)
	• docker pull
#	What is a Docker volume?
	• A directory that bypasses the container’s union file system (Ans)
	• The union file system for a container
	• A directory that mounts remote files
	• The host file system
#	How can you get files out of a container onto the host? Assume a process in a container is writing files, like ffmpeg saving the contents of a converted video.
#	Where do you write this data?
	• Write files to a volume mounted from the host (Ans)
	• Write files to the default host file system mounts at C:\host or /mnt/host on Linux
	• Write files to network shares
	• Write files to the container file system, all writes are automatically copied to the host file system in the same folder
	On Windows 10 which container types can you run?
	• Hyper-V Containers (Ans)
	• Windows 10 Containers
	• Both Hyper-V and Windows Server Containers
	• Windows Server Containers
	In the past, we often download applications packaged in a zip file, or MSI, or some other package format. With Docker, what format is used to distribute software?
	• Image (Ans)
	• DMG
	• ISO
	• Zip file
	• VHD
#	Which of the following allows you to add files from the host to a running container?
	• docker cp (Ans)
	• docker volumes
	• docker add
	• docker commit
	• docker share
#	When executing the command “docker pull microsoft/aspnet:4.6.2” what is the “4.6.2” piece called?
	• Repository
	• Registry
	• Tag (Ans)
	• User
#	What’s a good analogy for docker stop?
	• Uninstalls the container
	• Stops a single process in a container
	• Stops the processes running in a container (Ans)
	• Removes the container
	To get Ctrl+C to work to kill a container, what should you pass when running the container?
	• –name
	• -p
	• -d
#	How is it possible that we can run a command prompt in a container created from the microsoft/dotnet image?
	• It’s not possible to run anything but the one application provided by the image
	• Common OS applications like CMD.exe are mapped into the container by default
	• The image also provides CMD.exe (Ans)
	• We have access to all apps on the machine in addition to those in the container
#	What format does Docker use to export images?
	• tar (Ans)
	• dmg
	• zip
	• iso
	On Windows Server 2016 which container types can you run?
	• Both Hyper-V and Windows Server Containers (Ans)
	• Hyper-V Containers
#	Where do dangling images typically come from?
	• When you stop many of the same containers
	• When running lots of containers from the same image
	• When building custom docker images (Ans)
	• When downloading images from Docker hub
#	Why do containers exist?
	• To make it easier to use virtual machines
	• A replacement for monolithic operating systems
	• A replacement for virtual machines
	• To make it easier to use software (Ans)
#	What’s a good analogy for docker exec?
	• Allows you to run additional processes in new containers
	• It’s similar to installing software
	• Allows you to run additional processes in a container (Ans)
	• Allows you to run additional processes outside a container
#	What is a repository on Docker Hub?
	• An image ta
	• A user account
	• A single image
	• A collection of images (Ans)
#	What is used to resolve ip addresses with the embedded DNS in user-defined networks? What value is pulled from the docker-compose.yml file?
	• DNS name
	• environment
	• Service name (Ans)
	• Image name
#	How can I run another process inside a running container?
	• docker start
	• docker exec (Ans)
	..-29/> 
#	What is a tag?
	• A reference to a registry
	• A reference to a repository
	• A reference to a specific image in a repository (Ans)
	• A reference to a specific image in a registry
#	Why are image layers read only?
	• So they can be compressed to reduce disk space
	• So we cannot write data inside a container
	• So they can be reused (Ans)
#	Which of the following container types doesn’t use namespace isolation?
	• Windows Server Container
	• Hyper-V Container (Ans)
	• Linux Container
#	Which of the following provides the initial container file system?
	• Volume(s)
	• Network drive
	• Host file system
#	Database data should be stored in:
	• Image layer
	• Volume (Ans)
	• Container Read/Write layer
	In the past, to find software, we often used standalone web sites hosted by the creator of the software. Now, with Docker, how do we discover software?
	• Package Managers
	• Still use standalone web sites
	• App Stores
	In the past, we usually downloaded software in some sort of package to install it, for example a zip file or MSI file. Now, with Docker, how do we download
	software?
	• docker pull (Ans)
	• docker download
#	When executing the command “docker pull microsoft/aspnet:4.6.2” what is the “microsoft” piece called?
	• User (Ans)
	• Tag
	On a computer, with either Linux or Windows installed, there’s a program that runs in a privileged mode that abstracts hardware and provides services to other
	processes. What is this program?
	• User space
	• Kernel
	• Kernel space (Ans)
	• Application
#	After stopping a container, how do you run the application in it again?
	• docker start (Ans)
	• docker restart
#	What’s the primary purpose of docker-compose?
	• Build containers, volumes, and networks (Ans)
	• Build images
	• Pull and push images
	• Cleanup containers.
	• Build containers
#	What does the -d in docker run -d nginx do?
	• Runs an attached container
	• Runs a container that will display output from the NGINX process in our console
	• Deletes the container when we stop the NGINX proces
	• Runs a detached container (Ans)
#	Where does the file system come from for a container?
	• From the machine the container is started on
	• From the image used to create the container (Ans)
	• From another special container called a parent container
	• From a remote network share hosted through Hyper-V
#	Which of the following allows you to share the host file system with a process in a container?
	• Network drive(s)
	• Image(s)
	• symlinks
	• Volume(s) (Ans)
#	How can you see the output of a process running in a detached container?
	• docker output
	• docker Is
	• docker run -it
	• docker exec -it
	• docker logs (Ans)
#	What does docker commit do?
	• Copies files into a container
	• Creates a container
	• Duplicates a container
	• Creates a snapshot of a running container for rolling back
	• Creates an image (Ans)
#	Which of the following is a good analogy for creating a container?
	• Installing software (Ans)
	• Downloading software
	• Extracting a zip file
	• Running software
#	How can processes in different containers talk to each other when using docker-compose?
	• Embedded DNS for Service Discovery (Ans)
	• Pass IP addresses in configuration files
	• Pass IP addresses in environment variables
	• Linking containers
#	What does an image contain?
	• The user space files (Ans)
	• Only an application’s files
	• Both the user and kernel space files
	• The kernel space files
	• The operating system
	Removing an image is akin to what in traditional software management?
	• Deleting an installer file or zip file (Ans)
	• Uninstalling an application
	• Restarting an application
	• Stopping an application
	..-28/> 
#	By default, what happens to a Docker Container when the process it is running exits?
	• The Container exits. (Ans)
	• The Container reboots and restarts the process.
	• The Container performs a crash dump.
	• The Container continues running in detached mode with a Bash prompt available.
#	Which of the following commands will install the Docker engine on a CentOS server?
	• yum install docker.io
	• apt-get install docker.io
	• yum install docker (Ans)
	• apt-get install docker
	In a default installation, how does the Docker daemon natively access features like kernel namespaces and cgroups?
	• via capabilities
	• via devicemapper
	• via LXC
	• via libcontainer (Ans)
#	How are comments added to a Dockerfile?
	• Any line starting with a # (Ans)
	• Any text following a #
	• Any text following //
	• Any line starting with //
#	Which Dockerfile Instruction must be the first Instruction in a Dockerfile?
	• MAINTAINER
	• A comment
	• FROM (Ans)
#	Which transient image layer exists below the rootfs while a container starts?
	• The datalink layer
	• Layer 1
	• Block aggregation layer
	• Bootfs (Ans)
#	Which Dockerfile instruction defines the base image to build from?
	• BASEIMAGE
	• BaseImage
	• BASE
#	At the time of recording the course, what is the default storage driver used by CentOS for Docker containers?
	• OverlayFS
	• NTFS.SYS
	• AUFS
	• devicemapper (Ans)
#	Which of the following is the correct way to name a Dockerfile?
	• DockerFile
	• DOCKERFILE
	• dockerfile
#	Which of the following is true about RUN Instructions in a Dockerfile?
	• All RUN lines are compiled down to a single RUN Instruction
	• Each Dockerfile can only contain one
	• Each new RUN line creates a new image layer (Ans)
	• RUN Instructions only work with containers that have elevated privileges
#	From a Docker Host, which command can we use to stop a container?
	• docker stp
	• docker halt
	• docker-stop
#	Which of the following is another term to describe container virtualization?
	• Storage virtualization
	• Hypervisor virtualization
	• OS level virtualization (Ans)
	• Software Defined Data Center
#	What is a dangling volume?
	• A volume created without a name
	• A volume that’s not associated with a container (Ans)
	• A volume that’s removed from a running container
	• The default volume for the container file system that’s unpacked from the image
#	What image type is blessed by both Docker and the people behind the software it contains?
	• Blessed
	• Official (Ans)
	• Trusted
	• Automated Build
#	What does docker history do?
	• Shows commands that we ran inside a given container
	• Shows image history (Ans)
	• Shows container history
	• Shows a diff of changes in the container layer
#	Why does Docker for Windows need Hyper-V?
	• To run windows containers inside a Windows Server VM and linux containers inside a linux VM
	• To run windows containers inside a Windows Server VM
	• To run linux containers inside a linux VM
	• To run linux containers inside a linux VM and Hyper-V windows containers (Ans)
	In the past we had to install software before we could run it. What is the equivalent step with Docker to be able to run software?
	• Run a container
	• Installs a container
	• Create a container (Ans)
	• Pulls a container
#	What docker command executes software?
#	When executing the command “docker pull microsoft/aspnet:4.6.2” what does “microsoft/aspnet:4.6.2” refer to?
#	When using docker-compose, by default, what network are linux containers connected to?
	• host
	• none
	• bridge
	• user defined network (Ans)
	..-27/> 
#	What Docker Client command can be used to convert a Dockerfile into an Image?
	• docker createimage
	• docker buildimage
	• docker build (Ans)
	• docker create
#	Which option can we pass to the Docker daemon to make it assign the Docker bridge a specific IP range?
	• –bip (Ans)
	• –network
	• –ip-range
	• –cidr
#	Which Dockerfile Instruction is the preferred instruction for setting the main process to run inside a container?
	• DEFAULT
	• ENTRYPOINT (Ans)
	• CMD
#	Which command shows us detailed container info including the containers PID within the Docker Hosts process tree?
	• docker config
	• docker detail
	• docker inspect (Ans)
	• docker pid
#	When using the ENTRYPOINT Instruction in a Dockerfile, how are CMD Instructions treated?
	• CMD Instructions are treated as arguments to the ENTRYPOINT Instruction (Ans)
	• CMD Instructions override ENTRYPOINT Instructions
	• ENTRYPOINT Instructions are ignored
	• CMD Instructions are ignored
#	Which Dockerfile Instruction do we use to install packages to our new Image?
	• FROM
	• RUN (Ans)
	• apt-get install
#	What is the name of the primary virtual Ethernet NIC inside of each Docker container?
	• veth0
	• eth1
	• veth1
	• eth0 (Ans)
#	Which Docker command lets us attach to a running container?
	• docker ssh
	• docker login
	• docker telnet
	• docker attach (Ans)
#	Which of the following docker run commands will start a Container based on an Ubuntu 14.04 Base Image?
	• docker run Ubuntu:14.04 ….
	• docker run ubuntu -v 14.04 …..
	• docker run ubuntu:14.04 …. (Ans)
	• docker run ubuntu –version=14.04 ….
#	Which of the following commands will install the Docker engine on an Ubuntu server?
	• cf install docker.io
	• rkt install docker
	• yum install docker
	• apt-get install docker.io (Ans)
	Virtual Machines are a form of what type of virtualization?
	• Container
	• Hypervisor (Ans)
	• VLAN
	• Mainframe
#	How do recipient containers learn about the networking config of source containers they are linked to?
	• By querying the Docker daemon
	• Via a sub-space secure channel to the source container
	• Environment variables + entries in the /etc/hosts file (Ans)
	• The /link file in the root filesystem of the container
#	Which of the following commands will show version information for the various installed Docker components?
	• docker version (Ans)
	• apt-get update
	• rkt version
#	Which Docker command builds a new image from a Dockerfile in the current directory?
	• docker build-image .
	• docker image .
	• docker build . (Ans)
#	What does pressing Control+P+Q inside of a container do?
	• Issues a print-screen of the current contents of the terminal window
	• Detaches the Docker Hosts terminal from the container (Ans)
	• Kills the container
	• Generates a stack trace of the container
#	Which Docker command shows running Docker Containers?
	• docker ps (Ans)
	• docker list containers
	• docker show containers
	• rkt ps
#	Which of the following is a major advantage of Containers over Virtual Machines?
	• Containers are more lightweight than Virtual Machines. (Ans)
	• Containers are encrypted by default.
	• A single Container can host more apps than a Virtual Machine.
	• Containers are cross-platform.
#	Which of the following is an advantage of Linking Containers when compared to exposing ports?
	• Linking containers is more efficient on memory.
	• Linking containers allow more active network connections.
	• Linking containers allows for faster container startup times.
	• Linking containers is considered more secure. (Ans)
#	What is the correct syntax to mount the /project/data directory from the Docker host into a directory called /data in a container?
	• docker run -v /data:/project/data
	• docker run -volumes-from /project/data:/data
	• docker run -v /project/data:/data (Ans)
	• docker run -volumes-from /data:/project/data
	..-26/> 
#	Docker works the same way as virtual machines.
	Setting up communications between multiple containers always requires multiple Docker run statements to be executed.
#	You’ve run the “docker ps” command but no containers are showing. Why?
	• You don’t have an image for the container.
	• All containers are stopped. (Ans)
	• All containers are running.
#	What options are available for getting source code into Docker Containers?
	• Create a custom docker image with the source code or create a data volume pointing to your dev machine (Ans)
	• Use the Dockerfile “embedcode” instruction
	• Create a custom container with the source code and use the “mount” command to point to your dev machine
	• docker-machine env [machine name] (Ans)
	VirtualBox is required to use Docker on Mac and Windows dev machines.
#	Which of the following use Docker’s layered file system?
	• Docker images only
	• Docker containers only
	• Docker images and containers (Ans)
	• docker build -t /tagName . (Ans)
	..-25/> 
#	How do you show all containers on a machine?
	• docker rmi -p
	• docker showAllContainers -a
	• docker ps -a (Ans)
	• docker-machine ps -a
#	What syntax can be used to create a volume that “hooks” to a source code folder on your machine?
	• docker run -v $(pwd):/app imageName (Ans)
	• docker run -vol /var/temp imageName
	• docker run -v /var/www imageName
#	What Docker command can be used to view information about a custom network?
	• docker network inspect (Ans)
	• docker network view
	• docker view network
	What cloud provider does Docker Compose support?
	• Amazon Web Services
	• Digital Ocean
	• Microsoft Azure
	• docker run [image name] (Ans)
#	Docker Cloud YAML files are identical to Docker Compose YAML files.
	Key benefits of Docker for web developers includes:
	• Setup a development environment quickly
	• Simplify working with multiple framework versions
	• Consistency between environments
	• Ship code faster
	..-24/> 
	• Namespaces and control groups
	• Capabilities and control groups (Ans)
#	Which of the following open-source tools is the underlying technology for Docker Swarm?
	• SwarmKit (Ans)
	• InfraKit
#	Docker UCP implements RBAC via Grants. Which of the following make up a Grant?
	• Subjects, roles, and nodes
	• Subjects, roles, and collections (Ans)
	• Roles and collections
#	Which of the following built-in Docker networks creates a single layer-2 container-only network across multiple Docker hosts that can be on different underlying networks?
	• Overlay (Ans)
#	Which Docker command shows the network ports that a container is exposed on?
	• docker container ports
	• docker port (Ans)
	• docker network –port
#	What happens when you perform a docker volume rm against a volume attached to a running container?
	• The command will fail (Ans)
	• The volume will be deleted
	• The volume and the container will be deleted
	• You will be asked to confirm the command
#	Which set of container-related Linux tools did Docker’s libcontainer replace?
	• LXD
	• libc
	• LXC (Ans)
#	How can you make a Docker Secret available to a standalone container (not a service replica)?
	• Make sure it us running on an overlay network
	• Make sure it is on a node running in Swarm mode
#	Which Docker technology allows you to manage an entire application comprising multiple Docker Services?
	• Service Mesh
	• Stacks (Ans)
	• Bundles
#	Which are the two major Docker container orchestrators?
	• Swarm and VMware vSphere
	• Swarm and Marathon
	• Swarm and Kubernetes (Ans)
	• Kubernetes and VMware vSphere
	..-23/> 
	..-22/> 
	• Compose v3 file format
	• Docker Cloud (Ans)
	• Token-ring (Ans)
	• A single-host network
	..-21/> 
#	What type of software deals with running (placement) applications on a given node in the cluster?
	• Placer
	• VM runtime
	• Container runtime
	• Provisioner
	• Scheduler (Ans)
#	What is the net effect of a separate PID namespace? Each process can have an entirely separate __ .
	• filesystem
	• network stack
	• hostname
	• list of processes (Ans)
#	How would you avoid port conflicts? Use separate _ namespaces per process.
	• mount
	• PID
	• network (Ans)
	• IPC
	• UTS
#	How would you avoid shared library conflicts between processes? Use separate _______ namespaces per process.
	• mount (Ans)
	• network
#	What is the net effect of a separate UTS namespace? Each process can have an entirely separate __________ .
	• list of processes
	• hostname (Ans)
	• IP address
#	What’s the benefit of a user namespace?
	• Provide each process with its own networking stack and IP addresses
	• Allow privileged operations on resources in the namespaces associated with a process but not system-wide (Ans)
	• Allow privileged operations on all system resources
	• Create users specific to only a given user namespace
	• Provide each process with its own filesystem
#	What does an app container run?
	• A single application (Ans)
	• Runs the container runtime
	• Runs the host OS init process
	• Runs an OS init process to emulate a VM
	What aspect of a scheduler handles app failure?
	• Load Balancing
	• Service Discovery
	• Enforce Desired State (Ans)
	• Scaler
#	What is a root namespace, i.e. a root network namespace?
	• A namespace for processes run by root, i.e. a network namespace for processes run by root
	• A type of namespace with access to all system resources, i.e. to all network devices in all network namespaces
	• A default namespace, i.e. the default network namespace (Ans)
	• A namespace for root processes, i.e. a network namespace for root processes
	What can you use to find vulnerabilities in images?
	• Isolate container networking to avoid malicious processes from talking to other processes
	• Run anti-virus services inside containers
	• Image registries with security scanning (Ans)
	• Image signing and verification
#	What do cgroups isolate?
	• Which CPUs a process can use
	• Specific device access
	• The amount of a resource a process can use
	Specific framework versions (Node.js, ASP.NET, etc.) can be loaded on a developer machine by creating a custom Dockerfile.
#	What file does Docker Compose use to define services?
	• compose.xml
	• Dockerfile
	• docker- compose.son
	• docker- compose.yml (Ans)
#	What Dockerfile instruction can be used to execute “npm install” when creating a custom Image?
	• npm install
	• EXECUTE npm install
	• RUN npm install (Ans)
#	What command- line switches are used with legacy linking?
#	Docker Kitematic provides a way to visually search for images hosted on __________?
	..-20/> 
	What can you use to run multiple containers from a single YAML file?
	• docker-compose (Ans)
	• docker run containers.yml
#	Which of the following is not a benefit of Virtual Memory?
	• Use more memory than is physically available
	• Processes can use memory as if they are the only process running
	• Compress data stored in memory to increase capacity (Ans)
	• Don’t have to save entire contents of memory when switching processes
#	Which of the following is not a benefit of a union filesystem for containers?
	• Decrease startup time for containers with images pre-extracted into an image cache
	• Save disk space by sharing common files with the host OS filesystem via symbolic links (Ans)
	• Share page cache entries to reduce memory overhead
	• Save disk space with readonly layers reused among containers
#	What does it mean for two containers to share a network namespace?
	• They share the host’s (or root) network namespace.
	• They have isolated virtual network adapters.
	• They share a virtual network but still have isolated virtual network adapters.
	• They share a single network stack. (Ans)
#	Which networking approach would you use if you don’t trust an application?
	• Share network with other containers
	• None (Ans)
	• Share with host
	• Virtual network
#	When you create a process with separate namespaces (network, mount, IPC, UTS, PID, and user), what is the net effect?
	• It appears as if the process is running on a different machine. (Ans)
	• Processses get their own isolated instances of system resources.
	• Processes can share system resources.
#	Why do you use tools like Docker, LXC and rkt?
	• To kill processes that consume too much of a system resource
	• To configure the additional isolation necessary to create a container (Ans)
	• To create VMs to isolate processes
	• To emulate virtual resources per process
#	When a mount namespace is created, what does it contain?
	• An empty list of mount points
	• The list of mount points passed when creating the new mount namespace
	• A default set of mount points from /etc/mountns.defaults
	• Essentially a copy of the existing filesystem (Ans)
#	What does Layered Responsibility mean?
	• You can rely upon others for base layers in container images. (Ans)
	• You can’t see the layers beneath yours in container images.
	• You don’t ever have to see the layers beneath yours in container images.
	• You need to validate that all layers are built properly when using an image.
#	What is a context switch?
	• When the executing process is changed (Ans)
	• When the executing cgroup is changed
	• When the contents of virtual memory is loaded into physical memory
	• When the contents of physical memory is swapped to disk
#	What is a substantial reason for moving from a single node to a multi-node cluster?
	• It’s a best practice to use multi-node clusters in production.
	• It’s a best practice to run individual containers on individual nodes.
	• When containers saturate the resources of a single node (Ans)
	• When containers conflict with each other, i.e. port conflicts or file system conflicts
#	Where is there a natural separation in responsibility when building a cluster?
	• Running apps & running VMs
	• Node operating system & cluster services
	• Machine hardware & operating system
	• Provisioning nodes & running apps (Ans)
#	What is the net effect of a separate network namespace? Each process can have an entirely separate __ .
	• IP address (Ans)
#	What runtime or execution environments can be used with a cluster?
	• Containers
	• chroot Processes
	• Virtual Machines
#	What does an Image from a site like Docker Hub provide?
	• A container’s hostname
	• The host filesystem to run a container
	• A container’s network configuration
	• The entire host filesystem
	• A container’s filesystem (Ans)
#	What is the net effect of a separate IPC namespace? Each process can have an entirely separate ______ .
	• message queue (Ans)
#	What does a system container run?
	• Runs an OS init process, effectively emulating a VM (Ans)
	• Runs a single application
#	Why are images so valuable?
	• Manually configuring a hostname for a container is hard work.
	• Manually building a filesystem for a container is hard work. (Ans)
	• Manually configuring service discovery for a container is hard work.
	• Manually configuring networking for a container is hard work.
#	What do capabilities isolate?
	• Privileged operations (Ans)
	• Unprivileged processes
	• Privileged processes
	• Unprivileged operations
#	Which of the following is NOT an analogy for namespaces?
	• A slice of a pizza per process (Ans)
	• A whole pizza per process
	• Database
	• List
	..-19/> 
	If you want to perform maintenance on a node, to what availability should you change it?
	• Ready
	• Down
	• Drain (Ans)
	• Pause
	• Active
#	Assuming you have a stack called APIS, what is the equivalent of docker service ps for stacks?
	• docker stack deploy
	• docker stack ls
	• docker stack ps APIS (Ans)
	• docker stack services APIS
#	When a service is updated that requires a change in the running container, what happens to the corresponding task?
	• The existing task is kept and its metadata is updated.
	• A new task is also created. (Ans)
	• The existing task is kept.
#	What happens when a new node is attached to the cluster that matches the constraints of a pending replicated service?
	• The pending task for the service will be assigned to the new node and a container will be started. (Ans)
	• The existing containers for the service will be rebalanced so that a fair share are placed onto the new node.
	• A new task will be allocated to the new node for the global service.
	• Nothing will run on the new node unless you change the service.
#	If you don’t want a service to run, but you don’t want to remove it, what’s the safest thing to do?
	• Add constraints that aren’t fulfilled.
	• Scale it to zero. (Ans)
	• Manually mark it pending.
	In the “Manager Status” column in the output of docker node ls, what shows for worker nodes?
	• Worker
	• Nothing (Ans)
	• Leader
	• Reachable
#	Which service mode puts a task and a container on each node in the cluster?
	• Global (Ans)
	• Per Node
	• Replicated
#	Which of the following would you use to stop a health check that’s running for a long time?
	• timeout (Ans)
	• interval
	• retries
#	Which node role maintains the state of the cluster?
	• Manager (Ans)
	• Replica
	• Slave
#	Which service mode allows you to arbitrarily scale your service?
	• Replicated (Ans)
	• Global
#	If you want to convert a manager node into a worker node, what do you use?
	• docker node promote
	• docker node demote (Ans)
	• docker swarm manager
	• docker swarm worker
	• docker node rm
#	How are Docker and rkt container images structured on disk?
	• Each container has access to the host filesystem for common files and then a special directory for apps unique to the container.
	• Images are typically split into readonly layers that can be shared between containers. (Ans)
	• Each container has its own extracted, isolated copy of the filesystem from an image.
	• Images are extracted into a readonly directory that can be shared between containers.
#	What is the net effect of a separate mount namespace? Each process can have an entirely separate __ .
	• ipc
	• filesystem (Ans)
	Virtual Memory is similar to which of the following?
	• Capabilities
	• AppArmor
	• SELinux
	• Namespaces (Ans)
	• Control Groups
#	Why is networking a concern with containers?
	• Because container networking is a new frontier and is different than how you network VMs and physical machines
	• Because you have to use port forwarding to share the host’s physical network adapter
	• Because you don’t want applications to have port conflicts
	• Because each container usually has its own network namespace that needs configuring (Ans)
	What can you use to create persistent storage in a container?
	• Share the container host’s (root) mount namespace
	• Root file system
	• Image layers
#	What is one reason for a top Container Layer added to the underlying image layers when creating the filesystem for a container?
	• Easily provide a filesystem for containers from a pre-built image extracted into the top container layer
	• Easily create a new image by snapshotting the top container layer (Ans)
	• Easily configure the networking stack for a container via the top container layer
#	What is a host or container host?
	• A process running in the root namespaces on a system (Ans)
	• A process running in a namespace labeled “host”
	• A process running outside of all namespaces
#	Why do you use mount namespaces?
	• To isolate networking and avoid issues with port conflicts
	• To isolate hostnames to make it appear as if a process is running on a separate machine
	• To isolate the list of processes with which a process can interact
	• To isolate the filesystem and only provide files that a single application needs (Ans)
	What cluster component helps you find the IP address of another application?
	• Service Discovery (Ans)
	• Scheduler
	• Persistent Storage
	..-18/> 
#	If you run docker network ls and do not see a network that you’re looking for, what is the most likely culprit?culprit?
	• That node is not a worker node.
	• That node is not a manager node.
	• You’re not authorized to see the network.
	• That node doesn’t have a container running that uses that network. (Ans)
#	What does –update-parallelism control?
	• The time between updating tasks
	• The number of tasks updated at the same time (Ans)
	• What to do when an update fails
	• Whether or not to update all tasks at once, or one at a time
#	Which published port mode would you use to load balance requests across all containers for a service?
	• Host
	• None
	• Ingress
	• LoadBalanced
#	If you only have a replicated service, what will happen when you add a new node to the cluster?
	• The pending task for the service will be assigned to the new node and a container will be started.
	• Nothing will run on the new node unless you change the service. (Ans)
#	If you want multiple containers for an application, what command is easiest to use to go from a service with one task replicas to two?
	• docker clone …
	• docker service rm; docker service create –replicas 2 …
	• docker service scale …
	• docker service update –replicas 2 … (Ans)
	• docker run …
	On a swarm, if a container dies that’s part of a service, and a new container is created, what concept explains this?
	• High Availability
	• Desired State Reconciliation (Ans)
	• Scheduling
	• Service Scaling
#	What does the “*” mean in the output of docker node ls?
	• The nearest manager
	• The leader
	• A worker node
	• The node you’re connected to (Ans)
	Joining a node as a manager by default that node will perform __ role(s).
	• Manager only
	• Leader only
	• Manager and Worker (Ans)
	• Replica only
	• Slave and Replica
#	Which of the following would you use to decrease the time between health checks?
	• timeout
	• interval (Ans)
#	Assuming you have a stack called APIS, what is the equivalent of docker service ls for stacks?
	• docker stack services APIS (Ans)
	• docker stack ps APIS
#	What happens to containers on a node that you drain?
	• They’re shut down until you make the node active again.
	• They keep running, just no new work is allowed to be put onto the node.
	• They’re snapshotted and migrated to other nodes.
	• They’re terminated and migrated as new containers on other nodes. (Ans)
#	Assuming you have a service named web, what will the dns query tasks.web return?
	• The Swarm Load Balancer
	• Individual container IPs for the web service (Ans)
	• The web service’s Virtual IP
#	What does –update-delay control?
	• The number of tasks updated at the same time
	• The time between updating tasks (Ans)
#	What command do you use to create containers on a swarm?
	• docker service create (Ans)
	• docker swarm run
	• docker-compose up
#	Which of the following has a one-to-one relationship with a container?
	• Task (Ans)
	• Service
	• Swarm
	What can you put in front of a swarm so that end users don’t have to pick a node, nor deal with node failures, to access a service with a published port?
	• Round Robin DNS to all nodes
	• Load Balancer to all nodes (Ans)
	• Single DNS entry to one node
#	When no nodes in the cluster fulfill the constraints of a service, what is the status of the service?
	• Failed
	• Running
	• Pending (Ans)
	• Started
#	What does “starting” mean in terms of health checks?
	• The health check has not yet run for a new container. (Ans)
	• This shows each time the health check runs to indicate that it is starting.
	• The health checking service is starting up and is not ready to run health checks.
#	What happens when Docker Swarm Mode detects an unhealthy container?
	• Restarts the container
	• Shuts the corresponding task down and starts a new one (Ans)
	• Nothing, health checks are not integrated into Swarm Mode.
	• Sends an email to the system operator
#	Which of the following would you use to avoid recreating a task on a recoverable application failure?
	• retries (Ans)
	..-17/> 
#	Which of the following will upload a new stack to your Docker Cloud account?
	• docker-cloud stack create docker-cloud.yml
	• docker-cloud stack create -f docker-cloud.yml (Ans)
	• docker-cloud stack create -f dockerfile
	• docker stack create -f docker-cloud.yml
#	Docker Engine is:
	• The locally installed runtime through which you administrate Docker containers (Ans)
	• An online Docker administration interface
	• An online Docker image repository
	• A local Docker image repository
#	Docker Trusted Registry is:
	• A local, commercial image management tool
	• An open source tool for securing the infrastructure on which Docker Engine runs
	• A web-based, commercial, hosted image management tool (Ans)
	• An open source tool for coordinating Docker container clusters
#	A Docker container will run faster when its image is properly optimized. Which of the following will have the greatest positive impact on speed?
	• Build the image using as few layers as possible. (Ans)
	• Always base your images on the latest operating system version available.
	• Always be consistent in the software package versions you choose for your image layers.
	• Build the image using a Dockerfile rather than from a running container.
#	Where are the image files stored on a Linux machine running a package-based Docker Registry?
	• /var/lib/docker/docker-registry
	• /var/lib/docker/volumes//_data/docker/registry/v2/repositories/
	• /var/lib/docker/docker-registry/docker/registry/v2/repositories (Ans)
	• /var/lib/docker/docker-registry/docker/registry/v2/_catalog
#	Which of these commands will return a list of images currently stored in a Docker Registry?
	• curl 192.168.1.17:5000/v2/_catalog (Ans)
	• curl 192.168.1.17:5000/v2/_data
	• docker registry ls
#	Which of the following commands will successfully build an image with the name “myimage”?
	• docker build -t myimage
	• docker build –tag-image myimage
	• docker build -n myimage .
	• docker build -t myimage . (Ans)
#	What does “retries” specify for a health check?
	• How many times a container is restarted before it’s marked unhealthy
	• How many times an individual health check is simultaneously performed before assuming a failure
	• How many times a container is restarted before its task is shutdown and a new one is created
	• How many times a health check fails before a container is marked unhealthy (Ans)
#	docker-compose is roughly equivalent to what swarm mode command: __?
	• docker stack deploy (Ans)
	• docker service create
#	What purpose does the ingress network serve?
	• Routing traffic from published ports to running containers (Ans)
	• Load balancing internal container to container traffic
	• Routing internal container to container traffic
#	How are secrets made available to a container?
	• Environment Variables
	• Filesystem (Ans)
	• Socket
	• HTTP API
	Pinning is the process of ______?
	• Resolving an image tag to a digest (Ans)
	• Assigning a image repository to a digest
	• Assigning a task to a node
	• Assigning a container to a task
	• Resolving a image digest to a tag
#	Which published port mode would you use to map the port on a given node to a specific container running on that node?
	• Host (Ans)
	Services are a template for:
	• Tasks (Ans)
	• Images
	• Swarms
#	If you only have a global service, what will happen when you add a new node to the cluster?
	• A new task will be allocated to the new node for the global service. (Ans)
	Let’s say you have a service with four replicas, and four tasks currently running with IDs: A, B, C, and D. Let’s say you stop the container associated with task D.
#	What happens?
	• The service is terminated.
	• A new task E and a new container are created. Task D and its container are removed. (Ans)
	• The container is restarted.
	• The container is removed, and a new one is created and associated with Task D.
#	What happens if you try to view cluster state from a worker only node?
	• List of cluster state for all nodes
	• List of state for that worker node only
	• An error (Ans)
#	How can you see a log of health checks?
	• docker service ps MYSERVICE
	• docker inspect CID (Ans)
	• docker service inspect MYSERVICE
	• docker stack ps MYSTACK
#	If you want to convert a worker node into a manager node, what do you use?
	• docker node demote
	• docker node promote (Ans)
#	A stack manages multiple:
	• Replicas
	• Nodes
	• Tasks
	• Services (Ans)
	..-16/> 
#	Which fundamental networking technology does the native (local) overlay driver leverage when creating multi-host container networks?
	• Token Ring
	• VXLAN (Ans)
	• FCoE
#	You need to create a singe container network that spans multiple hosts and gives all containers on the network IP addresses from the same L2 subnet.
#	Which built-in Docker networking driver would you use?
	• overlay (Ans)
	• ipvlan
	• l2-overlay
#	Which of the following commands would you use to display all networks present on a particular Docker host?
	• docker networks get
	• docker network ls (Ans)
	• docker network display
	• docker network show
	In which of the following scenarios will the built-in Docker name resolution allow two containers to resolve each other by name?
	• Two containers created with the –name flag and both containers are on the same container network (Ans)
	• Two containers created with the –name flag and both containers are part of the same Swarm Service
	• Two containers created with the –name flag and both containers are part of the same Swarm
	• Both containers are on the same Docker host
#	You manage a production Docker estate and want to make sure all of the nodes in a particular Swarm can handle and process requests for a particular service. You
	need this to work even if nodes in the Swarm are not running a task for the service. Which technology should you use to accomplish this?
	• IPVLAN
	• The Routing Mesh (Ans)
	• An traditional external load balancer
#	Which of the following container networks is used by Swarm Mode for internal routing of traffic?
	• overlay
	• nat
	• ingress (Ans)
#	Which core Docker component contains the bulk of networking code and is the de facto implementation of the CNM?
	• bridgenetwork
	• containerbridge
	• libnetwork (Ans)
	• libcontainer
#	Which of the following describes a sandbox in the context of Docker networking?
	• A container within a container that contains a shared network stack
	• A ring-fenced area of the Host OS that contains an isolated network stack (Ans)
	• An area of virtual memory used as scratch space by Libnetwork
	• A ring-fenced area of a container made available to all other containers on the same network
	In which programming language is Libnetwork written?
	• C
	• Pascal
	• Python
	• Golang (Ans)
#	You have a container network called m1-prd that is scoped to “swarm.” However, when you are logged onto a node in the Swarm, you cannot see the network. Why
	might this be the case?
	• The node you are logged onto is not running a task that is using the network, so the network has not been extended to the node yet. (Ans)
	• Docker takes a lazy approach to creating networks on all nodes in the Swarm. You probably haven’t waited the 30 minutes it takes to infect the entire Swarm
#	with the network.
	• The m1-prd network is encrypted and therefore not visible in the output of regular docker network commands.
	• The docker network ls command does not display networks scoped to to “swarm.”
#	What is the purpose of the MACVLAN driver?
	• To put containers on existing networks and VLANs
	• To create multi-host overlay networks
	• To enhance container networking for Docker Engines running on Docker for Mac (DFM) (Ans)
#	Which of the following open source specification documents forms the foundation of Docker networking?
	• The Docker Network Model (DNM)
	• The Container Network Interface (CNI)
	• The Container Network Model (CNM) (Ans)
	• Virtual Extensible LAN (VXLAN)
#	Which of the following are the three major constructs defined in the Container Network Model (CNM)?
	• Container, endpoint, network
	• Sandbox, endpoint, network (Ans)
	• Service, endpoint, network
	• Sandbox, container, network
#	Which native Docker feature simplifies and enhances creation and management of Docker networks?
	• Content Trust
	• The volume driver interface
	• Swarm Mode (Ans)
#	Which of the following will display the specific command that created each layer in an image?
	• docker build -th imagename
	• docker history imagename (Ans)
	• docker search imagename
	• docker images -t imagename
#	What is accomplished by running the following command?
#	docker run -p 5000:5000 registry:latest
	• Docker Engine will run a “hot update” on the live Registry image.
	• The Docker Registry image will (if necessary) be pulled and then run, exposing port 5000. (Ans)
	• Only if the Docker Registry image has already been pulled will it be run, exposing port 5000.
	• The Docker Registry image will be pulled from Docker Hub using port 5000.
#	You would prepare an image called hello-world for uploading to a local Docker Registry using which of the following commands?
	• docker tag hello-world localhost:5000/hello-world:latest (Ans)
	• docker tag hello-world localhost/hello-world:latest
	• docker -tag 127.0.0.1/hello-world:latest
	• docker -t hello-world localhost:5000/hello-world:latest
	To add encryption using a self-signed certificate to your Docker Registry infrastructure, to which directory must the certificate be copied (assuming your domain is
#	domain.com)?
	• /etc/docker/certs.d/domain.com:5000/ (Ans)
	• /etc/docker/cert.d/domain.com:5000/
	• /var/lib/docker/certs.d/domain.com:5000/
	• /etc/docker/certs.d/domain.com/
#	Which of these is the correct command to display a list images currently stored in a Docker Registry using a self-signed certificate?
	• curl –insecure http://192.168.1.16:5000/v2/_catalog
	• curl -i https://192.168.1.16:5000/v2/_catalog
	• curl -i https://192.168.1.16:5000/v2/_data
	• curl –insecure https://192.168.1.16:5000/v2/_catalog (Ans)
#	How do you temporarily enable Docker Content Trust on your local machine to take advantage of digitally signed images?
	• export DOCKER_CONTENT_TRUST=1 (Ans)
	• export $DOCKER_CONTENT_TRUST=0
	• echo DOCKER_CONTENT_TRUST=1 >> /etc/profile
	• echo $DOCKER_CONTENT_TRUST=1
	..-15/> 
#	What is the function of this command?
#	docker search apache/ubuntu
	• It will search your local Docker client environment for images related to either apache or ubuntu.
	• It will search Docker Hub for images related to both apache and ubuntu. (Ans)
	• It will search your local Docker client environment for images related to both apache and ubuntu.
	• It will search Docker Hub for images related to either apache or ubuntu.
#	For security, the Docker website uses encryption certificates to ________.
	• secure the computers of local Docker clients
	• ensure that all images uploaded to Docker Hub are free of malware
	• ensure that all “docker run” operations are valid
	• secure connections between the website and clients (Ans)
#	What is the role of apache2ctl in this command?
#	docker run -d -p 80:80 webserver /usr/sbin/apache2ctl -D FOREGROUND
	• apache2ctl will launch a new Docker container as a backend server to your main container.
	• apache2tcl will run the Apache webserver software package when the container boots. (Ans)
	• apache2ctl will check to make sure the Apache webserve software package is properly installed on a container.
	• apache2ctl is the name of a Docker image.
#	Which of these commands will associate a network interface with a Docker container?
	• docker attach network newnet
	• docker network connect newnet newname (Ans)
	• docker network connect newname newnet
	• docker net connect newname newnet
#	How do you configure a repository in DTR to allow it to be signed by one or more UCP users?
	• Using the DTR Web UI: select ‘Content Trust’ for the repo and add the UCP users who can sign.
	• Using the Docker client: initialize the snapshot, rotate the root key, add delegation imports.
	• Using the Notary client: initialize the repo, make the snapshot key user-managed, add delegation targets. (Ans)
#	For a repo with content trust delegations configured, how do you sign an image?
	• Set DOCKER_CONTENT_TRUST=TRUE on the client, then docker sign and enter your UCP key passphrase.
	• Run docker push to upload the image, then upload your private key in the DTR Web UI to sign it.
	• Set DOCKER_CONTENT_TRUST=1 on the client, then docker push and enter your UCP key passphrase. (Ans)
#	What is the difference between a ‘service’ and an ‘application’ in UCP?
	• A service runs as a single task on each node in the cluster; an application can run as one or more tasks spread throughout the cluster.
	• A service has one or more tasks created from a single image; an application is a distributed solution with containers created from many images. (Ans)
	• A service is a system-level component, like the UCP agent or the DTR Notary server; an application is a user-level component created through the Web UI.
#	How are global services and replicated services different?
	• Global services are restricted so only UCP administrators can see and manage them, replicated services can be secured using role-based access control.
	• Global services are workloads which run on the UCP servers but are not containers, they are application processes which Docker doesn’t manage.
	• Global services run a single task on each UCP node, replicated services run one or more tasks spread across all nodes. (Ans)
#	How do you deploy an distributed application in UCP?
	• You can build an installer into a Docker image and upload it to DTR, then run a container from the image in UCP.
	• You can copy a Docker Compose file into the Web UI and UCP will deploy all the resources.
	• You can create networks and volumes manually, then start containers in the correct dependency order. (Ans)
#	Can you install Docker Datacenter with the free, open-source Docker engine?
	• No, DDC requires the commercially supported engine, which is licensed with DDC. (Ans)
	• Yes, but you need to add Docker’s CA cert into your host’s certificate store.
	• Yes, provided you are using version 1.12 of the open-source engine.
#	How do you install UCP and DTR once you have the commercially-supported Docker engine installed?
	• The installers are images on the Docker Hub; to install just run containers from docker/ucp and docker/dtr. (Ans)
	• Packaged installers are available for all major Linux distros; in debian just run apt-get install docker-ddc.
	• Download an installer from Docker’s website, which is an image archive, then uncompress and run as a container.
#	What’s the difference between Docker repositories and Docker registries?
	• A repository can only store images built for one OS, a registry can store images for many OSes
	• A repository stores many versions of an image, a registry stores many repositories (Ans)
	• A registry is a store for images, a repository is a store for containers running on a host
#	What does Docker Datacenter provide that you don’t get from the free open-source Docker ecosystem?
	• Scalable, secure, and supported platforms for managing images and container workloads (Ans)
	• Licensing which lets you run Docker on Windows servers as well as Linux servers
	• A locked-down container environment, where you can only manage Docker if you have SSH access to the hosts
#	How does Docker Trusted Registry provide high availability and high scale?
	• Replica nodes can be added to provide HA, and a cloud storage service can be used for scalable storage. (Ans)
	• You can host DTR behind a load balancer, so the LB provides high availability and scale.
	• DTR runs on DDC as a replicated service, so you can increase scale by adding replicas in UCP.
#	How do organizations and teams in DTR let you capture permissions for multi-user access to a repository?
	• Repos are created at team level, teams are members of organizations in UCP, users inherit organization permissions
	• Repos are created at organization level, access is granted to teams in the organization, users inherit team access (Ans)
	• Repos are created at organization level, organizations are owned by a UCP team, users inherit team permissions
#	How do you add new UCP controllers to the cluster, to make UCP highly available?
	• Run docker swarm join –as-manager with the swarm token, and the new node will join as a controller.
	• Run docker swarm join using the manager token, and the new node will be configured as a controller. (Ans)
	• Run docker swarm join to join as a node, and then run the docker/ucp installer image to become a controller.
#	If you need to install an OS patch on one of the UCP nodes, how can you do it?
	• Put the node into drain mode which kills all containers and exits the swarm, apply the patch and rejoin.
	• Stop any services and applications which have tasks running on the node, then apply the patch and restart.
	• Put the node into drain mode to stop all container workloads, leave the swarm, apply the patch and rejoin. (Ans)
#	How do you push an image from your local Docker engine to a remote Docker Trusted Registry?
	• Set your default registry to be DTR using docker config and then just push as normal.
	• Tag your image with your DTR user name, then run docker push specifying the DTR URL.
	• Run docker save to archive the image, then log in to DTR using the Web UI and upload the archive.
	• Tag your image with the DTR domain name, run docker login to authenticate to DTR, and then docker push . (Ans)
#	Which component of the Docker network stack implements specific network topologies such as overlay networking or bridge networking?
	• Libnetwork
	• The driver layer (Ans)
	• The CNM
#	Which of the following commands would you use if you were logged onto a Docker host and needed to look at detailed information about a network called prod-fe?
	• docker network inspect prod-fe (Ans)
	• docker network ls prod-fe
	• docker network show prod-fe
	• docker network ls prod-fe –verbose
	..-14/> 
#	Which of the following problems (not solved by hypervisor virtualization) do containers solve?
	• Heterogeneous application management
	• Network Function Virtualization (NFV)
	• Software Defined Storage (SDS)
	• Overheads incurred by the multiplicity of Operating Systems (OS) (Ans)
#	Which of the following commands will download the Ubuntu image from Docker Hub?
	• dkr pull ubuntu
	• docker download ubuntu
	• docker pull ubuntu (Ans)
	• dkr download ubuntu
#	What is the Open Container Initiative responsible for?
	• Container security standards
	• Container format and runtime standards (Ans)
	• Image format and orchestration standards
#	Which of the following is an important question to answer within your organization?
	• Which public cloud platform to deploy your container infrastructure on
	• Whether to deploy your containerized apps on Windows or Linux systems
	• Who will pay for container-related infrastructure and services (Ans)
	What are the three Docker channels?
	• Community, Docker, 3rd Party
	• Linux, Windows, BSD
	• Experimental, Stable, Commercially Supported (Ans)
	• Development, Test, Production
#	Which of the following is true of Docker containers?
	• Docker containers are not persistent.
	• Docker containers only run in the cloud.
	• Docker containers are persistent. (Ans)
	• Docker containers are more secure than virtual machines.
#	Which of the following products can run inside of a corporation’s firewall and allows them to ship containerized apps?
	• Docker Universal Control Plane
	• Docker Hub
	• Docker Content Trust
	• Docker Trusted Registry (Ans)
#	Where is Docker Inc. based?
	• Boston, Massachusetts
	• Austin, Texas
	• San Jose, California
	• San Francisco, California (Ans)
#	Which Docker Technology turns on image signing and verification for pushing and pulling images?
	• Docker Image Trust
	• Docker Content Trust (Ans)
	• Docker Trusted Registry
	• Docker Trusted Images
#	Which of the following is not an advantage of containerized cloud native apps?
	• Portability
	• Security (Ans)
	• Scalability
	• Self-healing
#	If you needed to deploy a container registry within your own corporate firewall that you own and manage, which of the following products could you use?
	• Docker Trusted Repository
	• Private repositories on Docker Hub
	• Docker Trusted Hub
#	Which of the following is true of ECS?
	• ECS offers integration with either the ECS registry or Docker Hub images. (Ans)
	• Besides for the regular AWS resources in use, ECS charges users on a per-cluster basis.
	• ECS automatically launches a fully-managed EC2 instance for every cluster created.
	• At the cluster level, ECS can only be managed from the browser-based console.
#	You can display detailed information about an ECS cluster from the command line using…
	• aws ecs cluster –help
	• aws ecs clusters –list
	• aws ecs list-clusters
	• aws ecs describe-clusters (Ans)
#	You can set load balancing and auto scaling for a deployment in the _______ configuration menu of the console.
	• Cluster Update
	• Task Definitions
	• Services
#	Adding the “Amazon EC2 Container Service for EC2 Role” to your EC2 instance allows __________.
	• ECS resources to connect to the EC2 instance
	• the EC2 instance to be registered within an ECS system
	• the EC2 instance to connect to ECS resources (Ans)
	• the account root user to manage the EC2 instance
#	An ECS task can be described as:
	• A software tool used to manage cluster resources
	• A software agent used to enable communication across a cluster environment
	• A collection metadata defining the environment elements needed to launch Docker containers (Ans)
	• A virtual container profile
#	Which of the following files on an EC2 ECS-optimized AMI instance must be edited to permit access to Docker Hub private repositories?
	• /etc/ecs/ecs.config (Ans)
	• /etc/ecs-config
	• /ecs/ecs.config
	• /etc/ecs/ecs-config
#	What is the primary purpose of adding a tag to a Docker image?
	• To identify the object as an image
	• To identify the image’s ownership and origin
	• To allow for easier visual identification once your infrastructure grows
	• To direct Docker to the appropriate remote repository (Ans)
#	Which of the following commands will return authentication credentials for the EC2 Container Repository service?
	• aws ecr login –region
	• aws ecr get-login –region (Ans)
	• aws get-login –region
	• aws get-region
#	Which of these tools provides information about all the Docker resources on your system?
	• docker info (Ans)
	• docker inspect
	..-13/> 
#	Which of the following flags tells the Swarm Manager process that it will be part of a highly available multi-manager configuration?
	• –replicate
	• –replication (Ans)
	• –multi-manager
	• –multi-master
#	Which three scheduling strategies does Swarm currently support?
	• Random, fastest response, spread
	• Random, round-robin, binpack
	• Random, spread, binpack (Ans)
	• Random, spread, stack
	What are the two major services required for a Swarm cluster to operate correctly?
	• Directory service and Swarm manager
	• Discovery service and Swarm manager (Ans)
	• Discovery service and Directory service
	• Docker Hub and Discovery service
#	What is the recommended way for clients to communicate with Swarm nodes in the Docker Swarm cluster?
	• Directly to the engine daemon on each node
	• Via the Swarm manager (Ans)
	• Via Docker Hub
	• Via Docker Trusted Registry
#	Why does the binpack scheduling strategy choose the smallest node in the cluster when choosing new nodes to schedule containers on?
	• Larger nodes take longer to query
	• To keep operational costs as low as possible
	• To save larger nodes for larger containers (Ans)
#	You have a node in your Swarm cluster that does not have any running containers but is being overlooked when new containers are scheduled against the cluster.
#	Which of the following could be a reason for this?
	• The node has too many images in its local store.
	• The node has a lot of containers in the stopped state. (Ans)
	• The node has a lot of containers in the destroyed state.
	• The node has rebooted within the last two hours.
#	Who is the founder and current CTO of Docker Inc.?
	• Ben Golub
	• Linux Torvalds
	• Mark Zuckerberg
	• Solomon Hykes (Ans)
#	Which open source license is the Docker project licensed?
	• CDDL
	• Apache License 2.0 (Ans)
	• GPL v3.0
	• MIT
#	Which of the following describes the relationship between repositories and registries?
	• Repositories contain one or more registries.
	• Registries contain one or more repositories. (Ans)
	• Repositories are always public, while registries are always private.
	• Registries are always public, while repositories are always private.
#	Which of the following is driving stateful workloads towards becoming first-class citizens on the Docker ecosystem?
	• Data volumes
	• The pluggable storage backend (Ans)
	• The key/value store used in multi-host networking
#	Which of the following problems did hypervisor virtualization solve for businesses and IT?
	• Data Center security
	• Operating System management overhead
	• Wasted physical server resources (Ans)
	• Re-writing of legacy monolithic apps
	If you were using container orchestration tools from Docker Inc., which tool would manage your cluster of Docker hosts?
	• Docker Swarm (Ans)
	• Docker Compose
	• Docker Clustering
#	Which of the following advantages do containers have over virtual machines?
	• They are more fault-tolerant.
	• They are more efficient with system resources. (Ans)
	• They are more mature.
	• They are more secure.
#	Which of the following does the author believe will best help you prepare to thrive in a container world?
	• Partnerships with strategic vendors
	• A Windows only infrastructure
	• Knowledge and experience (Ans)
	• Good change-management processes
#	Which of the following is a popular place to get developers started with containers in your infrastructure?
	• Continuous Integration/Continuous Delivery solutions
	• Your production estate
	• Deploying infrastructure services such as DNS and Active Directory
	• New software defined networking solutions (Ans)
#	Which of the following best describes the Commercially Supported Docker Engine (CS Engine)?
	• Released every ~6 months, supported by Docker Inc., and based on the same codebase as the stable release of the Docker Engine (Ans)
	• Released every ~6 months containing proprietary code contributed by 3rd parties such as IBM, Microsoft, and Red Hat
	• Released every ~6 months, hosted and managed by Docker Inc. on the dotCloud cloud platform
	• Released by 3rd parties such as IBM and Red Hat but based on the stable release of the Docker Engine
#	Which of the following container registries will be used in a default installation of Docker?
	• Quay Enterprise
	• GitHub
#	Where can the Docker project and its source code be found?
	• BitBucket
	• It is proprietary code owned and kept in-house at Docker Inc.
	• GitHub (Ans)
#	Which of the following best describes a stateless app or workload?
	• One that stores changed data
	• One that does not care which public cloud platform it runs on
	• One that does not store any changed data (Ans)
	• One that can run in any state or territory without legal issues
#	Which of the following is described in the course as being a pro and a con of the hypervisor virtualization model?
	• Being able to move existing apps directly into virtual machines (Ans)
	• The need to change existing apps before they can run inside of virtual machines
	• Virtual machines can run on existing x86 and x64 hardware
	• Hypervisors contain a lot of code, making them feature rich but vulnerable to more attacks
#	Which of the following does container orchestration help with?
	• Interal cross charging
	• Scaling (Ans)
	• Unit testing
	• Data volume management
	..-12/> 
#	Which of the following are the standard secured and unsecured Docker engine daemon ports?
	• 2375 (unsecured), 2376 (secured) (Ans)
	• 4000 (unsecured), 4001 (secured)
	• 3375 (unsecured), 3376 (secured)
	• 80 (unsecured), 443 (secured)
#	Which of the following arguments gets passed to the swarm command to join a node to the Swarm cluster?
	• raft-join
	• join (Ans)
	• swarm-join
	• cluster-join
#	Which of the following describes what occurs when the primary Swarm Manager that is part of a highly available set of Swarm Managers fails?
	• A leader election occurs and an administrator selects which of the secondary managers is promoated to primary.
	• The Swarm cluster enters a split brain configuration.
	• A leader election occus and a secondary Swarm Manager seamlessly takes over the role of primary. (Ans)
	• The remaining secondary Swarm Managers combine to fill the role of primary.
#	Which of the following technologies allows Docker Swarm to leverage a pluggable discovery service backend?
	• libnetwork
	• libkv (Ans)
	• Consul
	• godep
#	Which two resources can containers reserve on the nodes they will run on?
	• CPU and RAM (Ans)
	• CPU and TCP ports
	• CPU and IOPS
	• IOPS and RAM
#	Which of the following is not a standard constraint?
	• storagedriver
	• networkdriver (Ans)
	• executiondriver
	• operatingsystem
#	Which of the following is the preferred way to get TLS certificates into a Swarm manager container?
	• Start the Swarm manager container and copy the keys in via SCP.
	• Mount them in via a data volume. (Ans)
	• Rebuild the swarm image with the certificates baked in via a Dockerfile.
#	Which environment variable can be used to automatically enable TLS for Docker Engine client commands?
	• DOCKER_TLS_AUTHENTICATE
	• DOCKER_TLS
	• DOCKER_TLS_VERITY (Ans)
	• DOCKER_TLS_ENABLE
#	Which of the following filter types allows you to launch new containers on the same node as another container?
	• Affinity (Ans)
	• Resource
	• Custom
	• Node
#	How is the Swarm Discovery Service implemented in a production-grade Swarm cluster?
	• As a distributed key-value store (Ans)
	• A flat text file stored on every node in the cluster
	• As a high-speed relational database
	• Using Docker Hub as the hosted discovery service
#	Which of the following would be a good design for a Swarm cluster?
	• Three Swarm managers on separate VMs and separate physical hosts (Ans)
	• Three Swarm managers on separate VMs on a single physical host
	• Three Swarm managers all on the same VM
	• Five Swarm managers on separate VMs on a single physical host
#	Which of the following is passed to the swarm command to start a new Swarm Manager process?
	• manager
	• master
	• manage (Ans)
	• leader
#	Which of the following allows Swarm related components to trust a CA?
	• The presence of the Swarm component’s own public key
	• The presence of the Swarm component’s own private key
	• The presence of the CA’s public key on the Swarm component (Ans)
	• The presence of the CA’s private key on the Swarm component
#	Which of the following shows the way Docker prefers keys to be named?
	• ca-cert.pem, swarm-cert.pem, swarm-key.pem
	• ca-cert.pem, node-cert.pem, node-key.pem
	• ca.pem, cert.pem, key.pem (Ans)
#	By default, how does Swarm enforce affinity filters?
	• Best effort. If the affinity cannot be met the container is still started
	• Strictly. If an affinity cannot be met the container is not started (Ans)
#	Which of the following is true of configuring the Docker Engine daemon for TLS?
	• The Engine daemon dynamically picks up TLS options.
	• The Engine daemon must be restarted to pick up TLS options. (Ans)
	• The Engine daemon must be re-installed and compiled with the TLS configuration.
#	Which of the following discovery service backends are supported by Swarm?
	• MongaDB, CouchDB, MySQL
	• MySQL, PostgreSQL, etcd
	• Consul, etcd, Zookeeper (Ans)
	• Consul, etcd, MySQL
#	Which of the following describes the Swarm manager high availability model?
	• The Swarm manager service does not support high availability.
	• Point in time (PiT) copies that can be quickly be promoted to live in the event of failure
	• A single primary manager with n secondary managers (Ans)
	• Multiple primary managers that are all active
#	Which of the following filter types works with labels/tags that are applied to Docker engine daemons?
	• Affinity filters
	• Standard constraints
	• Custom constraints (Ans)
	• Resource filters
#	How do Consul agents learn about other agents etc?
	• Using libkv
	• Using the Serf gossip protocl (Ans)
	• Using libnetwork
	• Leveraging the Consul key-value store
#	Which of the following Consul commands allows you to see the status of agents in the Consul cluster?
	• consul agent status
	• consul members (Ans)
	• consul list members
	• consul status
	..
	• docker rm -f $(docker ps -q) (Ans)
#	When executing the command “docker pull microsoft/aspnet:4.6.2” what is the “aspnet” piece called?
	• Repository (Ans)
#	Which of the following commands will start a new container on the same nodes as container C1?
	• docker run -d -e affinity==c1 nginx
	• docker run -d -e constraint:container==c1 nginx
	• docker run -d -e affinity:container==c1 nginx (Ans)
	• docker run -d -e constraint==c1 nginx
#	Which of the following flags tells the Docker daemon to listen on the network using the default secured Docker port?
	• -H tcp://0.0.0.0:3375
	• -H tcp://0.0.0.0:2376 (Ans)
	• -H tcp://0.0.0.0:2375
	• -H tcp://0.0.0.0:3376
#	Which of the following flags turns on TLS authentication for the Docker daemon?
	• –tlscert
	• –tlsauthenticate
	• –tlsenable
	• –tlsverify (Ans)
#	How are custom labels implemented?
	• They are stored in an external KV store
	• They are applied to the Docker Engine daemon at startup (Ans)
	• They are applied to the Docker host as environment variables
	• A custom metadata container runs on the Docker host
#	How does Swarm support a pluggable discovery service backend?
	• Using libstorage as an abstraction layer
	• Using libkv as an abstraction layer (Ans)
	• By publishing an open API that key-value stores can work with
#	Which of the following is the default scheduling strategy for Swarm clusters?
	• Stack
	• Spread (Ans)
	• Random
	• Binpack
#	Which of the following Swarm components support High Availability?
	• Swarm manager and directory service
	• Swarm manager and discovery service (Ans)
	• Swarm manager and scheduling service
	• Just the Swarm manager
	..-10/> 
	In the past, we usually downloaded software in some sort of package to install it, for example a zip file or MSI file. Now, with Docker, how do we download software?
	..-8/> 
#	How can you get files out of a container onto the host? Assume a process in a container is writing files, like ffmpeg saving the contents of a converted video. Where do you write this data?
	• docker ls
	On a computer, with either Linux or Windows installed, there’s a program that runs in a privileged mode that abstracts hardware and provides services to other processes. What is this program?
	• Kernel space
	• Kernel (Ans)
#	What does docker-compose help us avoid? Excessive calls to __?
#	What is a dangling image?
	• An intermediate part of the chain of image layers
	• An image that’s not associated with a volume
	• An image that’s not associated with a tag (Ans)
	• An image that’s not associated with a running container

