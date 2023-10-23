# Download All Acount List

## Description
`download all account list` module executes reconnaissance and dumps all identities in the connected tenant.

## Trigger
```
MAAD Attack Arsenal -> "AzureAD" -> 2
```

## MITRE ATT&CK Information

| Tactic         | Technique                                                                                                                                                                                                                                     |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Discovery | [Account Discovery: Cloud Account](https://attack.mitre.org/techniques/T1087/004/)|

## Additional Details
Revert module changes: N/A

Microsoft services accessed by module:

* [Entra ID (Azure AD)](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id)

External PowerShell module used: 

* [AzureAd](https://www.powershellgallery.com/packages/AzureAD/)