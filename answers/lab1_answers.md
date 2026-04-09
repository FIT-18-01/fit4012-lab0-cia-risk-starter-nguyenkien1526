# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Nguyễn Trung Kiên

**MSSV:** 1871020345

**Lớp/Nhóm:** CNTT 18-01

---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1: Dữ liệu điểm của sinh viên
- Asset 2: Tài khoản đăng nhập (giảng viên, sinh viên)
- Asset 3: Hệ thống server / cơ sở dữ liệu

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A -> Availability (Không đăng nhập được → hệ thống không sẵn sàng)
- Sự cố B -> Integrity (Điểm bị thay đổi sai → mất tính toàn vẹn)
- Sự cố C -> Confidentiality (Lộ dữ liệu → mất tính bảo mật)

---

## 3. Phân tích sự cố B
- Threat: Hacker hoặc người dùng nội bộ sửa điểm trái phép
- Vulnerability: Không có kiểm soát quyền truy cập hoặc thiếu log/kiểm tra thay đổi dữ liệu
- Mitigation: 
  - Áp dụng phân quyền rõ ràng (RBAC)
  - Ghi log và kiểm tra thay đổi dữ liệu
  - Sử dụng xác thực mạnh (2FA)

---

## 4. Reflection
- Qua bài lab, em hiểu rõ hơn về mô hình CIA.
- Mỗi sự cố đều liên quan đến một yếu tố trong CIA 
- Phần khó nhất là phân biệt giữa threat và vulnerability.  
- Threat là tác nhân gây hại, còn vulnerability là điểm yếu của - - hệ thống (còn mitigation là giảm thiểu rủi ro).
- Học được cách đề xuất giải pháp mitigation phù hợp
---

## 5. Bonus Flag
`FIT4012{A-Availability-B-Integrity-C-Confidentiality}`

Flag của em:
`FIT4012{A-Availability-B-Integrity-C-Confidentiality}`
