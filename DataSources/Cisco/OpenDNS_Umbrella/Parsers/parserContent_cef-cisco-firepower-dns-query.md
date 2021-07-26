#### Parser Content
```Java
{
Name = cef-cisco-firepower-dns-query
  DataType = "dns-query"
  Conditions = [ """|Cisco|""" , """|Firepower|""","""|CONNECTION STATISTICS|""", """destinationDnsDomain=""" ]
  Fields = ${CiscoParsersTemplates.cisco-firepower-events.Fields}[
  """destinationDnsDomain=({query}[^\s]+)""",
  ]
}
cisco-firepower-events = {
  Vendor = Cisco
  Product = Cisco Firepower
  Lms = Direct
  IsHVF = true
  TimeFormat = "yyyy-MM-dd'T'HH:mm:ss.SSSZ"
  Fields = [
    """@timestamp[":]*({time}\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\d.\d\d\dZ)""",
    """"host[":]*({host}[^"]+)""",
    """act=({action}[^\s]+)""",
    """reason=(?:N\/A|({failure_reason}[^\s]+))""",
    """deviceInboundInterface=({src_interface}[^\s]+)\s*deviceOutboundInterface=({dest_interface}[^\s]+)""",
    """app=(?:Unknown|({app}[^\s]+))""",
    """bytesIn=({bytes_in}\d+)\s*bytesOut=({bytes_out}\d+)""",
    """proto=({protocol}[^\s]+)""",
    """cs1=({policy}[^\s]+)""",
    """cs2=({rule}[^\s]+)""",
    """cs5Label=({category}[^\s]+)""",
    """dpt=({dest_port}\d+)\s*dst=({dest_ip}[A-Fa-f:\d.]+)""",
    """request=({url}[^\s]+)""",
    """spt=({src_port}\d+)\s*src=({src_ip}[A-Fa-f:\d.]+)""",
    """user=(?:No Authentication Required|({user}[^"\s]+))""",
        ]

```