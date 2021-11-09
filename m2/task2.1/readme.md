#Task 2.1
## Part 1
#### 1.What are the most popular hypervisors for infrastructure virtualization?
The most popular hypervisors are vmWare vSphere, Microsoft Hyper-V, Citrix XenServer.
##### VMware ESXI
Have a free version with limited functional. It allows to consolidate a limited number of operating systems on one computer, and it cannot be managed through a central management server - vCenter.

Currently, the free VMware Free vSphere Hypervisor has no host processor or memory limits. But there are a number of other restrictions:

1. Product APIs are read-only.
1. A virtual machine can have a maximum of 8 vCPUs.
1. Cannot be used in conjunction with Veeam to create backups.
1. Connection to vCenter Server not supported
1. VM host live migration, VM storage live migration technologies are not supported, and high availability is not supported.
##### Hyper-V
Absolutely free, but:

1. All virtual machines running Windows must be licensed.
1. There is no graphical interface, however, there is a remote console.
1. Lack of manufacturer support (but there are updates).
##### XenServer
Open source and based on Linux environment.
XEN has two of the most significant features: paravirtualization and minimal code of the hypervisor itself.

##Part 2

I completed all the tasks of the second part. Created a virtual machine, cloned it, played with snapshots and export, etc.

I see no reason to make a table of possible connections because it is presented in Lecture2.2 pdf.

## Part 3

I installed vagrant and played with it.

Possibility to create ready-to-work virtual machine in one click looks pretty useful.
