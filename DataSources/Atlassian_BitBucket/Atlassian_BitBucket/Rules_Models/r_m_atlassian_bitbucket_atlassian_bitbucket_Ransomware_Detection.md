Vendor: Atlassian BitBucket
===========================
### Product: [Atlassian BitBucket](../ds_atlassian_bitbucket_atlassian_bitbucket.md)
### Use-Case: [Ransomware Detection](../../../../UseCases/uc_ransomware_detection.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   3   |   0    |     1      |      1      |    1    |

| Event Type   | Rules                                                                                                                                                                                                                                                                                      | Models |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------ |
| app-activity | <b>T1188 - T1188</b><br> ↳ <b>Auth-Tor-Shost</b>: User authentication or login from a known TOR IP<br> ↳ <b>Auth-Blacklist-Shost</b>: User authentication or login from a known blacklisted IP<br> ↳ <b>Auth-Ransomware-Shost</b>: User authentication or login from a known ransomware IP |        |