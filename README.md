# Detection Engineering Journey

A collection of detection engineering projects built using Splunk and Windows telemetry.

## Completed Detections

### PowerShell Script Block Logging Detection (4104)
- MITRE: T1059.001
- Focus: Suspicious PowerShell execution
- Repo: https://github.com/HariCipher/powershell-scriptblock-recon

### Failed Login Detection (4625)
- MITRE: T1110
- Focus: Authentication failures
- Repo: https://github.com/HariCipher/Splunk-failed-login-detection

### Account Creation Detection (4720)
- MITRE: T1136
- Focus: New local user creation
- Repo: https://github.com/HariCipher/4720-account-creation-detection

### Service Installation Detection (7045)
- MITRE: T1543.003
- Focus: Windows service persistence
- Repo: https://github.com/HariCipher/7045-service-installation-detection

## Skills Developed

- Splunk SPL
- Windows Event Analysis
- Telemetry Validation
- Alert Creation
- Sigma Rules
- MITRE ATT&CK Mapping
- Detection Documentation

## Summary

Over the first few days of this journey, I focused on building a strong foundation in Windows telemetry analysis and detection engineering using Splunk.

Instead of rushing into advanced detections, I concentrated on understanding how logs are generated, how telemetry behaves in real environments, and how to validate fields before writing detections.

So far, I have built detections covering:

- PowerShell Script Block Logging (4104)
- Failed Login Activity (4625)
- User Account Creation (4720)
- Service Installation Persistence (7045)

The biggest lesson wasn't writing SPL queries—it was troubleshooting. Most of the learning came from investigating why logs weren't appearing, validating field names, understanding event structure, and fixing issues before building detections.

Moving forward, the goal is to progress beyond individual detections into:
- event correlation
- threat hunting
- PCAP analysis
- detection tuning
- dashboard development
- broader blue team investigations

This repository serves as a record of that progression and documents the practical skills, mistakes, troubleshooting, and lessons learned along the way.
