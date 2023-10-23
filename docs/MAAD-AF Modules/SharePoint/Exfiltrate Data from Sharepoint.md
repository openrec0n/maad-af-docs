# Exfiltrate Data from SharePoint

## Description
`exfiltrate data from sharepoint` module exfiltrates all files or files matching a user defined criteria to the users local host.

## Trigger
```
MAAD Attack Arsenal -> "SharePoint" -> 4
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
