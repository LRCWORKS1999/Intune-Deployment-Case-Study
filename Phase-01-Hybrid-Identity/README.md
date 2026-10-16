- Establish identity synchronisation between Active Directory and Microsoft Entra ID
- Enable Password Hash Synchronisation
- Minimise risk by limiting synchronisation scope
- Validate synchronisation before wider rollout

A Microsoft Entra Connect server was installed within the existing server environment.

The configuration was connected to the on-premises Active Directory domain controllers and configured for:

- Password Hash Synchronisation (PHS)
- Organisational Unit filtering
- Limited initial synchronisation scope

Dedicated pilot OUs were created to ensure only authorised test objects were synchronised to Microsoft Entra ID.
