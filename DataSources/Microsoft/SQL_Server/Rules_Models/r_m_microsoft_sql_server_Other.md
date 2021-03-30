Vendor: Microsoft
=================
### Product: [SQL Server](../ds_microsoft_sql_server.md)
### Use-Case: [Other](../../../../UseCases/uc_other.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   6   |   1    |     3      |      3      |    3    |

| Event Type       | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | Models                                       |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------- |
| failed-app-login | <b>T1078 - Valid Accounts</b><br> ↳ <b>APP-Account-deactivated</b>: Activity from a de-activated user account<br> ↳ <b>APP-F-FL</b>: Failed login to application<br><br><b>T1188 - T1188</b><br> ↳ <b>Auth-Tor-Shost-Failed</b>: User authentication or login failure from a known TOR IP<br> ↳ <b>Auth-Blacklist-Shost-Failed</b>: User authentication or login failure from a known blacklisted IP<br> ↳ <b>Auth-Ransomware-Shost-Failed</b>: User authentication or login failure from a known ransomware IP<br><br><b>T1133 - External Remote Services</b><br> ↳ <b>FA-UC-F</b>: First Failed activity in session from country in which user has never had a successful activity |  • <b>UA-UC</b>: Countries for user activity |