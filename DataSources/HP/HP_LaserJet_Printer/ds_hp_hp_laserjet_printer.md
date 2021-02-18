Vendor: HP
==========
Product: HP LaserJet Printer
----------------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   1   |   1    |     1      |      1      |    1    |

|                           Use-Case                           | Activity Types                         | Event Types/Parsers                                                                       | MITRE TTP         | Content                                                                                  |
|:------------------------------------------------------------:| -------------------------------------- | ----------------------------------------------------------------------------------------- | ----------------- | ---------------------------------------------------------------------------------------- |
| [Lateral Movement](../../../UseCases/uc_lateral_movement.md) | <ul><li>Data Loss Prevention</li></ul> |  print-activity<br> ↳ [gm-print-activity](Parsers/parserContent_gm-print-activity.md)<br> | T1086 - T1086<br> | [<ul><li>1 Rules</li></ul>](Rules_Models/r_m_hp_hp_laserjet_printer_Lateral_Movement.md) |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access | Execution | Persistence | Privilege Escalation | Defense Evasion | Credential Access | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration | Impact |
| -------------- | --------- | ----------- | -------------------- | --------------- | ----------------- | --------- | ---------------- | ---------- | ------------------- | ------------ | ------ |
|                |           |             |                      |                 |                   |           |                  |            |                     |              |        |