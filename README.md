# [IE104.O12.Group2] - XÂY DỰNG WEBSITE CỬA HÀNG ĐIỆN MÁY TECHTWO.


## Công nghệ sử dụng
* [Node.js] - Xử lý API, Back-end
* [Express] - Framework nằm trên chức năng máy chủ web của NodeJS
* [EJS] - Hỗ trợ phát triển các trang web bằng cách cho phép tạo ra các mẫu HTML được kết hợp với mã JavaScript
* [Xampp] - Cung cấp các môi trường phát triển cục bộ cho các ứng dụng web
* [MySQL] - Hệ quản trị cơ sở dữ liệu quan hệ sử dụng để lưu trữ dữ liệu cho trang web
* [HTML-CSS-JS] - Bộ ba công nghệ web, hiện thức hóa giao diện

## Hướng dẫn và Cài đặt
Yêu cầu: 
* [Node.js](https://nodejs.org/) v19+ để có thể chạy chương trình.

* Bật Apache và MySQL
* Sau khi MySQL chạy, hãy nhấn chọn Admin của MySQL
![image](https://github.com/namtuthien/SE104.O11.Group6/assets/145759907/1b60556b-657c-482c-8928-163192962c65)


Tạo database mới có tên là
```
techshop
```
![image](https://github.com/NunNunIT/IE104.O12.Group2/assets/145759907/4dcd1d54-f022-4c7f-b6d1-a5544b29c34e)

Bạn có thể tạo database theo cách trong hình hoặc mở tab SQL tại thanh điều hướng và sử dụng lệnh 
```
CREATE DATABASE techshop;
```

#### Bước 3: Nhập dữ liệu cho cơ sở dữ liệu:
- Đầu tiên, truy cập thư mục src/config/database. Tại đây chứa file sql cần thiết
![image](https://github.com/NunNunIT/IE104.O12.Group2/assets/145759907/b5841b38-d7db-4927-bcaf-e87fc78eaffe)
- Tải file: ie104_group2.sql
- Chọn tab Import trên thanh điều hướng
- Chọn Choose File --> Chọn file mới tải về ở trên
![image](https://github.com/NunNunIT/IE104.O12.Group2/assets/145759907/eadc23ee-fe49-418d-a57e-09d4ee48c48f)
    + Sau đó, vuốt xuống dưới để nhấn nút 'Import'

Sau khi thực hiện cách trên bạn sẽ có đầy đủ cơ sở dữ liệu của trang web. Kết quả như trong hình:
![image](https://github.com/NunNunIT/IE104.O12.Group2/assets/145759907/0afa3cdd-46ec-4eda-abdc-bac2ca1729fd)

#### Bước 4: Thực hiện clone repository này với lệnh
```
https://github.com/NunNunIT/IE104.O12.Group2.git
```
#### Bước 5: Mở dự án mới clone về và thực hiện các câu lệnh sau
```
npm install
```
```
npm start
```

* Bạn có thể đăng nhập bằng tài khoản sau:
  + Email: ```0987654321```
  + Mật khẩu: ```khachhang1```
* Bạn có thể đăng nhập tài khoản admin thông qua đường dẫn ``` http://127.0.0.1:3000/admin/login ```
  + Tên đăng nhập: ```21522436```
  + Mật khẩu: ```adminnhung```

![image](https://github.com/NunNunIT/IE104.O12.Group2/assets/145759907/2ba17bf7-ef6e-4b20-9e44-9d31403bf34f)

## Chúc các bạn thành công!!!
