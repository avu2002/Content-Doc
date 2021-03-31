Vendor: IBM
===========
### Product: [IBM DB2](../ds_ibm_ibm_db2.md)
### Use-Case: [Compromised Credentials](../../../../UseCases/uc_compromised_credentials.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  51   |   26   |     9      |      4      |    4    |

| Event Type            | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | Models                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| authentication-failed | <b>T1133 - External Remote Services</b><br> ↳ <b>FA-UC-F</b>: Failed activity from a new country<br> ↳ <b>FA-GC-F</b>: First Failed activity in session from country in which peer group has never had a successful activity                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |  • <b>UA-GC</b>: Countries for peer group<br> • <b>UA-UC</b>: Countries for user                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| file-read             | <b>T1083 - File and Directory Discovery</b><br> ↳ <b>FA-OG-A</b>: Abnormal access to source code files for user in the peer group<br> ↳ <b>FA-SFU-F</b>: First access to folder containing source code by user<br><br><b>T1078 - Valid Accounts</b><br> ↳ <b>FA-Account-deactivated</b>: File Activity from a de-activated user account                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |  • <b>FA-SFU</b>: Source code folder access by users<br> • <b>FA-OG</b>: Users accessing source code files in the peer group                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| remote-logon          | <b>T1078 - Valid Accounts</b><br> ↳ <b>AE-UA-F</b>: First activity type for user<br> ↳ <b>AS-PV-UHWoPC</b>: Access to Password Vault managed asset with no password checkout for user<br> ↳ <b>AL-F-MultiWs</b>: Multiple workstations in a single session<br> ↳ <b>NEW-USER-F</b>: User with no event history<br> ↳ <b>DC18-new</b>: Account switch by new user<br><br><b>T1133 - External Remote Services</b><br> ↳ <b>UA-UC-A</b>: Abnormal activity from country for user<br> ↳ <b>UA-UC-Suspicious</b>: Activity from suspicious country<br> ↳ <b>UA-UC-Two</b>: Activity from two different countries<br><br><b>T1550 - Use Alternate Authentication Material</b><br> ↳ <b>RLA-UAPackage-F</b>: First time usage of Windows authentication package<br> ↳ <b>RLA-UAPackage-A</b>: Abnormal usage of Windows authentication package<br><br><b>T1558.003 - Steal or Forge Kerberos Tickets: Kerberoasting</b><br> ↳ <b>A-KL-UToE-A</b>: Abnormal kerberos ticket options and encryption type for asset<br> ↳ <b>A-KL-ToEt-Roast</b>: Suspicious or weak encryption type used for obtaining the kerberos TGTs using non kerberos service for this asset<br> ↳ <b>KL-ToEt-Roast</b>: Suspicious or weak encryption type used for obtaining kerberos TGTs using non kerberos service<br> ↳ <b>KL-OEt-F</b>: First kerberos ticket encryption type for organization<br> ↳ <b>KL-OEt-A</b>: Abnormal kerberos ticket encryption type for organization<br> ↳ <b>KL-OTo-F</b>: First kerberos ticket options for organization<br> ↳ <b>KL-OTo-A</b>: Abnormal kerberos ticket options for organization<br> ↳ <b>KL-UTo-F</b>: First kerberos ticket options for user<br> ↳ <b>KL-UTo-A</b>: Abnormal kerberos ticket options for user<br> ↳ <b>KL-UToE-F</b>: First kerberos ticket options and encryption type combination for user<br> ↳ <b>KL-UToE-A</b>: Abnormal kerberos ticket options and encryption type for user<br> ↳ <b>KL-USn-A</b>: Abnormal service to obtain TGTs for user<br><br><b>T1078 - Valid Accounts</b><b>T1133 - External Remote Services</b><br> ↳ <b>UA-GC-F</b>: First activity from country for group<br> ↳ <b>UA-OC-F</b>: First activity from country for organization<br><br><b>T1550.002 - Use Alternate Authentication Material: Pass the Hash</b><br> ↳ <b>A-PTH-ALERT-sH</b>: Possible pass the hash attack from this source host<br> ↳ <b>PTH-ALERT-sH</b>: Possible pass the hash attack from the source<br> ↳ <b>NTLM-mismatch</b>: <br><br><b>T1021 - Remote Services</b><b>T1078 - Valid Accounts</b><br> ↳ <b>RLA-UsZ-F</b>: First source network zone for user<br> ↳ <b>RLA-UsZ-A</b>: Abnormal source network zone for user |  • <b>RLA-UAPackage</b>: Windows authentication packages used when connecting to remote hosts<br> • <b>KL-USn</b>: Services to obtain TGTs for user<br> • <b>KL-UToE</b>: Ticket options and encryption type combination for user<br> • <b>KL-OTo</b>: Ticket Options for organization<br> • <b>KL-OEt</b>: Encryption Types for organization<br> • <b>UA-OC</b>: Countries for organization<br> • <b>UA-GC</b>: Countries for peer group<br> • <b>UA-UC</b>: Countries for user<br> • <b>AS-PV-OA</b>: Password retrieval based accounts<br> • <b>AE-NTLM</b>: Models ntlm hostnames in the organization<br> • <b>AE-OHr</b>: Random hostnames<br> • <b>AE-UA</b>: All activity for users<br> • <b>RLA-UsZ</b>: Source zones for user<br> • <b>A-KL-UToE</b>: Ticket options and encryption type combination for asset<br> • <b>A-AE-OHr</b>: Random hostnames on asset |
| security-alert        | <b>T1078 - Valid Accounts</b><br> ↳ <b>SA-AN-ALERT-F</b>: First security alert name on the asset<br> ↳ <b>SA-AN-ALERT-A</b>: Abnormal security alert name on the asset<br> ↳ <b>SA-ON-ALERT-F</b>: First security alert (by name) in the organization<br> ↳ <b>SA-ON-ALERT-A</b>: Abnormal security alert (by name) in the organization<br> ↳ <b>SA-ZN-ALERT-F</b>: First security alert (by name) in the zone<br> ↳ <b>SA-ZN-ALERT-A</b>: Abnormal security alert (by name) in the zone<br> ↳ <b>SA-HN-ALERT-F</b>: First security alert (by name) in the asset<br> ↳ <b>SA-HN-ALERT-A</b>: Abnormal security alert (by name) in the asset<br> ↳ <b>SA-OA-ALERT-A</b>: Abnormal asset triggering security alert for organization<br> ↳ <b>SA-OU-ALERT-F</b>: First security alert triggered for this user in the organization<br> ↳ <b>SA-OU-ALERT-A</b>: Abnormal user triggering security alert in the organization<br> ↳ <b>SA-OG-ALERT-F</b>: First security alert triggered for peer group in the organization<br> ↳ <b>SA-OG-ALERT-A</b>: Abnormal peer group triggering security alert in the organization<br> ↳ <b>SA-UA-A</b>: Abnormal security alert name for user<br> ↳ <b>SA-OA-A</b>: Abnormal security alert name in the organization<br><br><b>T1027.005 - Obfuscated Files or Information: Indicator Removal from Tools</b><br> ↳ <b>ALERT-DL</b>: DL Correlation rule alert on asset accessed by this user<br><br><b>T1059.001 - Command and Scripting Interperter: PowerShell</b><br> ↳ <b>A-ALERT-COMPROMISED-POWERSHELL</b>: Powershell and security alerts                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |  • <b>SA-OA</b>: Security alert names in the organization<br> • <b>SA-UA</b>: Security alert names for user<br> • <b>SA-OG-ALERT</b>: Peer groups triggering security alerts in the organization<br> • <b>SA-OU-ALERT</b>: Users triggering security alerts in the organization<br> • <b>A-SA-OA-ALERT</b>: Assets triggering security alerts in the organization<br> • <b>A-SA-HN-ALERT</b>: Security alert names triggered by the asset<br> • <b>A-SA-ZN-ALERT</b>: Security alert names triggered in the zone<br> • <b>A-SA-ON-ALERT</b>: Security alert names triggered in the organization<br> • <b>A-SA-AN-ALERT</b>: Security alert names on asset                                                                                                                                                                                                                |