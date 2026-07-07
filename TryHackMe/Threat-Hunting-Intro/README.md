
# Threat Hunting: Intro

Threat Hunting is a proactive cybersecurity activity where security analysts actively search for hidden threats that may have bypassed existing security controls.

Unlike traditional security monitoring, threat hunting does not wait for alerts. Instead, analysts investigate systems, endpoints, and logs to discover malicious activity before significant damage occurs.

# Learning Objectives

After completing this room I learned:

- What Threat Hunting is
- Why organizations perform Threat Hunting
- Difference between Threat Detection and Threat Hunting
- Threat Hunting Workflow
- Types of Threat Hunting
- Common Hunting Techniques

## What is Threat Hunting?
Threat Hunting is the proactive process of searching for attackers inside an environment.
Instead of waiting for SIEM alerts, analysts investigate endpoints, logs, network traffic and user activity to identify suspicious behaviour.

## Why is Threat Hunting Important?

- Detect hidden attackers
- Reduce dwell time
- Find attacks missed by security tools
- Improve incident response
- Strengthen overall security posture

## Threat Hunting Workflow

1. Create a hypothesis
2. Collect logs and telemetry
3. Investigate suspicious activity
4. Confirm or reject the hypothesis
5. Document findings
6. Improve detections

## Types of Threat Hunting

### Hypothesis Driven

Starts with an assumption based on attacker behaviour.

Example:
"An attacker may be abusing PowerShell."

### Intelligence Driven

Uses Threat Intelligence.

Examples:
- Malicious IP
- Domain
- Hash
- IOC

### Data Driven

"Uses existing logs."

Examples:
- Windows Logs
- Sysmon
- Firewall Logs
- EDR
- DNS Logs

## Common Techniques

- IOC Hunting
- Behaviour Based Hunting
- TTP Hunting
- Anomaly Detection

| Threat Hunting              | Incident Response                           |
| --------------------------- | ------------------------------------------- |
| Proactive                   | Reactive                                    |
| Searches for hidden threats | Responds to detected incidents              |
| Begins without an alert     | Begins after an alert or confirmed incident |
| Goal: Find attackers early  | Goal: Contain and recover                   |

## Important Concepts

### IOC

Indicators of Compromise

Examples

- Malicious IP
- File Hash
- Domain

### IOA

Indicators of Attack

Focuses on attacker behaviour rather than specific malware.

### MITRE ATT&CK

Knowledge base of attacker tactics and techniques.

Used during Threat Hunting.

## Skills Learned

- Threat Hunting Basics
- IOC Investigation
- Behaviour Analysis
- Log Investigation
- Detection Thinking

## Interview Questions

### What is Threat Hunting?

### Difference between Threat Hunting and Threat Detection?

### What are IOCs?

### What are IOAs?

### What are the different types of Threat Hunting?

### Why is Threat Hunting important?

### What is MITRE ATT&CK?

## Key Takeaways
-Threat Hunting is proactive.
-Threat Detection is reactive.
-Behaviour analysis is more effective than relying only on signatures.
-Threat Hunting helps discover attackers that security tools may miss.

## References
MITRE ATT&CK
Microsoft Security Documentation
NIST Cybersecurity Framework
