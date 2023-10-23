# Upload File to SharePoint Site

## Description
`upload file to sharepoint site` module allows user to upload a (malicious) file to a target SharePoint site. This allows to deliver payload to other hosts who may download from the shared repository.

## Trigger
```
MAAD Attack Arsenal -> "SharePoint" -> 3
```

## MITRE ATT&CK Information

| Tactic         | Technique                                                                                                                                                                                                                                     |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Lateral Movement | [Taint Shared Content](https://attack.mitre.org/techniques/T1080/)|

## Additional Details
Microsoft services being accessed by this module:

* [SharePoint](https://www.microsoft.com/en-us/microsoft-365/sharepoint/collaboration)

External PowerShell module used: 

* [PnP.PowerShell](https://pnp.github.io/powershell/)