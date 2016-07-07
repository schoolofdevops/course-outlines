Containers Workshop - Docker, Kubernetes - FT
--------

2 days fast track  workshop

###Objectives

This workshop introduces participants to concepts of containers,  docker and its eco system . and   help them get started using docker to build, ship and run applications inside containers.

###Intended Audience
This course is intended for developers, qa and ops  professionals alike who are developing applications,  involved in CI/CD cycles, software delivery or managing  infrastructure deployments and intend to progress  their knowledge with the next generation container technologies to automate and expedite the workflows.

###Pre Requisites
* Linux/Unix Systems Fundaments
* Familiarity with Command Line Interface (CLI)
* Fundamental knowledge of editors
* Understanding of software development, delivery and or infrastructure management

###Systems Requisites

These are the systems prerequisites for setting up lab environment for this training.

| Hardware Requirements | Software Requirements |
| :---------------------| :--------------------- |
| Laptop/Desktop with high speed internet connection | Base Operating System : Windows / Mac OSX |
| 8 GB RAM | VirtualBox |
| 4 CPU Cores | Vagrant |
| 20 GB Disk Space available | Docker Toolbox |


### Topics Summary
* Introduction Containers, Docker and the Eco System
*	Setting up Learning Environment
*	Getting Started - Fundamental Docker Operations
*	Rapid Provisioning of Apps with Docker
*	Dockerizing your Apps - Building Images, Dockerfile
* Connecting the dots - Building and Launching Multi Container Application Stacks with Container Linking, Docker Compose
*	Clustering and Orchestration Overview - Swarm, Kubernetes, ECS
* Kubernetes Quick Dive

###Detailed Course Outline

##### Introduction to Containers and Docker
  *	Containers vs Hypervisors
  *	Evolution of Containers
  *	Docker Story
  *	Docker Architecture
  *	Under the hood
	  - Namespaces
	  - Control Groups
	  - Union File System (Layering Concept)
	  - Libcontainer
  * Docker Eco System

##### Setting up Learning Environment
	-	Installing Prerequsites:-
		- Virtualbox
		-	GIT For Windows
    - Vagrant
  - Installing Docker Toolbox
  - docker-machine Primer
  - Creating Docker Hub Account
  - Validating The Setup

##### Getting Started - Fundamental Docker Operations
  * Using docker shell
  * Connecting to docker daemon
  * Docker Commands
  * Running Ephemeral Container
  * Running Interactive Containers
  * Making Containers Persist
  * Stop, Start, Remove Containers

##### Rapid Provisioning of Apps with Docker
  * Launching Application Containers with pre built images
  * Docker Registry Primer
  * Accessing Apps from outside - Network Port Mapping
  * Container Management Operations
		* Run
	  * Inspect
	  * Check Logs
	  * Stop
	  * Delete
	  * Attach

##### Dockerizing your Apps - Building Images, Dockerfile
  * Docker Image Basics
  * Working with Docker Hub Registry
  * Image Operations
	  * List
	  * Search
	  * Pull
  * docker commit - Building docker image manually
  * docker build  - building image automatically
  * Dockerfile Primer
    * Anatomy of a Dockerfile
    * Instruction Types
  *	Private Docker Registry Overview
  * Pushing  image to Docker Hub

##### Connecting the dots - Building and Launching Multi Container Application Stacks. Container Linking, Docker Compose
  *	Connecting Containers with Network Port Mappings
  *	Container linking system for inter container communication
  *	Automatic Discovery with environment variables
  *	Advanced Docker Networking
  * Container Data Management
  * Docker Compose - Automated approach to launch multi container application stack
  *	Docker Compose File 2.0 Primer
     - Stacks
     - Networks
     - Apps
     - Links
     - Dependencies
  *	Writing docker-compose specifications
  * Launching, scaling and managing stacks

##### Clustering and Orchestration Overview - Swarm, Kubernetes, ECS
  * Container Orchestration : building clusters to run containers
  * Orchestration Tools
    * Docker Swarm
    * Kubernetes
    * Amazon ECS
  *	Discovery Services - etcd/consul/zookeeper
  * Swarm - Native Clustering Tool by Docker
    * Tokens/Discovery Backend
    * Docker Machine to launch swarm nodes
    * Swarm Strategies
    * Demo of building  Swarm Cluster

##### Kubernetes Quick Dive - Production Grade Container Orchestration by Google
  * Introduction to Kubernetes
  * Key Features/Advantages
    * Horizontal Scaling
    * Optimal Scheduling (binpacking)
    * Rolling Updates and Auto Rollbacks
    * Self Healing
    * Multi Storage Support
    * Service Discovery and Load Balancing
    * Batch Execution
  * Kubernetes concepts
    * Pods
    * Nodes
    * Replication Controllers
    * Services
    * Discovery Backends
    * kubectl
  * Setting up a simple Kubernetes Cluster
    * Installing Kubernetes
    * using kubectl
    * Kubernetes Operations
