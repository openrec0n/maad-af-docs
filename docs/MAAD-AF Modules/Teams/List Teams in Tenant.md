# List Teams in Tenant

## Description
`list teams in tenant` module executes reconnaissance to find all teams in the connected Entra ID tenant. 

## Trigger
```
MAAD Attack Arsenal -> "Teams" -> 1
```

## MITRE ATT&CK Information

| Tactic         | Technique                                                                                                                                                                                                                                     |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Discovery | [Permission Groups Discovery: Cloud Groups](https://attack.mitre.org/techniques/T1069/003/)|

## Additional Details
Revert module changes: N/A

Microsoft services accessed by module:

* [Teams](https://www.microsoft.com/en-us/microsoft-teams/group-chat-software)

External PowerShell module used: 

* [MicrosoftTeamsPowerShell](https://learn.microsoft.com/en-us/powershell/module/teams/?view=teams-ps)