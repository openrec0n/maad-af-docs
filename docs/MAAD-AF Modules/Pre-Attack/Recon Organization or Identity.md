# Recon Organization/Identity

## Description
`recon organization/identity` module executes uses a username/email address and executes reconnaissance to return various information such as tenant info, account existence in target tenant, DNS info, etc. 

## Trigger
```
MAAD Attack Arsenal -> "Pre-Attack" -> 1
```

## MITRE ATT&CK Information

| Tactic         | Technique                                                                                                                                                                                                                                     |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Discovery | [Account Discovery](https://attack.mitre.org/techniques/T1087/)|

## Additional Details

External PowerShell module used: 

* [AADInternals](https://aadinternals.com/aadinternals/)
