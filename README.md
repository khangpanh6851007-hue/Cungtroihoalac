# 🌌 Cung Trời Hóa Lạc — Tích Phước Báo & Mở Khóa Thần Thông

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)

Ứng dụng Web tương tác giúp ghi nhận & theo dõi tiến trình **Tích Phước Báo** qua các việc làm thiện nguyện thực tế. Mỗi mốc điểm phước đạt được sẽ tự động mở khóa các cấp độ **Thần Thông & Quyền Phép** mô phỏng cảnh giới cõi **Trời Hóa Lạc**.

> **⚡ Điểm nổi bật:** Tích hợp cơ chế **Đồng bộ Đám mây (Realtime Sync)** — Mọi thay đổi điểm số trên một thiết bị sẽ lập tức cập nhật thời gian thực trên tất cả các màn hình khác đang mở web.

---

## 🌟 Tính Năng Chính

- **🔄 Đồng bộ đa thiết bị (Realtime Sync):** Kết nối trực tiếp với Firebase Realtime Database. Dữ liệu Phước Báo luôn nhất quán giữa máy tính, điện thoại và người dùng khác nhau.
- **✨ 500 Cấp Độ Phép Hóa Lạc:** Cứ mỗi **100 Phước Báo** thu thập được, bạn sẽ mở khóa 1 Phép Thần Thông tương ứng:
  - *Phép 1–50:* Thuận Ý Y Phục & Thực Phẩm
  - *Phép 51–150:* Biến Cảnh Cung Điện & Lâu Đài
  - *Phép 151–300:* Tịnh Nhãn & Phi Hành Thời Không
  - *Phép 301–450:* Diễn Xướng Pháp Âm An Lạc
  - *Phép 451–500:* Đại Tự Tại Viên Mãn
- **📋 Danh Sách Nhiệm Vụ Giúp Người:** Gợi ý các hành động thiết thực (Phát cơm, hiến máu, bảo trợ học sinh, xây nhà tình nghĩa...) kèm phần thưởng Phước Báo tương ứng.
- **🔒 Bảng Quản Trị Tùy Chỉnh (Admin Control):** Tích hợp tính năng cộng/trừ điểm thủ công hoặc reset dữ liệu, bảo mật bằng Admin Key.

---

## ⚙️ Thông Số Cấu HÌnh Mặc Định

| Thông số | Giá trị mặc định |
| :--- | :--- |
| **Tỷ lệ quy đổi** | `100 Phước Báo` = `1 Phép Thần Thông` |
| **Mục tiêu tối đa** | `50.000 Phước Báo` (500 Phép) |
| ** Key** | `*******` |
| **Database** | Firebase Realtime Database |

---

## 🚀 Hướng Dẫn Chạy Dự Án

### 1. Chạy cục bộ (Local)
Không cần cài đặt Node.js hay Build tool phức tạp:
1. Clone repository về máy:
   ```bash
   git clone [https://github.com/username/cung-troi-hoa-lac.git](https://github.com/username/cung-troi-hoa-lac.git)
