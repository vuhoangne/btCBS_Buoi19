# 👥 Hệ Thống Quản Lý Nhân Viên

![Banner](https://hebbkx1anhila5yf.public.blob.vercel-storage.com/image-2VebsO5SZqXD03BM0o5zyCI3JO0otj.png)

Ứng dụng web quản lý nhân viên toàn diện được xây dựng bằng HTML, CSS, JavaScript và Bootstrap 5. Hệ thống cho phép quản lý thông tin nhân viên, tính lương, phân loại hiệu suất và tạo báo cáo thống kê.

## 📋 Mục lục

- [Tính năng](#-tính-năng)
- [Demo](#-demo)
- [Cài đặt](#-cài-đặt)
- [Cấu trúc dự án](#-cấu-trúc-dự-án)
- [Hướng dẫn sử dụng](#-hướng-dẫn-sử-dụng)
- [Yêu cầu hệ thống](#-yêu-cầu-hệ-thống)
- [Công nghệ sử dụng](#-công-nghệ-sử-dụng)
- [Tác giả](#-tác-giả)
- [Giấy phép](#-giấy-phép)

## ✨ Tính năng

### 🏠 Dashboard
- **Thống kê tổng quan**: Hiển thị số lượng nhân viên theo từng chức vụ
- **Biểu đồ trực quan**: Phân tích dữ liệu nhân viên theo nhiều tiêu chí
- **Cards thống kê**: Hiển thị thông tin quan trọng một cách trực quan

### 👥 Quản lý nhân viên
- **Thêm nhân viên mới**: Form với validation đầy đủ theo yêu cầu
- **Danh sách nhân viên**: Hiển thị trong bảng với đầy đủ thông tin
- **Sửa/Xóa nhân viên**: Cập nhật hoặc xóa thông tin nhân viên
- **Xuất Excel**: Xuất danh sách nhân viên ra file CSV

### 🔍 Tìm kiếm & Lọc
- **Tìm theo tên**: Tìm kiếm nhân viên theo tên
- **Lọc theo loại**: Lọc nhân viên theo xếp loại (Xuất sắc, Giỏi, Khá, Trung bình)
- **Lọc theo chức vụ**: Lọc theo vị trí (Giám đốc, Trưởng Phòng, Nhân Viên)

### 📊 Báo cáo & Thống kê
- **Thống kê theo chức vụ**: Phân tích số lượng nhân viên theo chức vụ
- **Thống kê theo xếp loại**: Phân tích hiệu suất của nhân viên
- **Top nhân viên xuất sắc**: Hiển thị danh sách nhân viên xuất sắc nhất

## 🖼️ Demo

![Dashboard](https://hebbkx1anhila5yf.public.blob.vercel-storage.com/image-2VebsO5SZqXD03BM0o5zyCI3JO0otj.png)
![Danh sách nhân viên](https://hebbkx1anhila5yf.public.blob.vercel-storage.com/image-sdvCdirQjSQ0bbFnybI3A5Ru4JbhHH.png)
![Validation](https://hebbkx1anhila5yf.public.blob.vercel-storage.com/image-aQjIvkFWFkqrekvLHlLY579zx5kKWB.png)
![Xếp loại](https://hebbkx1anhila5yf.public.blob.vercel-storage.com/image-6zs2U89IwjvoVKqiOhZA7uAFXZBUUi.png)

## 🚀 Cài đặt

1. **Tải xuống**: Clone repository hoặc tải file `index.html`
   \`\`\`bash
   git clone https://github.com/vuhoangne/employee-management-system.git
   \`\`\`
   hoặc tải trực tiếp file `index.html`

2. **Chạy ứng dụng**: Mở file `index.html` bằng trình duyệt web

3. **Bắt đầu sử dụng**: Không cần cài đặt thêm, ứng dụng chạy hoàn toàn trên client-side

## 📁 Cấu trúc dự án

\`\`\`
employee-management-system/
│
├── index.html          # File chính chứa toàn bộ code HTML, CSS và JavaScript
├── README.md           # Tài liệu hướng dẫn
└── screenshots/        # Thư mục chứa ảnh chụp màn hình (nếu có)
\`\`\`

## 📝 Hướng dẫn sử dụng

### Thêm nhân viên mới

1. Click vào "Thêm Nhân Viên" trong sidebar
2. Điền đầy đủ thông tin vào form:
   - **Tài khoản**: 4-6 ký tự
   - **Họ tên**: Chỉ chứa chữ cái
   - **Email**: Đúng định dạng email
   - **Mật khẩu**: 6-10 ký tự (chứa ít nhất 1 số, 1 chữ hoa, 1 ký tự đặc biệt)
   - **Ngày làm**: Định dạng mm/dd/yyyy
   - **Lương cơ bản**: 1,000,000 - 20,000,000 VND
   - **Chức vụ**: Chọn từ dropdown (Giám đốc, Trưởng Phòng, Nhân Viên)
   - **Giờ làm trong tháng**: 80-200 giờ
3. Click "Thêm Nhân Viên" để lưu

### Quản lý danh sách nhân viên

1. Click vào "Danh Sách NV" trong sidebar
2. Xem danh sách nhân viên trong bảng
3. Sử dụng nút "Sửa" (màu vàng) để chỉnh sửa thông tin
4. Sử dụng nút "Xóa" (màu đỏ) để xóa nhân viên
5. Click "Xuất Excel" để tải danh sách dưới dạng file CSV

### Tìm kiếm nhân viên

1. Click vào "Tìm Kiếm" trong sidebar
2. Sử dụng các bộ lọc:
   - Tìm theo tên
   - Lọc theo loại nhân viên
   - Lọc theo chức vụ
3. Kết quả sẽ hiển thị ngay lập tức

### Xem báo cáo và thống kê

1. Click vào "Báo Cáo" trong sidebar
2. Xem các thống kê về chức vụ và xếp loại
3. Xem danh sách top nhân viên xuất sắc

## 💻 Yêu cầu hệ thống

- **Trình duyệt**: Chrome 60+, Firefox 55+, Safari 12+, Edge 79+
- **Kết nối internet**: Cần để tải Bootstrap và Font Awesome từ CDN
- **JavaScript**: Phải được bật trong trình duyệt

## 🛠️ Công nghệ sử dụng

- **HTML5**: Cấu trúc trang web
- **CSS3**: Styling và animation
- **JavaScript (ES6+)**: Logic xử lý và tương tác
- **Bootstrap 5**: Framework CSS responsive
- **Font Awesome 6**: Icons
- **LocalStorage API**: Lưu trữ dữ liệu

## 🧮 Công thức tính toán

### Tính tổng lương
- **Giám đốc**: Lương cơ bản × 3
- **Trưởng Phòng**: Lương cơ bản × 2
- **Nhân Viên**: Lương cơ bản × 1

### Xếp loại nhân viên
- **Xuất sắc**: Giờ làm ≥ 192h
- **Giỏi**: Giờ làm ≥ 176h và < 192h
- **Khá**: Giờ làm ≥ 160h và < 176h
- **Trung bình**: Giờ làm < 160h

## 🔧 Tùy chỉnh và mở rộng

### Thêm chức vụ mới
1. Thêm option mới vào select trong form
2. Cập nhật hàm `calculateSalary()` để tính lương cho chức vụ mới

### Thay đổi tiêu chí xếp loại
1. Cập nhật hàm `classifyEmployee()` với các ngưỡng giờ làm mới

### Thêm trường dữ liệu mới
1. Thêm trường vào form HTML
2. Cập nhật đối tượng employee trong hàm `createEmployee()`
3. Cập nhật hàm render để hiển thị trường mới

## 👨‍💻 Tác giả

**Lê Nguyễn Vũ Hoàng**
- Email: vuhoangdz2003@gmail.com
- GitHub: [github.com/vuhoangne](https://github.com/vuhoangne)
- Hotline: 0937036966

## 📄 Giấy phép

Dự án này được phát hành dưới giấy phép MIT. Bạn có thể tự do sử dụng, chỉnh sửa và phân phối.

---

## 🐛 Báo lỗi và đóng góp

Nếu bạn phát hiện lỗi hoặc có ý tưởng cải thiện, vui lòng:
1. Tạo issue trên GitHub
2. Hoặc liên hệ trực tiếp qua email: vuhoangdz2003@gmail.com

## 🔜 Tính năng sắp tới

- [ ] Đăng nhập và phân quyền người dùng
- [ ] Biểu đồ thống kê nâng cao với Chart.js
- [ ] Xuất báo cáo dạng PDF
- [ ] Tích hợp API để lưu trữ dữ liệu trên server
- [ ] Giao diện dark mode

---

**© 2024 Lê Nguyễn Vũ Hoàng. All rights reserved.**
