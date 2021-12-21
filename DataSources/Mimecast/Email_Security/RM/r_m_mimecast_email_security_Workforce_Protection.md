Vendor: Mimecast
================
### Product: [Email Security](../ds_mimecast_email_security.md)
### Use-Case: [Workforce Protection](../../../../UseCases/uc_workforce_protection.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   5   |   0    |     2      |     11      |   11    |

| Event Type          | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | Models |
| ------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| dlp-email-alert-out | <b>T1048.003 - Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol</b><br> ↳ <b>EM-Competition</b>: Email to competition<br> ↳ <b>EM-OutSpam-M</b>: Email sent to more recipients than usual, at least one external. (M)<br> ↳ <b>EM-OutSpam-L</b>: Email sent to more recipients than usual, at least one external. (L)<br> ↳ <b>EM-Personal-Job</b>: Email with job seeking keywords in subject is sent to personal email address from company email address |        |
| web-activity-denied | <b>T1071.001 - Application Layer Protocol: Web Protocols</b><br> ↳ <b>WEB-JS</b>: User has accessed a job search domain                                                                                                                                                                                                                                                                                                                                                                                     |        |