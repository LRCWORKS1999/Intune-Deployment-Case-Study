# Phase 1 - Hybrid Identity

## Objective

Implement Microsoft Entra Connect to establish synchronisation between on-premises Active Directory and Microsoft Entra ID.

## Approach

A dedicated Microsoft Entra Connect server was configured to synchronise identities from the on-premises Active Directory environment to Microsoft Entra ID.

To minimise risk, OU filtering was used to limit synchronisation to dedicated pilot organisational units during the testing phase.

Password Hash Synchronisation (PHS) was selected as the sign-in method to provide a simple and reliable hybrid identity solution.

## Actions Completed

- Installed Microsoft Entra Connect
- Connected Active Directory to Microsoft Entra ID
- Enabled Password Hash Synchronisation (PHS)
- Configured OU filtering
- Created pilot user and device OUs
- Validated successful synchronisation
- Monitored synchronisation health

## Screenshots

### Entra Connect Configuration

<img width="1199" height="970" alt="password hash sync enabled " src="https://github.com/user-attachments/assets/eb4e5cbf-3794-4d8e-93bc-1d178977eeb8" />
<img width="935" height="981" alt="synchronization service 1" src="https://github.com/user-attachments/assets/93b80ede-0718-46dc-9113-bffdd0e6127e" />

![Synchronisation Service Manager](../Diagramst OU Structure

<img width="1456" height="988" alt="Active directory OU&#39;s for entra" src="https://github.com/user-attachments/assets/d678e973-8623-460d-b006-4e357f647f13" />

### Successful User Synchronisation

<img width="1587" height="870" alt="synced from onprem" src="https://github.com/user-attachments/assets/2be60323-f506-49ab-a1b0-63189defd1d1" />


## Outcome

Hybrid identity was successfully established between Active Directory and Microsoft Entra ID, providing the foundation for user onboarding, device registration and Microsoft Intune deployment.


