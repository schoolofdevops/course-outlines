
# Docker  Fundamentals
--------

|      |      |
| :------------- | :------------- |
| Duration       | 2days     |
| Difficulty     | Easy |
| Level          | Beginner |

## Objectives

This course  introduces participants to linux container,  docker and open container eco system . Its intended to  help  participants to get started using docker to build,  package  and run applications.

## Who is this for ?
This course is intended for anyone who is part of the software delivery process and would like to get started using docker in their workflows to build, ship and run applications with containers.

This includes developers, qa and ops  professionals alike who are part of the software delivery process either as part of developing applications, creating  tests or part of the ops team in charge of deploying applications or automation team which enables developers to create their workflows.  

## What will you do as part of this course ?

As part of this course you will,  

   * Learn what linux containers are, what is docker and get an overview of  open container eco system.
   * Setup a local docker development environment
   * Launch containers, publish ports and connect to the applications running inside containers
   * Learn basic container operations and troubleshooting
   * Build docker images with best practices for  web application, create optimal dockerfiles
   * Learn single host container networking and volumes primitives.
   * Launch multi container application stacks with interlinked application.
   * Create specifications for setting up automated development environments with Docker Compose
   * Get a quick overview of Container Orchestration Engine (COE) functionality with Kubernetes/SWARM.

## What will you not learn ?

Since this course is a beginner level, its not meant to cover advanced concepts such as,

  * Advanced Container Orchestration
  * Container Security
  * Logging and Monitoring setup for container based systems
  * Multi Host Networking/Overlay/CNI
  * Writing Micro Services Applications
  * Customising Docker Installation and Setup
  * Production grade docker setup and deployment
  * Custom registries, base images etc.
  * Cloud Integrations
  * Network storage and persistence


## Pre Requisites

Following are the pre requisite skills to attend this course. Since its a beginner level course, no prior experience with linux containers is assumed.  

### Skills

* Linux/Unix Systems Fundamentals
* Familiarity with Command Line Interface (CLI)
* Fundamental knowledge of editors on linux (any one of vi/nano/emacs)

### Hardware and Software  Requirements

These are the prerequisites for each attendee.

| Hardware Requirements | Software Requirements |
| :---------------------| :--------------------- |
| Laptop/Desktop with high speed internet connection | Base Operating System : Windows / Mac OSX |
| 8 GB RAM | Docker for Mac/Windows  |
| 4 CPU Cores | For windows versions < 10, Docker for Windows |
| 20 GB Disk Space available | ConeEmu (Windows Only) |
| | Git for Windows (windows only) |


## Supporting Materials

Following is the supporting material which will be provided to you before/during the course
  * Slides (online)
  * Workshop (online link)
  * Video Course - Zero to Docker by School of Devops
  * Reading List : Reference Material

## Pre Class Checklist (Must)

All participants should have completed the following checklist before attending the course .

  * Watch  "Docker Mini Course" videos. This covers the introduction to Docker and the theory related to containers, key features, advantages and workflow.
  * Verify  your system meets the  hardware pre requisites.
  * Validate the setup : verify all pre requisite software is installed on your system and is functional.


## Topics
Following are the topics which would be covered as part of this course. Detailed course outline follows.

  * Course Introduction and Use Case
  * Pre-assesment  
  *	Validating Learning Environment
  *	Launching and Operating Containers
  *	Building Docker Images
  *	Docker Networking
  *	Docker Storage
  *	Launching Multi Container Apps with Compose

##  Detailed Course Outline

This is the detailed course outline with day wise list of contents. 

*	Introduction to Containers and Docker
*	Containers vs Hypervisors
*	Evolution of Containers
*	Docker Story
*	Docker Architecture
*	Under the hood
	- Namespaces
	- Control Groups
	- Union File System
	- Libcontainer
*	Setting up Learning Environment
	-	Installing Prerequsites:-

		-  	Virtualbox
		-	GIT For Windows

 - 	Installing Boot2docker
 -  Installing Kinematic
 -  Installing Docker Machine
 -  Creating Docker Hub Account
 -  Validating The Setup
*	Getting Familiar with Docker
 - Using docker shell
 - Connecting to docker daemon
 - Docker Commands
 - Running Ephemeral Container
 - RunningInteractive Containers
 - Running  Persistent Containers
*	Working with Containers
	- Launching a Application Container with an existing image
	- Container Operations

		- Run
		- Inspect
		- Check Logs
		- Stop
		- Delete
		- Attach
	-	Network Port Mapping
*	Working with Images
	 - 	Docker Image Basics
	 -  Working with Docker Hub Registry
	 -  Image Operations

		- List
		- Search
		- Pull

   - Customising Image Manually
	- Committing Image to Docker Hub Registry
	- Building Image Automatically with Dockerfile
	-	Private Docker Registry Overview
* Dockerfile Primer
	- 	Dockerfile Basics
	-	Dockerfile Anatomy
	-	Dockerfile Instructions

	  - 	FROM
	  -  MAINTAINER
	  -  RUN
	  -  LABEL
	  -  ENV
	  -  ADD
	  -  COPY
	  -  EXPOSE
	  -  VOLUME
	  -  USER
	  -  WORKDIR
	  -  ONBUILD
	  -  CMD
	  -  ENTRYPOINT
*	Connecting Containers
	-	Connecting Containers with Network Port Mappings
	-	Linking System for Inter Container Communication
	-	Discovery with environment variables
	-	Advanced Docker Networking
* Container Data Management
	-	Managing Data for Containers
	-	Creating Data Volumes
	-	Using Data Volume Container
*	Launching Multi Container Apps with Compose
	-	Docker Compose Overview
	-	Running Multi Container Apps
	-	Using Compose
*	Creating Multi Node Cluster with Swarm
	-	Swarm Overview
	-	Clustering Nodes with Swarm
	-	Discovery Services
	-	Using Swarm to cluster docker hosts
*	Working with Docker Registry
	-	Docker Registry Types
	-	Trusted Registry vs Open Source Registry  
	-	Configuring Security and TLS for Registry
	-	Working with Local Registries

*	Docker Eco System
