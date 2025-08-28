# Lịch Vạn Niên Việt Nam

## Giới thiệu

**Lịch Vạn Niên Việt Nam** là một ứng dụng web cung cấp lịch vạn niên với giao diện hiện đại, hỗ trợ cả lịch dương và lịch âm, cùng với các tính năng như hiển thị ngày lễ, ghi chú cá nhân và tùy chỉnh giao diện theo nhiều chủ đề đẹp mắt. Ứng dụng được thiết kế để hỗ trợ người dùng Việt Nam theo dõi ngày tháng, các sự kiện quan trọng và quản lý ghi chú cá nhân một cách dễ dàng.

### Các tính năng chính

- **Hiển thị lịch dương và âm lịch**: Xem ngày dương lịch kèm ngày âm lịch tương ứng, bao gồm cả thông tin về tháng nhuận.
- **Ngày lễ Việt Nam**: Tự động đánh dấu các ngày lễ quan trọng theo lịch dương và lịch âm, ví dụ: Tết Nguyên Đán, Quốc khánh, Giỗ Tổ Hùng Vương, v.v.
- **Ghi chú cá nhân**: Cho phép người dùng thêm, chỉnh sửa và xóa ghi chú cho bất kỳ ngày nào, được lưu trữ trong trình duyệt (localStorage).
- **Tùy chỉnh giao diện**: Hỗ trợ nhiều chủ đề (theme) đẹp mắt như Hoa Anh Đào, Đại Dương, Rừng Xanh, Hoàng Hôn, Dark Mode, v.v., với các hiệu ứng gradient mượt mà.
- **Điều hướng dễ dàng**: Chuyển đổi nhanh giữa các tháng, năm hoặc quay về ngày hiện tại với các nút điều khiển thân thiện.
- **Responsive Design**: Giao diện tương thích với cả máy tính và thiết bị di động.

## Demo

Ứng dụng đã được triển khai trên GitHub Pages. Truy cập tại:  
🔗 [https://phanhongha.github.io/Calendar-WebApp/](https://phanhongha.github.io/Calendar-WebApp/)

## Công nghệ sử dụng

- **HTML5, CSS3**: Xây dựng giao diện người dùng với các hiệu ứng chuyển đổi mượt mà.
- **JavaScript**: Xử lý logic lịch, chuyển đổi dương lịch - âm lịch, quản lý ghi chú và tương tác người dùng.
- **LocalStorage**: Lưu trữ ghi chú và tùy chọn chủ đề của người dùng.
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
4. **Thêm ghi chú**: Nhấn vào bất kỳ ngày nào để mở modal, nhập ghi chú và nhấn "Lưu ghi chú". Ghi chú sẽ được lưu và hiển thị trên lịch.
5. **Xóa ghi chú**: Trong modal, nhấn "Xóa ghi chú" để xóa ghi chú của ngày đó.
6. **Xem ngày lễ**: Các ngày lễ được tự động đánh dấu bằng màu sắc nổi bật, kèm tên sự kiện.

## Các chủ đề (Themes)

Ứng dụng cung cấp 12 chủ đề với các phong cách màu sắc độc đáo:
- 🌈 Mặc định
- 🌸 Hoa anh đào
- 🌊 Đại dương
- 🌲 Rừng xanh
- 🌅 Hoàng hôn
- 👑 Hoàng gia (Vàng kim)
- 🍂 Mùa thu
- 🌙 Dark Mode
- 🌚 Midnight Black
- 🧛‍♂️ Vampire
- 💚 Matrix
- ☀️ Light Mode

## Đóng góp

Chúng tôi hoan nghênh mọi đóng góp để cải thiện ứng dụng! Để đóng góp:
1. Fork repository này.
2. Tạo branch mới: `git checkout -b feature/<tên-tính-năng>`.
3. Commit các thay đổi: `git commit -m "Thêm <tính năng>"`.
4. Push lên branch: `git push origin feature/<tên-tính-năng>`.
5. Tạo Pull Request trên GitHub.

## Giấy phép

Dự án được phát hành dưới [Giấy phép MIT](LICENSE). Bạn có thể sử dụng, sao chép, chỉnh sửa và phân phối mã nguồn theo các điều khoản của giấy phép.

## Liên hệ

Nếu bạn có câu hỏi hoặc đề xuất, vui lòng liên hệ qua [GitHub Issues](https://github.com/phanhongha/Calendar-WebApp/issues) hoặc email <your-email>.

---

**Lịch Vạn Niên Việt Nam** - Mang nét đẹp truyền thống kết hợp hiện đại đến với mọi người!