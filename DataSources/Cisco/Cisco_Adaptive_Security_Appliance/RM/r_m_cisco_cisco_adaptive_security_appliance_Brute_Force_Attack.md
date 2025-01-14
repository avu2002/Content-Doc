Vendor: Cisco
=============
### Product: [Cisco Adaptive Security Appliance](../ds_cisco_cisco_adaptive_security_appliance.md)
### Use-Case: [Brute Force Attack](../../../../UseCases/uc_brute_force_attack.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   2   |   1    |     1      |     10      |   10    |

| Event Type     | Rules                                                                                                    | Models                                                                     |
| -------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| print-activity | <b>T1110 - Brute Force</b><br> ↳ <b>PR-SRC-CODE</b>: Printed document with source code file extension    |                                                                            |
| vpn-logout     | <b>T1110 - Brute Force</b><br> ↳ <b>AUTH-F-COUNT</b>: Abnormal number of failed authentications for user |  • <b>AUTH-F-COUNT</b>: Count of failed authentication events in a session |