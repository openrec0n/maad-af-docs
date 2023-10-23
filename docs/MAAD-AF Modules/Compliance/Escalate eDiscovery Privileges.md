# Escalate eDiscovery Privileges

## Description
`escalate ediscovery privileges` module escalates the connected identities privileges by attempting to assign the eDiscovery Manager/Administrator roles.

## Trigger
```
MAAD Attack Arsenal -> "Compliance" -> 7
```

## MITRE ATT&CK Information

| Tactic         | Technique                                                                                                                                                                                                                                     |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Persistence | [Account Manipulation: Additional Cloud Roles](https://attack.mitre.org/techniques/T1098/003/)|

## Additional Details
Revert module changes: No

Microsoft services being accessed by this module:

* [Compliance](https://learn.microsoft.com/en-us/purview/microsoft-365-compliance-center)

External PowerShell module used: 

* [ExchangePowerShell](https://learn.microsoft.com/en-us/powershell/module/exchange/?view=exchange-ps)