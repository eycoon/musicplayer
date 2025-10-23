# 🎵 Circle Music App

**Circle Music App** là một giao diện web mô phỏng ứng dụng nghe nhạc hiện đại, được thiết kế với bố cục 3 cột (Sidebar – Main – Rightbar) và thanh phát nhạc (Footer Player).  
Giao diện mang phong cách **Glassmorphism + Neon Gradient**, lấy cảm hứng từ Spotify và YouTube Music.

---

## 🧩 Mục tiêu dự án

- Xây dựng giao diện nghe nhạc bằng **HTML + CSS thuần túy** (không cần JavaScript).  
- Thực hành bố cục **CSS Grid + Flexbox**.  
- Tạo cảm giác giao diện chuyên nghiệp, hiện đại, và tương tác mượt mà.  
- Ứng dụng **hiệu ứng động (hover, animation, transition)** và **màu sắc gradient neon**.

---

## 🚀 Tính năng giao diện

### 🔹 Sidebar (thanh điều hướng bên trái)
- Chứa logo **Circle** và danh mục điều hướng:
  - Home  
  - Search  
  - Playlists  
  - Notifications  
  - Premium⭐  
- Ở cuối có thông tin người dùng với ảnh đại diện.
- Hover có hiệu ứng **glow + dịch chuyển nhẹ**, tạo cảm giác tương tác thực.

### 🔹 Main Content (phần nội dung chính)
- **Thanh header:** chứa tag lọc nhạc (Music, Podcasts, Jazz,...) và thanh tìm kiếm.
- **Popular Albums:** hiển thị các album nổi bật (hình ảnh + tên + nghệ sĩ).
- **Picked for you:** playlist được chọn gợi ý.
- **Recent:** danh sách các bài hát gần đây, có hover sáng nhẹ.

### 🔹 Rightbar (thanh bên phải)
- Danh sách **Popular Artists** (dạng grid 3x3).  
- Danh sách **Top Podcasts**.  
- Hover hình ảnh có hiệu ứng phóng to + đổ bóng neon.

### 🔹 Player (Footer)
- Thanh phát nhạc hiện đại gồm:
  - Thông tin bài hát (ảnh, tên, nghệ sĩ, biểu tượng tim).  
  - Nút điều khiển: ⏮ ⏯ ⏭  
  - Thanh tiến trình với thời gian hai bên.  
  - Điều chỉnh âm lượng + chế độ toàn màn hình.  
- Có hiệu ứng gradient **xanh–tím–cyan** và **phát sáng nhẹ** khi hover.

---

## 💅 Công nghệ sử dụng

| Thành phần | Công nghệ |
|-------------|------------|
| Cấu trúc giao diện | HTML5 |
| Thiết kế & hiệu ứng | CSS3 (Flexbox + Grid + Animation + Gradient + Blur) |
| Font chữ | [Poppins](https://fonts.google.com/specimen/Poppins) |
| Ảnh minh họa | [Picsum Photos](https://picsum.photos) & [Pravatar](https://i.pravatar.cc) |

---

## 📂 Cấu trúc thư mục

```
📁 Circle-Music-App
│
├── index.html       # File giao diện chính
├── style.css        # File định dạng giao diện
└── README.md        # Tài liệu mô tả dự án
```

---

## ⚙️ Cách chạy dự án

1. Tải toàn bộ thư mục về máy.  
2. Mở file **`index.html`** bằng trình duyệt bất kỳ (Chrome, Edge, Firefox,...).  
3. Giao diện sẽ hiển thị ứng dụng nghe nhạc giả lập.

---

## 🌈 Nâng cấp giao diện (CSS cải tiến)

Phần CSS mở rộng được thêm vào cuối file `style.css`:
- Nâng cấp màu nền với **radial-gradient** lam tím.  
- Tăng độ sáng, độ nổi khối (glass blur, shadow).  
- Thêm **hover glow** và **animation chuyển động nhẹ**.  
- Tăng tính thẩm mỹ của **Player bar**, tạo cảm giác chuyên nghiệp hơn.

Hiệu ứng chính được bổ sung:
```css
.sidebar nav li:hover,
.sidebar nav .active {
  background: rgba(96, 165, 250, 0.2);
  color: #60a5fa;
  transform: translateX(8px);
}

.album-card:hover {
  transform: translateY(-10px) scale(1.03);
  box-shadow: 0 8px 25px rgba(99, 102, 241, 0.3);
}

.player {
  background: linear-gradient(90deg, #6366f1, #3b82f6, #06b6d4);
  box-shadow: 0 0 20px rgba(99, 102, 241, 0.4);
}
```

---

## 💡 Gợi ý mở rộng
Nếu muốn phát triển thêm:
- 🎚 Thêm **chế độ sáng – tối (Dark/Light Mode)** bằng JavaScript toggle.  
- 🎵 Kết hợp **Audio API** để điều khiển phát nhạc thật.  
- 🔄 Tạo **hiệu ứng equalizer động** khi nhạc phát.  
- 🧠 Dùng **React hoặc Vue** để biến thành ứng dụng nghe nhạc tương tác.

---

## ✨ Tác giả
Me

---

> 🖤 “Music is not just sound — it’s the rhythm of your code.”
<img width="1857" height="967" alt="image" src="https://github.com/user-attachments/assets/39b55a73-a9f6-4006-b481-3ab0293c1158" />
