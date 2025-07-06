# Building-a-Virtual-Cybersecurity-Laboratory
Building a Virtual Cybersecurity Laboratory and Conducting Android Forensics Investigations

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

### Downloaded Files/Tools
The following files were downloaded 
1. Kali iso file 
2. Window 10 iso 
3. Vmware workstation 
4. Autopsy 
5. 7zip
6. Android image provided 

VMware 17 Workstation was downloaded and installed.
Two virtual machines were created
(a) Kali Linux (attacker environment)
(b) Microsoft Windows 10 64 bit  (target environment)
Internal virtual networking between VMs was established by assigning local Ip addresses to each vm.
Connectivity was tested by pinging the ip addresses of each guest operating system from both VMS.
Minimum System Specifications (per VM):
RAM: 2 GB (minimum)
Storage: 20 GB
Processor: Dual-core or higher
Note: BIOS-level virtualization must be enabled for optimal performance.
Part II – Android Forensics Analysis and Reporting
Objective:
To analyze a provided Android forensic image and compile a formal digital investigation report.
Resources Provided:
Android forensic image file (.zip or .img) containing mock digital evidence
Forensic tools (e.g., Autopsy)
Tasks:
Conduct forensic analysis of the Android image:
Extract and document:
SMS messages, call logs, contact lists
Application usage history
Files, images, browser history, crypto wallets, deleted content
Generate a comprehensive Forensics Investigation Report including:
Methodology and tools used
Screenshots and findings
Conclusion and professional recommendations
Part III – (Optional) Virtual Firewall Implementation
Objective:
To enhance the lab environment with a virtual firewall for traffic inspection and segmentation.
Tasks:
Create a virtual pfSense or OPNsense appliance Configure:
WAN and LAN interfaces
NAT, DHCP, and DNS as needed
Basic firewall rules (e.g., port filtering)
Connect the Kali and Windows machines to route traffic through the firewall
Test filtering and logging functionality; document configuration steps and output

3. DELIVERABLES
4. 
Cyber Lab Documentation: Setup screenshots and descriptions
Forensics Report (PDF):
Toolset used
Analysis methodology
Extracted evidence and key findings
Summary and recommendations
(Optional) Firewall configuration overview and test screenshots

5. Expected Learning Outcomes
Upon successful completion of the project, participants will be able to:
Build and configure virtual cybersecurity testing environments
Perform foundational mobile device forensics
Document findings using industry-standard reporting practices
(Optional) Understand and deploy basic firewall security in simulated enterprise networks
