# SPLUNK SIEM THREAT INVESTIGATION

## Project Overview
This project simulates a SOC investigation using Splunk SIEM to detect malicious activity in Windows event logs.

## Log Sources
- Windows Security Logs
- Sysmon Logs
- Authentication Events
- Process Creation Logs

## Investigation Objectives
- Identify suspicious login attempts
- Detect malicious process execution
- Investigate network activity
- Identify persistence mechanisms

## Key Queries Used
index=main EventCode=4624
index=main EventCode=4625
index=main EventCode=1
index=main sourcetype=WinEventLog:Security

## Findings
- Suspicious login activity detected
- Malicious process execution observed
- Possible persistence mechanism identified
- Attack timeline correlated successfully

## Conclusion
The investigation successfully identified suspicious authentication behavior and malicious process activity using Splunk SIEM.
