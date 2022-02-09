Vendor: Rapid7
==============
### Product: [InsightVM](../ds_rapid7_insightvm.md)
### Use-Case: [Data Exfiltration](../../../../UseCases/uc_data_exfiltration.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  12   |   0    |     10     |      1      |    1    |

| Event Type      | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | Models |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------ |
| process-created | <b>T1048 - Exfiltration Over Alternative Protocol</b><br> ↳ <b>A-Exfil-Tunnel-Tools-Exec</b>: Tools known for data exfiltration and tunneling were executed on this asset.<br> ↳ <b>A-Netsh-Connections-Win-Firewall</b>: Netsh commands were used to allow incoming connections by Port or Application on Windows Firewall on this asset.<br> ↳ <b>DNS-Exfiltration-Tools-Exec</b>: Well-known DNS Exfiltration tools were executed.<br> ↳ <b>Tap-Installer</b>: TAP software was installed.<br><br><b>T1041 - Exfiltration Over C2 Channel</b><br> ↳ <b>A-Sus-Double-Extension</b>: An .exe extension was used after a different non-executable file extension on this asset.<br> ↳ <b>Exfil-Tunnel-Tools-Exec</b>: Tools known for data exfiltration and tunneling were executed.<br><br><b>T1071.001 - Application Layer Protocol: Web Protocols</b><br> ↳ <b>A-Sus-Double-Extension</b>: An .exe extension was used after a different non-executable file extension on this asset.<br> ↳ <b>Exfil-Tunnel-Tools-Exec</b>: Tools known for data exfiltration and tunneling were executed.<br><br><b>T1572 - Protocol Tunneling</b><br> ↳ <b>A-Sus-Double-Extension</b>: An .exe extension was used after a different non-executable file extension on this asset.<br> ↳ <b>Exfil-Tunnel-Tools-Exec</b>: Tools known for data exfiltration and tunneling were executed.<br><br><b>T1071.004 - Application Layer Protocol: DNS</b><br> ↳ <b>A-Netsh-Connections-Win-Firewall</b>: Netsh commands were used to allow incoming connections by Port or Application on Windows Firewall on this asset.<br> ↳ <b>DNS-Exfiltration-Tools-Exec</b>: Well-known DNS Exfiltration tools were executed.<br><br><b>T1040 - Network Sniffing</b><br> ↳ <b>A-EPA-SNIFF</b>: Network sniffing tool has been found running on this asset<br> ↳ <b>DLL-AppData</b>: DLL loaded from 'AppData(slash)Local' path<br><br><b>T1059 - Command and Scripting Interperter</b><br> ↳ <b>A-Rubeus-CMD-Tool</b>: Command line parameters used by Rubeus hack tool detected on this asset<br> ↳ <b>Rubeus-CMD-Tool</b>: Command line parameters used by Rubeus hack tool detected<br><br><b>T1560 - Archive Collected Data</b><br> ↳ <b>A-Rubeus-CMD-Tool</b>: Command line parameters used by Rubeus hack tool detected on this asset<br> ↳ <b>Rubeus-CMD-Tool</b>: Command line parameters used by Rubeus hack tool detected<br><br><b>T1003 - OS Credential Dumping</b><br> ↳ <b>A-JPanda-Activity</b>: Judgement Panda Exfil Activity detected on this asset<br> ↳ <b>JPanda-Activity</b>: Judgement Panda Exfil Activity detected<br><br><b>T1552.001 - T1552.001</b><br> ↳ <b>A-JPanda-Activity</b>: Judgement Panda Exfil Activity detected on this asset<br> ↳ <b>JPanda-Activity</b>: Judgement Panda Exfil Activity detected |        |