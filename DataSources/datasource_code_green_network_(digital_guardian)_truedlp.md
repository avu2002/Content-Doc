Vendor: Code Green Network (Digital Guardian)
=============================================
Product: TrueDLP
----------------
|                                 Use-Case                                  | Activity Types                                                      | Event Types/Parsers                                                                                                                                                                                                                                                                                                                                 | MITRE TTP                                                                                                                                                                                                                      | Content                     |
|:-------------------------------------------------------------------------:| ------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------- |
| [Compromised Credentials](../UseCases/usecase_compromised_credentials.md) | - Critical System Activity                                          |  dlp-alert<br> -- [s-codegreen-dlp-alert](../Parsers/parserContent_s-codegreen-dlp-alert.md)<br><br> dlp-email-alert-out<br> -- [s-codegreen-dlp-email-out](../Parsers/parserContent_s-codegreen-dlp-email-out.md)<br><br> dlp-email-alert-out-failed<br> -- [s-codegreen-dlp-email-out](../Parsers/parserContent_s-codegreen-dlp-email-out.md)<br> | T1078 - Valid Accounts<br>                                                                                                                                                                                                     |  - 1 Rules<br>              |
|       [Data Exfiltration](../UseCases/usecase_data_exfiltration.md)       | - Data Loss Prevention<br>- Email Activity                          |  dlp-alert<br> -- [s-codegreen-dlp-alert](../Parsers/parserContent_s-codegreen-dlp-alert.md)<br><br> dlp-email-alert-out<br> -- [s-codegreen-dlp-email-out](../Parsers/parserContent_s-codegreen-dlp-email-out.md)<br><br> dlp-email-alert-out-failed<br> -- [s-codegreen-dlp-email-out](../Parsers/parserContent_s-codegreen-dlp-email-out.md)<br> | T1020 - Automated Exfiltration<br>T1048 - Exfiltration Over Alternative Protocol<br>T1048.003 - Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol<br>T1204 - User Execution<br> |  - 51 Rules<br> - 12 Models |
|       [Malware Detection](../UseCases/usecase_malware_detection.md)       | - Data Loss Prevention<br>- Endpoint Activity<br>- Process Activity |  dlp-alert<br> -- [s-codegreen-dlp-alert](../Parsers/parserContent_s-codegreen-dlp-alert.md)<br><br> dlp-email-alert-out<br> -- [s-codegreen-dlp-email-out](../Parsers/parserContent_s-codegreen-dlp-email-out.md)<br><br> dlp-email-alert-out-failed<br> -- [s-codegreen-dlp-email-out](../Parsers/parserContent_s-codegreen-dlp-email-out.md)<br> | T1204 - User Execution<br>                                                                                                                                                                                                     |  - 5 Rules<br> - 1 Models   |
|                [Phishing](../UseCases/usecase_phishing.md)                | - Email Activity                                                    |  dlp-alert<br> -- [s-codegreen-dlp-alert](../Parsers/parserContent_s-codegreen-dlp-alert.md)<br><br> dlp-email-alert-out<br> -- [s-codegreen-dlp-email-out](../Parsers/parserContent_s-codegreen-dlp-email-out.md)<br><br> dlp-email-alert-out-failed<br> -- [s-codegreen-dlp-email-out](../Parsers/parserContent_s-codegreen-dlp-email-out.md)<br> | T1048 - Exfiltration Over Alternative Protocol<br>T1048.003 - Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol<br>                                                             |  - 7 Rules<br> - 2 Models   |
|    [Ransomware Detection](../UseCases/usecase_ransomware_detection.md)    | - Data Loss Prevention<br>- Endpoint Activity<br>- Process Activity |  dlp-alert<br> -- [s-codegreen-dlp-alert](../Parsers/parserContent_s-codegreen-dlp-alert.md)<br><br> dlp-email-alert-out<br> -- [s-codegreen-dlp-email-out](../Parsers/parserContent_s-codegreen-dlp-email-out.md)<br><br> dlp-email-alert-out-failed<br> -- [s-codegreen-dlp-email-out](../Parsers/parserContent_s-codegreen-dlp-email-out.md)<br> | T1204 - User Execution<br>                                                                                                                                                                                                     |  - 5 Rules<br> - 1 Models   |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                      | Execution                                                           | Persistence                                                         | Privilage escalation                                                | Defense evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration                                                                                                                                                                                                                                                                                                                    | Impact |
| ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [User Execution](https://attack.mitre.org/techniques/T1204)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  |            |                     | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br>[Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol](https://attack.mitre.org/techniques/T1048/003)<br><br>[Automated Exfiltration](https://attack.mitre.org/techniques/T1020)<br><br> |        |