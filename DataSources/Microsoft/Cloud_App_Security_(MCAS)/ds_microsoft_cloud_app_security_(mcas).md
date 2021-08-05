Vendor: Microsoft
=================
Product: Cloud App Security (MCAS)
----------------------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  78   |   35   |     11     |      5      |    5    |

|    Use-Case    | Event Types/Parsers    | MITRE TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Abnormal Authentication & Access](../../../UseCases/uc_abnormal_authentication_&_access.md) |  app-login<br> ↳[cef-azure-siem-app-logon](Ps/pC_cefazuresiemapplogon.md)<br><br> failed-app-login<br> ↳[cef-azure-siem-app-logon](Ps/pC_cefazuresiemapplogon.md)<br><br> file-upload<br> ↳[cef-azure-onedrive-file-upload](Ps/pC_cefazureonedrivefileupload.md)<br><br> file-write<br> ↳[cef-azure-onedrive-file-write](Ps/pC_cefazureonedrivefilewrite.md)<br><br> security-alert<br> ↳[q-o365-siem-security-alert](Ps/pC_qo365siemsecurityalert.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>    | [<ul><li>18 Rules</li></ul><ul><li>11 Models</li></ul>](RM/r_m_microsoft_cloud_app_security_(mcas)_Abnormal_Authentication_&_Access.md) |
|          [Compromised Credentials](../../../UseCases/uc_compromised_credentials.md)          |  app-login<br> ↳[cef-azure-siem-app-logon](Ps/pC_cefazuresiemapplogon.md)<br><br> failed-app-login<br> ↳[cef-azure-siem-app-logon](Ps/pC_cefazuresiemapplogon.md)<br><br> file-upload<br> ↳[cef-azure-onedrive-file-upload](Ps/pC_cefazureonedrivefileupload.md)<br><br> file-write<br> ↳[cef-azure-onedrive-file-write](Ps/pC_cefazureonedrivefilewrite.md)<br><br> security-alert<br> ↳[q-o365-siem-security-alert](Ps/pC_qo365siemsecurityalert.md)<br> | T1003.003 - T1003.003<br>T1027.005 - Obfuscated Files or Information: Indicator Removal from Tools<br>T1059.001 - Command and Scripting Interperter: PowerShell<br>T1078 - Valid Accounts<br>T1083 - File and Directory Discovery<br>T1133 - External Remote Services<br> | [<ul><li>37 Rules</li></ul><ul><li>19 Models</li></ul>](RM/r_m_microsoft_cloud_app_security_(mcas)_Compromised_Credentials.md)          |
|    [Data Access](../../../UseCases/uc_data_access.md)    |  app-login<br> ↳[cef-azure-siem-app-logon](Ps/pC_cefazuresiemapplogon.md)<br><br> failed-app-login<br> ↳[cef-azure-siem-app-logon](Ps/pC_cefazuresiemapplogon.md)<br><br> file-upload<br> ↳[cef-azure-onedrive-file-upload](Ps/pC_cefazureonedrivefileupload.md)<br><br> file-write<br> ↳[cef-azure-onedrive-file-write](Ps/pC_cefazureonedrivefilewrite.md)<br><br> security-alert<br> ↳[q-o365-siem-security-alert](Ps/pC_qo365siemsecurityalert.md)<br> | T1078 - Valid Accounts<br>T1083 - File and Directory Discovery<br>    | [<ul><li>11 Rules</li></ul><ul><li>10 Models</li></ul>](RM/r_m_microsoft_cloud_app_security_(mcas)_Data_Access.md)    |
|    [Data Exfiltration](../../../UseCases/uc_data_exfiltration.md)    |  app-login<br> ↳[cef-azure-siem-app-logon](Ps/pC_cefazuresiemapplogon.md)<br><br> failed-app-login<br> ↳[cef-azure-siem-app-logon](Ps/pC_cefazuresiemapplogon.md)<br><br> file-upload<br> ↳[cef-azure-onedrive-file-upload](Ps/pC_cefazureonedrivefileupload.md)<br><br> file-write<br> ↳[cef-azure-onedrive-file-write](Ps/pC_cefazureonedrivefilewrite.md)<br><br> security-alert<br> ↳[q-o365-siem-security-alert](Ps/pC_qo365siemsecurityalert.md)<br> | T1204 - User Execution<br>    | [<ul><li>2 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_microsoft_cloud_app_security_(mcas)_Data_Exfiltration.md)    |
|    [Evasion](../../../UseCases/uc_evasion.md)    |  app-login<br> ↳[cef-azure-siem-app-logon](Ps/pC_cefazuresiemapplogon.md)<br><br> failed-app-login<br> ↳[cef-azure-siem-app-logon](Ps/pC_cefazuresiemapplogon.md)<br><br> file-upload<br> ↳[cef-azure-onedrive-file-upload](Ps/pC_cefazureonedrivefileupload.md)<br><br> file-write<br> ↳[cef-azure-onedrive-file-write](Ps/pC_cefazureonedrivefilewrite.md)<br><br> security-alert<br> ↳[q-o365-siem-security-alert](Ps/pC_qo365siemsecurityalert.md)<br> | T1090.003 - Proxy: Multi-hop Proxy<br>    | [<ul><li>2 Rules</li></ul>](RM/r_m_microsoft_cloud_app_security_(mcas)_Evasion.md)    |
|    [Lateral Movement](../../../UseCases/uc_lateral_movement.md)    |  app-login<br> ↳[cef-azure-siem-app-logon](Ps/pC_cefazuresiemapplogon.md)<br><br> failed-app-login<br> ↳[cef-azure-siem-app-logon](Ps/pC_cefazuresiemapplogon.md)<br><br> file-upload<br> ↳[cef-azure-onedrive-file-upload](Ps/pC_cefazureonedrivefileupload.md)<br><br> file-write<br> ↳[cef-azure-onedrive-file-write](Ps/pC_cefazureonedrivefilewrite.md)<br><br> security-alert<br> ↳[q-o365-siem-security-alert](Ps/pC_qo365siemsecurityalert.md)<br> | T1027.005 - Obfuscated Files or Information: Indicator Removal from Tools<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_microsoft_cloud_app_security_(mcas)_Lateral_Movement.md)    |
|    [Malware](../../../UseCases/uc_malware.md)    |  app-login<br> ↳[cef-azure-siem-app-logon](Ps/pC_cefazuresiemapplogon.md)<br><br> failed-app-login<br> ↳[cef-azure-siem-app-logon](Ps/pC_cefazuresiemapplogon.md)<br><br> file-upload<br> ↳[cef-azure-onedrive-file-upload](Ps/pC_cefazureonedrivefileupload.md)<br><br> file-write<br> ↳[cef-azure-onedrive-file-write](Ps/pC_cefazureonedrivefilewrite.md)<br><br> security-alert<br> ↳[q-o365-siem-security-alert](Ps/pC_qo365siemsecurityalert.md)<br> | T1003.002 - T1003.002<br>T1027 - Obfuscated Files or Information<br>T1078 - Valid Accounts<br>T1090.003 - Proxy: Multi-hop Proxy<br>T1204 - User Execution<br>T1218.011 - Signed Binary Proxy Execution: Rundll32<br>    | [<ul><li>12 Rules</li></ul><ul><li>5 Models</li></ul>](RM/r_m_microsoft_cloud_app_security_(mcas)_Malware.md)    |
|    [Privilege Abuse](../../../UseCases/uc_privilege_abuse.md)    |  app-login<br> ↳[cef-azure-siem-app-logon](Ps/pC_cefazuresiemapplogon.md)<br><br> failed-app-login<br> ↳[cef-azure-siem-app-logon](Ps/pC_cefazuresiemapplogon.md)<br><br> file-upload<br> ↳[cef-azure-onedrive-file-upload](Ps/pC_cefazureonedrivefileupload.md)<br><br> file-write<br> ↳[cef-azure-onedrive-file-write](Ps/pC_cefazureonedrivefilewrite.md)<br><br> security-alert<br> ↳[q-o365-siem-security-alert](Ps/pC_qo365siemsecurityalert.md)<br> | T1078 - Valid Accounts<br>T1083 - File and Directory Discovery<br>    | [<ul><li>4 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_microsoft_cloud_app_security_(mcas)_Privilege_Abuse.md)    |
|    [Privileged Activity](../../../UseCases/uc_privileged_activity.md)    |  app-login<br> ↳[cef-azure-siem-app-logon](Ps/pC_cefazuresiemapplogon.md)<br><br> failed-app-login<br> ↳[cef-azure-siem-app-logon](Ps/pC_cefazuresiemapplogon.md)<br><br> file-upload<br> ↳[cef-azure-onedrive-file-upload](Ps/pC_cefazureonedrivefileupload.md)<br><br> file-write<br> ↳[cef-azure-onedrive-file-write](Ps/pC_cefazureonedrivefilewrite.md)<br><br> security-alert<br> ↳[q-o365-siem-security-alert](Ps/pC_qo365siemsecurityalert.md)<br> | T1068 - Exploitation for Privilege Escalation<br>T1078 - Valid Accounts<br>    | [<ul><li>3 Rules</li></ul>](RM/r_m_microsoft_cloud_app_security_(mcas)_Privileged_Activity.md)    |
|    [Ransomware](../../../UseCases/uc_ransomware.md)    |  app-login<br> ↳[cef-azure-siem-app-logon](Ps/pC_cefazuresiemapplogon.md)<br><br> failed-app-login<br> ↳[cef-azure-siem-app-logon](Ps/pC_cefazuresiemapplogon.md)<br><br> file-upload<br> ↳[cef-azure-onedrive-file-upload](Ps/pC_cefazureonedrivefileupload.md)<br><br> file-write<br> ↳[cef-azure-onedrive-file-write](Ps/pC_cefazureonedrivefilewrite.md)<br><br> security-alert<br> ↳[q-o365-siem-security-alert](Ps/pC_qo365siemsecurityalert.md)<br> | T1078 - Valid Accounts<br>    | [<ul><li>2 Rules</li></ul>](RM/r_m_microsoft_cloud_app_security_(mcas)_Ransomware.md)    |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution                                                                                                                                                                                                                                                       | Persistence                                                                                                                                      | Privilege Escalation                                                                                                                                          | Defense Evasion                                                                                                                                                                                                                                                                                                                                                                                                                                                 | Credential Access                                                          | Discovery                                                                         | Lateral Movement | Collection | Command and Control                                                                                                                       | Exfiltration | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- | --------------------------------------------------------------------------------- | ---------------- | ---------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Command and Scripting Interperter](https://attack.mitre.org/techniques/T1059)<br><br>[User Execution](https://attack.mitre.org/techniques/T1204)<br><br>[Command and Scripting Interperter: PowerShell](https://attack.mitre.org/techniques/T1059/001)<br><br> | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Exploitation for Privilege Escalation](https://attack.mitre.org/techniques/T1068)<br><br> | [Obfuscated Files or Information: Indicator Removal from Tools](https://attack.mitre.org/techniques/T1027/005)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Obfuscated Files or Information](https://attack.mitre.org/techniques/T1027)<br><br>[Signed Binary Proxy Execution](https://attack.mitre.org/techniques/T1218)<br><br>[Signed Binary Proxy Execution: Rundll32](https://attack.mitre.org/techniques/T1218/011)<br><br> | [OS Credential Dumping](https://attack.mitre.org/techniques/T1003)<br><br> | [File and Directory Discovery](https://attack.mitre.org/techniques/T1083)<br><br> |                  |            | [Proxy: Multi-hop Proxy](https://attack.mitre.org/techniques/T1090/003)<br><br>[Proxy](https://attack.mitre.org/techniques/T1090)<br><br> |              |        |