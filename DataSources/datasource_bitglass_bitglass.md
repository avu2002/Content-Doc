Vendor: Bitglass
================
Product: Bitglass
-----------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  24   |   5    |     4      |      3      |    3    |

|                              Use-Case                               | Activity Types                                                                            | Event Types/Parsers                                                                               | MITRE TTP                                                                    | Content                                              |
|:-------------------------------------------------------------------:| ----------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------- | ---------------------------------------------------- |
|    [Data Exfiltration](../UseCases/usecase_data_exfiltration.md)    | <ul><li>Data Loss Prevention</li></ul>                                                    |  dlp-alert<br> ↳ [cef-bitglass-dlp-alert](../Parsers/parserContent_cef-bitglass-dlp-alert.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>T1204 - User Execution<br> | <ul><li>14 Rules</li></ul><ul><li>3 Models</li></ul> |
|    [Malware Detection](../UseCases/usecase_malware_detection.md)    | <ul><li>Data Loss Prevention</li><li>Endpoint Activity</li><li>Process Activity</li></ul> |  dlp-alert<br> ↳ [cef-bitglass-dlp-alert](../Parsers/parserContent_cef-bitglass-dlp-alert.md)<br> | T1204 - User Execution<br>                                                   | <ul><li>5 Rules</li></ul><ul><li>1 Models</li></ul>  |
| [Ransomware Detection](../UseCases/usecase_ransomware_detection.md) | <ul><li>Data Loss Prevention</li><li>Endpoint Activity</li><li>Process Activity</li></ul> |  dlp-alert<br> ↳ [cef-bitglass-dlp-alert](../Parsers/parserContent_cef-bitglass-dlp-alert.md)<br> | T1204 - User Execution<br>                                                   | <ul><li>5 Rules</li></ul><ul><li>1 Models</li></ul>  |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access | Execution                                                           | Persistence | Privilege Escalation | Defense Evasion | Credential Access | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration                                                                                | Impact |
| -------------- | ------------------------------------------------------------------- | ----------- | -------------------- | --------------- | ----------------- | --------- | ---------------- | ---------- | ------------------- | ------------------------------------------------------------------------------------------- | ------ |
|                | [User Execution](https://attack.mitre.org/techniques/T1204)<br><br> |             |                      |                 |                   |           |                  |            |                     | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br> |        |