# Setup Email Deletion Rule

## Description
`setup email deletion rule` module deploys a new mailbox rule on a target mailbox that deletes emails matching a user specified criteria. This allows to hide emails that could indicate compromise such as security alerts, responses to Internal Spearphishing emails, etc. 

## Trigger
```
MAAD Attack Arsenal -> "Exchange" -> 4
```

## MITRE ATT&CK Information

| Tactic         | Technique                                                                                                                                                                                                                                     |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Defense Evasion | [Hide Artifacts: Email Hiding Rules](https://attack.mitre.org/techniques/T1564/008/)|

## Additional Details
Revert module changes: Yes

Microsoft services accessed by module:

* [Exchange Online](https://learn.microsoft.com/en-us/exchange/exchange-online)

External PowerShell module used: 

* [ExchangePowerShell](https://learn.microsoft.com/en-us/powershell/module/exchange/?view=exchange-ps)