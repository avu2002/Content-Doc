Vendor: Symantec
================
Product: Symantec CloudSOC
--------------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  69   |   32   |     5      |      7      |    7    |

|                Use-Case                | Event Types/Parsers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | MITRE TTP                                                                                                                                                   | Content                                                                                                       |
|:--------------------------------------:| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| [Other](../../../UseCases/uc_other.md) |  app-activity<br> ↳ [symantec-cloud-activity](Parsers/parserContent_symantec-cloud-activity.md)<br><br> app-login<br> ↳ [symantec-cloud-activity](Parsers/parserContent_symantec-cloud-activity.md)<br><br> dlp-alert<br> ↳ [symantec-cloud-dlp-alert](Parsers/parserContent_symantec-cloud-dlp-alert.md)<br><br> failed-app-login<br> ↳ [symantec-cloud-activity](Parsers/parserContent_symantec-cloud-activity.md)<br><br> file-delete<br> ↳ [symantec-cloud-activity](Parsers/parserContent_symantec-cloud-activity.md)<br><br> file-download<br> ↳ [symantec-cloud-activity](Parsers/parserContent_symantec-cloud-activity.md)<br><br> file-upload<br> ↳ [symantec-cloud-activity](Parsers/parserContent_symantec-cloud-activity.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>T1078 - Valid Accounts<br>T1133 - External Remote Services<br>T1188 - T1188<br>T1204 - User Execution<br> | [<ul><li>69 Rules</li></ul><ul><li>32 Models</li></ul>](Rules_Models/r_m_symantec_symantec_cloudsoc_Other.md) |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution                                                           | Persistence                                                                                                                                      | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration                                                                                | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ------------------- | ------------------------------------------------------------------------------------------- | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [User Execution](https://attack.mitre.org/techniques/T1204)<br><br> | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  |            |                     | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br> |        |