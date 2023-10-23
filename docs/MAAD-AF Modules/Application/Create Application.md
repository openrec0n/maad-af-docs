# Create Application

## Description
`create application` module creates a new service principal in Entra ID. 

## Trigger
```
MAAD Attack Arsenal -> "Application" -> 2
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