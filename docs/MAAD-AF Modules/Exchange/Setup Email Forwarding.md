# Setup Mail Forwarding

## Description
`setup mail forwarding` module deploys a new mailbox forwarding rule on the target mailbox. This module forwards emails from the target mailbox to an external mailbox. 

## Trigger
```
MAAD Attack Arsenal -> "Exchange" -> 3
```

## MITRE ATT&CK Information

| Tactic         | Technique                                                                                                                                                                                                                                     |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Collection | [Email Collection](https://attack.mitre.org/techniques/T1114/)|

## Additional Details
Revert module changes: Yes

Microsoft services accessed by module:

* [Exchange Online](https://learn.microsoft.com/en-us/exchange/exchange-online)

External PowerShell module used: 

* [ExchangePowerShell](https://learn.microsoft.com/en-us/powershell/module/exchange/?view=exchange-ps)