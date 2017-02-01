## GIAO THUC TELNET ##

# GIAO THỨC CỦA TẤNG ỨNG DỤNG #

- Sử dụng TCP , Port:23
- Điều kiện: IP1 ping được đến IP2, Router phải mở cổng VTY 
       + R(config)#line vty 0 4
       + .....# password ****
       + ...# login
       


## GIAO THỨC CDP-cisco Discovery protocol ##

![](http://data.sinhvienit.net/lab1/CISCO/7_files/b10.jpg)

Là giao thức cho chúng ta biết được các router láng giềng của chúng ta đang kết nối với cổng số máy

Cứ 60s các thiết bị sẽ tự gửi thông tin qua láng giêng của nó bằng giao thucứ CDP 

CDP là giao thức cho biết thông tin các thiết bị kết nối trực tiếp với nó


- Cisco proprietary 
- kết nối giữa hai thiết bị phải thông nhau
- CDP: 
     + Hostname của láng giềng
     + Local-interface: cổng của mình đấu với láng giềng
     + Outgoinf port: cổng của láng giềng đấu với mình
     + Rlatform: cho biết router của láng gieng thuoc giồng nào
     + Capalibity: có chạy được giao thức R,S,I
     + Ip của láng giềng
     + IOS vesion 
  
- R# show cdp neighbcn
- R# show cdp neighbcn detail
- R#show cdp enty *
- r(config)#no cdp run
- r(config-if) no cdp enable


## SSH ##

- Applications
- TCP-22
- mã hóa