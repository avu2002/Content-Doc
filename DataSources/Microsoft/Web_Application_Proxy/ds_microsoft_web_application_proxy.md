Vendor: Microsoft
=================
Product: Web Application Proxy
------------------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  107  |   21   |     18     |      3      |    3    |

|                                  Use-Case                                  | Activity Types                                                                                                                                                                                                     | Event Types/Parsers                                                                                                                                                                                                                                                        | MITRE TTP                                                                                                                                                                                          | Content                                                                                                                             |
|:--------------------------------------------------------------------------:| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md) | <ul><li>Activity Time  and Type</li><li>Asset Logon and Access</li><li>Credential Switch Activity</li><li>Network zones and Location Access</li><li>Pass The Hash and Golden Ticket</li><li>Web Activity</li></ul> |  remote-logon<br> ↳ [microsoft-remote-desktop](Parsers/parserContent_microsoft-remote-desktop.md)<br><br> web-activity-allowed<br> ↳ [tmg-proxy](Parsers/parserContent_tmg-proxy.md)<br><br> web-activity-denied<br> ↳ [tmg-proxy](Parsers/parserContent_tmg-proxy.md)<br> | T1003 - OS Credential Dumping<br>T1021 - Remote Services<br>T1071 - Application Layer Protocol<br>T1075 - T1075<br>T1078 - Valid Accounts<br>T1133 - External Remote Services<br>T1208 - T1208<br> | [<ul><li>37 Rules</li></ul><ul><li>7 Models</li></ul>](Rules_Models/r_m_microsoft_web_application_proxy_Compromised_Credentials.md) |
|       [Data Exfiltration](../../../UseCases/uc_data_exfiltration.md)       | <ul><li>Data Loss Prevention</li><li>Web Activity</li></ul>                                                                                                                                                        |  remote-logon<br> ↳ [microsoft-remote-desktop](Parsers/parserContent_microsoft-remote-desktop.md)<br><br> web-activity-allowed<br> ↳ [tmg-proxy](Parsers/parserContent_tmg-proxy.md)<br><br> web-activity-denied<br> ↳ [tmg-proxy](Parsers/parserContent_tmg-proxy.md)<br> | T1041 - Exfiltration Over C2 Channel<br>T1048 - Exfiltration Over Alternative Protocol<br>T1102 - Web Service<br>T1213 - Data from Information Repositories<br>                                    | [<ul><li>3 Rules</li></ul>](Rules_Models/r_m_microsoft_web_application_proxy_Data_Exfiltration.md)                                  |
|          [Internal Fraud](../../../UseCases/uc_internal_fraud.md)          | <ul><li>Web Activity</li></ul>                                                                                                                                                                                     |  remote-logon<br> ↳ [microsoft-remote-desktop](Parsers/parserContent_microsoft-remote-desktop.md)<br><br> web-activity-allowed<br> ↳ [tmg-proxy](Parsers/parserContent_tmg-proxy.md)<br><br> web-activity-denied<br> ↳ [tmg-proxy](Parsers/parserContent_tmg-proxy.md)<br> | T1071 - Application Layer Protocol<br>                                                                                                                                                             | [<ul><li>3 Rules</li></ul><ul><li>2 Models</li></ul>](Rules_Models/r_m_microsoft_web_application_proxy_Internal_Fraud.md)           |
|        [Lateral Movement](../../../UseCases/uc_lateral_movement.md)        | <ul><li>Asset Logon and Access</li><li>Credential Switch Activity</li><li>Network zones and Location Access</li><li>Web Activity</li></ul>                                                                         |  remote-logon<br> ↳ [microsoft-remote-desktop](Parsers/parserContent_microsoft-remote-desktop.md)<br><br> web-activity-allowed<br> ↳ [tmg-proxy](Parsers/parserContent_tmg-proxy.md)<br><br> web-activity-denied<br> ↳ [tmg-proxy](Parsers/parserContent_tmg-proxy.md)<br> | T1021 - Remote Services<br>T1033 - System Owner/User Discovery<br>T1071 - Application Layer Protocol<br>T1078 - Valid Accounts<br>                                                                 | [<ul><li>20 Rules</li></ul><ul><li>7 Models</li></ul>](Rules_Models/r_m_microsoft_web_application_proxy_Lateral_Movement.md)        |
|       [Malware Detection](../../../UseCases/uc_malware_detection.md)       | <ul><li>Asset Logon and Access</li><li>Endpoint Activity</li><li>Network</li><li>Process Activity</li><li>Web Activity</li></ul>                                                                                   |  remote-logon<br> ↳ [microsoft-remote-desktop](Parsers/parserContent_microsoft-remote-desktop.md)<br><br> web-activity-allowed<br> ↳ [tmg-proxy](Parsers/parserContent_tmg-proxy.md)<br><br> web-activity-denied<br> ↳ [tmg-proxy](Parsers/parserContent_tmg-proxy.md)<br> | T1071 - Application Layer Protocol<br>T1075 - T1075<br>T1102 - Web Service<br>T1188 - T1188<br>T1189 - Drive-by Compromise<br>T1204 - User Execution<br>                                           | [<ul><li>43 Rules</li></ul><ul><li>5 Models</li></ul>](Rules_Models/r_m_microsoft_web_application_proxy_Malware_Detection.md)       |
|                   [Other](../../../UseCases/uc_other.md)                   | <ul><li>Asset Logon and Access</li><li>Web Activity</li></ul>                                                                                                                                                      |  remote-logon<br> ↳ [microsoft-remote-desktop](Parsers/parserContent_microsoft-remote-desktop.md)<br><br> web-activity-allowed<br> ↳ [tmg-proxy](Parsers/parserContent_tmg-proxy.md)<br><br> web-activity-denied<br> ↳ [tmg-proxy](Parsers/parserContent_tmg-proxy.md)<br> | T1071 - Application Layer Protocol<br>T1496 - Resource Hijacking<br>T1550 - Use Alternate Authentication Material<br>                                                                              | [<ul><li>6 Rules</li></ul>](Rules_Models/r_m_microsoft_web_application_proxy_Other.md)                                              |
|                [Phishing](../../../UseCases/uc_phishing.md)                | <ul><li>Network</li><li>Web Activity</li></ul>                                                                                                                                                                     |  remote-logon<br> ↳ [microsoft-remote-desktop](Parsers/parserContent_microsoft-remote-desktop.md)<br><br> web-activity-allowed<br> ↳ [tmg-proxy](Parsers/parserContent_tmg-proxy.md)<br><br> web-activity-denied<br> ↳ [tmg-proxy](Parsers/parserContent_tmg-proxy.md)<br> | T1071 - Application Layer Protocol<br>                                                                                                                                                             | [<ul><li>8 Rules</li></ul>](Rules_Models/r_m_microsoft_web_application_proxy_Phishing.md)                                           |
|     [Privileged Activity](../../../UseCases/uc_privileged_activity.md)     | <ul><li>Asset Logon and Access</li><li>Executives</li></ul>                                                                                                                                                        |  remote-logon<br> ↳ [microsoft-remote-desktop](Parsers/parserContent_microsoft-remote-desktop.md)<br><br> web-activity-allowed<br> ↳ [tmg-proxy](Parsers/parserContent_tmg-proxy.md)<br><br> web-activity-denied<br> ↳ [tmg-proxy](Parsers/parserContent_tmg-proxy.md)<br> | T1068 - Exploitation for Privilege Escalation<br>                                                                                                                                                  | [<ul><li>2 Rules</li></ul><ul><li>1 Models</li></ul>](Rules_Models/r_m_microsoft_web_application_proxy_Privileged_Activity.md)      |
|    [Ransomware Detection](../../../UseCases/uc_ransomware_detection.md)    | <ul><li>Asset Logon and Access</li><li>Endpoint Activity</li><li>Network</li><li>Process Activity</li><li>Web Activity</li></ul>                                                                                   |  remote-logon<br> ↳ [microsoft-remote-desktop](Parsers/parserContent_microsoft-remote-desktop.md)<br><br> web-activity-allowed<br> ↳ [tmg-proxy](Parsers/parserContent_tmg-proxy.md)<br><br> web-activity-denied<br> ↳ [tmg-proxy](Parsers/parserContent_tmg-proxy.md)<br> | T1071 - Application Layer Protocol<br>T1075 - T1075<br>T1102 - Web Service<br>T1188 - T1188<br>T1189 - Drive-by Compromise<br>T1204 - User Execution<br>                                           | [<ul><li>42 Rules</li></ul><ul><li>4 Models</li></ul>](Rules_Models/r_m_microsoft_web_application_proxy_Ransomware_Detection.md)    |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                                                                                           | Execution                                                           | Persistence                                                                                                                                      | Privilege Escalation                                                                                                                                          | Defense Evasion                                                                                                                                               | Credential Access                                                          | Discovery                                                                        | Lateral Movement                                                                                                                                               | Collection                                                                              | Command and Control                                                                                                                             | Exfiltration                                                                                                                                                                 | Impact                                                                  |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------- |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Drive-by Compromise](https://attack.mitre.org/techniques/T1189)<br><br> | [User Execution](https://attack.mitre.org/techniques/T1204)<br><br> | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Exploitation for Privilege Escalation](https://attack.mitre.org/techniques/T1068)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Use Alternate Authentication Material](https://attack.mitre.org/techniques/T1550)<br><br> | [OS Credential Dumping](https://attack.mitre.org/techniques/T1003)<br><br> | [System Owner/User Discovery](https://attack.mitre.org/techniques/T1033)<br><br> | [Remote Services](https://attack.mitre.org/techniques/T1021)<br><br>[Use Alternate Authentication Material](https://attack.mitre.org/techniques/T1550)<br><br> | [Data from Information Repositories](https://attack.mitre.org/techniques/T1213)<br><br> | [Web Service](https://attack.mitre.org/techniques/T1102)<br><br>[Application Layer Protocol](https://attack.mitre.org/techniques/T1071)<br><br> | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br>[Exfiltration Over C2 Channel](https://attack.mitre.org/techniques/T1041)<br><br> | [Resource Hijacking](https://attack.mitre.org/techniques/T1496)<br><br> |