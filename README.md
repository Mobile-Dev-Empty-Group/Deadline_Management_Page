# 🚀 DineLex App - Ứng dụng Quản lý Deadline

**Slogan:** "Deadline không đuổi bạn mà bạn đuổi deadline"

## 📖 Tổng quan dự án

**DineLex App** là ứng dụng quản lý deadline được thiết kế đặc biệt dành cho sinh viên, giúp quản lý các công việc, bài tập và dự án một cách khoa học.

Vấn đề lớn nhất của sinh viên hiện nay là không biết cách quản lý deadline hiệu quả, thường xuyên bỏ lỡ bài tập hoặc làm việc trễ hạn. DineLex giải quyết vấn đề này bằng cách tập trung vào **nhắc nhở thông minh** dựa trên độ ưu tiên, giúp giảm thiểu tình trạng quên hạn.

### Mục tiêu chính:

- Hỗ trợ người dùng theo dõi và sắp xếp công việc theo thời hạn.
- Tạo hệ thống thông báo tự động và tùy chỉnh.
- Đảm bảo giao diện thân thiện, dễ dùng trên nền tảng mobile.

---

## ✨ Tính năng cốt lõi

Ở giai đoạn MVP, ứng dụng tập trung vào các tính năng thiết yếu nhất để đảm bảo trải nghiệm người dùng nhanh chóng và hiệu quả:

| Tính năng                    | Mô tả                                                                                          |
| :--------------------------- | :--------------------------------------------------------------------------------------------- |
| **📝 Tạo & Quản lý Task**    | Cho phép tạo, sửa, xóa và phân loại các đầu việc cần làm.                                      |
| **🔔 Nhắc nhở thông minh**   | Hệ thống thông báo linh hoạt (Reminders) và tính năng hoãn lại (Snooze) khi chưa thể làm ngay. |
| **📅 Lịch & Timeline**       | Giao diện hiển thị tổng quan các deadline sắp tới trên lịch hoặc dòng thời gian.               |
| **📈 Theo dõi tiến độ**      | Cập nhật trạng thái hoàn thành hoặc phần trăm tiến độ của công việc.                           |
| **⚡ Tạo nhanh (Quick Add)** | Thêm nhanh deadline mới mà không cần qua nhiều bước phức tạp.                                  |

---

## 📱 Luồng người dùng & Kiến trúc thông tin

Dưới đây là sơ đồ luồng hoạt động của ứng dụng:

### 1. Kiến trúc thông tin (Information Architecture)

Sơ đồ tổng quan các màn hình chính: Onboarding, Đăng nhập, Màn hình chính (Home), Danh sách Task, Tạo Task, Lịch và Hồ sơ người dùng.

<img width="915" height="701" alt="MobileDeadlineApp-Infomation Architecture drawio" src="https://github.com/user-attachments/assets/77325add-b2af-4217-89ff-87f6c4305073" />

### 2. Luồng Đăng nhập & Quên mật khẩu

Quy trình xác thực người dùng, bao gồm đăng ký, đăng nhập và khôi phục mật khẩu qua OTP.

<img width="650" height="982" alt="MobileDeadlineApp-Log in_Sign in drawio" src="https://github.com/user-attachments/assets/2e54c34e-250b-4b42-aac3-1c65c1597f7e" />

### 3. Luồng Tạo Task (Create Task)

Quy trình người dùng nhập tiêu đề, danh mục, ngày giờ và xác nhận tạo task mới.

<img width="462" height="722" alt="MobileDeadlineApp-Create task drawio" src="https://github.com/user-attachments/assets/c40b8fe1-28a0-4648-9446-f9c829141c76" />

### 4. Luồng Đánh dấu tiến độ (Mark Progress)

Người dùng có thể đánh dấu "Hoàn thành" (Done) hoặc cập nhật phần trăm (%) tiến độ công việc.

<img width="462" height="452" alt="MobileDeadlineApp-Mark progress drawio" src="https://github.com/user-attachments/assets/83dd7ebd-a1ef-493b-9d13-48d5d168884a" />

### 5. Luồng Nhắc nhở & Snooze (Reminder)

Cách ứng dụng hiển thị thông báo và xử lý khi người dùng chọn "Làm ngay" hoặc "Nhắc lại sau" (Snooze).

<img width="1079" height="1079" alt="image" src="https://github.com/user-attachments/assets/80f0ef4e-b49d-4d20-91b1-fed827607725" />

---

## 💡 Mô hình kinh doanh (Business Model Canvas)

- **Đối tượng mục tiêu:** Sinh viên đại học (18-25 tuổi), nhóm người dùng am hiểu công nghệ (Tech-savvy Gen Z).
- **Giải pháp công nghệ:** Ứng dụng đa nền tảng (Cross-platform) sử dụng **React Native**, hỗ trợ đồng bộ hóa ngoại tuyến (Offline Synchronization).
- **Dòng doanh thu:**
  - Đăng ký gói Premium (Premium Subscriptions).
  - Mua hàng trong ứng dụng (In-app Purchases).
  - Quảng cáo (Advertisement Revenue).

<img width="1164" height="1146" alt="image" src="https://github.com/user-attachments/assets/a3167b09-b0c9-453f-a18a-530111214ec9" />

---

## 🗺️ Định hướng phát triển (Roadmap)

Dựa trên nghiên cứu thị trường từ các ứng dụng như Todoist, TickTick và Microsoft To Do, lộ trình phát triển của DineLex được chia như sau:

1.  **Giai đoạn 1 (Hiện tại):** Tập trung vào tính năng cốt lõi thật tốt và dễ dùng (Core Features).
2.  **Giai đoạn 2 (Tương lai):** Sau khi có lượng người dùng ổn định, sẽ mở rộng thêm các module nâng cao như:
    - Dạng bảng (Kanban Board).
    - Lọc nhãn (Filter tags).
    - Template nâng cao.

---

## 👥 Đội ngũ thực hiện

Dự án được thực hiện bởi nhóm phát triển DineLex.

- Nguyễn Thành Lộc - [LocNguyenthanhh](https://github.com/LocNguyenthanhh)
- Nguyễn Đăng Khoa - [dagkoa](https://github.com/dagkoa)
- Huỳnh Thanh Tâm - [Thahn-Tam](https://github.com/Thahn-Tam)
- Nguyễn Đoàn Minh Tâm - [mtaamm](https://github.com/mtaamm)
