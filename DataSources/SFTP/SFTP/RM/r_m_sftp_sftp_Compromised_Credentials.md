Vendor: SFTP
============
### Product: [SFTP](../ds_sftp_sftp.md)
### Use-Case: [Compromised Credentials](../../../../UseCases/uc_compromised_credentials.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  67   |   0    |     6      |      7      |    7    |

| Event Type   | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | Models |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| app-activity | <b>T1078 - Valid Accounts</b><br> ↳ <b>UA-UI-F</b>: First activity from ISP<br> ↳ <b>UA-UC-new</b>: Abnormal country for user by new user<br> ↳ <b>UA-OC-new</b>: Abnormal country for organization by new user<br> ↳ <b>UA-UC-Suspicious</b>: Activity from suspicious country<br> ↳ <b>UA-UC-Two</b>: Activity from two different countries<br> ↳ <b>APP-UApp-F</b>: First login or activity within an application for user<br> ↳ <b>APP-UApp-A</b>: Abnormal login or activity within an application for user<br> ↳ <b>APP-AppU-F</b>: First login to an application for a user with no history<br> ↳ <b>APP-F-SA-NC</b>: New service account access to application<br> ↳ <b>APP-AppG-F</b>: First login to an application for group<br> ↳ <b>APP-GApp-A</b>: Abnormal login to an application for group<br> ↳ <b>APP-UTi</b>: Abnormal user activity time<br> ↳ <b>APP-UAg-F</b>: First user agent string for user<br> ↳ <b>APP-UAg-2</b>: Second new user agent string for user<br> ↳ <b>APP-UAg-3</b>: More than two new user agents used by the user in the same session<br> ↳ <b>APP-UsH-F</b>: First source asset for user in application<br> ↳ <b>APP-UsH-A</b>: Abnormal source asset for user in application<br> ↳ <b>APP-UOb-F</b>: First access to application object for user<br> ↳ <b>APP-UOb-A</b>: Abnormal access to application object for user<br> ↳ <b>APP-UappA-F</b>: First application activity for user<br> ↳ <b>APP-UappA-A</b>: Abnormal application activity for user<br> ↳ <b>APP-GappA-F</b>: First application activity for peer group<br> ↳ <b>APP-GappA-A</b>: Abnormal application activity for peer group<br> ↳ <b>APP-AA-F</b>: First application activity in the organization<br> ↳ <b>APP-AA-A</b>: Abnormal activity in application for the organization<br> ↳ <b>APP-UId-F</b>: First use of client Id for user<br> ↳ <b>APP-IdU-F</b>: Reuse of client Id<br> ↳ <b>APP-UMime-F</b>: First mime type for user<br> ↳ <b>APP-UMime-A</b>: Abnormal mime type for user<br> ↳ <b>APP-GMime-F</b>: First mime type for peer group<br> ↳ <b>APP-GMime-A</b>: Abnormal mime type for peer group<br> ↳ <b>APP-OMime-F</b>: First mime type for organization<br> ↳ <b>APP-OMime-A</b>: Abnormal mime type for organization<br> ↳ <b>APP-AppSz-F</b>: First application access from network zone<br> ↳ <b>APP-AT-PRIV</b>: Non-privileged user performing privileged application activity<br><br><b>T1133 - External Remote Services</b><br> ↳ <b>UA-UI-F</b>: First activity from ISP<br> ↳ <b>UA-UC-new</b>: Abnormal country for user by new user<br> ↳ <b>UA-OC-new</b>: Abnormal country for organization by new user<br> ↳ <b>UA-UC-Suspicious</b>: Activity from suspicious country<br> ↳ <b>UA-UC-Two</b>: Activity from two different countries |        |
| app-login    | <b>T1078 - Valid Accounts</b><br> ↳ <b>UA-UI-F</b>: First activity from ISP<br> ↳ <b>UA-UC-new</b>: Abnormal country for user by new user<br> ↳ <b>UA-OC-new</b>: Abnormal country for organization by new user<br> ↳ <b>UA-UC-Suspicious</b>: Activity from suspicious country<br> ↳ <b>UA-UC-Two</b>: Activity from two different countries<br> ↳ <b>APP-UApp-F</b>: First login or activity within an application for user<br> ↳ <b>APP-UApp-A</b>: Abnormal login or activity within an application for user<br> ↳ <b>APP-AppU-F</b>: First login to an application for a user with no history<br> ↳ <b>APP-F-SA-NC</b>: New service account access to application<br> ↳ <b>APP-AppG-F</b>: First login to an application for group<br> ↳ <b>APP-GApp-A</b>: Abnormal login to an application for group<br> ↳ <b>APP-UTi</b>: Abnormal user activity time<br> ↳ <b>APP-UAg-F</b>: First user agent string for user<br> ↳ <b>APP-UAg-2</b>: Second new user agent string for user<br> ↳ <b>APP-UAg-3</b>: More than two new user agents used by the user in the same session<br> ↳ <b>APP-UsH-F</b>: First source asset for user in application<br> ↳ <b>APP-UsH-A</b>: Abnormal source asset for user in application<br> ↳ <b>APP-UId-F</b>: First use of client Id for user<br> ↳ <b>APP-IdU-F</b>: Reuse of client Id<br> ↳ <b>APP-AppSz-F</b>: First application access from network zone<br><br><b>T1133 - External Remote Services</b><br> ↳ <b>UA-UI-F</b>: First activity from ISP<br> ↳ <b>UA-UC-new</b>: Abnormal country for user by new user<br> ↳ <b>UA-OC-new</b>: Abnormal country for organization by new user<br> ↳ <b>UA-UC-Suspicious</b>: Activity from suspicious country<br> ↳ <b>UA-UC-Two</b>: Activity from two different countries                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |        |
| file-delete  | <b>T1083 - File and Directory Discovery</b><br> ↳ <b>FA-UA-UI-F</b>: First file activity from ISP<br> ↳ <b>FA-UA-UC-F</b>: First file activity from country for user<br> ↳ <b>FA-UA-UC-A</b>: Abnormal file activity from country for user<br> ↳ <b>FA-UA-GC-F</b>: First file activity from country for group<br> ↳ <b>FA-UA-GC-A</b>: Abnormal file activity from country for group<br> ↳ <b>FA-UA-OC-F</b>: First file activity from country for organization<br> ↳ <b>FA-UA-OC-A</b>: Abnormal file activity from country for organization<br> ↳ <b>FA-UTi</b>: Abnormal user file activity time<br> ↳ <b>FA-UH-F</b>: First file access from asset for user<br> ↳ <b>FA-UH-A</b>: Abnormal file access from asset for user<br> ↳ <b>FA-OZ-F</b>: First file access from network zone for organization<br> ↳ <b>FA-OZ-A</b>: Abnormal file access from network zone for organization<br> ↳ <b>FA-UZ-F</b>: First file access from network zone for user<br> ↳ <b>FA-UZ-A</b>: Abnormal file access from network zone for user<br> ↳ <b>FA-UA-F</b>: First file access activity for user<br> ↳ <b>FA-UA-A</b>: Abnormal file access activity for user<br> ↳ <b>FA-OU-F</b>: First access to source code files for user in the organization<br> ↳ <b>FA-OU-A</b>: Abnormal access to source code files for user in the organization<br> ↳ <b>FA-OG-F</b>: First access to source code files for user in the peer group<br> ↳ <b>FA-OG-A</b>: Abnormal access to source code files for user in the peer group<br> ↳ <b>FA-UD-F</b>: First file server access for user<br> ↳ <b>FA-UD-A</b>: Abnormal file server access for user<br> ↳ <b>FA-GD-F</b>: First file server access for group<br> ↳ <b>FA-GD-A</b>: Abnormal file server access for group                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |        |
| file-read    | <b>T1003.001 - T1003.001</b><br> ↳ <b>FA-LSASS</b>: Possible Mimikatz attack by a user process<br><br><b>T1083 - File and Directory Discovery</b><br> ↳ <b>FA-UA-UI-F</b>: First file activity from ISP<br> ↳ <b>FA-UA-UC-F</b>: First file activity from country for user<br> ↳ <b>FA-UA-UC-A</b>: Abnormal file activity from country for user<br> ↳ <b>FA-UA-GC-F</b>: First file activity from country for group<br> ↳ <b>FA-UA-GC-A</b>: Abnormal file activity from country for group<br> ↳ <b>FA-UA-OC-F</b>: First file activity from country for organization<br> ↳ <b>FA-UA-OC-A</b>: Abnormal file activity from country for organization<br> ↳ <b>FA-UTi</b>: Abnormal user file activity time<br> ↳ <b>FA-UH-F</b>: First file access from asset for user<br> ↳ <b>FA-UH-A</b>: Abnormal file access from asset for user<br> ↳ <b>FA-OZ-F</b>: First file access from network zone for organization<br> ↳ <b>FA-OZ-A</b>: Abnormal file access from network zone for organization<br> ↳ <b>FA-UZ-F</b>: First file access from network zone for user<br> ↳ <b>FA-UZ-A</b>: Abnormal file access from network zone for user<br> ↳ <b>FA-UA-F</b>: First file access activity for user<br> ↳ <b>FA-UA-A</b>: Abnormal file access activity for user<br> ↳ <b>FA-OU-F</b>: First access to source code files for user in the organization<br> ↳ <b>FA-OU-A</b>: Abnormal access to source code files for user in the organization<br> ↳ <b>FA-OG-F</b>: First access to source code files for user in the peer group<br> ↳ <b>FA-OG-A</b>: Abnormal access to source code files for user in the peer group<br> ↳ <b>FA-UD-F</b>: First file server access for user<br> ↳ <b>FA-UD-A</b>: Abnormal file server access for user<br> ↳ <b>FA-GD-F</b>: First file server access for group<br> ↳ <b>FA-GD-A</b>: Abnormal file server access for group<br><br><b>T1003.003 - T1003.003</b><br> ↳ <b>A-NTDS-Access-F</b>: The NTDS database was accessed from a new location on this asset.<br> ↳ <b>A-NTDS-Access-A</b>: The NTDS database was accessed from a non default location on this asset.<br> ↳ <b>A-NTDS-Access</b>: The NTDS database was accessed from a non default location without 'ntds.dit' in the file path on this asset.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |        |
| file-write   | <b>T1083 - File and Directory Discovery</b><br> ↳ <b>FA-UA-UI-F</b>: First file activity from ISP<br> ↳ <b>FA-UA-UC-F</b>: First file activity from country for user<br> ↳ <b>FA-UA-UC-A</b>: Abnormal file activity from country for user<br> ↳ <b>FA-UA-GC-F</b>: First file activity from country for group<br> ↳ <b>FA-UA-GC-A</b>: Abnormal file activity from country for group<br> ↳ <b>FA-UA-OC-F</b>: First file activity from country for organization<br> ↳ <b>FA-UA-OC-A</b>: Abnormal file activity from country for organization<br> ↳ <b>FA-UTi</b>: Abnormal user file activity time<br> ↳ <b>FA-UH-F</b>: First file access from asset for user<br> ↳ <b>FA-UH-A</b>: Abnormal file access from asset for user<br> ↳ <b>FA-OZ-F</b>: First file access from network zone for organization<br> ↳ <b>FA-OZ-A</b>: Abnormal file access from network zone for organization<br> ↳ <b>FA-UZ-F</b>: First file access from network zone for user<br> ↳ <b>FA-UZ-A</b>: Abnormal file access from network zone for user<br> ↳ <b>FA-UA-F</b>: First file access activity for user<br> ↳ <b>FA-UA-A</b>: Abnormal file access activity for user<br> ↳ <b>FA-OU-F</b>: First access to source code files for user in the organization<br> ↳ <b>FA-OU-A</b>: Abnormal access to source code files for user in the organization<br> ↳ <b>FA-OG-F</b>: First access to source code files for user in the peer group<br> ↳ <b>FA-OG-A</b>: Abnormal access to source code files for user in the peer group<br> ↳ <b>FA-UD-F</b>: First file server access for user<br> ↳ <b>FA-UD-A</b>: Abnormal file server access for user<br> ↳ <b>FA-GD-F</b>: First file server access for group<br> ↳ <b>FA-GD-A</b>: Abnormal file server access for group<br><br><b>T1003.003 - T1003.003</b><br> ↳ <b>A-NTDS-Access-F</b>: The NTDS database was accessed from a new location on this asset.<br> ↳ <b>A-NTDS-Access-A</b>: The NTDS database was accessed from a non default location on this asset.<br> ↳ <b>A-NTDS-Access</b>: The NTDS database was accessed from a non default location without 'ntds.dit' in the file path on this asset.<br> ↳ <b>A-NTDS-Shadow-Copy1</b>: The NTDS database changed location to a shadowcopy using 'ntds.dit' and 'harddiskvolumeshadowcopy' in the file path on this asset.<br> ↳ <b>A-NTDS-Shadow-Copy2</b>: The NTDS database changed location to a shadowcopy using 'harddiskvolumeshadowcopy' in the file path on this asset.<br><br><b>T1003.002 - T1003.002</b><br> ↳ <b>A-ATP-Tool-FGDump</b>: Malicious exe/dll.<br> ↳ <b>A-ATP-Tool-PSTGDump</b>: Malicious pstgdump.exe was run from a temp folder on this asset.                                                                                                                       |        |