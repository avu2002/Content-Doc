Vendor: Varonis
===============
### Product: [Data Security Platform](../ds_varonis_data_security_platform.md)
### Use-Case: [Data Leak](../../../../UseCases/uc_data_leak.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  21   |   15   |     6      |      9      |    9    |

| Event Type | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | Models                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| ---------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| dlp-alert  | <b>T1204 - User Execution</b><br> ↳ <b>DLP-UBp-F</b>: First blocked process for the user<br><br><b>T1048 - Exfiltration Over Alternative Protocol</b><br> ↳ <b>DLP-OU-ALERT-F</b>: First DLP alert triggered for this user<br> ↳ <b>DLP-OU-ALERT-A</b>: Abnormal user triggering DLP alert<br> ↳ <b>DLP-OG-ALERT-F</b>: First DLP alert triggered for peer group in the organization<br> ↳ <b>DLP-OG-ALERT-A</b>: Abnormal peer group triggering DLP alert in the organization<br> ↳ <b>DLP-OA-F</b>: First DLP policy violation from asset for the organization<br><br><b>T1020 - Automated Exfiltration</b><br> ↳ <b>DLP-AN-ALERT-F</b>: First DLP alert name on the asset<br> ↳ <b>DLP-AN-ALERT-A</b>: Abnormal DLP alert name on the asset<br> ↳ <b>DLP-ON-ALERT-F</b>: First DLP alert (by name) in the organization<br> ↳ <b>DLP-ON-ALERT-A</b>: Abnormal DLP alert (by name) in the organization<br> ↳ <b>DLP-ZN-ALERT-F</b>: First DLP alert (by name) in the zone<br> ↳ <b>DLP-ZN-ALERT-A</b>: Abnormal DLP alert (by name) in the zone<br> ↳ <b>DLP-HN-ALERT-F</b>: First DLP alert (by name) in the asset<br> ↳ <b>DLP-HN-ALERT-A</b>: Abnormal DLP alert (by name) in the asset<br> ↳ <b>DLP-OA-ALERT-F</b>: First DLP alert triggered for asset in the organization |  • <b>DLP-UBp</b>: Processes that are blocked from execution for the user<br> • <b>DLP-OA</b>: Assets on which DLP policy violations occurred in the organization<br> • <b>DLP-OG-ALERT</b>: Peer groups triggering DLP alerts in the organization<br> • <b>DLP-OU-ALERT</b>: Users triggering DLP alerts in the organization<br> • <b>A-DLP-OA-ALERT</b>: Assets triggering DLP alerts in the organization<br> • <b>A-DLP-HN-ALERT</b>: DLP alert names triggered in the asset<br> • <b>A-DLP-ZN-ALERT</b>: DLP alert names triggered in the zone<br> • <b>A-DLP-ON-ALERT</b>: DLP alert names triggered in the organization<br> • <b>A-DLP-AN-ALERT</b>: DLP alert names on asset |
| vpn-logout | <b>T1052.001 - Exfiltration Over Physical Medium: Exfiltration over USB</b><br> ↳ <b>UW-BSum</b>: Abnormal amount of data written to USB<br><br><b>T1048.003 - Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol</b><br> ↳ <b>EM-FNum</b>: Abnormal number of outgoing emails<br> ↳ <b>EM-DNum</b>: Abnormal number of outgoing email domains<br> ↳ <b>EM-BSum-personal</b>: Abnormal size of outgoing emails to personal account<br> ↳ <b>EM-BSum</b>: Abnormal size of outgoing emails<br><br><b>T1052 - Exfiltration Over Physical Medium</b><br> ↳ <b>PR-BSum</b>: Abnormal size of print objects                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |  • <b>UW-BSum</b>: Sum of bytes written to USB<br> • <b>EM-BSum</b>: Sum of bytes in outgoing emails<br> • <b>EM-BSum-personal</b>: Sum of bytes in outgoing emails to personal domains<br> • <b>EM-DNum</b>: Number of distinct domains<br> • <b>EM-FNum</b>: Count of outgoing emails<br> • <b>PR-BSum</b>: Sum of bytes of data printed by user                                                                                                                                                                                                                                                                                                                                  |