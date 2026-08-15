# Laboratory 03 – Multi-Cloud Explorer

## Linux Server Investigation

A Linux server was launched using a KillerCoda Ubuntu 24.04 playground. Linux commands were used to identify the operating system, CPU, memory, and disk space of the server.

### Operating System

- **Operating System:** Ubuntu 24.04.4 LTS
- **Version Codename:** Noble Numbat
- **Architecture:** x86_64

### CPU Information

- **CPU:** Intel Xeon E312xx
- **CPU Count:** 1
- **CPU Cores:** 1
- **Threads per Core:** 1
- **Architecture:** x86_64
- **Virtualization:** KVM

### Memory

- **Total RAM:** 1.9 GiB
- **Used RAM:** 413 MiB
- **Available RAM:** 1.5 GiB
- **Swap:** 1.0 GiB

### Disk Space

The main Linux filesystem is `/dev/vda1`, mounted at `/`.

- **Total Disk Space:** 19 GiB
- **Used Space:** 5.4 GiB
- **Available Space:** 13 GiB
- **Disk Usage:** 30%

## Linux Server Cloud Hosting Options

If this Linux server were migrated to the cloud, it could be hosted using the virtual machine services of AWS, Microsoft Azure, or Google Cloud.

### AWS – Amazon EC2

Amazon Elastic Compute Cloud (EC2) provides virtual servers that can run Linux operating systems. The Linux server could be migrated to an EC2 instance with CPU, memory, and storage resources selected according to the application's requirements.

### Microsoft Azure – Azure Virtual Machines

Azure Virtual Machines provides virtual machines that can run Linux distributions. The server could be hosted on an appropriately sized Azure virtual machine and scaled when additional computing resources are needed.

### Google Cloud – Compute Engine

Google Compute Engine provides configurable virtual machines that can run Linux operating systems. The server could be migrated to a Compute Engine instance with the required CPU, memory, and storage resources.

## Conclusion

AWS EC2, Azure Virtual Machines, and Google Compute Engine can all host a Linux server similar to the one tested in KillerCoda. The final provider should be selected based on factors such as cost, performance requirements, existing technologies, location, scalability, and the other cloud services needed by the organization.

## Evidence

Screenshots of the KillerCoda terminal commands and outputs were collected as evidence for this investigation.
