# List Accounts in Tenant

## Description
`list accounts in tenant` module performs reconnaissance in the connected Entra ID tenant to lists all accounts in it. If the result is too large to display, this module dumps the accounts found into `\Outputs` directory.

## Trigger
```
MAAD Attack Arsenal -> "Account" -> 1
```

## MITRE ATT&CK Information

| Tactic         | Technique                                                                                                                                                                                                                                     |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Discovery | [Account Discovery: Cloud Account](https://attack.mitre.org/techniques/T1087/004/)|

## Additional Details
Microsoft services being accessed by this module:

* [Entra ID (Azure AD)](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id)

External PowerShell module used: 

* [AzureAd](https://www.powershellgallery.com/packages/AzureAD/)