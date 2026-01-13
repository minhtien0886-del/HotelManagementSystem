# HotelManagementSystem

Ok 👍 mình hiểu tình huống của bạn rồi.
Bạn chỉ code được C, mới tiếp cận OOP & Java, làm hệ thống quản lý khách sạn, chạy console, và được phép dùng AI → vậy proposal nên đơn giản – đúng kiến thức – không “vượt trình”.

Dưới đây là proposal tính năng phù hợp cho sinh viên mới học OOP/Java, không cần GUI, không cần database phức tạp.

1️⃣ Giới thiệu đề tài (Introduction)

Tên hệ thống:

Hotel Management System (Console-based)

Mục tiêu:
Hệ thống giúp quản lý các hoạt động cơ bản của khách sạn như:

Quản lý phòng

Quản lý khách hàng

Đặt phòng & trả phòng
Hệ thống được xây dựng bằng Java, áp dụng lập trình hướng đối tượng (OOP) và chạy trên màn hình console.

2️⃣ Công nghệ sử dụng (Technology)

Ngôn ngữ: Java

Môi trường: Console / Terminal

Kiến thức áp dụng:

Class & Object

Encapsulation

Array / ArrayList

Menu vòng lặp

Nhập xuất dữ liệu (Scanner)

👉 Không dùng GUI, không dùng database (dữ liệu lưu tạm trong chương trình)

3️⃣ Các đối tượng chính (OOP Design – vừa sức)
3.1. Class Room (Phòng)

Thuộc tính:

roomId

roomType (Single / Double)

price

status (Available / Occupied)

Chức năng:

Hiển thị thông tin phòng

Cập nhật trạng thái phòng

3.2. Class Customer (Khách hàng)

Thuộc tính:

customerId

name

phoneNumber

Chức năng:

Lưu thông tin khách

Hiển thị thông tin khách

3.3. Class Booking (Đặt phòng)

Thuộc tính:

bookingId

customer

room

checkInDate

checkOutDate

Chức năng:

Tạo thông tin đặt phòng

Hiển thị thông tin booking

3.4. Class HotelManagement (Main / Controller)

Chức năng:

Hiển thị menu

Xử lý lựa chọn người dùng

Quản lý danh sách phòng, khách, booking

4️⃣ Các tính năng chính (Core Features)
🔹 1. Quản lý phòng

Thêm phòng mới

Xem danh sách phòng

Xem phòng còn trống

🔹 2. Quản lý khách hàng

Thêm khách hàng mới

Xem danh sách khách hàng

🔹 3. Đặt phòng

Chọn khách hàng

Chọn phòng còn trống

Tạo booking

Cập nhật trạng thái phòng thành Occupied

🔹 4. Trả phòng

Kết thúc booking

Cập nhật trạng thái phòng thành Available

Tính tiền cơ bản (số ngày × giá phòng)

🔹 5. Menu console

Ví dụ:

1. Add Room
2. View Rooms
3. Add Customer
4. Book Room
5. Check Out
6. Exit

5️⃣ Phạm vi & giới hạn (Scope & Limitations)

❌ Không có giao diện đồ họa (GUI)

❌ Không lưu dữ liệu vĩnh viễn (mất khi tắt chương trình)

❌ Không có đăng nhập người dùng

✔ Phù hợp cho học OOP & Java cơ bản

6️⃣ Kết luận (Conclusion)

Hệ thống quản lý khách sạn dạng console là một bài tập phù hợp cho người mới học Java OOP, giúp hiểu rõ:

Cách thiết kế class

Cách tổ chức chương trình

Cách áp dụng OOP vào bài toán thực tế
