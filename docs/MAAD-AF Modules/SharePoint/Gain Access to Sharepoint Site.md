# Gain Access to SharePoint Site

## Description
`gain access to sharepoint site` module attempts to leverage the connected users privilege to grant access to a target SharePoint site.

## Trigger
```
MAAD Attack Arsenal -> "SharePoint" -> 2
```

## MITRE ATT&CK Information

| Tactic         | Technique                                                                                                                                                                                                                                     |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Collection | [Data from Information Repositories: Sharepoint](https://attack.mitre.org/techniques/T1213/002/)|

## Additional Details
Microsoft services being accessed by this module:

* [SharePoint](https://www.microsoft.com/en-us/microsoft-365/sharepoint/collaboration)

External PowerShell module used: 

* [PnP.PowerShell](https://pnp.github.io/powershell/)