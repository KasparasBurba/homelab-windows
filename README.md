# **Active Directory & Windows Server HomeLab**

## Lab Setup
* **Virtualization:** Oracle VirtualBox (Isolated Internal Network: 'intnet')
* **Server:** Windows Server 2022 (Static IP: 192.168.10.1, acting as Domain Controller, DNS and DHCP)
* **Client:** Windows 10 Pro

## Lab Screenshots & What I Did
1. **Active Directory & User Management**
* **Where:** Active Directory Users and Computers (dsa.msc)
* **What I did:** Created a custom domain (lab.local), set up Organizational Units (OUs) to mimic company departments and added a test user account.
2. **Group Policy (GPO)**
* **Where:** Group Policy Management (gpmc.msc)
* **What I did:** Created and linked a custom Group Policy Object to control settings and apply a restriction across specific department OUs.
3. **DHCP & Network Automation**
* **Where:** DHCP Manager (dhcpmgmt.msc)
* **What I did:** Set up an IPv4 scope (192.168.10.100 to 192.168.10.200) so machines can automatically get IP addresses and network configs without manual setup.

## Skills Practiced
* Setting up a Windows Domain Controller from scratch
* Organizing users and computers into OUs
* Automating IP assignment using DHCP
* Configuring policies with Group Policy
