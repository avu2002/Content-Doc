Vendor: Sophos
==============
### Product: [Sophos XG Firewall](../ds_sophos_sophos_xg_firewall.md)
### Use-Case: [Other](../../../../UseCases/uc_other.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   3   |   1    |     2      |      5      |    5    |

| Event Type                    | Rules                                                                                                                                                                                                                                                                                                                                                         | Models |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| network-connection-failed     | <b>T1496 - Resource Hijacking</b><br> ↳ <b>A-NET-Coin-IP</b>: Connection to IP associated with cryptocurrency mining                                                                                                                                                                                                                                          |        |
| network-connection-successful | <b>T1496 - Resource Hijacking</b><br> ↳ <b>A-NET-Coin-IP</b>: Connection to IP associated with cryptocurrency mining                                                                                                                                                                                                                                          |        |
| web-activity-denied           | <b>T1071 - Application Layer Protocol</b><br> ↳ <b>WEB-Shadow-Mining</b>: User has browsed to a known coinmining/shadowmining domain<br><br><b>T1496 - Resource Hijacking</b><br> ↳ <b>A-NET-Coin-IP</b>: Connection to IP associated with cryptocurrency mining<br> ↳ <b>A-WEB-Shadow-Mining</b>: Host has browsed to a known coinmining/shadowmining domain |        |