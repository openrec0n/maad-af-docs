# List Mailboxes in Tenant

## Description
`list mailboxes in tenant` module executes reconnaissance to find exchange mailboxes in the connected tenant. 

## Trigger
```
MAAD Attack Arsenal -> "Exchange" -> 1
```

## MITRE ATT&CK Information

| Tactic         | Technique                                                                                                                                                                                                                                     |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Discovery | [Account Discovery: Email Account](https://attack.mitre.org/techniques/T1087/003/)|

## Additional Details
Revert module changes: N/A (Recon Module)

Microsoft services accessed by module:

* [Exchange Online](https://learn.microsoft.com/en-us/exchange/exchange-online)

External PowerShell module used: 

* [ExchangePowerShell](https://learn.microsoft.com/en-us/powershell/module/exchange/?view=exchange-ps)