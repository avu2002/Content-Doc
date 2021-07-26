Vendor: F5
==========
### Product: [F5 BIG-IP Application Security Manager (ASM)](../ds_f5_f5_big-ip_application_security_manager_(asm).md)
### Use-Case: [Evasion](../../../../UseCases/uc_evasion.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   3   |   1    |     2      |      3      |    3    |

| Event Type           | Rules                                                                                                                                                                                                                                                                                                                                                           | Models                                                                                            |
| -------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- |
| web-activity-allowed | <b>T1071.001 - Application Layer Protocol: Web Protocols</b><br> ↳ <b>WEB-OUa-OS-F</b>: First web activity using this operating system for the organization<br><br><b>T1090.003 - Proxy: Multi-hop Proxy</b><br> ↳ <b>A-WEB-TorProxy</b>: Asset has accessed a known Tor web proxy<br> ↳ <b>A-WEB-UU-Tor</b>: Asset has accessed a URL containing '/tor/server' |  • <b>WEB-OUa-OS-New</b>: Top operating systems being used to connect to the web for organization |
| web-activity-denied  | <b>T1090.003 - Proxy: Multi-hop Proxy</b><br> ↳ <b>A-WEB-TorProxy</b>: Asset has accessed a known Tor web proxy<br> ↳ <b>A-WEB-UU-Tor</b>: Asset has accessed a URL containing '/tor/server'                                                                                                                                                                    |                                                                                                   |