
## 1. Kiểm thử hộp đen (Black-box Testing)
- Kiểm tra chức năng phần mềm **không cần biết code hay cấu trúc bên trong**.
- Dựa vào **yêu cầu/đặc tả** để thiết kế test case.

---

## 2. Phân vùng tương đương (Equivalence Partitioning)
- Chia input thành **nhóm hợp lệ** và **không hợp lệ**.
- Mỗi nhóm chỉ cần chọn 1 giá trị đại diện để test.

**Ví dụ:**  
Nhập số tầng từ `0–10`  
- Hợp lệ: 0 → 10  
- Không hợp lệ: `<0`, `>10`, ký tự không phải số

---

## 3. Phân tích giá trị biên (Boundary Value Analysis)
- Lỗi thường xuất hiện ở **giá trị ranh giới**.
- Test các giá trị:
  - Nhỏ hơn biên 1 đơn vị
  - Đúng bằng biên
  - Lớn hơn biên 1 đơn vị

**Ví dụ:**  
Khoảng 0–10 → Test: `-1`, `0`, `5`, `10`, `11`, ký tự không phải số

---

## 4. Bảng quyết định (Decision Table)
- Dùng khi yêu cầu liên quan đến **kết hợp nhiều điều kiện**.
- Các bước:
  1. Xác định điều kiện
  2. Liệt kê tất cả trường hợp (2^n)
  3. Xác định kết quả mong đợi

**Ví dụ:**  
Form đăng nhập:
| Email hợp lệ? | Password hợp lệ? | Kết quả                 |
|---------------|------------------|-------------------------|
| Có            | Có               | Đăng nhập thành công    |
| Có            | Không            | Báo lỗi                  |
| Không         | Có               | Báo lỗi                  |
| Không         | Không            | Báo lỗi                  |

---

## 5. Đoán lỗi (Error Guessing)
- Dựa vào **kinh nghiệm và trực giác** để đoán chỗ dễ có lỗi.
- Không theo quy tắc cố định.

**Ví dụ:**
- Nhập ký tự đặc biệt vào ô số tầng
- Để trống trường bắt buộc
- Nhập dữ liệu quá dài
