# Create-subdomian-fortest
##Crate subdomain
### step 1: Clone wilfly server
### step 2: sửa file host máy trong C:\Windows\System32\drivers\etc:
#### 172.16.0.120 trieunv.vn
####172.16.0.120 18095.trieunv.vn
####Trong đó: 172.16.0.120 là local ip (chạy ipconfig đề lấy)
####18095.trieunv.vn và trieunv.vn là domain
#### Chạy 2 lệnh ipconfig /flushdns; ipconfig /renew
### step 2: Thay đổi đoạn xml trong E:\Project\wildfly-8.2.0. Test Local\standalone\configuration\standalone.xml
### step 3: copy các file buil từ server buil trong ~\wildfly\standalone\deployments\* vào ~\wildfly Test Local\standalone\deployments
