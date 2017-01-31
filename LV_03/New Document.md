## CHIA IP ##


## CÁC THỨ CẦN NHỚ ##

**BẢNG 1**

00000000 --- 0

10000000 --- 128

11000000 --- 192

11100000 --- 224

11110000 --- 240

11111000 --- 248

11111100 --- 252

11111110 --- 254

11111111 --- 255


**BẢNG 2**

Gọi n : số bit mượn --> ** bước nhảy = 2^(8-n)

Số bit mượn:  1     2    3   4   5   6   7    8

Bước nhảy  :  128   64   32  16  8   4   2    1

**1. CẤU TRÚC CỦA MỘT ĐỊA CHỈ IP**

![](https://www.adminvietnam.org/wp-content/uploads/2016/10/IP-address-format.jpg)

- Cấc bit phần mạng không được phép đồng thời bằng 
- Nếu tất cả các bit phần Host = 0 ---> đại chỉ mạng
- Nếu tất cả các nit phần Host = 1 ----> ta có địa chỉ Broadcast)
** Địa chỉ Broadcast : là địa chỉa đại diện cho tất các các địa chỉ cho tất cả các Host trong mạng đó**

**2. CÁC LỚP ĐỊA CHỈ MẠNG**

![](https://voer.edu.vn/file/31712)

# ĐIẠ CHỈ LỚP A #

![](https://3.bp.blogspot.com/-nwIyxBDNQLk/VsfkguwPAUI/AAAAAAAAAYI/bvoUGDVgyzY/s1600/lopA.png)

- **Địa chỉ mạng :1.0.0.0 đến 127.0.0.0**
- Mạng 127.0.0.0: Loopback Network
- Định chỉ mạng sử dụng được : 1.0.0.0 đến 126.0.0.0 ( 126 mạng )
- Phần Host: 24 bit --> Mỗi mạng lớp A có 2^24 -2 Host.

# ĐỊA CHỈ LỚP B #

![](https://1.bp.blogspot.com/-BmtROjZT4RI/VsflOjrf5CI/AAAAAAAAAYQ/fsNZ44ofyXk/s1600/lopB.png)

- **Địa chỉ mạng: 128.0.0.0 đến 191.255.0.0**
- Có tất cả 2^16 mạng trọng lớp B
- Phần Host: 16 bit 
- Một mạng lớp B có 2^16 - 2 Host

# ĐỊA CHỈ LỚP C #

![](https://2.bp.blogspot.com/-2CLMRCLT7Ms/VsfmYgwYKoI/AAAAAAAAAYc/lOyrsX-JdrM/s1600/lopC.png)

- **Địa chỉ mạng : 192.0.0.0 đến 223.255.255.0**
- Có tất cả 2^21 mạng trong lớp C
- Phần Host: 8 bit
- Một mạng lớp C có 2^8 - 2 Host = 254 Host

# ĐỊA CHỈ LỚP D #

- **Địa chỉ 224.0.0.0 đến 239.255.255.255**
- Địa chỉ Multicast
- Ví dụ: 224.0.0.5 dùng cho OSPF
- Ví dụ: 224.0.0.9 dùng cho RIPv2

# ĐỊA CHỈ LỚP E #

- **Từ 240.0.0.0 trở đi**
- Gọi là mạng dự phòng

# ĐỊA CHỊ QUẢNG BÁ ( Broadcast ) #

- Direct : VD 192.168.1.255
- Local : VD 255.255.255.255


# SUBNET - MARK #

192.168.1.1

255.255.255.0

Dùng để khai báo địa chỉ IP cho máy biết nó thuộc lớp mạng nào

# Prefix - Length #

A.B.C.D /n 

n: Số bit mạng trong địa chỉ IP




