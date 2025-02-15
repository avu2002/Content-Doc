Vendor: Namespace rDirectory
============================
### Product: [Namespace rDirectory](../ds_namespace_rdirectory_namespace_rdirectory.md)
### Use-Case: [Lateral Movement](../../../../UseCases/uc_lateral_movement.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   4   |   0    |     3      |      7      |    7    |

| Event Type      | Rules                                                                                                                                                                                                                        | Models |
| --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| account-deleted | <b>T1110 - Brute Force</b><br> ↳ <b>A-ACCT-CR-DEL</b>: Account created and deleted on asset                                                                                                                                  |        |
| app-login       | <b>T1090.003 - Proxy: Multi-hop Proxy</b><br> ↳ <b>Auth-Tor-Shost</b>: User authentication or login from a known TOR IP                                                                                                      |        |
| security-alert  | <b>T1027.005 - Obfuscated Files or Information: Indicator Removal from Tools</b><br> ↳ <b>A-ALERT-DL</b>: DL Correlation rule alert on asset<br> ↳ <b>ALERT-DL</b>: DL Correlation rule alert on asset accessed by this user |        |