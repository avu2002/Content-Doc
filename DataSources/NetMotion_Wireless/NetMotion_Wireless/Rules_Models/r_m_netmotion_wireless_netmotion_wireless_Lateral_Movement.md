Vendor: NetMotion Wireless
==========================
### Product: [NetMotion Wireless](../ds_netmotion_wireless_netmotion_wireless.md)
### Use-Case: [Lateral Movement](../../../../UseCases/uc_lateral_movement.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   3   |   2    |     2      |      2      |    2    |

| Event Type | Rules                                                                                                                                                                                                                                                                                                                                                                 | Models                                                                                                                                                                                           |
| ---------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| vpn-logout | <b>T1078 - Valid Accounts</b><br> ↳ <b>DC14g-new</b>: Abnormal number of accessed assets for group of new user<br><br><b>T1558.003 - Steal or Forge Kerberos Tickets: Kerberoasting</b><br> ↳ <b>KL-USnCOUNT-A</b>: Abnormal number of services used to obtain TGTs by user<br> ↳ <b>KL-GSnCOUNT-A</b>: Abnormal number of services used to obtain TGTs by peer group |  • <b>KL-GSnCOUNT</b>: Count of services used to obtain kerberos TGTs in a session for peer group<br> • <b>KL-USnCOUNT</b>: Count of services used to obtain kerberos TGTs in a session for user |