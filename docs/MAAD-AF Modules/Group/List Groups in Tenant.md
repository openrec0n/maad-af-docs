# List Groups in Tenant

## Description
`list groups in tenant` module performs reconnaissance in the connected Entra ID tenant to lists all groups in the tenant. If the result is too large to display, the module dumps the groups found into `\Outputs` directory.

## Trigger
```
MAAD Attack Arsenal -> "Group" -> 1
```

## MITRE ATT&CK Information

| Tactic         | Technique                                                                                                                                                                                                                                     |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Discovery | [Permission Groups Discovery: Cloud Groups](https://attack.mitre.org/techniques/T1069/003/)|

## Additional Details

Microsoft services being accessed by this module:

* [Entra ID (Azure AD)](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id)

External PowerShell module used: 

* [AzureAd](https://www.powershellgallery.com/packages/AzureAD/)