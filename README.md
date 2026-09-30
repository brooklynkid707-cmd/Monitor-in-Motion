# Monitor in Motion

## Microsoft Sentinel SOC Investigation Portfolio Project

Monitor in Motion is the recruiter-facing project entry for my Microsoft Sentinel security operations lab.

The full technical implementation is maintained in the **Cybersecurity-Hands-On-Labs** repository under **Lab 01 — Microsoft Sentinel Detection & Incident Investigation**.

## What the Project Demonstrates

- Windows Security Event telemetry
- Azure Arc endpoint onboarding
- Azure Monitor Agent
- Data Collection Rules
- Log Analytics
- Microsoft Sentinel
- KQL hunting and correlation
- Event ID 4625 failed-logon analysis
- Event ID 4624 successful-logon analysis
- detection engineering
- MITRE ATT&CK mapping
- SOC investigation methodology
- analyst notes, incident timeline, and remediation guidance

## Investigation Summary
A controlled test identity generated failed and successful network-authentication activity on a Windows endpoint. The telemetry path was validated into Microsoft Sentinel and investigated with KQL. A failed-to-successful authentication sequence was correlated and correctly dispositioned as an authorized lab simulation based on source and surrounding context.

## Evidence Standard
This project only claims what was observed in the authorized lab. It does not represent a production breach or customer environment, and no synthetic screenshot is used as evidence.

## Canonical Technical Repository
See **Cybersecurity-Hands-On-Labs → 01-sentinel-incident-investigation** for queries, evidence, analyst notes, timeline, MITRE mapping, and remediation.

## Author
**JohnPaul Scirica**  
Cybersecurity | Security Operations | Detection Engineering  
CompTIA Security+ | Certified Ethical Hacker (CEH)
