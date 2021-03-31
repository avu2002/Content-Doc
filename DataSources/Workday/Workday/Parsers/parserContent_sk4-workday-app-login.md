#### Parser Content
```Java
{
Name = sk4-workday-app-login
  DataType = "app-login"
  Conditions = [ """sk4-login-success""","""cat=access""","""workday"""]
  Fields = ${WorkdayParserTemplates.sk4-workday-login-template.Fields}[]
}
sk4-workday-login-template = {
    Vendor = Workday
    Product =  Workday
    Lms = Splunk
    TimeFormat = "epoch"
    Fields = [
      """exabeam_host=({host}[\w.\-]+)""",
      """exabeam_time=({time}\d\d\d\d-\d\d-\d\d \d\d:\d\d:\d\d)""",
      """destinationServiceName=({app}[^ ]+)""",
      """dproc=({host}[^\s]+)\s+\w+=""",
      """msg=({additional_info}[^=]+?)\s\w+=.""",
      """src=({src_ip}\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3})""",
      """suser=;?({user}[^\s;]+)""",
      """"+authenticationType"+:"+({auth_method}[^"]+)"+""",
      """"authenticationChannel"+:"+({auth_method}[^"]+)""",
      """"signonDateTime"+:({time}\d+)""",
      """([^\|]*\|){5}({activity}[^\|]+)""",
      """\Wdproc=(|({dproc}[^=]+?))(\s+\w+=|\s*$)""",
    ]

```