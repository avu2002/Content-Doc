Vendor: Juniper VPN
===================
### Product: [Juniper VPN](../ds_juniper_vpn_juniper_vpn.md)
### Use-Case: [Internal Fraud](../../../../UseCases/uc_internal_fraud.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   4   |   2    |     2      |      5      |    5    |

| Event Type           | Rules                                                                                                                                                                                                                                                                                         | Models                                                                                                                                           |
| -------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| vpn-logout           | <b>T1078 - Valid Accounts</b><br> ↳ <b>APP-UOb-Number</b>: Abnormal number of application objects accessed for user                                                                                                                                                                           |                                                                                                                                                  |
| web-activity-allowed | <b>T1071 - Application Layer Protocol</b><br> ↳ <b>WEB-OU-JS-F</b>: First job search activity for user in the organization<br> ↳ <b>WEB-OU-JS-A</b>: Abnormal job search activity for user in the organization<br> ↳ <b>WEB-OG-JS-F</b>: First job search activity for user in the peer group |  • <b>WEB-OG-JS</b>: Job search activities of users in the peer group<br> • <b>WEB-OU-JS</b>: Job search activities of users in the organization |