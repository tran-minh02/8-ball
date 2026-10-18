# 🎱 Magic 8-Ball Classic (Bản Cổ Điển Không AI)

Ứng dụng Quả Cầu Số 8 Tiên Tri theo chuẩn cơ học cổ điển, **100% Client-Side**, không cần máy chủ AI, không cần API Key, hoạt động ngoại tuyến và hỗ trợ cài đặt Progressive Web App (PWA).

---

## ✨ Tính Năng Nổi Bật

- **Hệ Thống Quỹ Đạo Vệ Tinh (Interactive Orbital Satellites)**: Các đường quỹ đạo elip phát sáng và vệ tinh kính mờ Glassmorphism trôi dập dềnh quanh quả cầu trung tâm. Sợi dây Laser Tether kết nối và tự động bung nở thẻ lời tiên tri khi có kết quả.
- **Hệ Thống Lời Tiên Tri Cổ Điển**: Các nhóm phán quyết Tích cực, Trung lập và Tiêu cực chuẩn Magic 8-Ball kèm diễn giải tiếng Việt tự nhiên, trực quan.
- **Công Nghệ Ngẫu Nhiên Provably Fair**: Sử dụng `crypto.getRandomValues` kết hợp khóa băm SHA-256 an toàn chạy ngầm cho từng lượt gieo quẻ.
- **Tối Ưu Mobile & Màn Hình Dọc**: Bố cục 1 màn hình duy nhất (Zero Scroll) trên iPhone và Android.
- **Cảm Biến Lắc Điện Thoại (Shake)**: Lắc máy vật lý để gieo quẻ (hỗ trợ cả iOS Safari và Android).
- **Phản Hồi Rung Xúc Giác (Haptic Vibration)**: Rung điện thoại khi lắc, chạm giữ nạp lực và khi nổi mặt xúc xắc.
- **Âm Thanh Mô Phỏng (Procedural Web Audio)**: Tiếng sóng sánh chất lỏng và hợp âm ngân vang khi hiện kết quả.
- **2 Giao Diện Cao Cấp**: Obsidian Glass sang trọng & Cyber-Terminal CRT phong cách hacker.
- **Tiêu Chuẩn PWA**: Chạy toàn màn hình (Standalone) không thanh URL như app native iOS/Android, hỗ trợ chơi Offline khi mất mạng.

---

## 🚀 Hướng Dẫn Deploy Lên GitHub Pages Trong 2 Phút

### Cách 1: Đẩy bằng Dòng Lệnh Git (Khuyên Dùng)

Mở Terminal / PowerShell ngay trong thư mục `classic-8-ball`:

```bash
# 1. Khởi tạo kho git
git init

# 2. Thêm tất cả tệp
git add .

# 3. Tạo commit
git commit -m "Phát hành bản Magic 8-Ball Classic PWA"

# 4. Đổi tên nhánh chính
git branch -M main

# 5. Thêm địa chỉ kho GitHub của bạn (thay bằng link repo của bạn)
git remote add origin https://github.com/<ten-tai-khoan>/<ten-repo>.git

# 6. Đẩy code lên GitHub
git push -u origin main
```

---

### Cách 2: Kéo Thả Trực Tiếp Trên Web GitHub

1. Truy cập [github.com](https://github.com), tạo một **New repository** (chọn chế độ **Public**).
2. Bấm vào dòng chữ **"uploading an existing file"**.
3. Kéo thả toàn bộ các tệp trong thư mục `classic-8-ball` này lên:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.svg`
   - `icon-512.svg`
   - `README.md`
4. Bấm **Commit changes**.

---

## ⚙️ Kích Hoạt GitHub Pages

1. Tại repository trên GitHub, vào **Settings** -> Mục **Pages** ở cột bên trái.
2. Tại mục **Branch**, chọn `main` và thư mục `/ (root)` -> Bấm **Save**.
3. Sau 1-2 phút, GitHub sẽ cấp link website:
   👉 `https://<ten-tai-khoan>.github.io/<ten-repo>/`

Mở link trên điện thoại và chọn **"Thêm vào Màn hình chính" (Add to Home Screen)** để cài đặt ứng dụng!
