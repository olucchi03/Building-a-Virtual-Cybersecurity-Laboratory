.# Building-a-Virtual-Cybersecurity-Laboratory
Building a Virtual Cybersecurity Laboratory and Conducting Android Forensics Investigations

## Table of Contents

## Project Expectation
I. Set up a fully functional virtual cybersecurity lab

II. Analyze an Android forensic image and produce a professional investigation report

III Deploy a virtual firewall to simulate an enterprise-grade network security Environment.

## PROJECT SCOPE
Part I – Virtual Cybersecurity Lab Setup

Objective:

To simulate a secure, real-world environment for offensive and defensive security testing through virtual machines.

## Activities:

Virtualization was enabled from the BIOS settings of the Host system (Main System Running on Windows 10 Enterprise Version. Hyper V features was also enabled on the windows settings on the Host machine.
Processor (Host Machine): Core i5

### Downloaded Files/Tools
The following files were downloaded 
1. Kali iso file 
2. Window 10 iso 
3. Vmware workstation 
4. Autopsy 
5. 7zip
6. Android image provided
7. OPNsense Iso

VMware 17 Workstation was downloaded and installed.
Two virtual machines were created

(a) Kali Linux (attacker environment)
RAM: 2 GB
Storage: 20 GB

(b) Microsoft Windows 10 64 bit  (target environment)
RAM: 2 GB
Storage: 60 GB

Internal virtual networking between VMs was established by assigning local Ip addresses to each vm.
Connectivity was tested by pinging the ip addresses of each guest operating system from both VMS.

## Part II – Android Forensics Analysis and Reporting

Objective:

To analyze a provided Android forensic image and compile a formal digital investigation report.
Resources Provided:

Android forensic image file (.zip or .img) containing mock digital evidence

Forensic tools used -  Autopsy

Forensic analysis of the Android image provided was conducted using Autopsy on the Windows 10 VM

The following were extracted and documented:

SMS messages, call logs, contact lists

Application usage history

Files, images, browser history, crypto wallets, deleted content

Please see attached.pdf file for the comprehensive report.

## Part III – Virtual Firewall Implementation

Objective:
To enhance the lab environment with a virtual firewall for traffic inspection and segmentation.

The following activities were carried out on the VMware

Create a virtual pfSense or OPNsense appliance Configure:
WAN and LAN interfaces
NAT, DHCP, and DNS as needed
Basic firewall rules (e.g., port filtering)
Connect the Kali and Windows machines to route traffic through the firewall
Test filtering and logging functionality; document configuration steps and output
