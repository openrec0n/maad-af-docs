# Add User to Group

## Description
`add user to group` module attempts adding a target account to a sepcified group allowing account to assume the group roles. 

## Trigger
```
MAAD Attack Arsenal -> "Group" -> 3
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