# Disable Mailbox Auditing

## Description
`disable mailbox auditing` module deploys configuration to enable audit log bypass for a target account effectively disabling logging for actions taken by the account on any mailbox.

## Trigger
```
MAAD Attack Arsenal -> "Exchange" -> 5
```

## MITRE ATT&CK Information

| Tactic         | Technique                                                                                                                                                                                                                                     |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Defense Evasion | [Impair Defenses](https://attack.mitre.org/techniques/T1562/)|

## Additional Details
Revert module changes: Yes

Microsoft services accessed by module:

* [Exchange Online](https://learn.microsoft.com/en-us/exchange/exchange-online)

External PowerShell module used: 

* [ExchangePowerShell](https://learn.microsoft.com/en-us/powershell/module/exchange/?view=exchange-ps)