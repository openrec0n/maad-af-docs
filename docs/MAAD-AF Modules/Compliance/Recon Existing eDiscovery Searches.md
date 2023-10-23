# Recon Existing eDiscovery Searches

## Description
`recon existing ediscovery searches` module executes reconnaissance to find searches in existing eDiscovery cases in the tenant. Existing searches can help quickly find critical data without having to launch new searches.

## Trigger
```
MAAD Attack Arsenal -> "Compliance" -> 3
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