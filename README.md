# virtual-cybersecurity-lab-NETWORKWALKS-B083-WK2
VirtualBox and Kali Linux lab environment for penetration testing, vulnerability assessment, and cybersecurity practice.
## Project Overview
This project focuses on setting up a virtual cybersecurity and penetration-testing lab using VirtualBox and Kali Linux.
## Objectives
- Install Android and Windows 10 VMs
- Assign static IPs on Windows 10 and Android VMs
- Test connectivity and DNS resolution
- Take a snapshot of the VMs
- Install Zenmap on Windows 10 VM for network scanning
- Footprint the live website networkwalks.com using six built-in Kali Linux tools
## Purpose of Lab
The purpose of this lab is to gather information about the live website networkwalks.com using six Kali Linux tools: WHOIS, WhatWeb, Nslookup, Curl, Wafw00f, and DNSRecon. Each tool provides different information about the target, helping to build a basic security profile. The findings will be used in later tasks for scanning, security testing, and reporting. 

⚠️ Important: This laboratory must only be used for systems that you own or have explicit permission to test. Do not use the lab or its tools to attack unauthorized systems.

## Lab Architecture
![image alt](https://github.com/benjamin-ngandwe/-virtual-cybersecurity-lab-NETWORKWALKS-B083-WK2/blob/main/lab%20arch.jpg?raw=true)  
Additional target machines can be added to the same virtual network in future projects.
## Lab Configuration
![image alt](https://github.com/benjamin-ngandwe/-virtual-cybersecurity-lab-NETWORKWALKS-B083-WK2/blob/main/lab%20setup.png?raw=true)
## Lab Setup Procedure
**Install Windows 10**  
The Windows 10 virtual machine was downloaded installed in VirtualBox.  
The VM network adapter was configured as follows:  
Adapter 1  
- Attached to: NAT Network  
- Network:     NatNetwork  

The VM was allocated 2048MB RAM.
