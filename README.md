# School_Management_System

 Đây là repository chứa source code FrontEnd và BackEnd của nhóm em trong môn Lập trình nâng cao.
 Trong Bài tập lớn này em chịu các vấn đề liên quan đến thiết kế Models, Kiến trúc hệ thống, kết nối Realtime Database, hiện thực hóa các API,...


### Cách chạy dự án
Trước hết ta phải chạy ```backend``` của hệ thống(vì backend được kết nối với realtime database nên tốc độ load có thể hơi chậm)

Cách 1: Sử dụng câu lệnh để tới package được chạy từ trước của source code để khởi động ```Backend```
```
cd .\backend\
java -jar target/demo-0.0.1-SNAPSHOT.jar
```
Cách 2: Sử dụng button Run tại file ```DemoApplication.java``` tại đường dẫn ``School_Management_System\backend\src\main\java\com\example\demo\DemoApplication.java```


Sau đó ta tới ta tạo một terminal mới chạy song song với cái đang chạy ```backend``` bằng tổ hợp phím ```Ctrl + Shift + ```
Ta sử dụng các câu lệnh sau ở terminal để chạy frontend ở hệ thống
```
npm install
npm start
```

### Tiếp cận với giao diện hệ thống
Ta bật trình duyệt trong máy và truy cập đường dẫn sau để bắt đầu sử dụng hệ thống ```http://localhost:3000/home```

Các tài khoản có sẵn để test tính năng của hệ thống:

 +Student: username: "student_1", password: "1"
 
 +Teacher: username: "teacher1", password: "1"
 
 +Admin: username: "admin_1", password: "1"
