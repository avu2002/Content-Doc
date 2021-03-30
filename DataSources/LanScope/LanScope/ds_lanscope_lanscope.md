Vendor: LanScope
================
Product: LanScope
-----------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  125  |   47   |     12     |      5      |    5    |

|                Use-Case                | Event Types/Parsers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | MITRE TTP                                                                                                                                                                                                                                                                                                                                                                                               | Content                                                                                               |
|:--------------------------------------:| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| [Other](../../../UseCases/uc_other.md) |  app-activity<br> ↳ [s-lanscope-asset-alert](Parsers/parserContent_s-lanscope-asset-alert.md)<br><br> print-activity<br> ↳ [s-lanscope-print-activity](Parsers/parserContent_s-lanscope-print-activity.md)<br><br> process-created<br> ↳ [s-lanscope-process-created](Parsers/parserContent_s-lanscope-process-created.md)<br><br> process-network<br> ↳ [s-lanscope-process-created](Parsers/parserContent_s-lanscope-process-created.md)<br><br> web-activity-allowed<br> ↳ [s-lanscope-web-activity](Parsers/parserContent_s-lanscope-web-activity.md)<br> | T1036 - Masquerading<br>T1041 - Exfiltration Over C2 Channel<br>T1048 - Exfiltration Over Alternative Protocol<br>T1071 - Application Layer Protocol<br>T1078 - Valid Accounts<br>T1102 - Web Service<br>T1133 - External Remote Services<br>T1188 - T1188<br>T1189 - Drive-by Compromise<br>T1204 - User Execution<br>T1213 - Data from Information Repositories<br>T1219 - Remote Access Software<br> | [<ul><li>125 Rules</li></ul><ul><li>47 Models</li></ul>](Rules_Models/r_m_lanscope_lanscope_Other.md) |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                                                                                           | Execution                                                           | Persistence                                                                                                                                      | Privilege Escalation                                                | Defense Evasion                                                                                                                      | Credential Access | Discovery | Lateral Movement | Collection                                                                              | Command and Control                                                                                                                                                                                                        | Exfiltration                                                                                                                                                                 | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ | ----------------- | --------- | ---------------- | --------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Drive-by Compromise](https://attack.mitre.org/techniques/T1189)<br><br> | [User Execution](https://attack.mitre.org/techniques/T1204)<br><br> | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Masquerading](https://attack.mitre.org/techniques/T1036)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  | [Data from Information Repositories](https://attack.mitre.org/techniques/T1213)<br><br> | [Web Service](https://attack.mitre.org/techniques/T1102)<br><br>[Remote Access Software](https://attack.mitre.org/techniques/T1219)<br><br>[Application Layer Protocol](https://attack.mitre.org/techniques/T1071)<br><br> | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br>[Exfiltration Over C2 Channel](https://attack.mitre.org/techniques/T1041)<br><br> |        |