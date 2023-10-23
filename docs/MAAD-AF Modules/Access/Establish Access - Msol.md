# Establish Access - Msol

## Description
`establish access - msol` module attempts to establish access with Entra ID(Azure AD) service using the access & privilege of the credential supplied by user.

## Trigger
```
MAAD Attack Arsenal -> "Access" -> 8
```

## MITRE ATT&CK Information

| Tactic         | Technique                                                                                                                                                                                                                                     |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Initial Access | [Valid Accounts](https://attack.mitre.org/techniques/T1078/)|

## Additional Details
Microsoft services being accessed by this module:

* [Entra ID (Azure AD)](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id)

External PowerShell module used: 

* [Msol](https://www.powershellgallery.com/packages/MSOnline/)
