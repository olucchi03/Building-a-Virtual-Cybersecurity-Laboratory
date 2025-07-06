#  Building-a-Virtual-Cybersecurity-Laboratory

Building a Virtual Cybersecurity Laboratory and Conducting Android Forensics Investigations

## Table of Contents
### 
[Project Expectation](Project-Expectation)

[Downloaded Files and Tools](Downloaded-Files-and-Tools)

[Project Scope](Project-Scope)

[Part I – Virtual Cybersecurity Lab Setup](Part-I–Virtual-Cybersecurity-Lab-Setup)

[Part II – Android Forensics Analysis and Reporting](Part-II–Android-Forensics-Analysis-and-Reporting)

[Part III – Virtual Firewall Implementation](Part-III–Virtual-Firewall-Implementation)

## Project Expectation
I. Set up a fully functional virtual cybersecurity lab

II. Analyze an Android forensic image and produce a professional investigation report

III Deploy a virtual firewall to simulate an enterprise-grade network security Environment.


### Downloaded Files/Tools

The following files were downloaded 
1. Kali iso file 
2. Window 10 iso 
3. Vmware workstation 
4. Autopsy 
5. 7zip
6. Android image provided
7. OPNsense iso
8. Pfsense iso

   See Screenshots below

![IMG_20250626_202340_13](https://github.com/user-attachments/assets/c32d3781-690a-44d5-bc7b-4374cdec459a)
![Screenshot_20250702-204928](https://github.com/user-attachments/assets/a724f525-8ff7-42a4-ad34-fe84fe69dc80)
![Screenshot_20250702-203257](https://github.com/user-attachments/assets/0e15065d-0cb5-465e-afc2-834e006f0a77)
![Screenshot_20250702-203237](https://github.com/user-attachments/assets/fc9d015d-b227-48cd-abd5-6b60a2662d98)
![Screenshot_20250702-205111](https://github.com/user-attachments/assets/d48a9a34-a5d2-4bd6-9f73-4320ad43a692)
![Screenshot_20250702-205332](https://github.com/user-attachments/assets/d3a5c294-dba2-4620-a37c-72c2f0b7f22e)
![Screenshot_20250703-111730](https://github.com/user-attachments/assets/b6835eb3-c926-4dad-9ddd-d69edde68f23)
![Screenshot_20250703-111730](https://github.com/user-attachments/assets/53e0f416-72a4-4267-99c5-11566bfcd06c)
![Screenshot_20250706-201132](https://github.com/user-attachments/assets/e7ea5a91-7988-4c66-8658-8b5e76e8facc)
![Screenshot_20250706-164249](https://github.com/user-attachments/assets/1bb1ebd7-5e27-489b-a596-59967c31655f)
![Screenshot_20250706-222940](https://github.com/user-attachments/assets/0afd24e4-b7c3-415f-81eb-7465eefd9a57)

## PROJECT SCOPE

## Part I – Virtual Cybersecurity Lab Setup

Objective:

To simulate a secure, real-world environment for offensive and defensive security testing through virtual machines.

## Activities:

Virtualization was enabled from the BIOS settings of the Host system (Main System Running on Windows 10 Enterprise Version. Hyper V features was also enabled on the windows settings on the Host machine.
Processor (Host Machine): Core i5

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

see screenshots below 



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
see screenshots below 



Please see attached.pdf file for the comprehensive report.

## Part III – Virtual Firewall Implementation

Objective:
To enhance the lab environment with a virtual firewall for traffic inspection and segmentation.

The following activities were carried out on the VMware

both OPNsense iso and Pfsense were downloaded and extracted

A virtual pfSense appliance was created and the following configured. Configure:
WAN and LAN interfaces
NAT, DHCP, and DNS as needed
Basic firewall rules (e.g., port filtering)
The Kali and Windows VM machines were connected to route traffic through the firewall
Filtering was also done.

see screenshots below 


