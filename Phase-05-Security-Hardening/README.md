# Phase 05 - Security Hardening

# Objective 
Improve endpoint security through the deployment of Microsoft Defender and Intune security policies.

# Actions Completed 
- Deployed Microsoft Defender Antivirus across managed endpoints
- Verified Defender status and device onboarding
- Created endpoint security policies within Microsoft Intune
- Configured antivirus protection settings
- Configured real-time protection
- Configured cloud-delivered protection
- Configured automatic security intelligence updates
- Applied policies to pilot groups before wider deployment
- Monitored device compliance and security status


<img width="1915" height="849" alt="Devices - compliance " src="https://github.com/user-attachments/assets/93775d57-dcbb-48c1-9a94-10bc02b60202" />


## BitLocker Encryption

BitLocker encryption was utilised within the environment to protect endpoint data.

Encryption management was configured outside of Microsoft Intune and therefore no dedicated Intune BitLocker policy was deployed during this project.


## Attack Surface Reduction

Attack Surface Reduction (ASR) policies were configured through Microsoft Intune to reduce exposure to common attack vectors and improve endpoint security.

The environment utilised multiple ASR and Device Control policies to provide additional protection against malicious software and unauthorised device usage.

<img width="1650" height="858" alt="Attack surface Reduction" src="https://github.com/user-attachments/assets/c9b26d73-1707-4807-b42b-199515dd0e23" />

## Firewall Management

Microsoft Defender Firewall settings were centrally managed through Intune to provide consistent protection across enrolled devices.

A Windows Firewall policy was deployed to ensure endpoint firewall protection remained enabled and monitored.

### Screenshot

<img width="1631" height="820" alt="Firewall Policy" src="https://github.com/user-attachments/assets/664af69a-c0e2-431d-88be-bc522e49b556" />

## Security Baselines

Microsoft security baselines were reviewed and utilised to align endpoint configurations with Microsoft recommended security standards.

Security baselines provide a starting point for securing managed endpoints and reducing configuration drift across the environment.

### Screenshot

<img width="1834" height="832" alt="Endpoint Security baselines" src="https://github.com/user-attachments/assets/df0ed408-be36-433c-838f-c433512eb1ca" />


## Outcome

Security controls were centralised using Microsoft Intune and Microsoft Defender technologies.

The implementation provided:

- Endpoint firewall management
- Attack Surface Reduction controls
- Security baseline management
- Compliance monitoring
- Centralised security administration

These controls improved visibility, standardisation and endpoint security across managed devices.
