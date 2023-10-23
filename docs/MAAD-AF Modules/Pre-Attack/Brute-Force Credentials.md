# Brute-Force Credentials

## Description
`brute-force credentials` module executes a password brute-force attack on a target identity in Entra ID. Brute-force attempts to gain access to an account when the password for the account is unknown. 

This module requires a password list in txt file format as input for bruteforce. Placed the password file in `\MAAD-AF` directory.

If the brute-force is successful, this module stores the cracked credentials in *MAAD Credential Store* for use in future.

## Trigger
```
MAAD Attack Arsenal -> "Pre-Attack" -> 2
```

## MITRE ATT&CK Information

| Tactic         | Technique                                                                                                                                                                                                                                     |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Credential Access | [Brute Force](https://attack.mitre.org/techniques/T1110/)|

## Additional Details

* Brute-force is attempted against the reporting web service endpoint: https://reports.office365.com/ecp/reportingwebservice/reporting.svc
