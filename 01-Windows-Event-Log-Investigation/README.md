# Windows Event Log Investigation

## Project Overview

This project focuses on investigating Windows Security Event Logs to identify suspicious authentication activity, analyze potential security incidents, and reconstruct event timelines from available evidence.

The objective is to demonstrate a structured SOC investigation workflow using Windows Event Viewer, Windows Security logs, and PowerShell.

## Investigation Objectives

- Analyze failed and successful logon events.
- Identify patterns that may indicate brute-force attempts.
- Investigate suspicious authentication sequences.
- Understand security audit log clearing events.
- Develop an evidence-based investigation report.
- Recommend appropriate security response actions.

## Tools and Technologies

- Windows Event Viewer
- Windows Security Event Logs
- PowerShell
- MITRE ATT&CK
- GitHub Markdown documentation

## Windows Event IDs

| Event ID | Description |
|---|---|
| 4624 | Successful logon |
| 4625 | Failed logon |
| 4688 | Process creation, if auditing is enabled |
| 1102 | Security audit log cleared |

## Investigation Methodology

1. Collect relevant Windows Security events.
2. Filter events by timestamp, account, event ID, and source address where available.
3. Correlate related events to identify suspicious patterns.
4. Build a chronological investigation timeline.
5. Assess the evidence and determine the investigation verdict.
6. Document findings and recommended response actions.

## Expected Deliverables

- Investigation queries and commands
- Relevant event log evidence
- Timeline of observed activity
- Investigation screenshots
- MITRE ATT&CK mapping where supported by evidence
- Final SOC investigation report

## Disclaimer

This project is intended for defensive cybersecurity learning and authorized lab environments. Findings and conclusions will be documented based on the evidence collected during each investigation.
