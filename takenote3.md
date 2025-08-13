# Các loại kiểm thử phần mềm

## 1. Smoke Testing
- Kiểm tra nhanh các chức năng chính của phần mềm sau khi có bản build mới.
- **Mục tiêu:** Đảm bảo hệ thống ổn định trước khi thực hiện test chi tiết hơn.
- Giống như *“khám sức khỏe tổng quát”* của phần mềm.

---

## 2. Sanity Testing
- Kiểm tra hợp lý của hệ thống sau khi có thay đổi nhỏ hoặc sửa lỗi.
- **Mục tiêu:** Xác minh lỗi đã được sửa và các chức năng liên quan vẫn hoạt động đúng.
- Giống như *“khám sức khỏe chuyên sâu”* cho một khu vực cụ thể.

---

## 3. So sánh Smoke vs Sanity

| Tiêu chí        | Smoke Testing                          | Sanity Testing                         |
|-----------------|----------------------------------------|-----------------------------------------|
| Phạm vi         | Toàn bộ chức năng chính                | Chức năng cụ thể                        |
| Tài liệu/script | Có                                     | Không cần                               |
| Mục tiêu        | Xác minh tính ổn định                  | Xác minh tính hợp lý                    |

---
## 4. Confirmation Testing
- Còn gọi là kiểm thử xác nhận.
- Test lại lỗi đã được fix để đảm bảo lỗi biến mất và không ảnh hưởng vùng liên quan.

---

## 5. Regression Testing
- Kiểm tra lại các chức năng cũ sau khi có thay đổi (thêm tính năng mới, sửa lỗi, nâng cấp…).
- **Mục tiêu:** Đảm bảo các chức năng cũ vẫn hoạt động đúng.
- Có thể kết hợp **tự động hóa**.

---

## 6. So sánh Confirmation vs Regression

| Tiêu chí         | Confirmation Testing         | Regression Testing                       |
|------------------|------------------------------|-------------------------------------------|
| Phạm vi          | Chỉ test lại đúng lỗi đã fix | Test toàn bộ chức năng cũ bị ảnh hưởng   |
| Mục tiêu         | Xác nhận lỗi biến mất        | Đảm bảo hệ thống cũ không bị hỏng         |

---

## 7. Exploratory Testing (Ad-hoc Testing)
- Kiểm thử ngẫu hứng, không theo tài liệu hay quy trình cố định.
- **Ưu điểm:** Nhanh, linh hoạt, dễ phát hiện lỗi bất ngờ.
- **Nhược điểm:** Khó tái hiện lỗi vì không ghi lại bước test.
- Thường dùng:
  - Trước khi bàn giao sản phẩm
  - Khi có thời gian dư

