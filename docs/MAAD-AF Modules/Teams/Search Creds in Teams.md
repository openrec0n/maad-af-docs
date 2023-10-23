# Search Creds in Teams

## Description
`search credentials in teams` module searches for specified keywords in a target team. This can be used to find credentials or other critical data share in chat messages. 

## Trigger
```
MAAD Attack Arsenal -> "Teams" -> 2
```

## MITRE ATT&CK Information

| Tactic         | Technique                                                                                                                                                                                                                                     |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Credential Access | [Unsecured Credentials: Chat Messages](https://attack.mitre.org/techniques/T1552/008/)|

## Additional Details
Revert module changes: N/A

Microsoft services accessed by module:

* [Teams](https://www.microsoft.com/en-us/microsoft-teams/group-chat-software)

External PowerShell module used: 

* [MicrosoftTeamsPowerShell](https://learn.microsoft.com/en-us/powershell/module/teams/?view=teams-ps)