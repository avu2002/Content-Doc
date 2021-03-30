Vendor: Zscaler
===============
Product: Zscaler Internet Access
--------------------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  10   |   4    |     3      |      3      |    3    |

|                Use-Case                | Event Types/Parsers                                                                                                                                                                                                                                                                                                                                                                | MITRE TTP                                                                       | Content                                                                                                           |
|:--------------------------------------:| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------- |
| [Other](../../../UseCases/uc_other.md) |  authentication-successful<br> ↳ [zscaler-status](Parsers/parserContent_zscaler-status.md)<br><br> network-connection-failed<br> ↳ [zscaler-firewall](Parsers/parserContent_zscaler-firewall.md)<br><br> network-connection-successful<br> ↳ [zscaler-activity](Parsers/parserContent_zscaler-activity.md)<br> ↳ [zscaler-firewall](Parsers/parserContent_zscaler-firewall.md)<br> | T1078 - Valid Accounts<br>T1133 - External Remote Services<br>T1188 - T1188<br> | [<ul><li>10 Rules</li></ul><ul><li>4 Models</li></ul>](Rules_Models/r_m_zscaler_zscaler_internet_access_Other.md) |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                   | Execution | Persistence                                                                                                                                      | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration | Impact |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | --------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ------------------- | ------------ | ------ |
| [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |           | [External Remote Services](https://attack.mitre.org/techniques/T1133)<br><br>[Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  |            |                     |              |        |