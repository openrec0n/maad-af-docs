# Delete User

## Description
`delete user` module attempts to remove an identity from Entra ID to disable access. Users cannot use this module to remove the identity thats currently being used by MAAD-AF to access Entra ID.

## Trigger
```
MAAD Attack Arsenal -> "Account" -> 8
```

## MITRE ATT&CK Information

| Tactic         | Technique                                                                                                                                                                                                                                     |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Impact | [Account Access Removal](https://attack.mitre.org/techniques/T1531/)|

## Additional Details
Microsoft services being accessed by this module:

* [Entra ID (Azure AD)](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id)

External PowerShell module used: 

* [AzureAd](https://www.powershellgallery.com/packages/AzureAD/)