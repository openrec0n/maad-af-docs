# Recon Existing eDiscovery Cases

## Description
`recon existing ediscovery cases` module executes reconnaissance to find existing cases in the tenant. Existing cases in environment can help quickly find critical data without having to launch new searches.

## Trigger
```
MAAD Attack Arsenal -> "Compliance" -> 2
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