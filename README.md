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
The Windows 10 virtual machine was downloaded and installed in VirtualBox.  
The VM network adapter was configured as follows:  
Adapter 1  
- Attached to: NAT Network  
- Network:     NatNetwork  

The VM was allocated 2048 MB RAM.

![image alt](https://github.com/benjamin-ngandwe/-virtual-cybersecurity-lab-NETWORKWALKS-B083-WK2/blob/0992ffddceef8e3f9f4b0320470303b5ea110927/Win10.png)

**Configure the Windows 10 Network**  
The Windows 10 network configuration was checked and configured with a static IPv4 address.

![image alt](https://github.com/benjamin-ngandwe/-virtual-cybersecurity-lab-NETWORKWALKS-B083-WK2/blob/main/Win10%20network.png?raw=true)

## Create a Clean VM Snapshot
After completing the initial configuration, a VirtualBox snapshot (Backup) was created.

**Install Android**  
The Android virtual machine was downloaded and installed in VirtualBox.  
The VM network adapter was configured as follows:  
Adapter 1  
- Attached to: NAT Network  
- Network:     NatNetwork  

![image alt](https://github.com/benjamin-ngandwe/-virtual-cybersecurity-lab-NETWORKWALKS-B083-WK2/blob/main/android%20dashboard.png?raw=true)

**Configure the Android Network**  
The Android network configuration was checked and configured with a static IPv4 address.

![image alt](https://github.com/benjamin-ngandwe/-virtual-cybersecurity-lab-NETWORKWALKS-B083-WK2/blob/main/android%20network.png?raw=true)

## Create a Clean VM Snapshot
After completing the initial configuration, a VirtualBox snapshot (Backup) was created.

## Problems Encountered
## Problem 1. Android Bootup  
After completing the Android VM setup, I encountered a boot-related issue where the virtual machine became unresponsive and remained stuck during the initial startup sequence. The issue was resolved by increasing the allocated RAM, disabling 3D acceleration, and increasing the number of virtual CPU cores assigned to the VM.  

## Tools and Resources

- 7-Zip: https://7-zip.org/download.html
- VirtualBox: https://virtualbox.org/wiki/Downloads
- Kali Linux: https://kali.org/get-kali
- Android: https://www.android-x86.org/download

## Author
**Benjamin Ng'andwe**    
Cybersecurity Professional B083  
LinkedIn: https://www.linkedin.com/in/ngandwebenji/

## Project Information
Program Name: Cybersecurity at Networkwalks | Week: 02 | Project: FOOTPRINTING & RECONNAISSANCE ATTACKS WITH MULTIPLE KALI TOOLS | Repository: GitHub
