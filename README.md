# Checkpoint Firewall Home-Lab

## ℹ️Overview

In this Home Lab, we’ll learn to set up a Checkpoint firewall from scratch. This Lab will help you launch an attack with Nmap, Metasploit & custom scripts from Kali linux and defend your machine using a Checkpoint firewall.
![Blue Sand White Beach Simple Watercolor Etsy Shop Banner](https://github.com/0xrajneesh/Checkpoint-Firewall-Home-Lab/assets/40385860/84592e52-3196-4082-823e-94aa851c13cc)

## 🧮Requirements

- **Hardware**:
  - Computer with at least 16GB RAM and dual-core processor
- **VM/ISO Image**:
  - Checkpoint Standalone ISO file
  - Kali Linux OVA file
  - Metasploitable 2
  - Windows 11 OVA file



## 🖼️Lab Diagram

![AttackDefense with Checkpoint FW](https://github.com/0xrajneesh/Home-Lab/assets/40385860/a7c68832-954b-4c87-a143-e26c16ea6619)


## </> Setting up the Checkpoint Firewall Home-lab

- **Checkpoint Firewall**
  -  Download [Checkpint ISO image](https://twitter.com/rajneeshcyber/status/1636118233756610560)
  -  Setting up [Checkpoint Gateway](https://sc1.checkpoint.com/documents/R81/WebAdminGuides/EN/CP_R81_Gaia_AdminGuide/Topics-GAG/Running-FTCW-in-Gaia-Portal.htm)

- **Checkpoint Management Station Server(SMS)**
  -  Download [Checkpint ISO image](https://twitter.com/rajneeshcyber/status/1636118233756610560)
  -  Setting up [Checkpoint SMS Server](https://sc1.checkpoint.com/documents/R81/WebAdminGuides/EN/CP_R81_Gaia_AdminGuide/Topics-GAG/Running-FTCW-in-Gaia-Portal.htm)

 
- **Setting up DMZ Server(Victim Server)**
  -  Import Metasploitable 2 in Virtualbox

- **Setting up Workstation**
  -  Import Windows 11 OVA Machine
 
 


## 🧑‍💻Excercises- Network-based attacks
-  **Nmap Stealth Scan Detection**: Create a Suricata rule to detect TCP SYN packets sent to multiple ports within a short time frame, indicative of Nmap stealth scans.  
-  **Nmap OS Fingerprinting Detection**: Develop a Suricata rule to detect ICMP echo requests and responses with specific TTL values, characteristic of Nmap OS fingerprinting activities.  
-  **Nmap Service Version Detection Detection**: Formulate a Suricata rule to detect Nmap service version detection probes based on unique HTTP GET requests or TCP SYN/ACK packets.  
-  **Metasploit Exploit Payload Detection**: Craft a Suricata rule to detect Metasploit exploit payload traffic based on unique signatures or payloads commonly used in exploits.  
-  **Metasploit Reverse Shell Detection**: Develop a Suricata rule to detect Metasploit reverse shell connections by monitoring for outbound TCP connections to known attacker IP addresses.  
-  **Metasploit Meterpreter Communication Detection**: Create a Suricata rule to detect Meterpreter communication activities by analyzing HTTP or TCP traffic with characteristic Meterpreter payloads.
- **Metasploit Credential Harvesting Detection**: Formulate a Suricata rule to detect Metasploit credential harvesting activities by monitoring for specific LDAP or SMB traffic patterns indicative of credential theft.

## 🧑‍💻Excercises- Real-world Scenarios
-  **Deploying Checkpoint in Bridge Mode**: Configure Checkpoint Firewall transparently for enhanced security without altering IP addresses, ensuring comprehensive threat protection.
-  **Branch office to Data Center Server Access**: Establish secure connectivity between branch offices and data centers to ensure seamless access to critical resources while upholding robust security measures.
-  **Allow uploading of credit cards numbers by finance and only over HTTPS**:  Enable secure credit card uploads for finance, enforcing HTTPS protocol to safeguard data integrity during transmission and comply with regulatory standards.
-  **Block High-Risk Applications**: Proactively restrict access to high-risk applications to mitigate potential security threats and enhance network security posture.
-  **Block downloading of sensitive medical information**:  Prevent downloading of sensitive medical data to uphold compliance with healthcare regulations and safeguard patient confidentiality.
-  **Allow Facebook for HR**: Grant exclusive Facebook access to HR for internal communication and recruitment purposes while managing social media usage.
- **Monitor all traffic of Tiktok**: Analyze TikTok traffic to detect threats, enforce acceptable use policies, and mitigate risks associated with the platform through comprehensive network monitoring. 

