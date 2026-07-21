# 🌟 Luật Nhân Quả - Cung Trời Hoá Lạc

<p align="center">
  <img src="https://img.shields.io/badge/Version-2.0.0-gold?style=for-the-badge" alt="Version 2.0.0">
  <img src="https://img.shields.io/badge/Max--Ph%C6%B0%E1%BB%9Bc-5.000.000.000-orange?style=for-the-badge" alt="Max Phuoc 5 Billion">
  <img src="https://img.shields.io/badge/T%E1%BB%B7_L%E1%BB%87-100_Ph%C6%B0%E1%BB%9Bc_=_1_Ph%C3%A9p-yellow?style=for-the-badge" alt="Conversion Rate">
  <img src="https://img.shields.io/badge/Platform-Acode_%7C_Web-blue?style=for-the-badge" alt="Platform Acode Web">
</p>

Ứng dụng Web đơn giản mô phỏng hệ thống **Tích Luỹ Phước Báo** và quy đổi thành **Phép Thuật Cung Trời Hoá Lạc** dựa trên quy luật Nhân Quả. Dự án thiết kế tối ưu cho các trình duyệt di động và công cụ soạn thảo **Acode**.

---

## 📋 Mục Lục

- [✨ Tính Năng Nổi Bật](#-tính-năng-nổi-bật)
- [📊 Quy Định Tích Phước & Phép Thuật](#-quy-định-tích-phước--phép-thuật)
- [🚀 Hướng Dẫn Chạy Trên Acode](#-hướng-dẫn-chạy-trên-acode)
- [💻 Mã Nguồn Trọn Gói (`index.html`)](#-mã-nguồn-trọn-gói-indexhtml)
- [🛠 Công Nghệ Sử Dụng](#-công-nghệ-sử-dụng)

---

## ✨ Tính Năng Nổi Bật

- **Mục tiêu Phước Báo cao:** Nâng giới hạn tích luỹ lên tới **5.000.000.000 (5 Tỷ Phước)**.
- **Hệ thống Quy Đổi Phép Thuật:** Cứ **100 Phước Báo = 1 Phép Thuật** ở Cung Trời Hoá Lạc.
- **14 Danh Mục Thiện Hạnh:** Tích lũy phước từ cấp độ nhỏ (Khẩu Thiện +10) đến tối đại công đức (Xây Đền Chùa +10.000.000).
- **Thanh Tiến Trình Rõ Ràng:** Trực quan hóa % phước báo đã tích lũy.
- **Nút Reset Dữ Liệu:** Đặt lại toàn bộ dữ liệu về 0 với hộp thoại xác nhận an toàn.
- **Tự Động Lưu Dữ Liệu:** Tự ghi nhớ số phước qua `localStorage`, không mất dữ liệu khi đóng ứng dụng.

---

## 📊 Quy Định Tích Phước & Phép Thuật

| Hành Động Thiện Hạnh | Phước Báo Nhận Được | Loại Công Đức |
| :--- | :---: | :---: |
| Nói lời hòa nhã | **+10** | Khẩu Thiện |
| Giúp đỡ người khó khăn | **+50** | Thân Thiện |
| Ấn tạc kinh sách / Cung kính | **+100** | Ý Thiện |
| Phóng sinh & Cứu mạng | **+500** | Đại Thiện |
| Tùy hỷ công đức | **+1.000** | Tùy Hỷ |
| Cúng dâng Tam Bảo | **+5.000** | Cúng Cúng |
| Hiếu kính bố mẹ | **+10.000** | Hiếu Đạo |
| Xây cầu làm đường | **+50.000** | Lợi Chúng |
| Trồng rừng bảo vệ môi trường | **+100.000** | Hộ Sinh |
| Xây trường học & Giúp học sinh | **+500.000** | Khuyến Học |
| Xây nhà tình thương | **+1.000.000** | An Cư |
| Xây bệnh viện & Cứu chữa người | **+2.000.000** | Y Đạo |
| Truyền bá tri thức & Lời hay ý đẹp | **+5.000.000** | Khai Trí |
| Xây đền chùa & Nơi tu tập | **+10.000.000** | Đại Công Đức |

---

## 🚀 Hướng Dẫn Chạy Trên Acode

1. Mở ứng dụng **Acode** trên thiết bị di động.
2. Tạo một file mới và lưu tên là `index.html`.
3. Copy toàn bộ code HTML/JS/CSS ở mục dưới dán vào file `index.html`.
4. Nhấn nút **Play ▶** góc trên màn hình để khởi chạy trang web trực tiếp.

---

## 💻 Mã Nguồn Trọn Gói (`index.html`)

```html
<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Luật Nhân Quả - Tích Phước Hoá Lạc</title>
  <style>
    :root {
      --primary: #ffd700;
      --bg: #121212;
      --card-bg: #1e1e2e;
      --text: #e0e0e0;
      --accent: #ff9800;
      --danger: #f44336;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: var(--bg);
      color: var(--text);
      margin: 0;
      padding: 15px;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .container {
      width: 100%;
      max-width: 550px;
    }

    h1 {
      text-align: center;
      color: var(--primary);
      margin-bottom: 5px;
      font-size: 24px;
    }

    p.subtitle {
      text-align: center;
      font-size: 13px;
      color: #aaa;
      margin-top: 0;
      margin-bottom: 20px;
    }

    .stats-card {
      background-color: var(--card-bg);
      border: 1px solid #333;
      border-radius: 12px;
      padding: 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.5);
      margin-bottom: 20px;
    }

    .stat-row {
      display: flex;
      justify-content: space-between;
      margin-bottom: 10px;
      font-size: 15px;
    }

    .stat-value {
      font-weight: bold;
      color: var(--primary);
    }

    .progress-bar-container {
      width: 100%;
      background-color: #333;
      border-radius: 10px;
      height: 18px;
      overflow: hidden;
      margin-top: 8px;
    }

    .progress-bar {
      height: 100%;
      background: linear-gradient(90deg, #ff9800, #ffd700);
      width: 0%;
      transition: width 0.3s ease;
    }

    .actions {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 10px;
      margin-bottom: 20px;
    }

    button {
      background-color: var(--card-bg);
      color: #fff;
      border: 1px solid var(--accent);
      padding: 12px 10px;
