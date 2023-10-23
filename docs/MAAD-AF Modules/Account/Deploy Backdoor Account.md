# Deploy Backdoor Account

## Description
`deploy backdoor account` module creates a new identity in Entra ID that can be used as a backdoor for persistent access to the tenant. No roles are assigned to the new identity. To do that users can use [`assign azure ad role to account`](Assign Azure AD Role to Account.md) & [`assign management role to account`](Assign Management Role Account.md) modules.

If a backdoor account is successfully deployes, this modules stores the new identity information to *MAAD Credential Store* for use in future. 

## Trigger
```
MAAD Attack Arsenal -> "Account" -> 2
```

## MITRE ATT&CK Information

| Tactic         | Technique                                                                                                                                                                                                                                     |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Persistence | [Create Account: Cloud Account](https://attack.mitre.org/techniques/T1136/003/)|

## Additional Details
Microsoft services being accessed by this module:

* [Entra ID (Azure AD)](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id)

External PowerShell module used: 

* [AzureAd](https://www.powershellgallery.com/packages/AzureAD/)