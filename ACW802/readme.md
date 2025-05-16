# ACW802
This directory contains hands-on lab documentation and practical exercises for ACW802, focusing on offensive cybersecurity operations and malware analysis environments. The labs are designed to simulate real-world attack scenarios and prepare environments for advanced threat analysis and penetration testing.

---
## [ACW802_OperationShadowStrike.pdf](https://github.com/reyincyber/Cyberwarfare/blob/main/ACW802/ACW802_OperationShadowStrike.pdf)

Operation Shadow Strike simulates a multi-phase Advanced Persistent Threat (APT) campaign targeting a fictional IT firm, GlobalTech Solutions. The lab comprises five critical phases: _**DDoS attack simulation, spear phishing for credential harvesting, establishing persistence via backdoors, lateral movement across networked systems, and encrypted data exfiltration**_. Each phase demonstrates offensive techniques and reflects on associated defensive strategies. The lab highlights challenges faced during execution, including tool setup issues, and concludes with recommendations to enhance cybersecurity posture through endpoint detection, segmentation, and data loss prevention measures.

---
## [ACW802_FlareVM_SetUp.pdf](https://github.com/reyincyber/Cyberwarfare/blob/main/ACW802/ACW802_FlareVM_SetUp.pdf)

This lab outlines the setup of a Windows 10-based malware analysis environment using FLARE-VM within VirtualBox. The guide walks through step-by-step instructions to _**install VirtualBox, configure the Windows 10 ISO, disable security protections, and deploy the FLARE-VM toolkit**_. Key takeaways include the importance of isolating the analysis environment, disabling Windows Defender and automatic updates, and snapshotting at critical stages. The setup emphasizes safety and operational integrity for conducting reverse engineering and malware experimentation tasks.

---
## [ACW803_Dynamic Malware Analysis: Behavioral Profiling of a Suspicious Executable](https://github.com/reyincyber/Cyberwarfare/blob/main/ACW802/ACW802_Dynamic%20Malware%20Analysis_lab.pdf)

This lab involves dynamic behavioral analysis of a suspicious executable in a FLARE-VM setup. It explores real-time process activity using tools like Procmon, Regshot, and Wireshark. Findings include registry modifications, code injection into legitimate processes, creation of persistence mechanisms like Run keys and scheduled tasks, and HTTP POST beaconing to simulated C2 servers. The exercise helps identify indicators of compromise (IOCs) and emphasizes the importance of endpoint detection, registry auditing, and network monitoring to detect and contain malware threats.

---

## Contribution & Licensing
These labs are part of the ACW802 Offensive Security curriculum and are shared for educational purposes. Contributions, issue reports, and enhancements are welcome through pull requests.

## Contact
For more information, please visit the main repository.
