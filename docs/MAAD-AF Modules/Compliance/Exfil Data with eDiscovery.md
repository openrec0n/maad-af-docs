# Exfil Data from eDiscovery

## Description
`exfil data from ediscovery` module exfiltrates data from search results of a newly created or existing search of a eDiscovery case.

## Trigger
```
MAAD Attack Arsenal -> "Compliance" -> 6
```

## MITRE ATT&CK Information

| Tactic         | Technique                                                                                                                                                                                                                                     |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Collection | [Automated Collection](https://attack.mitre.org/techniques/T1119/)|

## Additional Details
Revert module changes: No

Microsoft services being accessed by this module:

* [Compliance](https://learn.microsoft.com/en-us/purview/microsoft-365-compliance-center)

External PowerShell module used: 

* [ExchangePowerShell](https://learn.microsoft.com/en-us/powershell/module/exchange/?view=exchange-ps)