# Gain Access to Another Mailbox

## Description
`gain access to another mailbox` module adds permissions to a target mailbox granting user access to that mailbox. 

## Trigger
```
MAAD Attack Arsenal -> "Exchange" -> 2
```

## MITRE ATT&CK Information

| Tactic         | Technique                                                                                                                                                                                                                                     |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Persistence | [Account Manipulation](https://attack.mitre.org/techniques/T1098/002/)|

## Additional Details
Revert module changes: Yes

Microsoft services accessed by module:

* [Exchange Online](https://learn.microsoft.com/en-us/exchange/exchange-online)

External PowerShell module used: 

* [ExchangePowerShell](https://learn.microsoft.com/en-us/powershell/module/exchange/?view=exchange-ps)