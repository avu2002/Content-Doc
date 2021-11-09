Vendor: Rapid7
==============
### Product: [InsightVM](../ds_rapid7_insightvm.md)
### Use-Case: [Data Exfiltration](../../../../UseCases/uc_data_exfiltration.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  11   |   0    |     10     |      1      |    1    |

| Event Type      | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | Models |
| --------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| process-created | <b>T1071.002 - Application Layer Protocol: File Transfer Protocols</b><br> ↳ <b>ATP-FTP-Exfil</b>: Exfiltration Over Alternative Protocol<br><br><b>T1105 - Ingress Tool Transfer</b><br> ↳ <b>A-Certutil-Encode</b>: Certutil commands to encode files were used on this asset.<br> ↳ <b>Certutil-Encode</b>: Certutil commands to encode files were used.<br><br><b>T1048 - Exfiltration Over Alternative Protocol</b><br> ↳ <b>DNS-Exfiltration-Tools-Exec</b>: Well-known DNS Exfiltration tools were executed.<br> ↳ <b>Tap-Installer</b>: TAP software was installed.<br><br><b>T1020 - Automated Exfiltration</b><br> ↳ <b>Exfil-Tunnel-Tools-Exec</b>: Tools known for data exfiltration and tunneling were executed.<br><br><b>T1040 - Network Sniffing</b><br> ↳ <b>NSniff-Cred</b>: Potential network sniffing was observed<br><br><b>T1059 - Command and Scripting Interperter</b><br> ↳ <b>JPanda-Activity</b>: Judgement Panda Exfil Activity detected<br><br><b>T1560 - Archive Collected Data</b><br> ↳ <b>JPanda-Activity</b>: Judgement Panda Exfil Activity detected<br><br><b>T1003 - OS Credential Dumping</b><br> ↳ <b>JPanda-RUS-G-Activity</b>: Judgement Panda Exfil Activity- Russian group activity detected<br><br><b>T1552.001 - T1552.001</b><br> ↳ <b>JPanda-RUS-G-Activity</b>: Judgement Panda Exfil Activity- Russian group activity detected<br><br><b>T1505.003 - Server Software Component: Web Shell</b><br> ↳ <b>A-WebShell-WebServer</b>: Possible web server web shell detected on this asset<br> ↳ <b>WebShell-WebServer</b>: Possible web server web shell detected |        |