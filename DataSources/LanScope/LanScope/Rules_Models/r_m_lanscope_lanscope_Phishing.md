Vendor: LanScope
================
### Product: [LanScope](../ds_lanscope_lanscope.md)
### Use-Case: [Phishing](../../../../UseCases/uc_phishing.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   8   |   1    |     1      |      8      |    8    |

| Event Type           | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | Models |
| -------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| process-network      | <b>T1071 - Application Layer Protocol</b><br> ↳ <b>NET-TI-H-Outbound</b>: Outbound connection to a known malicious host                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |        |
| web-activity-allowed | <b>T1071 - Application Layer Protocol</b><br> ↳ <b>A-WEB-Reputation-URL</b>: Asset attempted access to a url with bad reputation<br> ↳ <b>A-WEB-Reputation-Domain</b>: Asset attempted access to a domain with bad reputation<br> ↳ <b>A-WEB-Reputation-IP</b>: Asset attempted to connect to IP address with bad reputation<br> ↳ <b>A-WEB-IOC</b>: Indicator of Compromise (IOC) found in asset's web activity<br> ↳ <b>A-WEB-ALERT</b>: Asset attempted access to a domain with malicious reputation<br> ↳ <b>A-WEB-Phishing</b>: Asset has accessed a domain suspected to be a phishing domain.<br> ↳ <b>A-WEB-DynamicDNS</b>: Asset attempted access to a domain generated using Dynamic DNS service |        |