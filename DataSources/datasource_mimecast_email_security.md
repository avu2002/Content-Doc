Vendor: Mimecast
================
Product: Email Security
-----------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  126  |   19   |     12     |     56      |   56    |

|                                 Use-Case                                  | Activity Types                                                                                                                                                                                                                           | Event Types/Parsers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | MITRE TTP                                                                                                        | Content                                              |
|:-------------------------------------------------------------------------:| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- |
| [Compromised Credentials](../UseCases/usecase_compromised_credentials.md) | <ul><li>Activity Time  and Type</li><li>Application Activity</li><li>Asset Logon and Access</li><li>Critical System Activity</li><li>Email Activity</li><li>Network zones and Location Access</li><li>Service Account Activity</li></ul> |  app-activity<br> ↳ [s-mimecast-app-activity](../Parsers/parserContent_s-mimecast-app-activity.md)<br><br> app-login<br> ↳ [s-mimecast-app-login](../Parsers/parserContent_s-mimecast-app-login.md)<br><br> dlp-email-alert-in<br> ↳ [s-mimecast-dlp-email](../Parsers/parserContent_s-mimecast-dlp-email.md)<br> ↳ [cef-mimecast-security-alert](../Parsers/parserContent_cef-mimecast-security-alert.md)<br><br> dlp-email-alert-in-failed<br> ↳ [s-mimecast-dlp-email](../Parsers/parserContent_s-mimecast-dlp-email.md)<br> ↳ [cef-mimecast-security-alert](../Parsers/parserContent_cef-mimecast-security-alert.md)<br><br> dlp-email-alert-out<br> ↳ [s-mimecast-dlp-email](../Parsers/parserContent_s-mimecast-dlp-email.md)<br><br> dlp-email-alert-out-failed<br> ↳ [s-mimecast-dlp-email](../Parsers/parserContent_s-mimecast-dlp-email.md)<br><br> failed-app-login<br> ↳ [cef-mimecast-failed-app-login](../Parsers/parserContent_cef-mimecast-failed-app-login.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>T1078 - Valid Accounts<br>T1133 - External Remote Services<br> | <ul><li>42 Rules</li></ul><ul><li>5 Models</li></ul> |
|       [Data Exfiltration](../UseCases/usecase_data_exfiltration.md)       | <ul><li>Email Activity</li></ul>                                                                                                                                                                                                         |  app-activity<br> ↳ [s-mimecast-app-activity](../Parsers/parserContent_s-mimecast-app-activity.md)<br><br> app-login<br> ↳ [s-mimecast-app-login](../Parsers/parserContent_s-mimecast-app-login.md)<br><br> dlp-email-alert-in<br> ↳ [s-mimecast-dlp-email](../Parsers/parserContent_s-mimecast-dlp-email.md)<br> ↳ [cef-mimecast-security-alert](../Parsers/parserContent_cef-mimecast-security-alert.md)<br><br> dlp-email-alert-in-failed<br> ↳ [s-mimecast-dlp-email](../Parsers/parserContent_s-mimecast-dlp-email.md)<br> ↳ [cef-mimecast-security-alert](../Parsers/parserContent_cef-mimecast-security-alert.md)<br><br> dlp-email-alert-out<br> ↳ [s-mimecast-dlp-email](../Parsers/parserContent_s-mimecast-dlp-email.md)<br><br> dlp-email-alert-out-failed<br> ↳ [s-mimecast-dlp-email](../Parsers/parserContent_s-mimecast-dlp-email.md)<br><br> failed-app-login<br> ↳ [cef-mimecast-failed-app-login](../Parsers/parserContent_cef-mimecast-failed-app-login.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>                                                               | <ul><li>40 Rules</li></ul><ul><li>9 Models</li></ul> |
|          [Internal Fraud](../UseCases/usecase_internal_fraud.md)          | <ul><li>Application Activity</li></ul>                                                                                                                                                                                                   |  app-activity<br> ↳ [s-mimecast-app-activity](../Parsers/parserContent_s-mimecast-app-activity.md)<br><br> app-login<br> ↳ [s-mimecast-app-login](../Parsers/parserContent_s-mimecast-app-login.md)<br><br> dlp-email-alert-in<br> ↳ [s-mimecast-dlp-email](../Parsers/parserContent_s-mimecast-dlp-email.md)<br> ↳ [cef-mimecast-security-alert](../Parsers/parserContent_cef-mimecast-security-alert.md)<br><br> dlp-email-alert-in-failed<br> ↳ [s-mimecast-dlp-email](../Parsers/parserContent_s-mimecast-dlp-email.md)<br> ↳ [cef-mimecast-security-alert](../Parsers/parserContent_cef-mimecast-security-alert.md)<br><br> dlp-email-alert-out<br> ↳ [s-mimecast-dlp-email](../Parsers/parserContent_s-mimecast-dlp-email.md)<br><br> dlp-email-alert-out-failed<br> ↳ [s-mimecast-dlp-email](../Parsers/parserContent_s-mimecast-dlp-email.md)<br><br> failed-app-login<br> ↳ [cef-mimecast-failed-app-login](../Parsers/parserContent_cef-mimecast-failed-app-login.md)<br> | T1078 - Valid Accounts<br>                                                                                       | <ul><li>13 Rules</li></ul><ul><li>1 Models</li></ul> |
|        [Lateral Movement](../UseCases/usecase_lateral_movement.md)        | <ul><li>Activity Time  and Type</li><li>Application Activity</li><li>Network zones and Location Access</li></ul>                                                                                                                         |  app-activity<br> ↳ [s-mimecast-app-activity](../Parsers/parserContent_s-mimecast-app-activity.md)<br><br> app-login<br> ↳ [s-mimecast-app-login](../Parsers/parserContent_s-mimecast-app-login.md)<br><br> dlp-email-alert-in<br> ↳ [s-mimecast-dlp-email](../Parsers/parserContent_s-mimecast-dlp-email.md)<br> ↳ [cef-mimecast-security-alert](../Parsers/parserContent_cef-mimecast-security-alert.md)<br><br> dlp-email-alert-in-failed<br> ↳ [s-mimecast-dlp-email](../Parsers/parserContent_s-mimecast-dlp-email.md)<br> ↳ [cef-mimecast-security-alert](../Parsers/parserContent_cef-mimecast-security-alert.md)<br><br> dlp-email-alert-out<br> ↳ [s-mimecast-dlp-email](../Parsers/parserContent_s-mimecast-dlp-email.md)<br><br> dlp-email-alert-out-failed<br> ↳ [s-mimecast-dlp-email](../Parsers/parserContent_s-mimecast-dlp-email.md)<br><br> failed-app-login<br> ↳ [cef-mimecast-failed-app-login](../Parsers/parserContent_cef-mimecast-failed-app-login.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>                                                   | <ul><li>7 Rules</li></ul><ul><li>1 Models</li></ul>  |
|       [Malware Detection](../UseCases/usecase_malware_detection.md)       | <ul><li>Asset Logon and Access</li></ul>                                                                                                                                                                                                 |  app-activity<br> ↳ [s-mimecast-app-activity](../Parsers/parserContent_s-mimecast-app-activity.md)<br><br> app-login<br> ↳ [s-mimecast-app-login](../Parsers/parserContent_s-mimecast-app-login.md)<br><br> dlp-email-alert-in<br> ↳ [s-mimecast-dlp-email](../Parsers/parserContent_s-mimecast-dlp-email.md)<br> ↳ [cef-mimecast-security-alert](../Parsers/parserContent_cef-mimecast-security-alert.md)<br><br> dlp-email-alert-in-failed<br> ↳ [s-mimecast-dlp-email](../Parsers/parserContent_s-mimecast-dlp-email.md)<br> ↳ [cef-mimecast-security-alert](../Parsers/parserContent_cef-mimecast-security-alert.md)<br><br> dlp-email-alert-out<br> ↳ [s-mimecast-dlp-email](../Parsers/parserContent_s-mimecast-dlp-email.md)<br><br> dlp-email-alert-out-failed<br> ↳ [s-mimecast-dlp-email](../Parsers/parserContent_s-mimecast-dlp-email.md)<br><br> failed-app-login<br> ↳ [cef-mimecast-failed-app-login](../Parsers/parserContent_cef-mimecast-failed-app-login.md)<br> | T1188 - T1188<br>                                                                                                | <ul><li>6 Rules</li></ul>                            |
|                [Phishing](../UseCases/usecase_phishing.md)                | <ul><li>Email Activity</li></ul>                                                                                                                                                                                                         |  app-activity<br> ↳ [s-mimecast-app-activity](../Parsers/parserContent_s-mimecast-app-activity.md)<br><br> app-login<br> ↳ [s-mimecast-app-login](../Parsers/parserContent_s-mimecast-app-login.md)<br><br> dlp-email-alert-in<br> ↳ [s-mimecast-dlp-email](../Parsers/parserContent_s-mimecast-dlp-email.md)<br> ↳ [cef-mimecast-security-alert](../Parsers/parserContent_cef-mimecast-security-alert.md)<br><br> dlp-email-alert-in-failed<br> ↳ [s-mimecast-dlp-email](../Parsers/parserContent_s-mimecast-dlp-email.md)<br> ↳ [cef-mimecast-security-alert](../Parsers/parserContent_cef-mimecast-security-alert.md)<br><br> dlp-email-alert-out<br> ↳ [s-mimecast-dlp-email](../Parsers/parserContent_s-mimecast-dlp-email.md)<br><br> dlp-email-alert-out-failed<br> ↳ [s-mimecast-dlp-email](../Parsers/parserContent_s-mimecast-dlp-email.md)<br><br> failed-app-login<br> ↳ [cef-mimecast-failed-app-login](../Parsers/parserContent_cef-mimecast-failed-app-login.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>                                                               | <ul><li>7 Rules</li></ul><ul><li>2 Models</li></ul>  |
|     [Privileged Activity](../UseCases/usecase_privileged_activity.md)     | <ul><li>Application Activity</li><li>Email Activity</li><li>Service Account Activity</li></ul>                                                                                                                                           |  app-activity<br> ↳ [s-mimecast-app-activity](../Parsers/parserContent_s-mimecast-app-activity.md)<br><br> app-login<br> ↳ [s-mimecast-app-login](../Parsers/parserContent_s-mimecast-app-login.md)<br><br> dlp-email-alert-in<br> ↳ [s-mimecast-dlp-email](../Parsers/parserContent_s-mimecast-dlp-email.md)<br> ↳ [cef-mimecast-security-alert](../Parsers/parserContent_cef-mimecast-security-alert.md)<br><br> dlp-email-alert-in-failed<br> ↳ [s-mimecast-dlp-email](../Parsers/parserContent_s-mimecast-dlp-email.md)<br> ↳ [cef-mimecast-security-alert](../Parsers/parserContent_cef-mimecast-security-alert.md)<br><br> dlp-email-alert-out<br> ↳ [s-mimecast-dlp-email](../Parsers/parserContent_s-mimecast-dlp-email.md)<br><br> dlp-email-alert-out-failed<br> ↳ [s-mimecast-dlp-email](../Parsers/parserContent_s-mimecast-dlp-email.md)<br><br> failed-app-login<br> ↳ [cef-mimecast-failed-app-login](../Parsers/parserContent_cef-mimecast-failed-app-login.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>T1078 - Valid Accounts<br>                                     | <ul><li>5 Rules</li></ul><ul><li>1 Models</li></ul>  |
|    [Ransomware Detection](../UseCases/usecase_ransomware_detection.md)    | <ul><li>Asset Logon and Access</li></ul>                                                                                                                                                                                                 |  app-activity<br> ↳ [s-mimecast-app-activity](../Parsers/parserContent_s-mimecast-app-activity.md)<br><br> app-login<br> ↳ [s-mimecast-app-login](../Parsers/parserContent_s-mimecast-app-login.md)<br><br> dlp-email-alert-in<br> ↳ [s-mimecast-dlp-email](../Parsers/parserContent_s-mimecast-dlp-email.md)<br> ↳ [cef-mimecast-security-alert](../Parsers/parserContent_cef-mimecast-security-alert.md)<br><br> dlp-email-alert-in-failed<br> ↳ [s-mimecast-dlp-email](../Parsers/parserContent_s-mimecast-dlp-email.md)<br> ↳ [cef-mimecast-security-alert](../Parsers/parserContent_cef-mimecast-security-alert.md)<br><br> dlp-email-alert-out<br> ↳ [s-mimecast-dlp-email](../Parsers/parserContent_s-mimecast-dlp-email.md)<br><br> dlp-email-alert-out-failed<br> ↳ [s-mimecast-dlp-email](../Parsers/parserContent_s-mimecast-dlp-email.md)<br><br> failed-app-login<br> ↳ [cef-mimecast-failed-app-login](../Parsers/parserContent_cef-mimecast-failed-app-login.md)<br> | T1188 - T1188<br>                                                                                                | <ul><li>6 Rules</li></ul>                            |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution | Persistence                                                                                                                                      | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration                                                                                | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ------------------- | ------------------------------------------------------------------------------------------- | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |           | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  |            |                     | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br> |        |