
Puppet Fundamentals
---------------
Fundamentals

Duration: 2days

-----------

### Objective
Objective of this course is to introduce students to what Puppet is, make them familiar with the core concepts, Master/Agent and Standalone modes, and focus on helping them get started to write  Infrastructure as a code.  

### Targeted Audience

This introductory course is targeted for the budding devops professionals,  experienced sysadmins who understand operating systems and linux/unix administration intend to use puppet to automate common infrastructure tasks such as installing and configuring systems, deploy applications, deliver softwares  manage  infrastructures at scale with ease.

### Prerequisites:

*	Basic understanding of linux/unix system concepts
*	Familiarity with Command Line Interface (CLI)
*	Familiarity with a Text Editor
* Basic Systems Administration knowledge

### System Requirements

| Hardware | Software |
| :-------- | :-------- |
| Laptop/Desktop with internet connection | Base Operating System |
| 8GB RAM ( 4GB Min) | VirtualBox |
| 4 CPU Cores  | Vagrant |
| 50 GB Disk Space available |



### Course Outline

*	Introduction to Puppet
*	Setting up Learning Environment
*	Building Blocks - Resources and Manifests
*	Creating Reusable Code - Modules
*	Creating Dynamic Configurations - Template and Variables, Parameterized Classes
* Defined Types
*	Puppet Master/Agent
*	Puppet Forge
* Externilizing Data with Hiera

** Additional Topics if time permits**
* Using Custom Resources and Providers
* Orchestration with MCollective
* Writing Custom Facts


### Detailed Course Contents

**Day I**

*	Introduction to Puppet
  *	Scripts vs Puppet - Introduction to Descriptive Approach
  * Infrastrcuture as a Code
  * Puppet Overview and Features

*	Setting up Learning Environment
  * Introduction to the Tools - Vagrant, VirtualBox
  * Setting up VMs using Vagrant
  * Installing Software - Master, Agent
  * Connecting Agents with the Master

*	Building Blocks - Resources and Manifests
  * Introduction to Puppet DSL
  * Syntax
  * Using Puppet's Resource Shell
  * Creating Resources
  * Writing Manifests
  * Using puppet apply for standalone installation  
  * Introduction to Node Classification

*	Creating Reusable Code - Modules
  * Introduction to Modules
  * Creating Classes
  * Class Naming Conventions
  * Ordering with Meta Parameters
  * Writing Nginx Module with File, Package and Service Resources


**Day II**

*	Creating Dynamic Configurations - Template and Variables, Parameterized Classes
  * Separating Code and Data
  * Overview of Templates and Variables
  * ERB Syntax Primer
  * Working with Variables
  * Inheritance
  * Automatic Variables - Facts
  * Parameterized Classes
  * Extending Nginx Module with Parameterized Classes, Templates and Variables.

* Multiple Instances with Defined Types
  * Defined Types vs Parameterized Classes
  * Multiple Instances
  * Defined Types Examples
  * Enhancing Nginx to support Virtual Hosts with Defined Types

*	Puppet Master/Agent
  * Puppet Master and Agent Configurations
  * Logs
  * Puppet Enterprise

*	Puppet Forge
  * Introduction to Puppet Forge
  * Using Community Modules
  * Puppet Modules Utility
  * Installing NTP Service with Puppet Forge module

* Externilizing Data with Hiera
  * Code vs Data
  * Introduction to Hiera
  * Defining Hierarchy
  * Hiera Demo


### Example Code Manifests/Modules

*	Nginx Module to Install and Configure a Web Server
*	NTP Module
*	Windows specific modules for Puppet
