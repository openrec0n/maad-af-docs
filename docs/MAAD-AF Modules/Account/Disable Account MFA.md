# Disable Account MFA

## Description
`disable account mfa` module attempts to disable tenant level MFA on a target account in Entra ID.

## Trigger
```
MAAD Attack Arsenal -> "Account" -> 7
```

## MITRE ATT&CK Information

| Tactic         | Technique                                                                                                                                                                                                                                     |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Persistence | [Modify Authentication Process: Multi-Factor Authentication](https://attack.mitre.org/techniques/T1556/006/)|
| Defense Evasion | [Modify Authentication Process: Multi-Factor Authentication](https://attack.mitre.org/techniques/T1556/006/)|
| Credential Access | [Modify Authentication Process: Multi-Factor Authentication](https://attack.mitre.org/techniques/T1556/006/)|

## Additional Details
Microsoft services being accessed by this module:

* [Entra ID (Azure AD)](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id)

External PowerShell module used: 

* [AzureAd](https://www.powershellgallery.com/packages/AzureAD/)