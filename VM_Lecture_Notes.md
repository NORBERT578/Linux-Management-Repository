# **<ins> Assignment No.</ins>**
Virtual Machine is a software based emulation of a physical computer that runs its own operating system and applications.

* Virtual machines run on hypervisors that allocate physical resources for example CPU, memory and storage to each guest OS.

* Enables rapid provisioning, scaling and isolation of workloads.

* Ideal for testing Linux environments without dedicated hardware.

## What Is a Cloud Platform ?
Cloud Platform: is an online environment that provides infrastructure, tools and services for developing and managing applications over the internet.

***Key characteristics :***

* ***Scalability*** – resources can be expanded or reduced on demand.

* ***Accessibility*** – services reachable from anywhere with an Internet connection.

* ***Flexibility*** – supports multiple operating systems, languages, and frameworks.

## Benefits of Cloud Platforms.

* ***Reduced hardware costs*** – no need to purchase, maintain, or upgrade physical servers.

* ***Rapid scaling*** – resources can be increased or decreased instantly to match demand.

* ***High availability*** – built‑in redundancy and failover mechanisms.

## Provider Services Offered.

| Provider | Service Portfolio | Market Position |
|---------|------------------|-----------------|
| Amazon Web Services (AWS) | IaaS, PaaS, SaaS | Leading provider |
| Microsoft Azure | IaaS, PaaS | Strong growth |
| Google Cloud Platform (GCP) | IaaS, PaaS | Innovative features |
| IBM Cloud | IaaS, PaaS, SaaS | Enterprise focus |

## Step 1: Azure Account with a 100$ Credit. 
I first created an account at [Azure Portal](https://portal.azure.com/) using my HAMK student credentials. Then i activated my Azure for students to be eligble for the free  100$ credit. 

## Step 2: Create Resource Group 
I made a resource group named Linux management-1 in Sweden Central server. 

## Created the Virtual Machine
Setup used :

* Image: Ubuntu Server 24.04 LTS
* Size: Standard D2s v3
* Name: prade-ubuntu-LinuxLearning
* Authentication: SSH key
* Allowed SSH from my IP

  Then the Virtual Machine came to life fully operational.

  This is an overview of the Virtual Machine:
![Virtual Machine](https://github.com/pradeepsapkota-dot/Linux-learning/raw/main/Images/Virtual%20machine.png)

## Step 4: Connected with SSH using PuTTY
I downloaded PuTTY from the official site.
Took the public IP from Azure → opened PuTTY → entered IP + username + loaded my SSH key.

This is how it looked like after:
![Ubuntu](https://github.com/pradeepsapkota-dot/Linux-learning/raw/main/Images/Disk.png)

## Step 5: Connected to the terminal
Now that all the necessary steps has been taken into consideration,I can now run my Virtual Machine in my terminal. With the lecture's guidance, I also created a shortcut key so that i can access the Virtual Machine in the terminal smoothly when needed.









