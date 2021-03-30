Vendor: RangerAudit
===================
Product: RangerAudit
--------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  59   |   27   |     5      |      5      |    5    |

|                Use-Case                | Event Types/Parsers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | MITRE TTP                                                                                                                                                   | Content                                                                                                    |
|:--------------------------------------:| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| [Other](../../../UseCases/uc_other.md) |  app-activity<br> ↳ [cef-rangeraudit-app-activity](Parsers/parserContent_cef-rangeraudit-app-activity.md)<br><br> app-login<br> ↳ [cef-rangeraudit-app-login](Parsers/parserContent_cef-rangeraudit-app-login.md)<br><br> failed-app-login<br> ↳ [cef-rangeraudit-failed-login](Parsers/parserContent_cef-rangeraudit-failed-login.md)<br><br> file-read<br> ↳ [cef-rangeraudit-file-operations](Parsers/parserContent_cef-rangeraudit-file-operations.md)<br><br> file-write<br> ↳ [cef-rangeraudit-file-operations](Parsers/parserContent_cef-rangeraudit-file-operations.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>T1078 - Valid Accounts<br>T1133 - External Remote Services<br>T1188 - T1188<br>T1204 - User Execution<br> | [<ul><li>59 Rules</li></ul><ul><li>27 Models</li></ul>](Rules_Models/r_m_rangeraudit_rangeraudit_Other.md) |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution                                                           | Persistence                                                                                                                                      | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration                                                                                | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ------------------- | ------------------------------------------------------------------------------------------- | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [User Execution](https://attack.mitre.org/techniques/T1204)<br><br> | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  |            |                     | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br> |        |