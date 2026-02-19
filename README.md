🏠 Home Lab  


Goal:
Simulate a small-to-medium enterprise environment to practice system administration, networking, and security concepts using Windows Server, Linux, Active Directory, and virtualization.  


🎯 Objectives  


This lab is designed to learn and simulate: 


Active Directory deployment  

 
DNS & DHCP configuration  


Group Policy management  


Virtual networking  


Linux server administration  


Security hardening  


Monitoring & logging  


💻 Lab Setup  

Servers  
 
Server	OS	Role / Notes	IP Address  

Server 1	Windows Server 2016 VM	Domain Controller, AD, DNS	192.168.0.150  

Server 2	Windows Server 2022 VM	DHCP, File Server, Additional AD Roles	192.168.0.149  

Server 3	Linux Live Server (Old Toshiba Laptop)	Linux services, Security testing	Unallocated  

Clients  

Client	OS	Language	IP Address  
 
Client 1	Windows 10 VM	English	192.168.0.148
Client 2	Windows 10 VM	German	192.168.0.147
🌐 Network Configuration

All servers and clients connected via virtual networking

Static IPs configured for servers

Clients can optionally use DHCP from Windows Server 2022

Linux server can act as a testing platform for network/security tasks

⚙️ Notes

The lab is designed for learning and testing only — not for production use.

Focus on hands-on practice with Active Directory, DNS/DHCP, Group Policy, and Linux administration.

Security hardening and monitoring practices can be implemented on both Windows and Linux servers.
