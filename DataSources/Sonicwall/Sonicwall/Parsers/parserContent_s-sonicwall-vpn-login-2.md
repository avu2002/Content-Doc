#### Parser Content
```Java
{
Name = s-sonicwall-vpn-login-2
  Product = Sonicwall
  DataType = "vpn-login"
  Conditions = [ """ m=1080 """, """id=""", """ usr=""", """ fw=""","""sslvpn"""]
  Fields = ${SonicwallParserTemplates.sonicwall-vpn-login.Fields} [
    """({outcome}allowed)"""
  ]
}
sonicwall-vpn-login = {
  Vendor = Sonicwall
  Lms = Splunk
  TimeFormat = "yyyy-MM-dd HH:mm:ss"
  Fields = [
    """exabeam_host=([^=]+@\s*)?({host}\S+)""",
    """\d\d:\d\d:\d\d ({host}[^\s]+)\sSSLVPN:""",
    """\stime="({time}\d\d\d\d\-\d\d\-\d\d \d\d:\d\d:\d\d)""",
    """\ssrc=({src_ip}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3})(:({src_port}\d+))?(:({src_interface}[^\s:]+))?(:({src_host}[^\s:]+))?""",
    """\sdst=({dest_ip}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3})(:({dest_port}\d+))?(:({dest_interface}[^\s:]+))?(:({dest_host}[^\s:]+))?""",
    """\suser="\s*(({user_email}[^@"]+@[^\\\s"]+)|({user}[^\\\s"]+))""",
    """\susr="\s*(({user_email}[^@"]+@[^\\\s"]+)|({user}[^\\\s"]+))\s*"""",
    """\sproto=({protocol}\S+)""",
    """\sdomain="({domain}[^"]+)"""",
    """\sportal="({realm}[^"]+)"""",
    """\sagent="({user_agent}[^"]+)"""",
    """\sduration=({session_duration}\d+)""",
    """\sbytesIn=({bytes_in}\d+)""",
    """\sbytesOut=({bytes_out}\d+)""",
    """\sbytesTotal=({bytes}\d+)"""
  ]

```