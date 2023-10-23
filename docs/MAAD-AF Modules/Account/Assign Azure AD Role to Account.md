# Assign Azure AD Role to Account

## Description
`assign azure ad role to account` module attempts to assign a azure ad role to a specified target account. This can be used to elevate privileges by granting roles to an account under control in the tenant. 

## Trigger
```
MAAD Attack Arsenal -> "Account" -> 3
```

## MITRE ATT&CK Information

| Tactic         | Technique                                                                                                                                                                                                                                     |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Persistence | [Account Manipulation: Additional Cloud Roles](https://attack.mitre.org/techniques/T1098/003/)|

## Additional Details
Microsoft services being accessed by this module:

* [Entra ID (Azure AD)](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id)

External PowerShell module used: 

* [AzureAd](https://www.powershellgallery.com/packages/AzureAD/)