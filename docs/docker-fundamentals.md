
# Docker  Fundamentals
--------

|      |      |
| :------------- | :------------- |
| Duration       | 2days     |
| Level     | Beginner |
| Modules          | 08 |
| Nano Projects | 04 |
| Flipped Class | No |
| Customizable  | Yes |

## Objectives

This course  introduces participants to linux container,  docker and open container eco system . Its intended to  help  participants to get started using docker to build,  package  and run applications.

## Who is this for ?
This course is intended for anyone who is part of the software delivery process and would like to get started using docker in their workflows to build, ship and run applications with containers.

This includes developers, qa and ops  professionals alike who are part of the software delivery process either as part of developing applications, creating  tests or part of the ops team in charge of deploying applications or automation team which enables developers to create their workflows.  

## Who is this not for ?

  * If you are a advanced user of docker already, this course is definitely not for you.
  * If you already know the fundamentals of docker, mainly the concepts listed below,  but would like to know advanced concepts, you may want to enroll for Docker Advanced course instead.
  * If you are interested in learning docker on windows, this course is not ideal for you as it focuses on linux containers, even though docker is now supported on windows.


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

## What is not covered ?

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
* Understanding of YAML syntax and familiarity with reading/writing basic YAML specifications


### Hardware and Software  Requirements

These are the prerequisites for each attendee.

| Hardware Requirements | Software Requirements |
| :---------------------| :--------------------- |
| Laptop/Desktop with high speed internet connection | Base Operating System : Windows / Mac OSX |
| 8 GB RAM | Docker for Mac/Windows  |
| 4 CPU Cores | For windows versions < 10, Docker for Windows |
| 20 GB Disk Space available | ConEmu (Windows Only) |
| | Git for Windows (windows only) |
| | Minikube |

Lab Setup : Instructions can be found at xxx

## Supporting Content/Materials

Following is the supporting material which will be provided to you before/during the course  

  * Slides (online)  
  * Workshop (online link)  
  * Video Course - Zero to Docker by School of Devops  

## Pre Class Checklist

All participants should have completed the following checklist before attending the course .

  * Watch  "Docker Mini Course" videos by School of Devops. This covers the introduction to Docker and the theory related to containers, key features, advantages and workflow.
  * Verify  your system meets the  hardware pre requisites.
  * Validate the setup : verify all pre requisite software is installed on your system and is functional.
  * Join our [docker channel on gitter](https://gitter.im/schoolofdevops/docker?utm_source=share-link&utm_medium=link&utm_campaign=share-link)

## Topics
Following are the topics which would be covered as part of this course. Detailed course outline follows.

  * Course Introduction and Use Case
  * Introduction to Docker
  *	Validating Learning Environment
  *	Launching and Operating Containers
  *	Dockerizing your applications - building docker images
  *	Docker Networking
  *	Docker Storage
  *	Launching Multi Container Apps with Compose
  * Container Orchestration Quick Dive

Additional Topics if time permits

  * Docker eco system
  * Docker log drives

##  Detailed Course Outline

This is the detailed course outline with day wise list of contents.

### Day I  

#### Module1 : Introduction to Containers and Docker
  *	Containers vs VMs
  *	Under the hood
	  * Namespaces
	  * Control Groups
	  * Overlay File System
  * Advantages of using a Container
  *	Evolution of Containers
  *	Docker Story
  *	Docker Workflow


#### Module 2: Validating Learning Environment
  * Validating Setup
		* Docker for Mac/Windows or
		* Docker Toolbox


#### Module 3: Launching and Operating Containers
  * Docker CLI
    * Using docker cli
    * Display information about docker setup  
  * Basics of Docker Images
    * Registry - Docker Hub
    * Image format
  * Run a container
    * Ephemeral Container
    * Container with interactive options
    * With detach mode
  * Basic Operations
    * inspect
    * logs
    * exec
    * copy
    * stop
    * rm
    * attach
    * detach
  * Advanced Container Operations
    * Port Mapping
    * Limiting Resources
      * memory
      * cpu
    * Defining restart policies


**Nano Project** : Launch portainer.io management app with docker, connect to it and use it to manage local docker environment.

#### Module 4 : Dockerising your applications - building docker images
  * Docker image basics
  * Approaches to build images
    * imperative approach
    * declarative approach
  * Building an image with imperative approach and docker commit
  * Building an image with dockerfile and docker build
  * Dockerfile Primer
    * How to create dockerfiles
    * Overview of Instructions
    * Dockerfile Demos

**Nano Project** : Provided with the source code, build a dockerimage for facebooc clone. Its an app written in C which uses sqlite as a database backend

  * Multi stage builds
  * Automated builds with DockerHub and Git

### Day II   

#### Module 5: Docker Networking and storage
  * Container networking concepts: how docker networks a container
  * Single host network modes
    * bridge
    * host
    * none
  * Multi host networking conceptual overview  

#### Module 6: Docker Storage
  * Local storage and persistent volumes
  * Types of volumes:
    * automated
    * named volumes
    * host path

  * Overview of persistent storage in multi host env

#### Module 7: Launching and connecting Micro services with Compose
  * Overview of docker compose
    * Run time configurations
    * Linking applications
  * Writing compose v1 spec to define multi app stack
  * Converting to v3 spec  


#### Module 8: Container Orchestration Quick Dive
  * Container Orchestration Concepts
    * Why do you need a COE
    * COE Options and Comparison   
  * Kubernetes Overview
    * What is kubernetes ?
    * Features
  * Key Concepts
    * Pods
    * Labels and Selectors
    * Services
    * Deployments  
  * Setup Minikube
    * Minicube run down
    * Setup minikube environment
    * Validate kubernetes setup
  * Deploy Voting application with minikube
    * Launch and operate a Pod
    * Create deployments
    * Expose an app with the Service
    * Create a Zero downtime deployment

**Nano Project** : Complete the kubernetes yaml spec given with **k8s-code** repo for deploying voting application stack. Once complete apply it with kubectl.  Validate all serivces are up and running.

## Reading List

Here is the list of curated resources which you could refer to to learn about docker before the training and  and get an in depth understanding post training.  

### Pluralsight Courses
  * [Getting Started with Docker](https://www.pluralsight.com/courses/docker-getting-started) by Nigel Poulton
  * [Docker and Container](https://www.pluralsight.com/courses/docker-containers-big-picture), the Big Picture by Nigel Poulton

### Safaribooks Online
  * Docker: Up & Running by Karl Matthias, Sean P. Kane by Oreilly
  * Using Docker by Adrian Mouat, Oreilly

### Tutorials
  * [Tutorials with Live Environment](https://www.katacoda.com/)
  * [Labs by Docker](https://github.com/docker/labs)
  * [Docker Tutorials by hacks.io]( https://hackr.io/tutorials/learn-docker)

### Articles
  * The Docker Story [How Docker Escaped Near-Death To Become Software’s Next Big Thing](
http://www.forbes.com/sites/alexkonrad/2015/07/01/how-docker-escaped-near-death-to-become-softwares-next-big-thing/)
