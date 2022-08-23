#### Máy chủ DNS và máy chủ Proxy
- Máy chủ DNS có tên máy chủ, tên miền của địa chỉ email, v.v. liên quan đến thông tin địa chỉ IP.
- Sẽ không thể thực hiện truyền tin nếu bên kia được mô tả bằng tên máy chủ, tên miền, v.v. khi máy tính hoặc máy in thực hiện truyền tin bằng IP.
- Truy vấn máy chủ DNS để biết thông tin này và nhận địa chỉ IP của bên kia. Quá trình này được gọi là phân giải tên.
- Vì vậy, những thiết bị như máy tính và máy in có thể trao đổi thông tin bằng địa chỉ IP.
- Việc phân giải tên là cần thiết để máy in trao đổi thông tin bằng chức năng email hoặc chức năng kết nối Internet.
- Khi bạn sử dụng những chức năng này, hãy thiết lập cài đặt máy chủ DNS.
- Khi bạn gán địa chỉ IP của máy in bằng chức năng DHCP của máy chủ DHCP hoặc bộ định tuyến, cài đặt này được thiết lập tự động.
- Máy chủ proxy được đặt tại cổng giữa mạng và Internet và máy chủ này kết nối với máy tính và Internet (máy chủ đối lập) thay cho mỗi máy chủ. Máy chủ đối lập chỉ kết nối với máy chủ proxy. Do đó, không thể đọc thông tin máy in như địa chỉ IP và số cổng và cần phải tăng cường bảo mật.
- Khi bạn kết nối với Internet thông qua máy chủ proxy, hãy đặt cấu hình máy chủ proxy trên máy in.
