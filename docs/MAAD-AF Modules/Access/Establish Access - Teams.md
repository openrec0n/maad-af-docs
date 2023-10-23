# Establish Access - Teams

## Description
`establish access - teams` module attempts to establish access with Teams service using the access & privilege of the credential supplied by user.

## Trigger
```
MAAD Attack Arsenal -> "Access" -> 7
```

## MITRE ATT&CK Information

| Tactic         | Technique                                                                                                                                                                                                                                     |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Initial Access | [Valid Accounts](https://attack.mitre.org/techniques/T1078/)|

## Additional Details
Microsoft services being accessed by this module:

* [Microsoft Teams](https://www.microsoft.com/en-us/microsoft-teams/group-chat-software)

External PowerShell module used: 

* [MicrosoftTeams](https://www.powershellgallery.com/packages/MicrosoftTeams/)
