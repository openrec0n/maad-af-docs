# Reset Password

## Description
`reset password` module allows users to reset password of another identity in Entra ID. Resetting the password can allow access as the target entity leading to privilege escalation. 

If a target identity's password is successfully reset, this module will store the new credentials for the identity to *MAAD Credential Store* for use in future. 

## Trigger
```
MAAD Attack Arsenal -> "Account" -> 5
```

## MITRE ATT&CK Information

| Tactic         | Technique                                                                                                                                                                                                                                     |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Defense Evasion | [Valid Accounts: Cloud Accounts](https://attack.mitre.org/techniques/T1078/004/)|
| Persistence | [Valid Accounts: Cloud Accounts](https://attack.mitre.org/techniques/T1078/004/)|
| Privilege Escalation | [Valid Accounts: Cloud Accounts](https://attack.mitre.org/techniques/T1078/004/)|
| Initial Access | [Valid Accounts: Cloud Accounts](https://attack.mitre.org/techniques/T1078/004/)|

## Additional Details
Microsoft services being accessed by this module:

* [Entra ID (Azure AD)](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id)

External PowerShell module used: 

* [AzureAd](https://www.powershellgallery.com/packages/AzureAD/)