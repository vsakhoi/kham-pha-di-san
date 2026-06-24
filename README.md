[README.md](https://github.com/user-attachments/files/29274002/README.md)
# 🏛️ Khám Phá Di Sản Việt

> Board game giáo dục trực tuyến về Di sản Văn hóa và Thiên nhiên Việt Nam được UNESCO công nhận.

---

## 🎮 Giới thiệu

**Khám Phá Di Sản Việt** là một trò chơi board game chạy trên trình duyệt, giúp người chơi khám phá và học hỏi về các di sản thế giới, di sản phi vật thể, di sản tư liệu và khu dự trữ sinh quyển của Việt Nam thông qua các câu hỏi trắc nghiệm và thẻ sự kiện thú vị.

---

## ✨ Tính năng

- 🎲 **Chế độ Single Player** — chơi một mình, tự khám phá bản đồ di sản
- 👥 **Chế độ Multiplayer** — chơi online 2 người theo thời gian thực qua Firebase Realtime Database
- 💬 **Chat trong phòng** — nhắn tin với đối thủ ngay trong game
- 🧩 **Câu hỏi trắc nghiệm** — hơn 27 câu hỏi về di sản Việt Nam
- 🃏 **Thẻ Cơ Hội & Khí Vận** — dịch chuyển đến các ô di sản đặc biệt hoặc nhận hiệu ứng bất ngờ
- 🏅 **Hệ thống Ấn Tín** — thu thập 4 loại ấn tín: Di sản Thế giới, Phi vật thể, Di sản Tư liệu, Khu sinh quyển
- 🎵 **Nhạc nền** — bật/tắt nhạc nền trong game
- ⏱️ **Bộ đếm thời gian** — mỗi lượt có 15 giây để gieo xúc xắc

---

## 🗺️ Cách chơi

1. Truy cập `index.html` (Multiplayer) hoặc `1-main.html` (Single Player)
2. Gieo xúc xắc để di chuyển quân cờ trên bản đồ
3. Dừng ở các ô đặc biệt để:
   - **Câu hỏi** — trả lời đúng để tiến thêm, sai thì lùi 2 ô
   - **Cơ Hội** — bốc thẻ và dịch chuyển đến ô di sản tương ứng
   - **Khí Vận** — nhận hiệu ứng ngẫu nhiên (tiến/lùi)
   - **Ô Di sản** — thu thập ấn tín cho loại di sản đó
4. Người đầu tiên thu thập đủ **4 ấn tín** và về đến ô đích sẽ **chiến thắng**!

---

## 📁 Cấu trúc dự án

```
kham-pha-di-san/
├── index.html        # Chế độ Multiplayer (Firebase)
├── 1-main.html       # Chế độ Single Player
└── assets/
    ├── sa ban.png    # Bản đồ bàn chơi
    ├── nam.jpg       # Quân cờ Người 1
    ├── nu.jpg        # Quân cờ Người 2
    ├── C1–C20.jpg    # Thẻ Cơ Hội (20 di sản)
    ├── kv*.png       # Thẻ Khí Vận
    ├── move.mp3      # Âm thanh di chuyển
    ├── win.mp3       # Âm thanh chiến thắng
    └── bg.mp3        # Nhạc nền
```

---

## 🚀 Cài đặt & Chạy

Không cần cài đặt thêm gì. Chỉ cần mở file HTML trong trình duyệt:

```bash
# Clone repo
git clone https://github.com/vsakhoi/kham-pha-di-san.git
cd kham-pha-di-san

# Mở trực tiếp trong trình duyệt
open index.html         # Multiplayer
open 1-main.html        # Single Player
```

> **Lưu ý:** Chế độ Multiplayer yêu cầu kết nối internet để sử dụng Firebase Realtime Database.

---

## 🔥 Multiplayer — Hướng dẫn tạo & tham gia phòng

1. Người chơi 1 mở `index.html` → một **Room ID** sẽ được tạo tự động
2. Nhấn **📋 Copy link** để sao chép đường link phòng
3. Gửi link cho Người chơi 2 → họ mở link đó để tham gia
4. Hai người có thể chat và chơi theo lượt cùng nhau!

---

## 🏛️ Các di sản xuất hiện trong game

| Loại | Ví dụ |
|------|-------|
| Di sản Thế giới | Cố đô Huế, Phố cổ Hội An, Thánh địa Mỹ Sơn, Vịnh Hạ Long, Tràng An... |
| Phi vật thể | Nhã nhạc Huế, Đờn ca tài tử, Cồng chiêng Tây Nguyên, Quan họ, Ca Trù... |
| Di sản Tư liệu | Mộc bản triều Nguyễn, Bia Tiến sĩ Văn Miếu |
| Khu sinh quyển | Khu dự trữ sinh quyển Đồng Nai |

---

## 🛠️ Công nghệ sử dụng

- **HTML / CSS / JavaScript** — thuần, không dùng framework
- **Firebase Realtime Database** — đồng bộ trạng thái game multiplayer theo thời gian thực

---

## 📜 Giấy phép

Dự án được phát triển với mục đích **giáo dục**. Nội dung di sản tham khảo từ UNESCO và các nguồn chính thống của Việt Nam.
