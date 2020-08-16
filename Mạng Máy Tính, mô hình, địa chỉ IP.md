# Mạng Máy Tính


## 1. Mạng máy tính là gì ?
- Là 1 mạng lưới cho phép các máy tính chia sẻ tài nguyên qua đường truyền mạng qua dây mạng , đường cáp quang, các phương tiện không dây như wifi.
- Mạng máy tính gồm 3 thành phần chính: máy tính, các thiết bị mạng cho phép kết nối mạng với nhau và các phần mềm , ứng dụng cho phép trao đổi thông tin qua mạng với nhau giữa các máy tính.
## 2. Mô hình mạng.

**a)** Mô hình mạng WorkGroup: là mô hình máy tính chia sẻ tài nguyên dữ liệu máy tính , máy in với nhau. Mô hình này việc chia sẻ tài nguyên giữa các máy tính sẽ không chịu sự kiểm soát của máy server , nói dễ hiểu thì là mô hình này được coi là mô hình peer to peer. Mỗi máy tính đều tự bảo trì , bảo mật giữ liệu của mình, và có thể liên kết thêm những nhóm mới.
![](https://i.imgur.com/vxU3rU8.png)
**b)** Mô hình mạng Domain: là mô hình mà các máy tính chia sẻ dữ liệu theo 1 cách tập chung. Và sẽ có 1 máy được cấu hình Domain controller, máy được cấu hình Domain controller sẽ có tất cả các đặc quyền quản lý các máy client hay các máy member dưới nó. Việc tham gia vào mô hình mạng domain thì máy chủ ( Domain controller) sẽ phải là người tham gia đầu tiên và mỗi máy tiếp theo tham gia sẽ phải được tạo 1 user với những quyền mà do máy chủ cấp cho.
- có 3 thành miền điển hình trong mô hình Domain : đó là máy điều khuyển miền ( domain controller), máy chủ thành viên ( member sever), máy thành viên ( clinet computer).
![](https://i.imgur.com/Saf6245.png)

## 3. Địa chỉ IP
- Địa chỉ IP(internet protocol) nói ngắn gon thì nó là địa chỉ giao thức của internet. Giúp các máy tính cho thể nhận ra nhau , nó tương tự như địa chỉ nhà vậy. Khi bạn muốn giao tiếp với 1 máy tính nào đó bạn phải biết được địa chỉ IP của máy tính đó.
- Bạn có thể nhập tên miền DNS của địa chỉ ip đó , và nó sẽ truy vấn đến DNS server rồi trả ngược lại địa chỉ IP của tên miền đó là gì.
## 4. IP public và IP private.
- IP public: là địa chỉ mà nhà mạng cung chấp cho chúng ta, khi ta muốn giao tiếp qua mạng với 1 máy tính khác thì ta cần phải giao tiếp qua địa chỉ ip public của máy tính đó.
- IP private: là địa chỉ trong mạng lan, không thể kết nối ra ngoài mạng. Địa chỉ này chỉ có thể giao tiếp trong nội bộ, được cấu hình bằng tay hoặc các bộ định tuyến sẽ tự động cấp cho từng máy.
