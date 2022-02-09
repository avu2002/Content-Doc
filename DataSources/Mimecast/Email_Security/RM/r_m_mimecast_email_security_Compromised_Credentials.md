Vendor: Mimecast
================
### Product: [Email Security](../ds_mimecast_email_security.md)
### Use-Case: [Compromised Credentials](../../../../UseCases/uc_compromised_credentials.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  90   |   46   |     10     |     11      |   11    |

| Event Type          | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | Models                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| ------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| app-activity        | <b>T1078 - Valid Accounts</b><br> ↳ <b>UA-UI-F</b>: First activity from ISP<br> ↳ <b>UA-UC-new</b>: Abnormal country for user by new user<br> ↳ <b>UA-GC-new</b>: Abnormal country for group by new user<br> ↳ <b>UA-OC-new</b>: Abnormal country for organization by new user<br> ↳ <b>UA-UC-Suspicious</b>: Activity from suspicious country<br> ↳ <b>UA-UC-Two</b>: Activity from two different countries<br> ↳ <b>UA-UC-Three</b>: Activity from 3 different countries<br> ↳ <b>APP-UApp-F</b>: First login or activity within an application for user<br> ↳ <b>APP-UApp-A</b>: Abnormal login or activity within an application for user<br> ↳ <b>APP-AppU-F</b>: First login to an application for a user with no history<br> ↳ <b>APP-F-SA-NC</b>: New service account access to application<br> ↳ <b>APP-AppG-F</b>: First login to an application for group<br> ↳ <b>APP-GApp-A</b>: Abnormal login to an application for group<br> ↳ <b>APP-UTi</b>: Abnormal user activity time<br> ↳ <b>APP-UAg-F</b>: First user agent string for user<br> ↳ <b>APP-UAg-2</b>: Second new user agent string for user<br> ↳ <b>APP-UAg-3</b>: More than two new user agents used by the user in the same session<br> ↳ <b>APP-UOs-F</b>: First os/browser combination for user<br> ↳ <b>APP-UsH-F</b>: First source asset for user in application<br> ↳ <b>APP-UsH-A</b>: Abnormal source asset for user in application<br> ↳ <b>APP-UOb-F</b>: First access to application object for user<br> ↳ <b>APP-UOb-A</b>: Abnormal access to application object for user<br> ↳ <b>APP-UappA-F</b>: First application activity for user<br> ↳ <b>APP-UappA-A</b>: Abnormal application activity for user<br> ↳ <b>APP-GappA-F</b>: First application activity for peer group<br> ↳ <b>APP-GappA-A</b>: Abnormal application activity for peer group<br> ↳ <b>APP-AA-F</b>: First application activity in the organization<br> ↳ <b>APP-AA-A</b>: Abnormal activity in application for the organization<br> ↳ <b>APP-UId-F</b>: First use of client Id for user<br> ↳ <b>APP-IdU-F</b>: Reuse of client Id<br> ↳ <b>APP-UMime-F</b>: First mime type for user<br> ↳ <b>APP-UMime-A</b>: Abnormal mime type for user<br> ↳ <b>APP-GMime-F</b>: First mime type for peer group<br> ↳ <b>APP-GMime-A</b>: Abnormal mime type for peer group<br> ↳ <b>APP-OMime-F</b>: First mime type for organization<br> ↳ <b>APP-OMime-A</b>: Abnormal mime type for organization<br> ↳ <b>APP-AppSz-F</b>: First application access from network zone<br> ↳ <b>APP-AT-PRIV</b>: Non-privileged user performing privileged application activity<br> ↳ <b>APP-AppED-F</b>: New Email-domain found in application<br><br><b>T1133 - External Remote Services</b><br> ↳ <b>UA-UI-F</b>: First activity from ISP<br> ↳ <b>UA-UC-new</b>: Abnormal country for user by new user<br> ↳ <b>UA-GC-new</b>: Abnormal country for group by new user<br> ↳ <b>UA-OC-new</b>: Abnormal country for organization by new user<br> ↳ <b>UA-UC-Suspicious</b>: Activity from suspicious country<br> ↳ <b>UA-UC-Two</b>: Activity from two different countries<br> ↳ <b>UA-UC-Three</b>: Activity from 3 different countries                                                                                                                                                                                                                                   |  • <b>APP-AppED</b>: Email-domains per application<br> • <b>APP-AT-PRIV</b>: Privileged application activities<br> • <b>APP-AppSz</b>: Source zones per application<br> • <b>APP-OMime</b>: Mime types for organization<br> • <b>APP-GMime</b>: Mime types per peer group<br> • <b>APP-UMime</b>: Mime types per user<br> • <b>APP-IdU</b>: User per Client Id<br> • <b>APP-UId</b>: Client Id per User<br> • <b>APP-AA</b>: Activity per application<br> • <b>APP-GappA</b>: Application activity per peer group<br> • <b>APP-UappA</b>: Application activity per user<br> • <b>APP-UOb</b>: Application objects per user<br> • <b>APP-UsH</b>: User's machines accessing applications<br> • <b>APP-UOs-New</b>: OS and Browser from user agent<br> • <b>APP-UAg</b>: User Agent Strings<br> • <b>APP-UTi</b>: Application activity time for user<br> • <b>APP-GApp</b>: Group Logons to Applications<br> • <b>APP-AppG</b>: Groups per Application<br> • <b>APP-AppU</b>: User Logons to Applications<br> • <b>APP-UApp</b>: Applications per User<br> • <b>UA-OC</b>: Countries for organization<br> • <b>UA-GC</b>: Countries for peer groups<br> • <b>UA-UC</b>: Countries for user activity<br> • <b>UA-UI-new</b>: ISP of users during application activity |
| app-login           | <b>T1078 - Valid Accounts</b><br> ↳ <b>UA-UI-F</b>: First activity from ISP<br> ↳ <b>UA-UC-new</b>: Abnormal country for user by new user<br> ↳ <b>UA-GC-new</b>: Abnormal country for group by new user<br> ↳ <b>UA-OC-new</b>: Abnormal country for organization by new user<br> ↳ <b>UA-UC-Suspicious</b>: Activity from suspicious country<br> ↳ <b>UA-UC-Two</b>: Activity from two different countries<br> ↳ <b>UA-UC-Three</b>: Activity from 3 different countries<br> ↳ <b>APP-UApp-F</b>: First login or activity within an application for user<br> ↳ <b>APP-UApp-A</b>: Abnormal login or activity within an application for user<br> ↳ <b>APP-AppU-F</b>: First login to an application for a user with no history<br> ↳ <b>APP-F-SA-NC</b>: New service account access to application<br> ↳ <b>APP-AppG-F</b>: First login to an application for group<br> ↳ <b>APP-GApp-A</b>: Abnormal login to an application for group<br> ↳ <b>APP-UTi</b>: Abnormal user activity time<br> ↳ <b>APP-UAg-F</b>: First user agent string for user<br> ↳ <b>APP-UAg-2</b>: Second new user agent string for user<br> ↳ <b>APP-UAg-3</b>: More than two new user agents used by the user in the same session<br> ↳ <b>APP-UOs-F</b>: First os/browser combination for user<br> ↳ <b>APP-UsH-F</b>: First source asset for user in application<br> ↳ <b>APP-UsH-A</b>: Abnormal source asset for user in application<br> ↳ <b>APP-UId-F</b>: First use of client Id for user<br> ↳ <b>APP-IdU-F</b>: Reuse of client Id<br> ↳ <b>APP-AppSz-F</b>: First application access from network zone<br> ↳ <b>APP-AppED-F</b>: New Email-domain found in application<br><br><b>T1133 - External Remote Services</b><br> ↳ <b>UA-UI-F</b>: First activity from ISP<br> ↳ <b>UA-UC-new</b>: Abnormal country for user by new user<br> ↳ <b>UA-GC-new</b>: Abnormal country for group by new user<br> ↳ <b>UA-OC-new</b>: Abnormal country for organization by new user<br> ↳ <b>UA-UC-Suspicious</b>: Activity from suspicious country<br> ↳ <b>UA-UC-Two</b>: Activity from two different countries<br> ↳ <b>UA-UC-Three</b>: Activity from 3 different countries                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |  • <b>APP-AppED</b>: Email-domains per application<br> • <b>APP-AppSz</b>: Source zones per application<br> • <b>APP-IdU</b>: User per Client Id<br> • <b>APP-UId</b>: Client Id per User<br> • <b>APP-UsH</b>: User's machines accessing applications<br> • <b>APP-UOs-New</b>: OS and Browser from user agent<br> • <b>APP-UAg</b>: User Agent Strings<br> • <b>APP-UTi</b>: Application activity time for user<br> • <b>APP-GApp</b>: Group Logons to Applications<br> • <b>APP-AppG</b>: Groups per Application<br> • <b>APP-AppU</b>: User Logons to Applications<br> • <b>APP-UApp</b>: Applications per User<br> • <b>UA-OC</b>: Countries for organization<br> • <b>UA-GC</b>: Countries for peer groups<br> • <b>UA-UC</b>: Countries for user activity<br> • <b>UA-UI-new</b>: ISP of users during application activity                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| failed-app-login    | <b>T1078 - Valid Accounts</b><br> ↳ <b>APP-F-FL</b>: Failed login to application                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| network-alert       | <b>T1027.005 - Obfuscated Files or Information: Indicator Removal from Tools</b><br> ↳ <b>A-ALERT-Other</b>: Alert on asset<br> ↳ <b>A-ALERT-Critical</b>: Security Alert on a critical asset<br> ↳ <b>A-IDS-OLA-F</b>: First network alert on asset with no previous alerts for organization<br> ↳ <b>A-IDS-OLA-A</b>: Abnormal network alert for asset for organization<br> ↳ <b>A-IDS-ZLA-F</b>: First network alert on asset with no previous alerts for zone<br> ↳ <b>A-IDS-ZLA-A</b>: Abnormal network alert for asset for zone<br> ↳ <b>A-IDS-OLZ-F</b>: First network alert for zone in the organization<br> ↳ <b>A-IDS-OLZ-A</b>: Abnormal network alert for zone in the organization<br> ↳ <b>A-IDS-OdPort-F</b>: First network alert on port for organization<br> ↳ <b>A-IDS-OdPort-A</b>: Abnormal network alert on port for organization<br> ↳ <b>A-IDS-HdPort-F</b>: First network alert on port for asset<br> ↳ <b>A-IDS-HdPort-A</b>: Abnormal network alert on port for asset<br> ↳ <b>A-IDS-dZdPort-F</b>: First network alert on port for zone<br> ↳ <b>A-IDS-dZdPort-A</b>: Abnormal network alert on port for zone<br> ↳ <b>A-IDS-LZAN-F</b>: First network alert (by name) for zone<br> ↳ <b>A-IDS-LZAN-A</b>: Abnormal network alert (by name) for zone<br> ↳ <b>A-IDS-OAN-F</b>: First network alert (by name) for organization<br> ↳ <b>A-IDS-OAN-A</b>: Abnormal network alert (by name) for organization<br> ↳ <b>A-IDS-SERVER</b>: First or Abnormal network alert in server zone                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |  • <b>A-AL-ZT-SERVER</b>: Server zones based on number of servers<br> • <b>A-IDS-OAN</b>: Network alert names triggered in the organization<br> • <b>A-IDS-LZAN</b>: Network alert names triggered in zone<br> • <b>A-IDS-dZdPort</b>: Destination ports on which network alerts have triggered in zone<br> • <b>A-IDS-HdPort</b>: Destination ports on which network alerts have triggered for the asset<br> • <b>A-IDS-OdPort</b>: Destination ports on which network alerts have triggered in the organization<br> • <b>A-IDS-OLZ</b>: Zones in which network alerts are triggered in the organization<br> • <b>A-IDS-ZLA</b>: Assets that triggered network alerts in the zone                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| process-alert       | <b>TA0002 - TA0002</b><br> ↳ <b>EPA-UP-ALERT-F</b>: First security alert for executing this process by the user<br> ↳ <b>EPA-UP-ALERT-A</b>: Abnormal security alert for executing this process by the user<br> ↳ <b>EPA-UP-ALERT-N</b>: Common security alert for executing this process by the user<br> ↳ <b>EPA-UH-Pen-F</b>: Known pentest tool used<br><br><b>T1027.005 - Obfuscated Files or Information: Indicator Removal from Tools</b><br> ↳ <b>A-ALERT-Other</b>: Alert on asset<br> ↳ <b>A-ALERT-Critical</b>: Security Alert on a critical asset                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |  • <b>EPA-UH-Pen</b>: Malicious tools used by user<br> • <b>EPA-UP-ALERT</b>: Processes that triggered alerts for the user                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| web-activity-denied | <b>T1071.001 - Application Layer Protocol: Web Protocols</b><br> ↳ <b>A-WEB-HA-F</b>: First web activity event on asset<br> ↳ <b>A-WEB-DC</b>: Web activity event on a Domain Controller<br> ↳ <b>A-WEBF-IP-Country-F</b>: Asset failed to directly connect to an IP address in a country never before accessed<br> ↳ <b>A-WEBF-IP-Country-A</b>: Abnormal direct access to an IP address by the asset belonging to an abnormal country for the asset to access has failed<br> ↳ <b>A-NETF-HCountry-Outbound-WEB-F</b>: First failed web browsing connection to this country from asset<br> ↳ <b>A-NETF-HCountry-Outbound-WEB-A</b>: Web browsing connection to abnormal country for asset has failed<br> ↳ <b>A-NETF-OCountry-Outbound-WEB-F</b>: First failed web browsing connection to this country from organization<br> ↳ <b>A-NETF-OCountry-Outbound-WEB-A</b>: Web browsing connection to abnormal country for the organization has failed<br> ↳ <b>WEB-UD-Reputation-F</b>: First access to this web domain which has been identified as risky by a reputation feed.<br> ↳ <b>WEB-UD-Reputation-A</b>: Abnormal access to this web domain which has been identified as risky by a reputation feed.<br> ↳ <b>WEB-UI-Reputation-F</b>: First access to this internet IP address which has been identified as risky by a reputation feed.<br> ↳ <b>WEB-UI-Reputation-A</b>: Abnormal access to this IP address which has been identified as risky by a reputation feed.<br> ↳ <b>WEB-UD-ALERT-F</b>: First security alert accessing this malicious domain for user<br> ↳ <b>WEB-UD-ALERT-A</b>: Abnormal security alert accessing this malicious domain for user<br> ↳ <b>WEB-UD-ALERT-N</b>: Common security alert on this malicious domain for user<br> ↳ <b>WEB-UT-TOW-A</b>: Abnormal day for this user to access the web via the organization<br> ↳ <b>WEB-UZ-F</b>: First web activity for this user in this zone<br> ↳ <b>WEB-GZ-F</b>: First web activity from this zone for the peer group<br> ↳ <b>WEB-OZ-F</b>: First web activity from this zone for the organization<br> ↳ <b>WEB-ALERT-EXEC</b>: Security violation by Executive in web activity<br> ↳ <b>WEB-URank-F</b>: First web activity to this low ranked web domain<br> ↳ <b>WEB-URank-A</b>: Abnormal web activity to this low ranked web domain<br> ↳ <b>WEB-Fail-10</b>: Failed to access 10 websites.<br> ↳ <b>WEB-IPF-Country-F</b>: User has failed trying to directly browse to an IP address belonging to a country never before accessed<br><br><b>T1189 - Drive-by Compromise</b><br> ↳ <b>WEB-URank-Binary</b>: Executable download from first low ranked web domain<br><br><b>T1204.001 - T1204.001</b><br> ↳ <b>WEB-URank-Binary</b>: Executable download from first low ranked web domain<br><br><b>T1566.002 - Phishing: Spearphishing Link</b><br> ↳ <b>WEB-URank-Binary</b>: Executable download from first low ranked web domain<br><br><b>T1078 - Valid Accounts</b><br> ↳ <b>WEB-ALERT-EXEC</b>: Security violation by Executive in web activity<br><br><b>T1568.002 - Dynamic Resolution: Domain Generation Algorithms</b><br> ↳ <b>WEB-UD-DGA-F</b>: First access to this domain which has been identified as DGA<br> ↳ <b>WEB-UD-DGA-A</b>: Abnormal access to this domain which has been identified as DGA<br><br><b>T1102 - Web Service</b><br> ↳ <b>A-WEB-DC</b>: Web activity event on a Domain Controller |  • <b>WEB-URank</b>: Web activity to low ranked domains for the user<br> • <b>WEB-OZ</b>: Network zones where users performs web activity in the organization<br> • <b>WEB-GZ</b>: Network zones where users performs web activity in the peer group<br> • <b>WEB-UZ</b>: Network zones where a user performs web activity from<br> • <b>WEB-UT-TOW</b>: Web activity activity time for user<br> • <b>WEB-UD-ALERT</b>: Top malicious web domain accessed by the user<br> • <b>WEB-UI-Reputation</b>: Top ip addresses flagged by a reputation service that have been accessed by the user<br> • <b>WEB-UD-Reputation</b>: Top web domain flagged by a reputation service that have been accessed by the user<br> • <b>WEB-UD-DGA</b>: Top web domains per user that seem to be DGA generated during web activity<br> • <b>A-NET-OCountry-Outbound</b>: Outbound country per organization<br> • <b>A-NET-HCountry-Outbound</b>: Outbound country per asset<br> • <b>A-WEB-IP</b>: IPs an asset has directly browsed to                                                                                                                                                                                                                                             |