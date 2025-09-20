1. Giới thiệu đề tài

Đề tài xây dựng một ứng dụng web quản lý nhà cung cấp và sản phẩm nhằm hỗ trợ công tác quản lý thông tin trong doanh nghiệp.
Ứng dụng được phát triển qua 2 giai đoạn (Part 1 và Part 2):

Part 1: Quản lý thông tin nhà cung cấp và sản phẩm (CRUD cơ bản).

Part 2: Bổ sung chức năng đăng ký, đăng nhập, quản lý phiên làm việc (session) để phân quyền sử dụng hệ thống.

2. Mục tiêu

Vận dụng kiến thức về Node.js, Express, MongoDB để phát triển ứng dụng web thực tế.

Thực hành mô hình MVC trong tổ chức project.

Xây dựng website có thể sử dụng để quản lý thông tin cơ bản của doanh nghiệp.

Hoàn thiện kỹ năng triển khai CRUD, xác thực người dùng, bảo mật phiên (session).

Sử dụng Git/GitHub trong quản lý project.

3. Công nghệ sử dụng

Ngôn ngữ: JavaScript (Node.js)

Backend Framework: Express.js

CSDL: MongoDB (Mongoose ODM)

Template Engine: EJS

CSS Framework: Bootstrap 5

Quản lý session: express-session, connect-mongo

Quản lý phiên bản: Git, GitHub

4. Kiến trúc hệ thống

Ứng dụng được phát triển theo mô hình MVC (Model – View – Controller):

Model: Định nghĩa schema (Supplier, Product, User) bằng Mongoose.

View: Giao diện hiển thị bằng EJS + Bootstrap.

Controller: Xử lý logic nghiệp vụ, gọi Model và render View.

5. Các chức năng chính
5.1. Part 1 – Quản lý Nhà cung cấp & Sản phẩm

Nhà cung cấp (Supplier): thêm, sửa, xóa, xem danh sách.

Sản phẩm (Product): thêm, sửa, xóa, gắn với nhà cung cấp.

5.2. Part 2 – Xác thực & Quản lý người dùng

Đăng ký tài khoản.

Đăng nhập / Đăng xuất.

Lưu trữ phiên làm việc bằng session + cookie.

Hiển thị thanh điều hướng tùy theo trạng thái đăng nhập.
