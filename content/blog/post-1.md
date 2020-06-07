---
title: "Introduction to Cloud Computing"
date: 2020-06-06
draft: false

# post thumb
image: "images/featured-post/post-1.jpg"

# meta description
description: "this is meta description"

# taxonomies
categories: 
  - "Cloud Computing"
tags:
  - "Cloud Computing Basics"
  - "Virtualization"
  - "ITInfra"

# post type
type: "featured"
---

## Basic Cloud Concepts

### What is cloud computing ?
Cloud computing is the on demand availability of computer system resources, especially data storage and computing power, without direct active management by the user. The term is generally used to describe data centres available to many users over the Internet.

## Advantages Of Cloud Computing

*	Cost saving 
*	Security
*	Flexibility
*	Mobiliy
*	Disaster Recovery
*	Automatic software updates
*	Large number of services available for use.

## Networking Concepts For Cloud Computing

### Linux Namespaces

A namespace is a way of scoping a particular set of identifiers. Using a namespace, you can use the same identifier multiple times in different namespaces. You can also restrict an identifier set visible to particular processes.
At a high level, Linux namespace allow for isolation of global system resources between independent processes. For example, the PID namespace isolates the process ID numberspace. This means that two processes running on the same host can have the same PID.

### Network Namespaces

In a network namespace, the scoped identifiers are network devices; so a given network device, such as eth0, exists in a particular namespace. Linux starts up with a default network namespace, so if your operating system does not do anything special, that is where all the network devices will be located. However, it is also possibleto create further non-default namespaces, and create new devices in those namespaces, or to move an existing device from one namespace to another.

### Overlay Networks

Overlay network is a network spread over another network. For example, any application that has or provides services and is in a client server architecture is an overlay network over the internet.
 
## Storage Concepts For Cloud Computing 

### Storage Virtualization

In computer science, storage virtualization is the process of presenting a logical view of the physical storage resources to a host computer system,treating all storage media (hard disk, optical disk, tape, etc.) in the enterprise as a single pool of storage.

### Storage Types

*	SAN : Storage area Network ( Fibre optics)
*	DAS : Direct attached storage ( Physical hard drive)
*	NAS : Network attached storage ( NFS)
 

## Cloud Computing Deployment Models 

__Public Cloud__: The public cloud is defined as computing services offered by third-party providers over the public Internet, making them available to anyone who wants to use or purchase them. They may be free or sold on-demand, allowing customers to pay only per usage for the CPU cycles, storage, or bandwidth they consume.

__Private Cloud__: A private cloud is a particular model of cloud computing that involves a distinct and secure cloud based environment in which only the specified client can operate.

__Hybrid Cloud__: Is a cloud-computing environment that uses a mix of on-premises,private cloud and third party, public cloud services with orchestration between the two platforms

__Community Cloud__: A community cloud in computing is a collaborative effort in which infrastructure is shared between several organizations from a specific community with common concerns (security, compliance, jurisdiction, etc.), whether managed internally or by a third party and hosted internally or externally. This is controlled and used by a group of organizations that have shared interest. The costs are spread over fewer users than a public cloud (but more than a private cloud), so only some of the cost savings potential of cloud computing are realized.


## Cloud Computing Service Delivery Model

__IAAS (Infrastructure as  a service__) : IaaS is the lowest-level cloud service paradigm and arguably the most important. With IaaS, pre-configured hardware resources are provided to users through a virtual interface. Unlike PaaS and SaaS, IaaS doesn’t include applications or even an operating system (implementing all of that is left up to the customer), it simply enables access to the infrastructure needed to power or support that software. IaaS can provide extra storage for corporate data backups, network bandwidth for a company website server, or it can even enable access to high power computing which was previously only accessible to those with supercomputers. Popular IaaS offerings like Amazon EC2.

__PAAS (Platform as a service)__ :  a cloud service model where the cloud is used to deliver a platform to users from which they can develop, initialize and manage applications. PaaS offerings typically include a base operating system and a suite of applications and development tools. PaaS eliminates the need for organizations to build and maintain the infrastructure traditionally used to develop applications.

__SAAS (Software as a service )__: Sometimes referred to as ‘on-demand software’, SaaS is a software licensing and delivery model where a fully functional and complete software product is delivered to users over the web on a subscription basis. SaaS offerings are typically accessed by end users through a web browser (making the user’s operating system largely irrelevant) and can be billed based on consumption or, more simply, with a flat monthly charge. Example ServiceNow.

