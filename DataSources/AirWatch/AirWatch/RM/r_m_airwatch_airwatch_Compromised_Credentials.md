Vendor: AirWatch
================
### Product: [AirWatch](../ds_airwatch_airwatch.md)
### Use-Case: [Compromised Credentials](../../../../UseCases/uc_compromised_credentials.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   8   |   0    |     2      |      3      |    3    |

| Event Type                | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | Models |
| ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------ |
| authentication-successful | <b>T1078 - Valid Accounts</b><br> ↳ <b>UA-UI-F</b>: First activity from ISP<br> ↳ <b>UA-UC-new</b>: Abnormal country for user by new user<br> ↳ <b>UA-OC-new</b>: Abnormal country for organization by new user<br> ↳ <b>UA-UC-Suspicious</b>: Activity from suspicious country<br> ↳ <b>UA-UC-Two</b>: Activity from two different countries<br><br><b>T1133 - External Remote Services</b><br> ↳ <b>UA-UI-F</b>: First activity from ISP<br> ↳ <b>UA-UC-new</b>: Abnormal country for user by new user<br> ↳ <b>UA-OC-new</b>: Abnormal country for organization by new user<br> ↳ <b>UA-UC-Suspicious</b>: Activity from suspicious country<br> ↳ <b>UA-UC-Two</b>: Activity from two different countries |        |
| failed-logon              | <b>T1078 - Valid Accounts</b><br> ↳ <b>SEQ-UH-04</b>: Failed logon by a service account<br> ↳ <b>SEQ-UH-05</b>: Failed interactive logon by a service account<br> ↳ <b>SEQ-UH-07</b>: Failed logon to an asset that user has not previously accessed                                                                                                                                                                                                                                                                                                                                                                                                                                                         |        |