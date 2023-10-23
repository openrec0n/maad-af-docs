# Establish Access - Sharepoint Admin Center

## Description
`establish access - sharepoint admin center` module attempts to establish access with Sharepoint Admin Portal using the access & privilege of the credential supplied by user.

## Trigger
```
MAAD Attack Arsenal -> "Access" -> 10
```

## MITRE ATT&CK Information

| Tactic         | Technique                                                                                                                                                                                                                                     |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Initial Access | [Valid Accounts](https://attack.mitre.org/techniques/T1078/)|

## Additional Details
Microsoft services being accessed by this module:

* [Sharepoint Admin Center](https://learn.microsoft.com/en-us/sharepoint/sharepoint-admin-role)

External PowerShell module used: 

* [Microsoft.Online.SharePoint.PowerShell](https://www.powershellgallery.com/packages/Microsoft.Online.SharePoint.PowerShell/16.0.23311.12000)