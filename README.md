# 🚀 APK GEN V3 - Google Play Downloader Pro

![Build Status](https://img.shields.io/github/actions/workflow/status/your-username/your-repo/deploy.yml?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Acode%20%7C%20Web-7000ff?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-ff007a?style=for-the-badge)

**APK GEN V3** là một công cụ web mạnh mẽ, nhẹ và hiện đại, được tối ưu hóa cho môi trường lập trình di động trên **Acode Editor**. Công cụ giúp trích xuất link tải trực tiếp từ Google Play Store với tỉ lệ thành công cao nhất năm 2026.

---

## 🌟 Tính năng chính

* ⚡ **Giải mã link tức thì**: Chuyển đổi link CH Play sang ID Package tự động.
* 🔗 **Đa nguồn tải (Multi-Source)**: Tích hợp 4 Server tải xuống độc lập (APKPure, Evozi, APK-DL...).
* 💾 **Lịch sử thông minh**: Tự động lưu lại các ứng dụng đã tìm kiếm bằng LocalStorage.
* 🎨 **Giao diện Cyberpunk**: Thiết kế Dark-mode cực chất, mượt mà trên điện thoại.
* 🤖 **CI/CD Ready**: Tích hợp sẵn GitHub Actions để Deploy lên web cá nhân trong 30 giây.

---

## 🛠️ Hướng dẫn cài đặt

### Sử dụng trên Acode
1. Sao chép mã nguồn từ file `index.html`.
2. Tạo một project mới trong Acode.
3. Dán code và nhấn nút **Play** để khởi chạy cục bộ.

### Triển khai lên GitHub Pages
1. Tạo Repo mới trên GitHub.
2. Đẩy file `index.html` và thư mục `.github/workflows/deploy.yml` lên.
3. Vào **Settings > Pages** -> Chọn **GitHub Actions** làm nguồn build.

---

## 📖 Cách sử dụng

1. **Copy Link**: Lấy link ứng dụng bất kỳ từ CH Play.
2. **Paste & Analyze**: Dán vào ô nhập liệu của APK GEN V3.
3. **Download**: Chọn một trong các Server để bắt đầu tải về file `.apk`.

---

## 📂 Cấu trúc thư mục

```text
├── .github/
│   └── workflows/
│       └── deploy.yml    # File cấu hình tự động hóa
├── index.html            # Mã nguồn chính (HTML/CSS/JS)
└── README.md             # Tài liệu hướng dẫn này
