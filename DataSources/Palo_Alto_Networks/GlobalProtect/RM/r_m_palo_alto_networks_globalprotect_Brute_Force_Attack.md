Vendor: Palo Alto Networks
==========================
### Product: [GlobalProtect](../ds_palo_alto_networks_globalprotect.md)
### Use-Case: [Brute Force Attack](../../../../UseCases/uc_brute_force_attack.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  13   |   5    |     4      |     10      |   10    |

| Event Type   | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | Models                                                                                                                                                                                                                                                                                                                               |
| ------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| failed-logon | <b>T1021.001 - Remote Services: Remote Desktop Protocol</b><b>T1110 - Brute Force</b><br> ↳ <b>A-FL-MULTI-USERS</b>: Multiple users failed to login<br> ↳ <b>FL-MULTI-USERS-S</b>: Multiple users failed to login (S)<br> ↳ <b>FL-MULTI-USERS-L</b>: Multiple users failed to login (L)<br> ↳ <b>FL-MULTI-USERS-M</b>: Multiple users failed to login (M)<br> ↳ <b>A-FL-MULTI-DEST</b>: Failed logins to multiple destinations from host<br> ↳ <b>FL-MULTI-DEST-S</b>: Failed logins to multiple destinations from host (S)<br> ↳ <b>FL-MULTI-DEST-M</b>: Failed logins to multiple destinations from host (M)<br> ↳ <b>RDP-Brute-Force</b>: Abnormal number of RDP failed logons for this user |                                                                                                                                                                                                                                                                                                                                      |
| remote-logon | <b>T1078 - Valid Accounts</b><br> ↳ <b>AS-PV-UHWoPC</b>: Access to Password Vault managed asset with no password checkout for user                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |  • <b>AS-PV-OA</b>: Password retrieval based accounts                                                                                                                                                                                                                                                                                |
| vpn-logout   | <b>T1003 - OS Credential Dumping</b><br> ↳ <b>AS-PV-USCOUNT-A</b>: Abnormal number of password safes used by user<br> ↳ <b>AS-PV-OSize-A</b>: Abnormal number of password retrievals in the organization<br> ↳ <b>AS-PV-GSize-A</b>: Abnormal number of password retrievals in the peer group<br> ↳ <b>AS-PV-USize-A</b>: Abnormal number of password retrievals in the user                                                                                                                                                                                                                                                                                                                    |  • <b>AS-PV-USize</b>: Count of password retrievals in a session for the user<br> • <b>AS-PV-GSize</b>: Count of password retrievals in a session for the peer group<br> • <b>AS-PV-OSize</b>: Count of password retrievals in a session for the organization<br> • <b>AS-PV-USCOUNT</b>: Count of safe values accessed in a session |