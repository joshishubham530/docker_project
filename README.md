#                                             Docker

Introduction:-

Docker is a container management service. The keywords of Docker are develop, ship and run anywhere. The whole idea of Docker is for developers to easily develop applications, ship them into containers which can then be deployed anywhere.

The initial release of Docker was in March 2013 and since then, it has become the buzzword for modern world development, especially in the face of Agile-based projects.

Features of Docker:-

1-Docker has the ability to reduce the size of development by providing a smaller footprint of the operating system via containers.

2-With containers, it becomes easier for teams across different units, such as development, QA and Operations to work seamlessly across applications.

3-You can deploy Docker containers anywhere, on any physical and virtual machines and even on the cloud.Since Docker containers are pretty lightweight, they are very easily scalable.


Components of Docker

Docker has the following components

 Docker for Mac − It allows one to run Docker containers on the Mac OS.

 Docker for Linux − It allows one to run Docker containers on the Linux OS.
 
 Hardware and software requirements

You can install UCP on-premises or on a cloud provider. To install UCP, all nodes must have:

    Linux kernel version 3.10 or higher
    CS Docker Engine version 1.10 or higher. Learn about the operating systems supported by CS Docker Engine.
    2.00 GB of RAM
    3.00 GB of available disk space
    A static IP address


When installing UCP on a host, make sure the following ports are open:
Hosts 	Direction 	Port 	Purpose
controllers, nodes 	in 	TCP 443 (configurable) 	Web app and CLI client access to UCP.
controllers, nodes 	in 	TCP 2375 	Heartbeat for nodes, to ensure they are running.
controllers 	in 	TCP 2376 (configurable) 	Swarm manager accepts requests from UCP controller.
controllers, nodes 	in, out 	UDP 4789 	Overlay networking.
controllers, nodes 	in, out 	TCP + UDP 7946 	Overlay networking.
controllers, nodes 	in 	TCP 12376 	Proxy for TLS, provides access to UCP, Swarm, and Engine.
controller 	in 	TCP 12379 	Internal node configuration, cluster configuration, and HA.
controller 	in 	TCP 12380 	Internal node configuration, cluster configuration, and HA.
controller 	in 	TCP 12381 	Proxy for TLS, provides access to UCP.
controller 	in 	TCP 12382 	Manages TLS and requests from swarm manager.
controller 	in 	TCP 12383 	Used by the authentication storage backend.
controller 	in 	TCP 12384 	Used by authentication storage backend for replication across controllers.
controller 	in 	TCP 12385 	The port where the authentication API is exposed.
controller 	in 	TCP 12386 	Used by the authentication worker.
Compatibility and maintenance lifecycle

Docker Datacenter is a software subscription that includes 3 products:
 CS Docker Engine,
 Docker Trusted Registry,
 Docker Universal Control Plane.

 
 

 Docker for Windows − It allows one to run Docker containers on the Windows OS.

 Docker Engine − It is used for building Docker images and creating Docker containers.

 Docker Hub − This is the registry which is used to host various Docker images.

 Docker Compose − This is used to define applications using multiple Docker containers.
