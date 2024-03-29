# Home Server Network Threat Detector
  
![github-header-image](https://github.com/Li1816/Home-Server-Network-Threat-Detector/assets/155325489/2eaa419a-ad3d-4075-9f36-7c3e04732826)

<p>This program aims to improve network privacy, detect indicators of compromise, and establish a secure VPN tunnel for Gonghan's family. The program provides various security controls and functionality by incorporating SIEM, DNS-Sinkhole, IDS, System Health Monitoring, Account Lockout, and VPN Tunneling.  
  
## Tools used:
- Splunk Enterprise: is used as a SIEM for Centrlize Management. 
- Pi-Hole: is used to as a DNS-Sinkhole for filtering ads, trackers, and malicious websites. 
- Snort: is used as an Intrusion Detection System for inspecting network traffic and alerting on Indicators of Compromise
- OpenMediaVault: is used as a Centralized Management to monitor the system's CPU, Memory, Disk usage and Authentication. 
- Fail2ban: is used as an Access Control for implementing account lock-out policies.
- TailScale: is used as a VPN for establishing secure communication from WAN to LAN while preventing eavesdropping attacks.


## Security Control Walk-Through:

**Splunk Enterprise**
![SpunkEnterprice](https://github.com/Li1816/Home-Server-Network-Threat-Detector/assets/155325489/bae035cd-002a-4adb-b29a-f946e6b470ca)

**Firstly, this program uses Pi-Hole as a DNS Sinkhole for filtering out ads, trackers, and malicious Websites. It also incorporates Cloudflare's DNS 1.1.1.2 for additional malware filtering.**
![pi_hole1](https://github.com/Li1816/Home-Server-Network-Threat-Detector/assets/155325489/a86436cc-9dc8-4446-93d9-ba3a53482ef2)
![pi_hole2](https://github.com/Li1816/Home-Server-Network-Threat-Detector/assets/155325489/bc082801-99c1-4f18-8203-0f460fd67dfa)

**Secondly, it uses Snort as an IDS for signature detection. Snort inspects network traffic and alerts when finding a suspicious signature.**
![Snort1](https://github.com/Li1816/Home-Server-Network-Threat-Detector/assets/155325489/826a84d7-3748-45ff-be01-5e5313859b07)
![snort2](https://github.com/Li1816/Home-Server-Network-Threat-Detector/assets/155325489/bc234aea-ab60-48f8-9b8d-8804da1ff1ba)
![Snort3](https://github.com/Li1816/Home-Server-Network-Threat-Detector/assets/155325489/8cdf79c2-f50b-4d7f-ad6e-52ab8c915fe2)

**Thirdly, the program uses OpenMediaVault for monitoring CPU, memory, and disk usage. OMV also monitors authentication logs and boot logs to identify unexpected logins.**
![OMV1](https://github.com/Li1816/Home-Server-Network-Threat-Detector/assets/155325489/c9f558f9-a228-472f-91ed-be42782f0012)
![OMV2](https://github.com/Li1816/Home-Server-Network-Threat-Detector/assets/155325489/c5d46a08-fba8-4200-a943-9f7cf33b11a8)

**Fourthly, the program uses Fail2Ban to implement account lock-out policies for access control.**
![image](https://github.com/Li1816/Home-Server-Network-Threat-Detector/assets/155325489/72b6667b-7e0d-4648-bf93-120766f03cf2)
![image](https://github.com/Li1816/Home-Server-Network-Threat-Detector/assets/155325489/0b619f5f-aeab-4bce-9055-981f4837eb66)

**Lastly, the program uses TailScale to establish a secure connection between WAN and LAN while preventing eavesdropping attacks.**
![TailScale1](https://github.com/Li1816/Home-Server-Network-Threat-Detector/assets/155325489/0c6cecfc-4a6e-4037-8c7d-b483e0d401ff)




