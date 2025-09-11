# Lịch Vạn Niên Việt Nam

## Giới thiệu

**Lịch Vạn Niên Việt Nam** là ứng dụng web một trang với giao diện hiện đại, hỗ trợ **lịch dương & âm**, hiển thị **ngày lễ**, **ghi chú cá nhân** và **tùy chỉnh giao diện** theo nhiều chủ đề đẹp mắt. Ứng dụng giúp người dùng Việt Nam theo dõi ngày tháng, sự kiện quan trọng và quản lý ghi chú một cách dễ dàng.

### Các tính năng chính

- **Hiển thị lịch dương & âm**: Xem ngày dương kèm ngày âm tương ứng, bao gồm thông tin **tháng nhuận**.
- **Ngày lễ Việt Nam**: Tự động đánh dấu các ngày lễ quan trọng theo dương/âm (Tết Nguyên Đán, Quốc khánh, Giỗ Tổ Hùng Vương, v.v.).
- **Ghi chú cá nhân**: Thêm, chỉnh sửa, xóa ghi chú cho từng ngày.
- **Đăng nhập Google & đồng bộ đám mây**: Ghi chú được lưu theo tài khoản và **đồng bộ thời gian thực** qua **Firebase Authentication + Cloud Firestore** (fallback **localStorage** khi chưa đăng nhập).
- **Tùy chỉnh giao diện (Themes)**: Nhiều chủ đề theo dịp lễ và **Auto Theme**.
- **Điều hướng & Responsive**: Chuyển tháng/năm nhanh, nút “Hôm nay”, giao diện tối ưu cho desktop & mobile.

## Demo

Ứng dụng đã được triển khai trên Firebase Hosting. Truy cập tại:  
🔗 [[demo](https://calendar-webapp-8e147.web.app/)]

## Công nghệ sử dụng

- **HTML5, CSS3**: Xây dựng giao diện người dùng với các hiệu ứng chuyển đổi mượt mà.
- **JavaScript**: Xử lý logic lịch, chuyển đổi dương lịch - âm lịch, quản lý ghi chú và tương tác người dùng.
- **Firebase Authentication (Google)** & **Cloud Firestore** (đồng bộ ghi chú)
- **Thuật toán âm lịch**: Tích hợp thuật toán chuyển đổi dương lịch sang âm lịch chính xác, hỗ trợ tính toán các ngày lễ âm lịch.

## Hướng dẫn cài đặt và chạy

### Yêu cầu
- Trình duyệt web hiện đại (Chrome, Firefox, Safari, Edge, v.v.).
- Không yêu cầu cài đặt server hay bất kỳ phụ thuộc nào, chỉ cần file HTML tĩnh.

### Cài đặt
1. Clone hoặc tải repository về máy:
   ```bash
   git clone https://github.com/phanhongha/Calendar-WebApp.git
   ```
2. Mở file `index.html` trong trình duyệt web để sử dụng ứng dụng.

### Cấu trúc file
- `index.html`: File chính chứa toàn bộ mã HTML, CSS và JavaScript.
- (Không yêu cầu thêm file phụ thuộc bên ngoài).

## Hướng dẫn sử dụng

1. **Chọn tháng/năm**: Sử dụng dropdown để chọn tháng và năm muốn xem.
2. **Điều hướng**: Nhấn các nút "Hôm nay", "Tháng trước", "Tháng sau" để di chuyển nhanh.
3. **Thay đổi giao diện**: Chọn chủ đề từ dropdown "Theme" để thay đổi giao diện theo sở thích.
4. **Tự động thay đổi giao diện**: Để giao diện tự động thay khi gần tới các ngày lễ, chọn vào nút "Tự động" sẽ chuyển qua trạng thái "Bật"
5. **Thêm ghi chú**: Nhấn vào bất kỳ ngày nào để mở modal, nhập ghi chú và nhấn "Lưu ghi chú". Ghi chú sẽ được lưu và hiển thị trên lịch.
6. **Xóa ghi chú**: Trong modal, nhấn "Xóa ghi chú" để xóa ghi chú của ngày đó.
7. **Xem ngày lễ**: Các ngày lễ được tự động đánh dấu bằng màu sắc nổi bật, kèm tên sự kiện.

## Các chủ đề (Themes)

Ứng dụng cung cấp 12 chủ đề với các phong cách màu sắc độc đáo:
- 🌈 Mặc định
- 🧧 Tết Nguyên Đán
- 👑 Giỗ Tổ Hùng Vương
- 🎉 Giải phóng miền Nam (30/4)
- 🛠️ Quốc tế Lao động (1/5)
- 🇻🇳 Quốc khánh (2/9)
- 🎓 Ngày Nhà giáo
- 🌸 Ngày Phụ nữ
- 🏮 Trung Thu
- 🎄 Noel
- 🎃 Halloween
- 💘 Valentine
- 🎆 New Year

## Đóng góp

Chúng tôi hoan nghênh mọi đóng góp để cải thiện ứng dụng! Để đóng góp:
1. Fork repository này.
2. Tạo branch mới: `git checkout -b feature/<tên-tính-năng>`.
3. Commit các thay đổi: `git commit -m "Add <tính năng>"`.
4. Push lên branch: `git push origin feature/<tên-tính-năng>`.
5. Tạo Pull Request trên GitHub.

## Liên hệ

Nếu bạn có câu hỏi hoặc đề xuất, vui lòng liên hệ qua [GitHub Issues](https://github.com/phanhongha/Calendar-WebApp/issues) hoặc email <phanhongha.2001@gmail.com>.

---

**Lịch Vạn Niên Việt Nam** - Mang nét đẹp truyền thống kết hợp hiện đại đến với mọi người!
