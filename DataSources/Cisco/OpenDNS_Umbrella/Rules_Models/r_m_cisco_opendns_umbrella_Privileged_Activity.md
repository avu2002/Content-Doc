Vendor: Cisco
=============
### Product: [OpenDNS Umbrella](../ds_cisco_opendns_umbrella.md)
### Use-Case: [Privileged Activity](../../../../UseCases/uc_privileged_activity.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   6   |   6    |     3      |      6      |    6    |

| Event Type | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | Models                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| ---------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| vpn-logout | <b>T1078 - Valid Accounts</b><br> ↳ <b>APP-UOb-Number</b>: Abnormal number of application objects accessed for user<br><br><b>T1068 - Exploitation for Privilege Escalation</b><br> ↳ <b>WPA-UACount</b>: Abnormal number of privilege access events for user<br> ↳ <b>FDS-UCount</b>: Abnormal number of failed directory service events in the user<br> ↳ <b>DS-Count</b>: Abnormal number of directory service events in the organization<br> ↳ <b>DS-UCount</b>: Abnormal number of directory service events in the user<br><br><b>T1003 - OS Credential Dumping</b><br> ↳ <b>AS-PV-USCOUNT-A</b>: Abnormal number of password safes used by user |  • <b>APP-UOb-Number</b>: Count of app objects accessed in a session<br> • <b>DS-UCount</b>: Count of directory service activity events in the user<br> • <b>DS-Count</b>: Count of directory service activity events in the organization<br> • <b>FDS-UCount</b>: Count of failed directory service activity events in the user<br> • <b>AS-PV-USCOUNT</b>: Count of safe values accessed in a session<br> • <b>WPA-UACount</b>: Count of admin privilege events for user |