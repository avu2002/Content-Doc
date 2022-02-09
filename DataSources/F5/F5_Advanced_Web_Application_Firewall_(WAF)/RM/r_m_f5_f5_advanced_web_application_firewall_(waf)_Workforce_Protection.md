Vendor: F5
==========
### Product: [F5 Advanced Web Application Firewall (WAF)](../ds_f5_f5_advanced_web_application_firewall_(waf).md)
### Use-Case: [Workforce Protection](../../../../UseCases/uc_workforce_protection.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   5   |   2    |     2      |      6      |    6    |

| Event Type          | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | Models                                                                                                                          |
| ------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| dlp-email-alert-out | <b>T1048.003 - Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol</b><br> ↳ <b>EM-Competition</b>: Email to competition<br> ↳ <b>EM-OutSpam-L</b>: Email sent to more recipients than usual, at least one external. (L)<br> ↳ <b>EM-G-EXEC-F</b>: First time this peer group has forwarded/sent an email from an executive user<br> ↳ <b>EM-Personal-Job</b>: Email with job seeking keywords in subject is sent to personal email address from company email address<br><br><b>T1048 - Exfiltration Over Alternative Protocol</b><br> ↳ <b>EM-OutSpam-M</b>: Email sent to more recipients than usual, at least one external. (M) |  • <b>EM-G-EXEC</b>: Peer groups that send emails from executives<br> • <b>EM-Recipients-usr</b>: Recipients per Email for user |