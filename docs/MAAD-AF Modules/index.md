# MAAD-AF Modules

MAAD-AF has `11` primary modules and `50+` sub-modules that can execute against various services & resources in EntraID (Azure AD) and M365 environment. MAAD-AF attack library is rapidly growing and new techniques are regularly added from maintainers and community contributions.

## Modules

| Module      | Option | Sub-Module                                 |
| ----------- | ------ | ------------------------------------------ |
| [Pre-Attack](Pre-Attack/Pre-Attack.md)  | 1      | [Recon Organization/Identity](Pre-Attack/Recon Organization or Identity.md)                |
| [Pre-Attack](Pre-Attack/Pre-Attack.md)  | 2      | [Brute-Force Credentials](Pre-Attack/Brute-Force Credentials.md)                    |
| [Access](Access/Access.md)      | 1      | [Show Available Credentials](Access/Show Available Credentials.md)                 |
| [Access](Access/Access.md)      | 2      | [Add Credentials](Access/Add Credentials.md)                            |
| [Access](Access/Access.md)      | 3      | [Establish Access - All](Access/Establish Access - All.md)                     |
| [Access](Access/Access.md)      | 4      | [Establish Access - AzureAD](Access/Establish Access - AzureAD.md)                 |
| [Access](Access/Access.md)      | 5      | [Establish Access - Az](Access/Establish Access - Az.md)                      |
| [Access](Access/Access.md)      | 6      | [Establish Access - Exchange Online](Access/Establish Access - Exchange Online.md)         |
| [Access](Access/Access.md)      | 7      | [Establish Access - Teams](Access/Establish Access - Teams.md)                   |
| [Access](Access/Access.md)      | 8      | [Establish Access - Msol](Access/Establish Access - Msol.md)                    |
| [Access](Access/Access.md)      | 9      | [Establish Access - Sharepoint Site](Access/Establish Access - Sharepoint Site.md)         |
| [Access](Access/Access.md)      | 10     | [Establish Access - Sharepoint Admin Center](Access/Establish Access - Sharepoint Admin Center.md) |
| [Access](Access/Access.md)      | 11     | [Establish Access - Compliance (eDiscovery)](Access/Establish Access - Compliance eDiscovery.md) |
| [Access](Access/Access.md)      | 12     | [Kill All Access](Access/Kill All Access.md)                            |
| [Access](Access/Access.md)      | 13     | [Anonymize Access with TOR](Access/Anonymize Access with TOR.md)                  |
| [Recon](Recon/Recon.md)       | 1      | AAD : Find All Accounts                    |
| [Recon](Recon/Recon.md)       | 2      | AAD : Find All Groups                      |
| [Recon](Recon/Recon.md)       | 3      | AAD : Find All Service Principals          |
| [Recon](Recon/Recon.md)       | 4      | AAD : Find All Auth Policy                 |
| [Recon](Recon/Recon.md)       | 5      | AAD : Recon Named Locations                |
| [Recon](Recon/Recon.md)       | 6      | AAD : Recon Conditional Access Policy      |
| [Recon](Recon/Recon.md)       | 7      | AAD : Recon Registered Devices for Account |
| [Recon](Recon/Recon.md)       | 8      | AAD : Recon All Accessible Tenants         |
| [Recon](Recon/Recon.md)       | 9      | AAD : Recon Account Group Roles            |
| [Recon](Recon/Recon.md)       | 10     | Teams : Recon All Teams                    |
| [Recon](Recon/Recon.md)       | 11     | SP : Recon All Sharepoint Sites            |
| [Recon](Recon/Recon.md)       | 12     | Exchange : Find All Mailboxes              |
| [Account](Account/Account.md)     | 1      | [List Accounts in Tenant](Account/List Accounts in Tenant.md)                    |
| [Account](Account/Account.md)     | 2      | [Deploy Backdoor Account](Account/Deploy Backdoor Account.md)                    |
| [Account](Account/Account.md)     | 3      | [Assign Azure AD Role to Account](Account/Assign Azure AD Role to Account.md)            |
| [Account](Account/Account.md)     | 4      | [Assign Management Role Account](Account/Assign Management Role Account.md)             |
| [Account](Account/Account.md)     | 5      | [Reset Password](Account/Reset Password.md)                             |
| [Account](Account/Account.md)     | 6      | [Brute-Force Credentials](Account/Brute-Force Credentials.md)                    |
| [Account](Account/Account.md)     | 7      | [Disable Account MFA](Account/Disable Account MFA.md)                        |
| [Account](Account/Account.md)     | 8      | [Delete User](Account/Delete User.md)                                |
| [Group](Group/Group.md)       | 1      | [List Groups in Tenant](Group/List Groups in Tenant.md)                      |
| [Group](Group/Group.md)       | 2      | [Create Group](Group/Create Group.md)                               |
| [Group](Group/Group.md)       | 3      | [Add user to Group](Group/Add user to Group.md)                          |
| [Group](Group/Group.md)       | 4      | [Assign Role to Group](Group/Assign Role to Group.md)                       |
| [Application](Application/Application.md) | 1      | [List Applications in Tenant](Application/List Applications in Tenant.md)                |
| [Application](Application/Application.md) | 2      | [Create Application](Application/Create Application.md)                         |
| [Application](Application/Application.md) | 3      | [Generate new Application Credentials](Application/Generate new Application Credentials.md)       |
| [AzureAD](AzureAD/AzureAD.md)     | 1      | [Modify Trusted IP Config](AzureAD/Modify Trusted IP Config.md)                   |
| [AzureAD](AzureAD/AzureAD.md)      | 2      | [Download All Account List](AzureAD/Download All Account List.md)                  |
| [AzureAD](AzureAD/AzureAD.md)      | 3      | [Exploit Cross Tenant Sync](AzureAD/Exploit Cross Tenant Sync.md)                  |
| [Exchange](Exchange/Exchange.md)    | 1      | [List Mailboxes in Tenant](Exchange/List Mailboxes in Tenant.md)                   |
| [Exchange](Exchange/Exchange.md)    | 2      | [Gain Access to Another Mailbox](Exchange/Gain Access to Another Mailbox.md)             |
| [Exchange](Exchange/Exchange.md)    | 3      | [Setup Email Forwarding](Exchange/Setup Email Forwarding.md)                     |
| [Exchange](Exchange/Exchange.md)    | 4      | [Setup Email Deletion Rule](Exchange/Setup Email Deletion Rule.md)                  |
| [Exchange](Exchange/Exchange.md)    | 5      | [Disable Mailbox Auditing](Exchange/Disable Mailbox Auditing.md)                   |
| [Exchange](Exchange/Exchange.md)    | 6      | [Disable Anti-Phishing Policy](Exchange/Disable Anti-Phishing Policy.md)               |
| [Teams](Teams/Teams.md)       | 1      | [List Teams in Tenant](Teams/List Teams in Tenant.md)                       |
| [Teams](Teams/Teams.md)        | 2      | [Search Creds in Teams](Teams/Search Creds in Teams.md)                      |
| [Teams](Teams/Teams.md)        | 3      | [Invite External User to Teams](Teams/Invite External User to Teams.md)              |
| [Sharepoint](SharePoint/SharePoint.md)  | 1      | [List Sharepoint Sites](SharePoint/List Sharepoint Sites.md)                      |
| [Sharepoint](SharePoint/SharePoint.md)  | 2      | [Gain Access to Sharepoint Site](SharePoint/Gain Access to Sharepoint Site.md)             |
| [Sharepoint](SharePoint/SharePoint.md)  | 3      | [Search Files in Sharepoint](SharePoint/Search Files in Sharepoint.md)                |
| [Sharepoint](SharePoint/SharePoint.md)  | 4      | [Exfiltrate Data from Sharepoint](SharePoint/Exfiltrate Data from Sharepoint.md)            |
| [Sharepoint](SharePoint/SharePoint.md)  | 5      | [Upload File to Sharepoint Site](SharePoint/Upload File to Sharepoint Site.md)             |
| [Compliance](Compliance/Compliance.md)  | 1      | [Launch New eDiscovery Search](Compliance/Launch New eDiscovery Search.md)          |
| [Compliance](Compliance/Compliance.md)  | 2      | [Recon Existing eDiscovery Cases](Compliance/Recon Existing eDiscovery Cases.md)            |
| [Compliance](Compliance/Compliance.md)  | 3      | [Recon Existing eDiscovery Searches](Compliance/Recon Existing eDiscovery Searches.md)         |
| [Compliance](Compliance/Compliance.md)  | 4      | [Find eDiscovery Search Details](Compliance/Find eDiscovery Search Details.md)                   |
| [Compliance](Compliance/Compliance.md)  | 5      | [Find eDiscovery Case Members](Compliance/Find eDiscovery Case Members.md)               |
| [Compliance](Compliance/Compliance.md)  | 6      | [Exfil Data with eDiscovery](Compliance/Exfil Data with eDiscovery.md)                 |
| [Compliance](Compliance/Compliance.md)  | 7      | [Escalate eDiscovery Privileges](Compliance/Escalate eDiscovery Privileges.md)             |
| [Compliance](Compliance/Compliance.md)  | 8      | [Install Unified Export Tool](Compliance/Install Unified Export Tool.md)                |

