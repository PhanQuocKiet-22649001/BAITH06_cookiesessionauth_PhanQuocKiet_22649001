1. Chạy file app.js: node app.js

2. Đăng ký tài khoảng với route "/register" với phương thức POST và http://localhost:3000/auth/register tại POSTMAN
- Nhập username và password: 
{
  "username": "testuser",
  "password": "123456"
}
sau đó nhấn Send. kết quả trả về là "message": "User registered successfully!"
<img width="1919" height="1079" alt="image" src="public/img/register.png" />
- Tài khoản mới được lưu trong database
<img width="1919" height="1079" alt="image" src="public/img/registerdatabase.png" />
<img width="1919" height="1079" alt="image" src="public/img/sessionregister.png.png" />

3. Login (Đăng nhập)

Method: POST
URL: http://localhost:3000/auth/login

-TH: Đăng nhập thành công, hiện thông báo ""message": "Login successful!""
<img width="1919" height="1079" alt="image" src="public/img/login.png" />
-Cookie trong postman
<img width="1919" height="1079" alt="image" src="public/img/cookieloginpostman.png" />
<img width="1919" height="1079" alt="image" src="public/img/cookie2.png" />
-Session được lưu trong database
<img width="1919" height="1079" alt="image" src="public/img/sessionlogin.png" />


-TH Đăng nhập thấy bại, hiện thông báo ""error": "Invalid username or password""
<img width="1919" height="1079" alt="image" src="public/img/faillogin.png" />
- Không lưu trong database
<img width="1919" height="1079" alt="image" src="public/img/sessionfaillogin.png" />









