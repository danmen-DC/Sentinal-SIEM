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

Use Azure portal create a Virtual machine and security group: <br/>
<img src="https://i.imgur.com/d24l9xF.png" height="80%" width="80%" alt="Sentinal SIEM Steps"/>
<br />


Define that the security group has all protocols/ports open and is properly labeled with: DANGER_ALL_IN
This will allow all traffic into the honeypot so we can collect telemetry.

<img src="https://i.imgur.com/pIMjdDr.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<br />

Navagate to the log analytics to create a workspace to ingest logs from the honeypot. Data ingested is the windows event logs.
Custom log will contain geographic information to show where the attack originated from.
<img src="https://i.imgur.com/mMySFQ2.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<br />

Add Microsoft Defender for Cloud to the correct subscription and VM. It defines that all data needs to be collected.
<img src="https://i.imgur.com/3iy8oBF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://i.imgur.com/VCg3RuY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

Connect the VM to the custom log created within log analytics 

<img src="https://i.imgur.com/ybFJUGj.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<br />



<img src="https://i.imgur.com/mMySFQ2.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<br />
