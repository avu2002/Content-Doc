Vendor: VMware
==============
### Product: [Endpoint Detection and Response](../ds_vmware_endpoint_detection_and_response.md)
### Use-Case: [Compromised Credentials](../../../../UseCases/uc_compromised_credentials.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  56   |   17   |     10     |      3      |    3    |

| Event Type      | Rules                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | Models                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| process-alert   | <b>T1003 - OS Credential Dumping</b><br> ↳ <b>EPA-UH-Pen-F</b>: Known pentest tool used<br><br><b>T1204 - User Execution</b><br> ↳ <b>EPA-UP-ALERT-N</b>: Common security alert for executing this process by the user<br><br><b>T1027.005 - Obfuscated Files or Information: Indicator Removal from Tools</b><br> ↳ <b>A-ALERT-Other</b>: Alert on asset<br> ↳ <b>A-ALERT-Critical</b>: Security Alert on a critical asset                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |  • <b>EPA-UH-Pen</b>: Malicious tools used by user<br> • <b>EPA-UP-ALERT</b>: Processes that triggered alerts for the user                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| process-created | <b>T1003.003 - T1003.003</b><br> ↳ <b>PC-Process-Hash-F</b>: First time process path creation with this hash<br> ↳ <b>PC-Process-Hash-A</b>: Abnormal for process path creation with this hash<br><br><b>T1040 - Network Sniffing</b><br> ↳ <b>A-EPA-SNIFF</b>: Network sniffing tool has been found running on this asset<br> ↳ <b>A-EPA-OH-SNIFF-F</b>: First time this asset has had an execution of a network sniffing tool<br> ↳ <b>A-EPA-OH-SNIFF-A</b>: Abnormal asset running network sniffing tool<br> ↳ <b>A-EPA-OZ-SNIFF-F</b>: First zone on which network sniffing tool was run<br> ↳ <b>A-EPA-OZ-SNIFF-A</b>: Abnormal zone on which network sniffing tool was run<br> ↳ <b>EPA-SNIFF</b>: Network sniffing tool has been run by this user<br> ↳ <b>EPA-OU-SNIFF-F</b>: First time this user has run a network sniffing tool<br> ↳ <b>EPA-OU-SNIFF-A</b>: Abnormal user has run a network sniffing tool<br> ↳ <b>EPA-OG-SNIFF-F</b>: First time this peer group has run a network sniffing tool<br> ↳ <b>EPA-OG-SNIFF-A</b>: Abnormal peer group running a network sniffing tool<br> ↳ <b>EPA-OH-SNIFF-F</b>: First time this host has run a network sniffing tool<br> ↳ <b>EPA-OH-SNIFF-A</b>: Abnormal host running a network sniffing tool<br> ↳ <b>EPA-OZ-SNIFF-F</b>: First time this network zone on which a networking sniffing tool run.<br> ↳ <b>EPA-OZ-SNIFF-A</b>: Abnormal network zone on which network sniffing tool was run<br> ↳ <b>NSniff-Cred</b>: Potential network sniffing was observed<br><br><b>T1003 - OS Credential Dumping</b><br> ↳ <b>EPA-UH-Pen-F</b>: Known pentest tool used<br> ↳ <b>Mimikatz-process</b>: A highly dangerous attacker tool, Mimikatz, has been used<br> ↳ <b>Rubeus-CMD-Tool</b>: Command line parameters used by Rubeus hack tool detected<br> ↳ <b>CP-Sensitive-Files</b>: Copying sensitive files with credential data<br> ↳ <b>CreateMiniDump-Hacktool</b>: CreateMiniDump Hacktool<br> ↳ <b>LSASS-Mem-Dump</b>: LSASS Memory Dumping<br> ↳ <b>Proc-Dump-Comsvcs</b>: Process Dump via Rundll32 and Comsvcs.dll<br> ↳ <b>AD-Diagnostic-Tool</b>: Invocation of Active Directory Diagnostic Tool (ntdsutil.exe)<br> ↳ <b>Sus-Procdump</b>: Suspicious Use of Procdump<br> ↳ <b>GRAB-REG-HIVES</b>: Grabbing Sensitive Hives via Reg Utility<br> ↳ <b>ShadowCP-OSUtilities</b>: Shadow Copies Creation Using Operating Systems Utilities<br> ↳ <b>Procdump-Comsvcs-DLL</b>: Process Dump via Comsvcs DLL<br> ↳ <b>Cmdkey-Cred-Recon</b>: Cmdkey Cached Credentials Recon<br><br><b>T1036 - Masquerading</b><br> ↳ <b>Proc-Dump-Comsvcs</b>: Process Dump via Rundll32 and Comsvcs.dll<br> ↳ <b>Sus-Procdump</b>: Suspicious Use of Procdump<br><br><b>T1547.004 - T1547.004</b><br> ↳ <b>SecX-Tool-Exec</b>: SecurityXploded Tool execution detected<br><br><b>T1016 - System Network Configuration Discovery</b><br> ↳ <b>WINCMD-Ipconfig</b>: 'Ipconfig' program used<br> ↳ <b>WINCMD-Route</b>: 'Route' program used<br> ↳ <b>WINCMD-Netsh</b>: 'Netsh' program used |  • <b>PC-Process-Hash</b>: Hashes used to create processes.<br> • <b>EPA-OZ-SNIFF</b>: Network Zones on which network sniffing tools are run<br> • <b>EPA-OH-SNIFF</b>: Hosts that have been found to be running network sniffing tools<br> • <b>EPA-OG-SNIFF</b>: Peer groups that are running network sniffing tools<br> • <b>EPA-OU-SNIFF</b>: Users that are running network sniffing tools<br> • <b>EPA-UH-Pen</b>: Malicious tools used by user                                                                                                                                                                                                                                                                |
| security-alert  | <b>T1078 - Valid Accounts</b><br> ↳ <b>A-SA-AN-ALERT-F</b>: First security alert name on the asset<br> ↳ <b>A-SA-ON-ALERT-F</b>: First security alert (by name) in the organization<br> ↳ <b>A-SA-ON-ALERT-A</b>: Abnormal security alert (by name) in the organization<br> ↳ <b>A-SA-ZN-ALERT-F</b>: First security alert (by name) in the zone<br> ↳ <b>A-SA-ZN-ALERT-A</b>: Abnormal security alert (by name) in the zone<br> ↳ <b>A-SA-HN-ALERT-F</b>: First security alert (by name) in the asset<br> ↳ <b>A-SA-HN-ALERT-A</b>: Abnormal security alert (by name) in the asset<br> ↳ <b>A-SA-OA-ALERT-F</b>: First security alert for this asset for organization<br> ↳ <b>SA-OU-ALERT-F</b>: First security alert triggered for this user in the organization<br> ↳ <b>SA-OU-ALERT-A</b>: Abnormal user triggering security alert in the organization<br> ↳ <b>SA-OG-ALERT-F</b>: First security alert triggered for peer group in the organization<br> ↳ <b>SA-OG-ALERT-A</b>: Abnormal peer group triggering security alert in the organization<br> ↳ <b>SA-UA-F</b>: First security alert name for user<br> ↳ <b>SA-UA-A</b>: Abnormal security alert name for user<br> ↳ <b>SA-GA-F</b>: First security alert name in the peer group<br> ↳ <b>SA-GA-A</b>: Abnormal security alert name in the peer group<br> ↳ <b>SA-OA-F</b>: First security alert name in the organization<br> ↳ <b>SA-OA-A</b>: Abnormal security alert name in the organization<br><br><b>T1133 - External Remote Services</b><br> ↳ <b>ALERT-VPN</b>: Security Alert on asset accessed by this user during VPN session<br><br><b>T1027.005 - Obfuscated Files or Information: Indicator Removal from Tools</b><br> ↳ <b>A-ALERT-Critical</b>: Security Alert on a critical asset                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |  • <b>SA-OA</b>: Security alert names in the organization<br> • <b>SA-GA</b>: Security alert names in the peer group<br> • <b>SA-UA</b>: Security alert names for user<br> • <b>SA-OG-ALERT</b>: Peer groups triggering security alerts in the organization<br> • <b>SA-OU-ALERT</b>: Users triggering security alerts in the organization<br> • <b>A-SA-OA-ALERT</b>: Assets triggering security alerts in the organization<br> • <b>A-SA-HN-ALERT</b>: Security alert names triggered by the asset<br> • <b>A-SA-ZN-ALERT</b>: Security alert names triggered in the zone<br> • <b>A-SA-ON-ALERT</b>: Security alert names triggered in the organization<br> • <b>A-SA-AN-ALERT</b>: Security alert names on asset |