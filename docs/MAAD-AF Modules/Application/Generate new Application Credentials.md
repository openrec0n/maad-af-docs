# Generate new Application Credentials

## Description
`generate new application credentials` module attempts to generate new credentials for an application in Entra ID. This can potentially allow performing actions using the access & privilege of the target application. 

The module stores the generated application credentials in *MAAD Credential Store* for use in future.

## Trigger
```
MAAD Attack Arsenal -> "Application" -> 3
```

## MITRE ATT&CK Information

| Tactic         | Technique                                                                                                                                                                                                                                     |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Defense Evasion | [Valid Accounts: Cloud Accounts](https://attack.mitre.org/techniques/T1078/004/)|
| Persistence | [Valid Accounts: Cloud Accounts](https://attack.mitre.org/techniques/T1078/004/)|
| Privilege Escalation | [Valid Accounts: Cloud Accounts](https://attack.mitre.org/techniques/T1078/004/)|
| Initial Access | [Valid Accounts: Cloud Accounts](https://attack.mitre.org/techniques/T1078/004/)|

## Additional Details
Revert module changes: No

Microsoft services being accessed by this module:

* [Entra ID (Azure AD)](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id)

External PowerShell module used: 

* [AzureAd](https://www.powershellgallery.com/packages/AzureAD/)