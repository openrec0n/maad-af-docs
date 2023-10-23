# Establish Access - Sharepoint Site

## Description
`establish access - sharepoint site` module attempts to establish access to a specified sharepoint site using the access of the credential supplied by user.

## Trigger
```
MAAD Attack Arsenal -> "Access" -> 9
```

## MITRE ATT&CK Information

| Tactic         | Technique                                                                                                                                                                                                                                     |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Initial Access | [Valid Accounts](https://attack.mitre.org/techniques/T1078/)|

## Additional Details
Microsoft services being accessed by this module:

* [Sharepoint](https://www.microsoft.com/en-us/microsoft-365/sharepoint/collaboration)

External PowerShell module used: 

* [Microsoft.Online.SharePoint.PowerShell](https://www.powershellgallery.com/packages/Microsoft.Online.SharePoint.PowerShell/16.0.23311.12000)