<div align="center">

# 🎬 TikTok & Douyin Bulk Downloader Suite

**Ứng dụng Desktop tải hàng loạt Video, Ảnh và Album từ TikTok, Douyin (抖音), Kuaishou (快手), Rednote (小红书) không logo watermark, độ phân giải gốc cao nhất.**

[![Release](https://img.shields.io/github/v/release/mihchis/Tiktok_Bulk_Downloader_Releases?color=blue&logo=github)](https://github.com/mihchis/Tiktok_Bulk_Downloader_Releases/releases)
[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey?logo=electron)](https://github.com/mihchis/Tiktok_Bulk_Downloader_Releases/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[📥 Tải về bản mới nhất](#-tải-về-ứng-dụng-downloads) • [✨ Tính năng chính](#-tính-năng-nổi-bật) • [⚙️ Cài đặt & Hướng dẫn](#️-lưu-ý-khi-cài-đặt) • [❓ FAQ](#-câu-hỏi-thường-gặp)

</div>

---

## 📌 Tính năng nổi bật

### 1. 🎵 TikTok Downloader
- **Tải hàng loạt theo kênh**: Nhập `@username` hoặc liên kết kênh để quét và tải toàn bộ video của tác giả.
- **Tải bài viết lẻ**: Phân tích và tải video không logo hoặc trọn bộ album ảnh (Slideshow/Photos) ở độ phân giải gốc cao nhất.
- **Tách âm thanh gốc**: Tải file MP3 chất lượng cao trực tiếp từ CDN máy chủ.
- **Xuất báo cáo Excel**: Xuất danh sách video đã quét ra `.xlsx` kèm đầy đủ số liệu thống kê (views, likes, comments, shares).

### 2. 🐉 Douyin (抖音) Downloader
- **Hỗ trợ liên kết chia sẻ**: Tự động nhận diện và giải mã link rút gọn `v.douyin.com/...`.
- **Tải Live Photo**: Tách trọn vẹn cả video chuyển động lẫn ảnh tĩnh sắc nét kèm âm thanh nguyên bản.
- **Cơ chế TTWID an toàn**: Tự động khởi tạo token an toàn giúp vượt rào cản kiểm duyệt của Douyin.
- **Trích xuất thông tin tác giả**: Hiển thị avatar, tên người dùng, tổng lượt thích và người theo dõi.

### 3. 🚀 Kuaishou (快手) & Rednote (小红书) *(Sắp ra mắt)*
- Trích xuất video ngắn và hình ảnh chất lượng cao không watermark từ 快手 và Tiểu Hồng Thư.

### 4. 🔗 Tải nhiều liên kết (Multi-URL Downloader)
- Dán danh sách hàng chục link TikTok và Douyin cùng lúc (mỗi dòng một link).
- Tự động nhận diện nền tảng và đưa vào tiến trình tải tuần tự an toàn.

### 5. 👥 Quản lý KOL (KOL Manager)
- Lưu trữ danh bạ các kênh sáng tạo nội dung quan trọng.
- Theo dõi chỉ số, cập nhật video mới và tải nhanh chỉ với 1 cú click.

### 6. 🛡️ Bảo mật Cookie & Kiểm tra sức khỏe tự động
- **Che mắt bảo mật vĩnh viễn**: Chuỗi Cookie trong Cài đặt luôn được che dạng mã hóa `••••` để chống quay lén hoặc chụp màn hình.
- **Kiểm tra tự động khi mở app**: Tự động ping API để xác định cookie còn sống hay đã hết hạn, hiển thị trạng thái `🟢 Còn sống` / `🔴 Hết hạn`.

### 7. 📥 Hàng đợi tải toàn cục & Chạy ngầm (System Tray)
- Tải tuần tự tránh bị chặn IP / WAF rate-limit.
- Tự động thu nhỏ xuống Khay hệ thống khi bấm nút đóng (X).
- Gửi thông báo Desktop khi hoàn tất tác vụ.

---

## 📥 Tải về ứng dụng (Downloads)

Vui lòng truy cập trang **[Releases](https://github.com/mihchis/Tiktok_Bulk_Downloader_Releases/releases)** để tải bản cài đặt phù hợp với hệ điều hành của bạn:

| Hệ điều hành | Tệp cài đặt | Mô tả |
| :--- | :--- | :--- |
| 🪟 **Windows** | `tiktok-bulk-downloader-x.x.x-setup.exe` | Trình cài đặt tự động cho Windows 10/11 (64-bit) |
| 🍎 **macOS** | `tiktok-bulk-downloader-x.x.x.dmg` | Bản cài đặt cho macOS (Intel & Apple Silicon) |
| 🐧 **Linux** | `tiktok-bulk-downloader-x.x.x.AppImage` | Gói ứng dụng chạy trực tiếp cho Linux |

---

## ⚠️ Lưu ý khi cài đặt

### macOS
Do ứng dụng chưa đăng ký chứng chỉ Apple Developer trả phí, macOS có thể hiện cảnh báo:  
> *"Tiktok Bulk Downloader" is damaged and can't be opened.*

**Cách khắc phục cực kỳ đơn giản:**
1. Mở ứng dụng **Terminal** trên Mac.
2. Dán lệnh sau và nhấn Enter:
   ```bash
   xattr -cr /Applications/Tiktok\ Bulk\ Downloader.app
   ```
3. Mở lại ứng dụng bình thường.

### Linux
Cấp quyền thực thi trước khi mở file:
```bash
chmod +x tiktok-bulk-downloader-*.AppImage
./tiktok-bulk-downloader-*.AppImage
```

---

## 🔄 Tự động cập nhật (Auto-Update)

Ứng dụng tích hợp sẵn cơ chế **kiểm tra bản cập nhật mới tự động**:
- Khi có phiên bản mới được phát hành tại repo này, ứng dụng sẽ thông báo trực tiếp trên màn hình.
- Bạn cũng có thể bấm biểu tượng xoay vòng ở thanh Sidebar hoặc vào **Cài đặt** -> **Kiểm tra cập nhật** để cập nhật nhanh chóng.

---

## 📄 Bản quyền & Tuyên bố miễn trừ trách nhiệm (Disclaimer)

- **License**: Phát hành theo giấy phép [MIT License](LICENSE).
- **Disclaimer**: Ứng dụng này được phát triển phục vụ mục đích học tập, nghiên cứu và sao lưu nội dung cá nhân. Chúng tôi không lưu trữ bất kỳ tệp video nào trên máy chủ riêng; mọi dữ liệu đều được truyền tải trực tiếp từ máy chủ CDN công khai của nền tảng tương ứng. Người dùng chịu hoàn toàn trách nhiệm đối với việc sử dụng nội dung tải về.

---

## 👨‍💻 Tác giả & Hỗ trợ

- **Tác giả**: [@mihchis (Minh Trí)](https://github.com/mihchis)
- **Facebook**: [https://www.facebook.com/mihchis/](https://www.facebook.com/mihchis/)
- **Báo lỗi & Góp ý (Issues)**: [Tạo Issue mới tại đây](https://github.com/mihchis/Tiktok_Bulk_Downloader_Releases/issues)
