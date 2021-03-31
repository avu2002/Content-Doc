Vendor: BlueCoat
================
### Product: [BlueCoat](../ds_bluecoat_bluecoat.md)
### Use-Case: [Phishing](../../../../UseCases/uc_phishing.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   7   |   0    |     3      |      1      |    1    |

| Event Type           | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | Models |
| -------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| web-activity-allowed | <b>T1071.001 - Application Layer Protocol: Web Protocols</b><br> ↳ <b>A-WEB-Reputation-URL</b>: Asset attempted access to a url with bad reputation<br> ↳ <b>A-WEB-Reputation-Domain</b>: Asset attempted access to a domain with bad reputation<br> ↳ <b>A-WEB-Reputation-IP</b>: Asset attempted to connect to IP address with bad reputation<br> ↳ <b>A-WEB-IOC</b>: Indicator of Compromise (IOC) found in asset's web activity<br> ↳ <b>A-WEB-ALERT</b>: Asset attempted access to a domain with malicious reputation<br><br><b>T1568 - Dynamic Resolution</b><br> ↳ <b>A-WEB-DynamicDNS</b>: Asset attempted access to a domain generated using Dynamic DNS service<br><br><b>T1071.001 - Application Layer Protocol: Web Protocols</b><b>T1566.002 - Phishing: Spearphishing Link</b><br> ↳ <b>A-WEB-Phishing</b>: Asset has accessed a domain suspected to be a phishing domain. |        |