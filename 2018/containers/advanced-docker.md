# Advanced Docker
---------
|       |       |
| :------------ | :------------ |
| Duration      |         |
| Difficulty    |         |

## Objectives

## Who is this for?

## What will you do as part of this course?

## Prerequisites

## Skills

## Hardware and Software Requirements

## Supporting Materials

## Pre Class Checklist (Must)

## Topics
Following are the topics which would be covered as part of this course. Detailed course outline follows.

  * Custom Docker Installation and Configuration
  * Introduction to Use Case - Mogambo.com
  * Building Custom Base Images
  * Deploying a Custom Registry - Harbor
  * Building and Distributing Secure Images
  * Securing Container Runtimes
  * Continuous Integration with Docker
  * Setting Up Monitoring
  * Centralized Log Management

## Detailed Course Outline
This is the detailed course outline with day wise list of contents

#### Module 1: Custom Docker Installation and Configuration
    - Setup a linux VM
    - Install Docker with package manager
    - Install Docker Compose
    - Docker daemon configuration
    - Run Docker on a port with certs
    - Configure local docker client to talk to remote server with certificates
#### Module 2: Introduction to Use Case - Mogambo.com
    - Mogambo - the XXXXXXX and the application
    - Overview of the Architecture
    - Code overview and the best practices the developers can incorporate
        * Application Repositories
        * Dockerfiles
        * Compose Specs
        * Makefiles
    - Demo of build, test, deploy etc.,
    - Local image distribution with load/save
#### Module 3: Building Custom Base Images
    - Parent images Vs Base images
    - Building a custom image with scratch
    - Creating a custom Ubuntu image with the bootstrap
    - Creating a CentOS image using a scripted approach
#### Module 4: Deploying a Custom Registry - Harbor
    - Introduction to Harbor by VMware
    - Install and Configure Harbor
    - Harbor Walkthrough
    - Working with a custom registry
    - Push/Publish images to Harbor
#### Module 5:Building and Distributing Secure Images
    - Dockerfiles with USER and gosu / COPY Vs ADD
    - Registry with RBAC
    - Vulnerability Scanning for Images
    - Enabling Content Trust
    - Using Notary to sign images
#### Module 6: Securing Container Runtimes
    - Host Security
        * SELinux
        * Apparmor
        * Updates & Patches
        * Linuxkit & Infrakit
    - Run Docker Bench Script for security scan
    - Securing Docker Daemon
        * Network traffic
        * Logging level
        * TLS
        * Ulimit default
    - Securing Container Runtime
        * Security Options
        * Memory and CPU restrictions
        * Restart, Policies
        * Ulimits
        * Capablities
#### Module 7: Continuous Integration with Docker
    - Docker based build, test, unit tests, e2d tests, setup for Mogambo
    - Makefiles & Scripts
    - Setting up CI env with Jenkins
    - Setup a pipeline
        * Build
        * Unit Tests
        * Functional Tests
        * e2e Tests
    - Tag, Push and Publish Images
#### Module 8: Setting Up Monitoring
    - Monitoring Containers, Hosts and Applcations
    - Prometheus
    - Adding Grafana for web UI
#### Module 9: Centralized Log Management
    - Docker Log drivers
    - Setup ELK Stack or equivalent
    - Launching containers with log drivers
