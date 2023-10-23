# Sample Tests
There is no strict way to use MAAD-AF (be creative). The modular structure allows users to execute attack modules in any sequence. Security practitioners can leverage the documented testing paths as example playbooks or reference to build their own.

## Test Path 1

An attacker compromises an identity through a phishing campaign to gain access to various Microsoft cloud services in the environment to steal high from M365 applications.

Standard employee accounts can be exploited to collect and exfiltrate critical data or abuse an identity’s reputation for greater organizational access. An attacker with access to an identity can easily access and exfiltrate data from cloud-accessible repositories, such as emails in users’ mailboxes, files in accessible SharePoint sites, teams messages, etc. During their attack, they may set up mail forwarding rules for continuous exfiltration or mailbox rules to hide signs of compromise. Once an attacker controls an account, they have access to any associated SaaS applications, leading to greater spreading through the organization.
```
Test Credential Privileges Required : Any identity with a exchange mailbox
```
| MAAD-AF Technique Name             | MAAD-AF Modules | MITRE Techniques                                                                                               |
| ---------------------------------- | --------------- | -------------------------------------------------------------------------------------------------------------- |
| Access via compromised credentials | Access.3        | [Initial Access : Valid Accounts: Cloud Accounts](https://attack.mitre.org/techniques/T1078/004/)              |
| Download from Sharepoint           | Sharepoint.4    | [Collection : Data from Information Repositories : Sharepoint](https://attack.mitre.org/techniques/T1213/002/) |
| Setup email deletion rule          | Exchange.4      | [Defense Evasion : Hide Artifacts](https://attack.mitre.org/techniques/T1564/008/)                             |
| Setup email forwarding             | Exchange.3      | [Collection : Email Collection](https://attack.mitre.org/techniques/T1114/)                                    |


## Test Path 2

Attackers have compromised a somewhat privileged identity in your environment through a credential breach. The attacker exploits the compromised identity's access & privileges to gain access to various Microsoft cloud services in the environment to perform reconnaissance, establish persistence, and perform privilege escalation.

Attackers exploit the access and privileges of the compromised identity to find valuable information within the environment and explore ways of abusing it further. In this case the attacker is exploiting the privileges of a user administrator in the environment to get all employees information which can be used in a further exploitation or in a future attack. The attacker also leverages the privilege of creating new identities in the environment to establish a backdoor that will allow for persistent access in future even the initially compromised identity were to get locked down. The attacker also attempts to assign privileges to the new backdoor account to allow execution of additional actions in the environment. Finally the attacker also attempts to reset password of another privileged identity which will allow the attacker to laterally move and perform actions with this new identities access & privileges.

```
Test Credential Privileges Required : User Administrator
* To execute all techniques with one credential
```

| MAAD-AF Technique Name                         | MAAD-AF Modules      | MITRE Techniques                                                                                  |
| ---------------------------------------------- | -------------------- | ------------------------------------------------------------------------------------------------- |
| All actions from PATH 1                        | #                    | \-                                                                                                |
| Access via compromised credentials             | Access.3             | [Initial Access : Valid Accounts: Cloud Accounts](https://attack.mitre.org/techniques/T1078/004/) |
| Dump user information                          | Recon.1 or Account.1 | [Account Discovery: Cloud Account](https://attack.mitre.org/techniques/T1087/004/)                                                                                               |
| Deploy backdoor account                        | Account.2            | [Create Account: Cloud Account](https://attack.mitre.org/techniques/T1136/003/)                   |
| Assign role                                    | Account.3            | [Persistence : Manipulation: Additional Cloud Roles](https://attack.mitre.org/tactics/TA0003)     |
| Reset password for another privileged identity | Account.5            | [Valid Accounts: Cloud Accounts](https://attack.mitre.org/techniques/T1078/004/)                                                                                                |

## Test Path 3

Attackers have gained access to a privileged identity in your environment through credentials bought on the dark web. Attackers enumerate through various Microsoft cloud services to gain access to them using the compromised identity's access & privilege.

With this level of access & privilege, attackers want to unlock access to as much service & data as possible in the environment and then exfiltrate it. Attackers begin by modifying trusted IP configuration to bypass any resource protect by a IP based conditional access policy. To maintain persistent access to critical information, attackers add an external attacker-controlled account to teams. To avoid leaving track of their actions, attackers proceed by attempting to disable Mailbox auditing. Attrackers progress by disabling MFA on a user account and then gaining access to that executive users mailbox followed by setting up mail forwarding from the mailbox which gives them access to a lot of sensitive data. Finally attackers attempt to leverage eDiscovery, a powerful search tool in Microsoft cloud environments. They create new searches to find sensitive data across different data repositories followed by escalating privileges to eDiscovery manager to exfiltrate that data out of the environment.

```
Test Credential Privileges Required : `Global Administrator`
* To execute all techniques with one credential
```

| MAAD-AF Technique Name               | MAAd-AF Modules | MITRE Technique                                                                                                                 |
| ------------------------------------ | --------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| All actions from PATH 1 & 2          | #               | \-                                                                                                                              |
| Access via compromised credentials   | Access.3        | [Initial Access : Valid Accounts: Cloud Accounts](https://attack.mitre.org/techniques/T1078/004/)                               |
| Modify Trusted IP configuration      | AzureAD.1       | [Defense Evasion : Impair Defenses](https://attack.mitre.org/techniques/T1562/)                                                 |
| Invite External User to Teams        | Teams.3         | [Collection : Data from Information Repositories](https://attack.mitre.org/techniques/T1213/)                                   |
| Disable Mailbox Auditing             | Exchange.5      | [Defense Evasion : Impair Defenses](https://attack.mitre.org/techniques/T1562/)                                                 |
| Disable MFA                          | Account.7       | [Defense Evasion : Modify Authentication Process : Multi-Factor Authentication](https://attack.mitre.org/techniques/T1556/006/) |
| Gain Access to Another Users Mailbox | Exchange.2      | [Persistence : Account Manipulation](https://attack.mitre.org/techniques/T1098/002/)                                            |
| Setup Email Forwarding               | Exchange.3      | [Collection : Email Collection](https://attack.mitre.org/techniques/T1114/)                                                     |
| eDiscovery search                    | Compliance.1    | [Collection : Automated Collection](https://attack.mitre.org/techniques/T1119/)                                                 |
| eDiscovery Privilege Esc. (Optional) | Compliance.7    | [Account Manipulation: Additional Cloud Roles](https://attack.mitre.org/techniques/T1098/003/)                                  |
| eDiscovery Exfil                     | Compliance.6    | [Collection : Automated Collection](https://attack.mitre.org/techniques/T1119/)                                                 |