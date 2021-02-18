Vendor: ICDB
============
Product: ICDB
-------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  50   |   6    |     4      |      1      |    1    |

|                                  Use-Case                                  | Activity Types                                                                                                                                                                                                                           | Event Types/Parsers                                                                             | MITRE TTP                                                                                                        | Content                                                                                                       |
|:--------------------------------------------------------------------------:| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md) | <ul><li>Activity Time  and Type</li><li>Application Activity</li><li>Asset Logon and Access</li><li>Critical System Activity</li><li>Email Activity</li><li>Network zones and Location Access</li><li>Service Account Activity</li></ul> |  app-activity<br> ↳ [cef-icdb-app-activity](Parsers/parserContent_cef-icdb-app-activity.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>T1078 - Valid Accounts<br>T1133 - External Remote Services<br> | [<ul><li>39 Rules</li></ul><ul><li>5 Models</li></ul>](Rules_Models/r_m_icdb_icdb_Compromised_Credentials.md) |
|       [Data Exfiltration](../../../UseCases/uc_data_exfiltration.md)       | <ul><li>Email Activity</li></ul>                                                                                                                                                                                                         |  app-activity<br> ↳ [cef-icdb-app-activity](Parsers/parserContent_cef-icdb-app-activity.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>                                                               | [<ul><li>3 Rules</li></ul>](Rules_Models/r_m_icdb_icdb_Data_Exfiltration.md)                                  |
|          [Internal Fraud](../../../UseCases/uc_internal_fraud.md)          | <ul><li>Application Activity</li></ul>                                                                                                                                                                                                   |  app-activity<br> ↳ [cef-icdb-app-activity](Parsers/parserContent_cef-icdb-app-activity.md)<br> | T1078 - Valid Accounts<br>                                                                                       | [<ul><li>13 Rules</li></ul><ul><li>1 Models</li></ul>](Rules_Models/r_m_icdb_icdb_Internal_Fraud.md)          |
|        [Lateral Movement](../../../UseCases/uc_lateral_movement.md)        | <ul><li>Activity Time  and Type</li><li>Application Activity</li><li>Network zones and Location Access</li></ul>                                                                                                                         |  app-activity<br> ↳ [cef-icdb-app-activity](Parsers/parserContent_cef-icdb-app-activity.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>                                                   | [<ul><li>6 Rules</li></ul><ul><li>1 Models</li></ul>](Rules_Models/r_m_icdb_icdb_Lateral_Movement.md)         |
|       [Malware Detection](../../../UseCases/uc_malware_detection.md)       | <ul><li>Asset Logon and Access</li></ul>                                                                                                                                                                                                 |  app-activity<br> ↳ [cef-icdb-app-activity](Parsers/parserContent_cef-icdb-app-activity.md)<br> | T1188 - T1188<br>                                                                                                | [<ul><li>3 Rules</li></ul>](Rules_Models/r_m_icdb_icdb_Malware_Detection.md)                                  |
|     [Privileged Activity](../../../UseCases/uc_privileged_activity.md)     | <ul><li>Application Activity</li><li>Email Activity</li><li>Service Account Activity</li></ul>                                                                                                                                           |  app-activity<br> ↳ [cef-icdb-app-activity](Parsers/parserContent_cef-icdb-app-activity.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>T1078 - Valid Accounts<br>                                     | [<ul><li>5 Rules</li></ul><ul><li>1 Models</li></ul>](Rules_Models/r_m_icdb_icdb_Privileged_Activity.md)      |
|    [Ransomware Detection](../../../UseCases/uc_ransomware_detection.md)    | <ul><li>Asset Logon and Access</li></ul>                                                                                                                                                                                                 |  app-activity<br> ↳ [cef-icdb-app-activity](Parsers/parserContent_cef-icdb-app-activity.md)<br> | T1188 - T1188<br>                                                                                                | [<ul><li>3 Rules</li></ul>](Rules_Models/r_m_icdb_icdb_Ransomware_Detection.md)                               |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution | Persistence                                                                                                                                      | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration                                                                                | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ------------------- | ------------------------------------------------------------------------------------------- | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |           | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  |            |                     | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br> |        |