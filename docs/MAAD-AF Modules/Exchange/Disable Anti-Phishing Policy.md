# Disable Anti-Phishing Policy

## Description
`disable anti-phishing policy` module modifies configuration to disable a specified exchange anti-phishing policy on a targeted mailbox.

## Trigger
```
MAAD Attack Arsenal -> "Exchange" -> 6
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