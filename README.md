# Style Store – Backend (Spring Boot)

## 📌 Giới thiệu
Style Store là dự án website bán quần áo/balo được xây dựng trong quá trình học tập.
Repository này chứa **phần Backend**, được phát triển bằng **Java Spring Boot**,
cung cấp **RESTful API** cho Frontend sử dụng.

Dự án nhằm rèn luyện kỹ năng Backend Java, làm việc với cơ sở dữ liệu
và quy trình phát triển phần mềm theo mô hình Agile.

---

## 🛠️ Công nghệ sử dụng
- Java
- Spring Boot
- Spring Data JPA (Hibernate)
- RESTful API
- MySQL
- Postman
- Git/GitHub

---

## ✨ Chức năng chính
- Quản lý sản phẩm (CRUD)
- Quản lý khách hàng
- Quản lý hóa đơn
- Xử lý logic bán hàng
- Cung cấp REST API cho Frontend

---

## 📂 Cấu trúc dự án (tiêu biểu)
src/main/java
├── controller # Xử lý request API
├── service # Xử lý logic nghiệp vụ
├── repository # Làm việc với database
├── entity # Entity JPA
├── dto # Data Transfer Object
└── exception # Xử lý exception

yaml
Sao chép mã

---

## ▶️ Hướng dẫn chạy dự án

### 1️⃣ Clone repository
```bash
git clone https://github.com/mitundevv/Website-Ban-Balo.git
2️⃣ Cấu hình database
Tạo database MySQL

Import file .sql (nếu có)

Cấu hình trong application.properties

properties
Sao chép mã
spring.datasource.url=jdbc:mysql://localhost:3306/style_store
spring.datasource.username=root
spring.datasource.password=your_password
3️⃣ Chạy ứng dụng
bash
Sao chép mã
mvn spring-boot:run
👉 Backend chạy tại:

arduino
Sao chép mã
http://localhost:8080
🔍 Test API
Sử dụng Postman

Các API trả dữ liệu dạng JSON

Hỗ trợ các method: GET, POST, PUT, DELETE

👥 Nhóm thực hiện
Số lượng thành viên: 5

Vai trò: Backend Developer (Thành viên)

Làm việc theo mô hình Agile/Scrum

📌 Ghi chú
Dự án phục vụ cho mục đích học tập và thực tập,
có thể tiếp tục mở rộng và tối ưu trong tương lai.
---
