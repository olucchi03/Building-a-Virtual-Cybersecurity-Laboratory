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

![Screenshot_20250702-204928](https://github.com/user-attachments/assets/cef97d41-ebac-4ab9-95be-09bbcdf6d372)
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
![IMG_20250626_202340_13](https://github.com/user-attachments/assets/2247f489-6fab-4c4d-bcaf-cb717c7be9c6)
 ![1](https://github.com/user-attachments/assets/103420fa-1e96-4a3c-96ae-b8641fe149d9)
![2](https://github.com/user-attachments/assets/e495adec-ba14-4542-8872-7e965df41b4e)
![3](https://github.com/user-attachments/assets/4e242c82-65ca-490d-a87a-72492e37d640)
![4](https://github.com/user-attachments/assets/1f843139-4d66-4fcc-9ad7-64d03bce072a)
![5](https://github.com/user-attachments/assets/5c6d7fd1-7d9d-414e-bc61-67e9e2f1dc8b)
![6](https://github.com/user-attachments/assets/6ae085bb-9bcd-4917-8e33-544484043fcf)
![7](https://github.com/user-attachments/assets/c87b3a6a-6a2e-4577-892f-418bdceeba40)
![8](https://github.com/user-attachments/assets/60049d3c-5d39-49e9-9b90-77c6e6bd14bc)
![8](https://github.com/user-attachments/assets/41d50678-f307-4fe9-908b-4207279d351d)
![8](https://github.com/user-attachments/assets/4e92358e-84cd-4d42-b11d-e05e0b866c96)
![9](https://github.com/user-attachments/assets/5dcde54e-ca95-45fa-82af-c80653e9ba0c)
![10](https://github.com/user-attachments/assets/66df4b3c-6393-428f-b300-9b374f6c09fa)
![11](https://github.com/user-attachments/assets/54f8e78c-8945-4635-80f8-af8ec10cce34)
attachments/assets/58c6a7b9-0821-4330-8788-48f8fafe8d95)
![Screenshot_20250706-205440_1](https://github.com/user-attachments/assets/de42fd95-9477-45cd-8a48-2a1dcc273665)
![IMG-20250706-WA0017_5]
![IMG-20250706-WA0017_4](https://github.com/user-attachments/assets/cd787ec0-66b9-423f-9726-bb45ab9de75b) 

 ## Part II – Android Forensics Analysis and Reporting

Objective:

To analyze a provided Android forensic image
 compile a formal digital investigation report.
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

both OPNsense iso and Pfsense were downloaded and extracted

A virtual pfSense appliance was created and the following configured. Configure:
WAN and LAN interfaces
NAT, DHCP, and DNS as needed
Basic firewall rules (e.g., port filtering)
The Kali and Windows VM machines were connected to route traffic through the firewall
Filtering was also done.

see screenshots below 


