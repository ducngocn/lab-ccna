<div align="center">
  <img src="https://img.shields.io/badge/Cisco-Packet_Tracer-blue?style=for-the-badge&logo=cisco" alt="Cisco Packet Tracer">
  <img src="https://img.shields.io/badge/CCNA-Lab_Practice-brightgreen?style=for-the-badge" alt="CCNA Lab">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" alt="Completed">

  <h1>🌐 CCNA Lab: Định tuyến tĩnh, VLAN, HSRP & DHCP</h1>
  <p><i>Bài thực hành tổng hợp kiến thức mạng CCNA thực chiến trên Cisco Packet Tracer</i></p>
</div>

---

## 📖 Về bài thực hành này (About)
Repository này lưu trữ tài liệu và cấu hình cho bài thực hành mạng máy tính (CCNA). Bài Lab mô phỏng một hệ thống mạng doanh nghiệp thu nhỏ, nơi các giao thức định tuyến, phân chia mạng và dự phòng được áp dụng thực tế để đảm bảo hệ thống mạng luôn hoạt động ổn định.

**Các công nghệ chính được ứng dụng:**
- 🛣️ **Định tuyến tĩnh (Static Routing):** Cấu hình đường đi thủ công cho các router để kết nối các mạng nội bộ.
- 🏢 **VLAN (Virtual Local Area Network):** Phân chia mạng vật lý thành nhiều mạng logic, tối ưu hóa băng thông và bảo mật mạng.
- 🛡️ **HSRP (Hot Standby Router Protocol):** Thiết lập cơ chế dự phòng Default Gateway (Active/Standby) để mạng không bao giờ bị mất kết nối khi có sự cố thiết bị.
- 🔄 **DHCP (Dynamic Host Configuration Protocol):** Cấp phát địa chỉ IP hoàn toàn tự động cho các thiết bị đầu cuối.

---

## 📂 Danh sách file
| Tên file | Mô tả |
|----------|-------|
| 📄 [`De_bai_Thuc_hanh_Mang.docx`](./De_bai_Thuc_hanh_Mang.docx) | Đề bài chi tiết và yêu cầu cấu hình của bài thực hành. |
| 💾 [`HSRP-DHCP.pkt`](./HSRP-DHCP.pkt) | File mô phỏng thiết kế mạng trên phần mềm Cisco Packet Tracer. |

---

## 🖼️ Sơ đồ mạng (Topology)
![Sơ đồ Lab](image.png)

---

## 🚀 Hướng dẫn cài đặt & thực hành
1. **Tải mã nguồn:** 
   Clone repository này về máy tính bằng lệnh:
   ```bash
   git clone https://github.com/ducngocn/lab-ccna.git
   ```
2. **Chuẩn bị môi trường:** Đảm bảo máy tính của bạn đã được cài đặt phần mềm **Cisco Packet Tracer** (khuyến nghị phiên bản mới nhất).
3. **Thực hành:** 
   - Đọc yêu cầu chi tiết trong file Word (`.docx`).
   - Mở file `.pkt` bằng Packet Tracer.
   - Click vào các Router/Switch, mở tab CLI và tiến hành gõ lệnh cấu hình hệ thống.

---
<div align="center">
  <i>Được xây dựng và hoàn thiện bởi Nguyễn Ngọc Đức • 2026</i>
</div>
