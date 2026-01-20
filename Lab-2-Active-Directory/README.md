## Objective
The purpose of this lab was to set up a Windows Server Domain Controller using Active Directory Domain Services (AD DS). 
This simulates a real-world enterprise environment where user authentication, authorization, and centralized management are required.

## Lab Environment
- Host OS: Windows 10/11
- Virtualization: Oracle VirtualBox Manager
- Server OS: Windows Server 2019 / 2022
- Domain Name: lab.local
- Server Name: DC01

## Tasks Performed
- Renamed Windows Server to DC01
- Configured a static IP address
- Installed Active Directory Domain Services (AD DS)
- Promoted the server to a Domain Controller
- Created a new Active Directory forest (lab.local)
- Installed and configured DNS services
- Verified Active Directory and DNS functionality

## Validation
- Successfully logged in using LAB\Administrator domain account
- Confirmed domain visibility in Active Directory Users and Computers
- Verified DNS zone creation for lab.local

## Skills Demonstrated
- Active Directory administration
- Windows Server configuration
- DNS configuration and troubleshooting
- Virtualization using Oracle VirtualBox
- Understanding of domain-based authentication
- Entry-level Help Desk & IT Support fundamentals

## Real-World Relevance
This lab reflects common tasks performed by Help Desk and Junior IT Support technicians, including:
- Supporting domain-joined environments
- Understanding user authentication issues
- Troubleshooting login and DNS-related problems

## Screenshots

### Server Manager – AD DS Installed
![Server Manager](screenshots/server-manager-ad.png)

### Active Directory Users and Computers
![ADUC](screenshots/aduc-domain.png)

### Domain Login
![Domain Login](screenshots/domain-login.png)
