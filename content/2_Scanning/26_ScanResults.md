---
title: "Scan Results Review" 
chapter: true
weight: 6 
---

# Scan Results Review

**Once the discovery is done, all the data (servers and services scanned) will be populated in the IT Explorer view in the UI.**

From the computer systems, processes, and communication details captured, the following sub-sections of data are created:
* Services
* Servers
* Found Groups
* Applications
* Found Applications

![IT Universe](/images/ituniverse.PNG)

### Services
Services identify groups of related applications that provide one or more functions.  

![Services](/images/services.PNG)

For instance, a Microsoft Exchange system is made of a number of Exchange Servers and Stores that together, form a single system providing an email Service. 
The set of WebServers, Application Servers, and Database Servers provide a merchant WebSite from an eCommerce Service.

### Servers
The CloudSphere Platform allows capturing Physical and Virtual Servers, Cloud Instances, Operating System level, and Virtualization level Clusters, as well as Containers (like Docker).

* Servers overview tab - contains the details of the server, including the OS details and hardware details.
* Communication tab - provides the communication of the server with other servers and applications.

![Servers](/images/servers.PNG)

### Found Groups

* Found Groups are auto-generated by Cloudsphere to provide hints on potential services.
* They capture communicating found applications and a few application components to show the relationship.
* They are built and maintained in real-time as Communication and/or FoundCommunication relationships are created and removed.
* These generated found groups can be converted to service by means of fingerprinting and templating.
* A group could also be a service that has not been fully identified (i.e. a potential service).

### Applications & Found Applications
* Applications - capture software such as Web Servers, Application Servers, Mail Servers, Database Servers, Middleware (MoM, Message Servers, Directory Servers), etc.
* Application Clusters - capture a group of homogenous Applications that together provide a service to client applications. Ex Database Clusters, Messaging system clusters, Hadoop Clusters, etc.
* Found Applications - are the processes that are communicating with each other, are potential applications, and can be converted into applications by means of fingerprinting.


#### **Great Job!!** <!-- MODIFY THIS HEADING -->
You've completed the first module of the Migration Planning workshop.  From here, we'll move on to the second module, Deep Data Exploration.  We hope you found this training helpful and look forward to engaging in the second portion of this workshop!

