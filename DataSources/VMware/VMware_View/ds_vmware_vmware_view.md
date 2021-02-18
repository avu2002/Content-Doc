Vendor: VMware
==============
Product: VMware View
--------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  95   |   14   |     12     |      5      |    5    |

|                                  Use-Case                                  | Activity Types                                                                                                                                                                                                                                                                                                      | Event Types/Parsers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | MITRE TTP                                                                                                                                                                                                      | Content                                                                                                                |
|:--------------------------------------------------------------------------:| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md) | <ul><li>Activity Time  and Type</li><li>Application Activity</li><li>Asset Logon and Access</li><li>Credential Switch Activity</li><li>Critical System Activity</li><li>Email Activity</li><li>Network zones and Location Access</li><li>Pass The Hash and Golden Ticket</li><li>Service Account Activity</li></ul> |  account-password-change<br> ↳ [vmware-view-password-change](Parsers/parserContent_vmware-view-password-change.md)<br><br> app-activity<br> ↳ [vmware-view-app-activity](Parsers/parserContent_vmware-view-app-activity.md)<br><br> app-login<br> ↳ [vmware-view-login](Parsers/parserContent_vmware-view-login.md)<br><br> failed-app-login<br> ↳ [vmware-view-failed-login](Parsers/parserContent_vmware-view-failed-login.md)<br><br> remote-logon<br> ↳ [vmware-view-remote-logon](Parsers/parserContent_vmware-view-remote-logon.md)<br> | T1003 - OS Credential Dumping<br>T1021 - Remote Services<br>T1048 - Exfiltration Over Alternative Protocol<br>T1075 - T1075<br>T1078 - Valid Accounts<br>T1133 - External Remote Services<br>T1208 - T1208<br> | [<ul><li>61 Rules</li></ul><ul><li>7 Models</li></ul>](Rules_Models/r_m_vmware_vmware_view_Compromised_Credentials.md) |
|       [Data Exfiltration](../../../UseCases/uc_data_exfiltration.md)       | <ul><li>Email Activity</li></ul>                                                                                                                                                                                                                                                                                    |  account-password-change<br> ↳ [vmware-view-password-change](Parsers/parserContent_vmware-view-password-change.md)<br><br> app-activity<br> ↳ [vmware-view-app-activity](Parsers/parserContent_vmware-view-app-activity.md)<br><br> app-login<br> ↳ [vmware-view-login](Parsers/parserContent_vmware-view-login.md)<br><br> failed-app-login<br> ↳ [vmware-view-failed-login](Parsers/parserContent_vmware-view-failed-login.md)<br><br> remote-logon<br> ↳ [vmware-view-remote-logon](Parsers/parserContent_vmware-view-remote-logon.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>                                                                                                                                                             | [<ul><li>3 Rules</li></ul>](Rules_Models/r_m_vmware_vmware_view_Data_Exfiltration.md)                                  |
|          [Internal Fraud](../../../UseCases/uc_internal_fraud.md)          | <ul><li>Application Activity</li></ul>                                                                                                                                                                                                                                                                              |  account-password-change<br> ↳ [vmware-view-password-change](Parsers/parserContent_vmware-view-password-change.md)<br><br> app-activity<br> ↳ [vmware-view-app-activity](Parsers/parserContent_vmware-view-app-activity.md)<br><br> app-login<br> ↳ [vmware-view-login](Parsers/parserContent_vmware-view-login.md)<br><br> failed-app-login<br> ↳ [vmware-view-failed-login](Parsers/parserContent_vmware-view-failed-login.md)<br><br> remote-logon<br> ↳ [vmware-view-remote-logon](Parsers/parserContent_vmware-view-remote-logon.md)<br> | T1078 - Valid Accounts<br>                                                                                                                                                                                     | [<ul><li>13 Rules</li></ul><ul><li>1 Models</li></ul>](Rules_Models/r_m_vmware_vmware_view_Internal_Fraud.md)          |
|        [Lateral Movement](../../../UseCases/uc_lateral_movement.md)        | <ul><li>Activity Time  and Type</li><li>Application Activity</li><li>Asset Logon and Access</li><li>Credential Switch Activity</li><li>Network zones and Location Access</li></ul>                                                                                                                                  |  account-password-change<br> ↳ [vmware-view-password-change](Parsers/parserContent_vmware-view-password-change.md)<br><br> app-activity<br> ↳ [vmware-view-app-activity](Parsers/parserContent_vmware-view-app-activity.md)<br><br> app-login<br> ↳ [vmware-view-login](Parsers/parserContent_vmware-view-login.md)<br><br> failed-app-login<br> ↳ [vmware-view-failed-login](Parsers/parserContent_vmware-view-failed-login.md)<br><br> remote-logon<br> ↳ [vmware-view-remote-logon](Parsers/parserContent_vmware-view-remote-logon.md)<br> | T1021 - Remote Services<br>T1033 - System Owner/User Discovery<br>T1078 - Valid Accounts<br>T1133 - External Remote Services<br>                                                                               | [<ul><li>22 Rules</li></ul><ul><li>5 Models</li></ul>](Rules_Models/r_m_vmware_vmware_view_Lateral_Movement.md)        |
|       [Malware Detection](../../../UseCases/uc_malware_detection.md)       | <ul><li>Asset Logon and Access</li><li>Endpoint Activity</li><li>Process Activity</li></ul>                                                                                                                                                                                                                         |  account-password-change<br> ↳ [vmware-view-password-change](Parsers/parserContent_vmware-view-password-change.md)<br><br> app-activity<br> ↳ [vmware-view-app-activity](Parsers/parserContent_vmware-view-app-activity.md)<br><br> app-login<br> ↳ [vmware-view-login](Parsers/parserContent_vmware-view-login.md)<br><br> failed-app-login<br> ↳ [vmware-view-failed-login](Parsers/parserContent_vmware-view-failed-login.md)<br><br> remote-logon<br> ↳ [vmware-view-remote-logon](Parsers/parserContent_vmware-view-remote-logon.md)<br> | T1188 - T1188<br>T1204 - User Execution<br>                                                                                                                                                                    | [<ul><li>10 Rules</li></ul><ul><li>1 Models</li></ul>](Rules_Models/r_m_vmware_vmware_view_Malware_Detection.md)       |
|                   [Other](../../../UseCases/uc_other.md)                   | <ul><li>Asset Logon and Access</li></ul>                                                                                                                                                                                                                                                                            |  account-password-change<br> ↳ [vmware-view-password-change](Parsers/parserContent_vmware-view-password-change.md)<br><br> app-activity<br> ↳ [vmware-view-app-activity](Parsers/parserContent_vmware-view-app-activity.md)<br><br> app-login<br> ↳ [vmware-view-login](Parsers/parserContent_vmware-view-login.md)<br><br> failed-app-login<br> ↳ [vmware-view-failed-login](Parsers/parserContent_vmware-view-failed-login.md)<br><br> remote-logon<br> ↳ [vmware-view-remote-logon](Parsers/parserContent_vmware-view-remote-logon.md)<br> | T1550 - Use Alternate Authentication Material<br>                                                                                                                                                              | [<ul><li>3 Rules</li></ul>](Rules_Models/r_m_vmware_vmware_view_Other.md)                                              |
|     [Privileged Activity](../../../UseCases/uc_privileged_activity.md)     | <ul><li>Application Activity</li><li>Asset Logon and Access</li><li>Email Activity</li><li>Executives</li><li>Service Account Activity</li></ul>                                                                                                                                                                    |  account-password-change<br> ↳ [vmware-view-password-change](Parsers/parserContent_vmware-view-password-change.md)<br><br> app-activity<br> ↳ [vmware-view-app-activity](Parsers/parserContent_vmware-view-app-activity.md)<br><br> app-login<br> ↳ [vmware-view-login](Parsers/parserContent_vmware-view-login.md)<br><br> failed-app-login<br> ↳ [vmware-view-failed-login](Parsers/parserContent_vmware-view-failed-login.md)<br><br> remote-logon<br> ↳ [vmware-view-remote-logon](Parsers/parserContent_vmware-view-remote-logon.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>T1068 - Exploitation for Privilege Escalation<br>T1078 - Valid Accounts<br>                                                                                  | [<ul><li>7 Rules</li></ul><ul><li>2 Models</li></ul>](Rules_Models/r_m_vmware_vmware_view_Privileged_Activity.md)      |
|    [Ransomware Detection](../../../UseCases/uc_ransomware_detection.md)    | <ul><li>Asset Logon and Access</li><li>Endpoint Activity</li><li>Process Activity</li></ul>                                                                                                                                                                                                                         |  account-password-change<br> ↳ [vmware-view-password-change](Parsers/parserContent_vmware-view-password-change.md)<br><br> app-activity<br> ↳ [vmware-view-app-activity](Parsers/parserContent_vmware-view-app-activity.md)<br><br> app-login<br> ↳ [vmware-view-login](Parsers/parserContent_vmware-view-login.md)<br><br> failed-app-login<br> ↳ [vmware-view-failed-login](Parsers/parserContent_vmware-view-failed-login.md)<br><br> remote-logon<br> ↳ [vmware-view-remote-logon](Parsers/parserContent_vmware-view-remote-logon.md)<br> | T1188 - T1188<br>T1204 - User Execution<br>                                                                                                                                                                    | [<ul><li>10 Rules</li></ul><ul><li>1 Models</li></ul>](Rules_Models/r_m_vmware_vmware_view_Ransomware_Detection.md)    |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution                                                           | Persistence                                                                                                                                      | Privilege Escalation                                                                                                                                          | Defense Evasion                                                                                                                                               | Credential Access                                                          | Discovery                                                                        | Lateral Movement                                                                                                                                               | Collection | Command and Control | Exfiltration                                                                                | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ------------------- | ------------------------------------------------------------------------------------------- | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [User Execution](https://attack.mitre.org/techniques/T1204)<br><br> | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Exploitation for Privilege Escalation](https://attack.mitre.org/techniques/T1068)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Use Alternate Authentication Material](https://attack.mitre.org/techniques/T1550)<br><br> | [OS Credential Dumping](https://attack.mitre.org/techniques/T1003)<br><br> | [System Owner/User Discovery](https://attack.mitre.org/techniques/T1033)<br><br> | [Remote Services](https://attack.mitre.org/techniques/T1021)<br><br>[Use Alternate Authentication Material](https://attack.mitre.org/techniques/T1550)<br><br> |            |                     | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br> |        |