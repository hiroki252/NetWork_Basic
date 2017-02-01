## ĐỊNH TUYẾN  ##

# ROUTER OPERATIONS #

![](http://www.cisco.com/c/dam/en_us/about/ac123/ac147/images/ipj/ipj_4-3/figure1.gif)

- Router là một thiết bị layer 3. Có khả năng định tuyến và chặn roatcast ( chức năng chặn roatcast chỉ có ở trên mạng Lan mà thôi )
- Chức năng chính của Router là định tuyến ( Định tuyến là tìm ra một đường đi tối ưu từ điểm này đến điểm kia của mạng )

**Khi định tuyến cần**

- Cần biết điểm đến của gói tin
- Học nguồn gốc thông tin của một mạng khi truyền ( tức các Router sẽ thông báo cho nhau biết là đường truyền nào tối ưu nhất )
- Biết đường các đường đi đi đến đích ( để dự phòng )
- Chọn đường đi tối ưu
- Duy trùy đường đi định tuyến tối ưu
- Muốn truyền được gói tin thì bảng định tuyến phải có trong Router
- có hai cách mà Router có thể học là : Người quản trị sẽ chỉ cho con router biết hoặc là Con router sẽ học từ các con router khác
- Định tuyến tĩnh : người quản trị mạng sẽ chỉ ra đường đi cho Router
- Định tuyến động: Router chỉ cần học những thông tin của các con router khác mà thôi
- Định tuyến Tĩnh: Router sử dụng các nút mạng do người quản trị nhập vào
- Định tuyến động: Các nút mạng được học được thông qua các giao thức định tuyến do các router tự trao đổi thông tin với nhau

**Static Router**

![](http://www.learncisco.net/assets/images/icnd1/92-static-default-route.jpg)