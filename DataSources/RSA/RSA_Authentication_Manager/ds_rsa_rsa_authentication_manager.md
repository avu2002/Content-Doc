Vendor: RSA
===========
Product: RSA Authentication Manager
-----------------------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   4   |   2    |     2      |      1      |    1    |

|    Use-Case    | Event Types/Parsers    | MITRE TTP    | Content    |
|:----:| ---- | ---- | ---- |
|    [Data Leak](../../../UseCases/uc_data_leak.md)    |  dlp-email-alert-out-failed<br> ↳[rsa-authentication-successful](Ps/pC_rsaauthenticationsuccessful.md)<br> ↳[rsa-authentication-successful-1](Ps/pC_rsaauthenticationsuccessful1.md)<br> | T1048.003 - Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol<br> | [<ul><li>3 Rules</li></ul><ul><li>2 Models</li></ul>](RM/r_m_rsa_rsa_authentication_manager_Data_Leak.md) |
|     [Privilege Abuse](../../../UseCases/uc_privilege_abuse.md)     |  dlp-email-alert-out-failed<br> ↳[rsa-authentication-successful](Ps/pC_rsaauthenticationsuccessful.md)<br> ↳[rsa-authentication-successful-1](Ps/pC_rsaauthenticationsuccessful1.md)<br> | T1078 - Valid Accounts<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_rsa_rsa_authentication_manager_Privilege_Abuse.md)    |
| [Privileged Activity](../../../UseCases/uc_privileged_activity.md) |  dlp-email-alert-out-failed<br> ↳[rsa-authentication-successful](Ps/pC_rsaauthenticationsuccessful.md)<br> ↳[rsa-authentication-successful-1](Ps/pC_rsaauthenticationsuccessful1.md)<br> | T1078 - Valid Accounts<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_rsa_rsa_authentication_manager_Privileged_Activity.md)    |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                      | Execution | Persistence                                                         | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration                                                                                                                                                                                                                                         | Impact |
| ------------------------------------------------------------------- | --------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |           | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  |            |                     | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br>[Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol](https://attack.mitre.org/techniques/T1048/003)<br><br> |        |