# Windows-Sysmon-Event-Analysis

Read Me
Summary
This project simulates suspicious activity on a Windows workstation and demonstrates detection using Sysmon logs in Event Viewer. The goal was to practice host based detection and incident triage workflows similar to real world SOC operations.

System & Log Source
System Analyzed: Windows Workstation (Local Machine)
Log Source: Windows Security Event Logs

Tools Used
Sysmon Installed with the SwiftOnSecurity configuration for comprehensive event logging
Event Viewer Used to extract and analyze relevant Sysmon Event IDs
PowerShell Simulated attacker techniques including user creation, persistence, and script execution

Setup & Methodology
Installed Sysmon using the SwiftOnSecurity config to enable detailed telemetry.
Used PowerShell to simulate common attacker techniques:
User account creation
Registry based persistence
Malicious script execution
Scheduled task creation
Monitored Sysmon Event IDs in Event Viewer to detect activity.
Performed file checks and correlated log data to validate findings.

Key Skills Demonstrated
Host based threat detection
Event log analysis with Sysmon and native Windows tools
Simulation of attacker persistence techniques
Incident triage and documentation for SOC escalation

Final Notes
This project showcases my ability to detect, analyze, and respond to host based suspicious activity using native Windows logging tools enhanced with Sysmon. By simulating real world attacker behavior and identifying the resulting log events, I reinforced practical skills in host intrusion detection, persistence identification, and incident triage key capabilities for a SOC analyst.
