# Using-Auxiliary-Modules-on-Metasploit-
Auxiliary Modules is use in task including threat detection, log analysis, network monitoring, and offensive testing to enhance system security. In this project I will demonstrate using Auxiliary Modules on Metasploit and also share checklist strategy against Auxiliary Modules scan.

# Objective
- Checklist of  strategies against Auxiliary Modules scan 
- Start Metasploit
- Set target  host for Auxiliary Modules scan
- Perform Auxiliary Modules scan for TCP
- Perform Auxiliary Module scan for FTP version



# Checklist of Strategies Against Auxiliary Scan

-Firewall configuration (restrict inbound traffic, block Ip range from region you are not serving, apply connection limit to detect and mitigate scanning pattern)
-Segmentation and isolation(Vlan)
-Honeypot(to detect reconnaissance behavior) 
-Remove customize service to hide software version 
-Active threat hunting (regular assessment)
-Use tool to block Ip address showing scanner behavior
-Disable unnecessary service
-Log monitoring
-Keep operating system patch and updated etc....... 


# Tools Used
-Kali Linux 
-VMware 



# Steps for Auxiliary Modules Scan
-Start Metasploit console(mfsconsole)
-Start Metasploit database(msfdb init)
-Access Workspace (workspace <name workspace>)
-Searching for Auxiliary module to access (search portscan)
-Scanning  for TCP (<use 5>, Auxiliary scanner/portscan/tcp)
-Set target host ( set RHOSTS 192.168.*.*)
-To perform scan (run)
-To access FTP version(search ftp_version,<use O>)
-Set target host ( set RHOSTS 192.168.*.*)
-To perform scan (run)




# Key Findings of<img width="632" height="292" alt="Accessing Metasploit Database #Searching For Auxiliary Module" src="https://github.com/user-attachments/assets/222bc398-df50-4aed-9a0c-5acefb82ba4c" />
<img width="626" height="270" alt="Auxilary Module Scan For TCP" src="https://github.com/user-attachments/assets/be3e5d07-ac32-4f90-b9e5-ca09582b0254" />
<img width="619" height="269" alt="Auxiliary Module Scan For FTP Version" src="https://github.com/user-attachments/assets/775dbfb0-4f79-413e-a277-2809461a29c7" />
 Auxiliary Modules Scan
- Can be seen in the screenshot attached 
