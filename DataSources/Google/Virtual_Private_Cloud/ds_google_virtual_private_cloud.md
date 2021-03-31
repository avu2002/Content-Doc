Vendor: Google
==============
Product: Virtual Private Cloud
------------------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  29   |   15   |     6      |      1      |    1    |

|                               Use-Case                               | Event Types/Parsers                                                                                           | MITRE TTP                                                                                                                                                                           | Content                                                                                                                      |
|:--------------------------------------------------------------------:| ------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
|    [Data Exfiltration](../../../UseCases/uc_data_exfiltration.md)    |  netflow-connection<br> ↳ [gcpvpc-netflow-connection](Parsers/parserContent_gcpvpc-netflow-connection.md)<br> | T1048.003 - Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol<br>T1071.002 - Application Layer Protocol: File Transfer Protocols<br> | [<ul><li>1 Rules</li></ul>](Rules_Models/r_m_google_virtual_private_cloud_Data_Exfiltration.md)                              |
|     [Lateral Movement](../../../UseCases/uc_lateral_movement.md)     |  netflow-connection<br> ↳ [gcpvpc-netflow-connection](Parsers/parserContent_gcpvpc-netflow-connection.md)<br> | T1043 - T1043<br>T1046 - Network Service Scanning<br>T1071 - Application Layer Protocol<br>T1090.002 - Proxy: External Proxy<br>T1571 - Non-Standard Port<br>                       | [<ul><li>25 Rules</li></ul><ul><li>14 Models</li></ul>](Rules_Models/r_m_google_virtual_private_cloud_Lateral_Movement.md)   |
|    [Malware Detection](../../../UseCases/uc_malware_detection.md)    |  netflow-connection<br> ↳ [gcpvpc-netflow-connection](Parsers/parserContent_gcpvpc-netflow-connection.md)<br> | T1071 - Application Layer Protocol<br>T1090.002 - Proxy: External Proxy<br>                                                                                                         | [<ul><li>13 Rules</li></ul><ul><li>9 Models</li></ul>](Rules_Models/r_m_google_virtual_private_cloud_Malware_Detection.md)   |
|             [Phishing](../../../UseCases/uc_phishing.md)             |  netflow-connection<br> ↳ [gcpvpc-netflow-connection](Parsers/parserContent_gcpvpc-netflow-connection.md)<br> | T1071 - Application Layer Protocol<br>                                                                                                                                              | [<ul><li>1 Rules</li></ul>](Rules_Models/r_m_google_virtual_private_cloud_Phishing.md)                                       |
| [Ransomware Detection](../../../UseCases/uc_ransomware_detection.md) |  netflow-connection<br> ↳ [gcpvpc-netflow-connection](Parsers/parserContent_gcpvpc-netflow-connection.md)<br> | T1071 - Application Layer Protocol<br>                                                                                                                                              | [<ul><li>3 Rules</li></ul><ul><li>1 Models</li></ul>](Rules_Models/r_m_google_virtual_private_cloud_Ransomware_Detection.md) |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access | Execution | Persistence | Privilege Escalation | Defense Evasion | Credential Access | Discovery                                                                     | Lateral Movement | Collection | Command and Control                                                                                                                                                                                                                                                                                                                                                                                       | Exfiltration                                                                                                                                                                                                                                         | Impact |
| -------------- | --------- | ----------- | -------------------- | --------------- | ----------------- | ----------------------------------------------------------------------------- | ---------------- | ---------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
|                |           |             |                      |                 |                   | [Network Service Scanning](https://attack.mitre.org/techniques/T1046)<br><br> |                  |            | [Non-Standard Port](https://attack.mitre.org/techniques/T1571)<br><br>[Application Layer Protocol: File Transfer Protocols](https://attack.mitre.org/techniques/T1071/002)<br><br>[Proxy: External Proxy](https://attack.mitre.org/techniques/T1090/002)<br><br>[Application Layer Protocol](https://attack.mitre.org/techniques/T1071)<br><br>[Proxy](https://attack.mitre.org/techniques/T1090)<br><br> | [Exfiltration Over Alternative Protocol](https://attack.mitre.org/techniques/T1048)<br><br>[Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol](https://attack.mitre.org/techniques/T1048/003)<br><br> |        |