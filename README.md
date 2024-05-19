# Sentinal SIEM
## Objective

The Sentinal SIEM project aimed to establish a controlled environment within Azure for attracting and detecting cyber attacks. The primary focus was to ingest and analyze logs using microsoft Sentinal. The Honeypot gathers test telemetry to mimic real-world attack scenarios. This hands-on experience was designed to deepen understanding of network security, attack patterns, and defensive strategies.

### Skills Learned

- Azure firewall and virtual machine configuration and deployment.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.
- Log Querying and Analysis
   
### Tools Used

- Windows 10 vm
- Azure Cloud services: Powershell, Firewall Manager, Log Analytics Workspace, Microsoft Defender for Cloud
- Microsoft Sentinal
- Telemetry generation script to create realistic network traffic and attack scenarios.

## Steps

Using Azure portal create a Virtual machine and security group: <br/>
<img src="https://i.imgur.com/d24l9xF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

Define that the security group has all protocols/ports open and is properly labeled with: DANGER_ALL_IN  
<img src="https://i.imgur.com/pIMjdDr.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<br />
