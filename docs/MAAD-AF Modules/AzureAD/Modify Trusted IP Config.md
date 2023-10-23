# Modify Trusted IP Config

## Description
`modify trusted ip config` module deploys a new named location policy which adds a specified IP as trusted in the Entra ID environment. This can allow users to circumvent certain conditional access policies in the environment enforcing access for only trusted locations. 

The module accepts a static IP for configuring the named location policy or can automatically query users current public IP for the configuration.

## Trigger
```
MAAD Attack Arsenal -> "AzureAD" -> 1
```

## MITRE ATT&CK Information

| Tactic         | Technique                                                                                                                                                                                                                                     |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Defense Evasion | [Impair Defenses](https://attack.mitre.org/techniques/T1562/)|

## Additional Details
Revert module changes: Yes

Microsoft services accessed by module:

* [Entra ID (Azure AD)](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id)

External PowerShell module used: 

* [AzureAd](https://www.powershellgallery.com/packages/AzureAD/)
