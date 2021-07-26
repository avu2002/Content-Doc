Vendor: Cisco
=============
### Product: [Cisco ISE](../ds_cisco_cisco_ise.md)
### Use-Case: [Lateral Movement](../../../../UseCases/uc_lateral_movement.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  34   |   18   |     6      |      9      |    9    |

| Event Type   | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | Models                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| remote-logon | <b>T1550.002 - Use Alternate Authentication Material: Pass the Hash</b><br> ↳ <b>A-NTLM-mismatch</b>: Mismatch between logged and resolved hostnames<br> ↳ <b>A-PTH-ALERT-sH</b>: Possible pass the hash attack from this source host<br> ↳ <b>NTLM-mismatch</b>: <br> ↳ <b>PTH-ALERT-sH-Possible</b>: Possible pass the hash attack with keylength of 0 in NTLM event and a 'null' sid.<br><br><b>T1550 - Use Alternate Authentication Material</b><br> ↳ <b>RLA-UAPackage-F</b>: First time usage of Windows authentication package<br> ↳ <b>RLA-UAPackage-A</b>: Abnormal usage of Windows authentication package<br><br><b>T1558.003 - Steal or Forge Kerberos Tickets: Kerberoasting</b><br> ↳ <b>A-KL-UToE-F</b>: First kerberos ticket options and encryption type combination for asset<br> ↳ <b>A-KL-UToE-A</b>: Abnormal kerberos ticket options and encryption type for asset<br> ↳ <b>A-KL-ToEt-Roast</b>: Suspicious or weak encryption type used for obtaining the kerberos TGTs using non kerberos service for this asset<br> ↳ <b>KL-ToEt-Roast</b>: Suspicious or weak encryption type used for obtaining kerberos TGTs using non kerberos service<br> ↳ <b>KL-OEt-F</b>: First kerberos ticket encryption type for organization<br> ↳ <b>KL-OEt-A</b>: Abnormal kerberos ticket encryption type for organization<br> ↳ <b>KL-OTo-F</b>: First kerberos ticket options for organization<br> ↳ <b>KL-OTo-A</b>: Abnormal kerberos ticket options for organization<br> ↳ <b>KL-UTo-F</b>: First kerberos ticket options for user<br> ↳ <b>KL-UTo-A</b>: Abnormal kerberos ticket options for user<br> ↳ <b>KL-UToE-F</b>: First kerberos ticket options and encryption type combination for user<br> ↳ <b>KL-UToE-A</b>: Abnormal kerberos ticket options and encryption type for user<br> ↳ <b>KL-USn-A</b>: Abnormal service to obtain TGTs for user<br><br><b>T1021 - Remote Services</b><br> ↳ <b>A-RLA-AA-F</b>: First asset-to-asset communication<br> ↳ <b>A-RLA-AA-A</b>: Abnormal asset-to-asset communication<br> ↳ <b>A-RLA-ZZ-A</b>: Abnormal zone-to-zone communication (DISABLED)<br> ↳ <b>A-RLA-sHdZ-F</b>: First remote access to zone from asset<br> ↳ <b>A-RLA-sHdZ-A</b>: Abnormal remote access to zone from asset<br> ↳ <b>A-RLA-dHsZ-F</b>: First remote access from zone to asset<br> ↳ <b>A-RLA-dHsZ-A</b>: Abnormal remote access from zone to asset<br><br><b>T1078 - Valid Accounts</b><br> ↳ <b>RLA-UsH-dZ-F</b>: First remote access to zone from new asset<br> ↳ <b>RLA-UsH-dZ-A</b>: Abnormal remote access to zone from new asset<br><br><b>T1018 - Remote System Discovery</b><br> ↳ <b>A-RLRA-AA-F</b>: First remote asset-to-asset communication<br> ↳ <b>A-RLRA-AA-A</b>: Abnormal asset-to-asset remote communication<br> ↳ <b>A-RLRA-ZZ-F</b>: First zone-to-zone communication<br> ↳ <b>A-RLRA-ZZ-A</b>: Abnormal zone-to-zone communication |  • <b>RLA-UAPackage</b>: Windows authentication packages used when connecting to remote hosts<br> • <b>KL-USn</b>: Services to obtain TGTs for user<br> • <b>KL-UToE</b>: Ticket options and encryption type combination for user<br> • <b>KL-OTo</b>: Ticket Options for organization<br> • <b>KL-OEt</b>: Encryption Types for organization<br> • <b>AE-NTLM</b>: Models ntlm hostnames in the organization<br> • <b>AE-OHr</b>: Random hostnames<br> • <b>AL-UsH</b>: Source hosts per User<br> • <b>A-KL-UToE</b>: Ticket options and encryption type combination for asset<br> • <b>A-AE-OHr</b>: Random hostnames on asset<br> • <b>A-RLA-dHsZ</b>: Destination Host to Source zone communication<br> • <b>A-RLA-sHdZ</b>: Source Host to Destination zone communication<br> • <b>A-RLA-ZZ</b>: Zone to zone communication (DISABLED)<br> • <b>A-RLRA-ZZ</b>: Zone to zone communication<br> • <b>A-RLRA-AA</b>: Asset to asset communication<br> • <b>A-RLA-AA</b>: Asset to asset communication (DISABLED) |
| vpn-logout   | <b>T1558.003 - Steal or Forge Kerberos Tickets: Kerberoasting</b><br> ↳ <b>KL-USnCOUNT-A</b>: Abnormal number of services used to obtain TGTs by user<br> ↳ <b>KL-GSnCOUNT-A</b>: Abnormal number of services used to obtain TGTs by peer group                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |  • <b>KL-GSnCOUNT</b>: Count of services used to obtain kerberos TGTs in a session for peer group<br> • <b>KL-USnCOUNT</b>: Count of services used to obtain kerberos TGTs in a session for user                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |