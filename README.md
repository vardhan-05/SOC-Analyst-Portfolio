# SOC Analyst Portfolio

**Security Operations | SIEM | Threat Detection | Incident Response**

Welcome to my SOC Analyst portfolio. This repository documents my hands-on cybersecurity practice, including security alert investigation, SIEM detection engineering, Windows event log analysis, network forensics, and threat hunting.

My goal is to develop practical skills in identifying suspicious activity, investigating security alerts, analyzing evidence, and documenting incident response recommendations.

## Technical Skills

- **SIEM:** Splunk, SPL queries, alert triage
- **Endpoint Security:** Windows Event Logs, Sysmon, EDR alert investigation
- **Network Security:** Wireshark, TCP/IP, DNS, network traffic analysis
- **Threat Intelligence:** IOC analysis, IP and domain reputation checks
- **Detection Engineering:** Sigma rules, MITRE ATT&CK mapping
- **Incident Response:** Investigation timelines, severity assessment, escalation and reporting

## Projects

### 1. Windows Event Log Investigation
- Analyze successful and failed authentication events.
- Investigate suspicious logon patterns and security audit log clearing.
- Build event timelines and document investigation findings.

**Tools:** Windows Event Viewer, PowerShell

### 2. Wireshark Network Analysis
- Analyze network traffic using PCAP files.
- Investigate DNS queries, TCP connections, and suspicious communication patterns.
- Document network indicators and findings.

**Tools:** Wireshark

### 3. Splunk Brute-Force Detection
- Develop SPL queries to identify repeated authentication failures.
- Investigate source IPs, targeted accounts, and suspicious login sequences.
- Document detection logic and recommended response actions.

**Tools:** Splunk, Windows Event Logs

### 4. Splunk Correlation Detection
- Correlate related security events across time.
- Investigate suspicious authentication and process activity.
- Document detection logic, test cases, and false-positive considerations.

**Tools:** Splunk, SPL

### 5. Threat Hunting
- Develop hypotheses based on suspicious activity.
- Search available logs for indicators of compromise and unusual behavior.
- Map supported findings to MITRE ATT&CK and recommend further investigation.

**Tools:** Splunk, Sysmon, MITRE ATT&CK

## Investigation Methodology

1. Alert review and initial triage
2. Evidence collection and validation
3. Timeline reconstruction and event correlation
4. Threat intelligence and IOC analysis
5. MITRE ATT&CK mapping where supported by evidence
6. Verdict assessment and confidence
7. Containment recommendations and incident reporting

## References

- [MITRE ATT&CK](https://attack.mitre.org/)
- [Splunk Documentation](https://docs.splunk.com/)
- [Sigma Rules](https://github.com/SigmaHQ/sigma)
- [Microsoft Security Documentation](https://learn.microsoft.com/en-us/windows/security/)

## Disclaimer

This portfolio is intended for educational and defensive cybersecurity purposes. Lab exercises use authorized environments, simulated scenarios, or publicly available training data. Any investigation conclusions are based on the evidence available in the respective project.

## Continuous Learning

I am continuously improving my SOC investigation, detection engineering, SIEM querying, and incident response skills through hands-on labs and documented case studies.
