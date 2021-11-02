#### Parser Content
```Java
{
Name = s-lanscope-web-activity
  Vendor = LanScope
  Product = LanScope Cat
  Lms = Splunk
  DataType = "web-activity"
  IsHVF = true
  TimeFormat = "yyyy-MM-dd HH:mm:ss"
  Conditions = [ """"Webアクセスログ"""" ]
  Fields = [
     ""","{0,20}(|({host}[^"]{1,2000}))"{0,20},"{0,20}(|({user}[^"]{1,2000}))"{0,20},"{0,20}({time}\d\d\d\d-\d\d-\d\d \d\d:\d\d:\d\d)"{0,20},"{0,20}[^"]{0,2000}"{0,20},"{0,20}(|({activity}[^"]{1,2000}))"{0,20},("{0,20}[^"]{0,2000}"{0,20},){5}"{0,20}(|({window_title}[^"]{1,2000}))"{0,20},"{0,20}(|({full_url}(\w+:\/+)?({web_domain}[^"\/]{0,2000}?([^"\.\/]{1,2000}))({uri_path}\/[^"\?]{0,2000})?({uri_query}\?[^"]{0,2000})?))"{0,20},""""
  ]
}
```