🛒 Website Bán Hàng - JSP/Servlet

📌 Giới thiệu

Dự án Website Bán Hàng Online cho phép:
•	Người dùng xem sản phẩm, tìm kiếm, thêm vào giỏ hàng, đặt hàng.
•	Quản trị viên quản lý sản phẩm, đơn hàng, tài khoản người dùng.

Công nghệ sử dụng:
•	Frontend: HTML, CSS, JavaScript
•	Backend: Java Servlet, JSP
•	Database: MySQL
•	Server: Apache Tomcat

________________________________________

👥 Phân chia công việc

________________________________________
🚀 Cách chạy dự án

- Yêu cầu môi trường
•	Java JDK 11+
•	Apache Tomcat 9/10
•	MySQL 8+
•	IDE: Eclipse / IntelliJ / NetBeans

- Cài đặt
1.	Clone project
2.	git clone https://github.com/your-org/ecommerce-jsp.git
3.	Import vào IDE (chọn "Import as Maven project" nếu có dùng Maven).
4.	Cấu hình Database
  - Tạo database ecommerce trong MySQL.
  - Import file database.sql có sẵn trong thư mục db/.
  - Sửa thông tin DB trong file DBConnection.java:
  - String url = "jdbc:mysql://localhost:3306/ecommerce";
  - String user = "root";
  - String password = "your_password";
5.	Chạy trên Tomcat
  - Add project vào Tomcat Server.
  - Start server và truy cập:
  - http://localhost:8080/ecommerce
________________________________________
🌳 Quy ước phân nhánh

•	main → Code ổn định, đã kiểm thử.
•	develop → Nhánh phát triển.
•	feature/[tên-tính-năng] → Code tính năng mới.
•	fix/[tên-lỗi] → Sửa bug.

👉 Ví dụ:
git checkout -b feature/cart
git checkout -b fix/login-error
________________________________________

🔄 Quy trình làm việc (Workflow)
1.	Lấy code mới nhất:
2.	git checkout develop
3.	git pull origin develop
4.	Tạo nhánh mới:
5.	git checkout -b feature/add-product
6.	Commit:
7.	git add .
8.	git commit -m "feat: thêm chức năng thêm sản phẩm"
9.	Push:
10.	git push origin feature/add-product
11.	Tạo Pull Request (PR) từ GitHub → merge vào develop.
________________________________________

📝 Quy ước commit message
•	feat: ... → Thêm tính năng
•	fix: ... → Sửa lỗi
•	docs: ... → Cập nhật tài liệu
•	style: ... → Chỉnh sửa UI, CSS
•	refactor: ... → Chỉnh sửa code không đổi logic
•	test: ... → Thêm/sửa test
________________________________________

📦 Deployment
•	Deploy trên Tomcat server (có thể dùng XAMPP + Tomcat plugin).
•	Database chạy trên MySQL (local hoặc server).
________________________________________

✅ Checklist
•	Code đúng phần được phân công.
•	Không commit trực tiếp vào main.
•	Test trước khi tạo Pull Request.
•	Review code cho nhau trước khi merge

