# Anonymize Access with TOR

## Description
`anonymize access with TOR` module sets up a SOCKS proxy and deploys local configuration on host to route network traffic through TOR nodes to anonymize identity. This module requires installation of the TOR executable and updating config in `MAAD_Local_Configuration` file

## Trigger
```
MAAD Attack Arsenal -> "Access" -> 13
```

## MITRE ATT&CK Information

| Tactic         | Technique                                                                                                                                                                                                                                     |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Command and Control | [Proxy](https://attack.mitre.org/techniques/T1090/)|

## Additional Details
* This module requires installation of TOR executable which can be downloaded from [torproject.org](https://www.torproject.org/download/) 
* Users also need to update *tor_root_directory* in `MAAD-AF\Local\MAAD_Local_Configuration.json` with the local installation path of TOR
* This module modifies two host key values: *HKCU:\Software\Microsoft\Windows\CurrentVersion\Internet Settings* & *HKCU:\Software\Microsoft\Windows\CurrentVersion\Internet Settings*

