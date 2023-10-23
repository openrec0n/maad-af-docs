# Invite External User to Teams

## Description
`invite external user to teams` module invites an external entity to Entra ID and attempts to add it to a teams group. This allows to maintain access to information in the teams group using the external entity.

## Trigger
```
MAAD Attack Arsenal -> "Teams" -> 3
```

## MITRE ATT&CK Information

| Tactic         | Technique                                                                                                                                                                                                                                     |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Collection | [Data from Information Repositories](https://attack.mitre.org/techniques/T1213/)|

## Additional Details
Revert module changes: Yes

Microsoft services accessed by module:

* [Teams](https://www.microsoft.com/en-us/microsoft-teams/group-chat-software)

External PowerShell module used: 

* [Azure AD](https://learn.microsoft.com/en-us/powershell/module/azuread/?view=azureadps-2.0)
* [MicrosoftTeamsPowerShell](https://learn.microsoft.com/en-us/powershell/module/teams/?view=teams-ps)