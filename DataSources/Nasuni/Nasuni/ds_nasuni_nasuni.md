Vendor: Nasuni
==============
Product: Nasuni
---------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   7   |   4    |     3      |      3      |    3    |

|                                  Use-Case                                  | Activity Types                                                   | Event Types/Parsers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | MITRE TTP                                                          | Content                                                                                                          |
|:--------------------------------------------------------------------------:| ---------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------- |
| [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md) | <ul><li>Critical System Activity</li><li>File Activity</li></ul> |  file-delete<br> ↳ [s-nasuni-file-delete](Parsers/parserContent_s-nasuni-file-delete.md)<br> ↳ [s-nasuni-file-delete-1](Parsers/parserContent_s-nasuni-file-delete-1.md)<br><br> file-permission-change<br> ↳ [s-nasuni-file-permission-change](Parsers/parserContent_s-nasuni-file-permission-change.md)<br> ↳ [s-nasuni-file-permission-change-2](Parsers/parserContent_s-nasuni-file-permission-change-2.md)<br> ↳ [s-nasuni-file-permission-change-1](Parsers/parserContent_s-nasuni-file-permission-change-1.md)<br><br> file-write<br> ↳ [s-nasuni-file-write](Parsers/parserContent_s-nasuni-file-write.md)<br> ↳ [s-nasuni-file-write-2](Parsers/parserContent_s-nasuni-file-write-2.md)<br> ↳ [s-nasuni-file-write-1](Parsers/parserContent_s-nasuni-file-write-1.md)<br> | T1078 - Valid Accounts<br>T1083 - File and Directory Discovery<br> | [<ul><li>3 Rules</li></ul><ul><li>2 Models</li></ul>](Rules_Models/r_m_nasuni_nasuni_Compromised_Credentials.md) |
|       [Data Exfiltration](../../../UseCases/uc_data_exfiltration.md)       | <ul><li>File Activity</li></ul>                                  |  file-delete<br> ↳ [s-nasuni-file-delete](Parsers/parserContent_s-nasuni-file-delete.md)<br> ↳ [s-nasuni-file-delete-1](Parsers/parserContent_s-nasuni-file-delete-1.md)<br><br> file-permission-change<br> ↳ [s-nasuni-file-permission-change](Parsers/parserContent_s-nasuni-file-permission-change.md)<br> ↳ [s-nasuni-file-permission-change-2](Parsers/parserContent_s-nasuni-file-permission-change-2.md)<br> ↳ [s-nasuni-file-permission-change-1](Parsers/parserContent_s-nasuni-file-permission-change-1.md)<br><br> file-write<br> ↳ [s-nasuni-file-write](Parsers/parserContent_s-nasuni-file-write.md)<br> ↳ [s-nasuni-file-write-2](Parsers/parserContent_s-nasuni-file-write-2.md)<br> ↳ [s-nasuni-file-write-1](Parsers/parserContent_s-nasuni-file-write-1.md)<br> | T1083 - File and Directory Discovery<br>                           | [<ul><li>2 Rules</li></ul><ul><li>2 Models</li></ul>](Rules_Models/r_m_nasuni_nasuni_Data_Exfiltration.md)       |
|         [Data Extraction](../../../UseCases/uc_data_extraction.md)         | <ul><li>File Activity</li></ul>                                  |  file-delete<br> ↳ [s-nasuni-file-delete](Parsers/parserContent_s-nasuni-file-delete.md)<br> ↳ [s-nasuni-file-delete-1](Parsers/parserContent_s-nasuni-file-delete-1.md)<br><br> file-permission-change<br> ↳ [s-nasuni-file-permission-change](Parsers/parserContent_s-nasuni-file-permission-change.md)<br> ↳ [s-nasuni-file-permission-change-2](Parsers/parserContent_s-nasuni-file-permission-change-2.md)<br> ↳ [s-nasuni-file-permission-change-1](Parsers/parserContent_s-nasuni-file-permission-change-1.md)<br><br> file-write<br> ↳ [s-nasuni-file-write](Parsers/parserContent_s-nasuni-file-write.md)<br> ↳ [s-nasuni-file-write-2](Parsers/parserContent_s-nasuni-file-write-2.md)<br> ↳ [s-nasuni-file-write-1](Parsers/parserContent_s-nasuni-file-write-1.md)<br> | T1083 - File and Directory Discovery<br>                           | [<ul><li>1 Rules</li></ul><ul><li>1 Models</li></ul>](Rules_Models/r_m_nasuni_nasuni_Data_Extraction.md)         |
|       [Malware Detection](../../../UseCases/uc_malware_detection.md)       | <ul><li>Endpoint Activity</li><li>File Activity</li></ul>        |  file-delete<br> ↳ [s-nasuni-file-delete](Parsers/parserContent_s-nasuni-file-delete.md)<br> ↳ [s-nasuni-file-delete-1](Parsers/parserContent_s-nasuni-file-delete-1.md)<br><br> file-permission-change<br> ↳ [s-nasuni-file-permission-change](Parsers/parserContent_s-nasuni-file-permission-change.md)<br> ↳ [s-nasuni-file-permission-change-2](Parsers/parserContent_s-nasuni-file-permission-change-2.md)<br> ↳ [s-nasuni-file-permission-change-1](Parsers/parserContent_s-nasuni-file-permission-change-1.md)<br><br> file-write<br> ↳ [s-nasuni-file-write](Parsers/parserContent_s-nasuni-file-write.md)<br> ↳ [s-nasuni-file-write-2](Parsers/parserContent_s-nasuni-file-write-2.md)<br> ↳ [s-nasuni-file-write-1](Parsers/parserContent_s-nasuni-file-write-1.md)<br> | T1204 - User Execution<br>                                         | [<ul><li>3 Rules</li></ul><ul><li>1 Models</li></ul>](Rules_Models/r_m_nasuni_nasuni_Malware_Detection.md)       |
|    [Ransomware Detection](../../../UseCases/uc_ransomware_detection.md)    | <ul><li>Endpoint Activity</li><li>File Activity</li></ul>        |  file-delete<br> ↳ [s-nasuni-file-delete](Parsers/parserContent_s-nasuni-file-delete.md)<br> ↳ [s-nasuni-file-delete-1](Parsers/parserContent_s-nasuni-file-delete-1.md)<br><br> file-permission-change<br> ↳ [s-nasuni-file-permission-change](Parsers/parserContent_s-nasuni-file-permission-change.md)<br> ↳ [s-nasuni-file-permission-change-2](Parsers/parserContent_s-nasuni-file-permission-change-2.md)<br> ↳ [s-nasuni-file-permission-change-1](Parsers/parserContent_s-nasuni-file-permission-change-1.md)<br><br> file-write<br> ↳ [s-nasuni-file-write](Parsers/parserContent_s-nasuni-file-write.md)<br> ↳ [s-nasuni-file-write-2](Parsers/parserContent_s-nasuni-file-write-2.md)<br> ↳ [s-nasuni-file-write-1](Parsers/parserContent_s-nasuni-file-write-1.md)<br> | T1204 - User Execution<br>                                         | [<ul><li>3 Rules</li></ul><ul><li>1 Models</li></ul>](Rules_Models/r_m_nasuni_nasuni_Ransomware_Detection.md)    |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                      | Execution                                                           | Persistence                                                         | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery                                                                         | Lateral Movement | Collection | Command and Control | Exfiltration | Impact |
| ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------------------------------------------------------------------------------- | ---------------- | ---------- | ------------------- | ------------ | ------ |
| [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [User Execution](https://attack.mitre.org/techniques/T1204)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   | [File and Directory Discovery](https://attack.mitre.org/techniques/T1083)<br><br> |                  |            |                     |              |        |