## 1. Khái niệm vòng đời lỗi

**Vòng đời lỗi**: Tập hợp các trạng thái mà một lỗi (bug) trải qua từ khi phát hiện đến khi đóng.

**Mục đích**: Giúp phối hợp, truyền đạt trạng thái, đảm bảo xử lý có hệ thống và hiệu quả.

> Trạng thái lỗi phụ thuộc vào dự án, công cụ quản lý lỗi, quy trình phát triển.

---

## 2. Các trạng thái phổ biến

- **New** → Tester phát hiện lỗi, log trên hệ thống.
- **Assigned** → Trưởng nhóm kiểm thử xác nhận hợp lệ, giao cho trưởng nhóm lập trình.
- **Open** → Trưởng nhóm lập trình chấp nhận, giao cho dev xử lý.
- **Fixed** → Dev sửa xong, cập nhật trạng thái.
- **Pending Retest** → Chờ tester kiểm tra lại.
- **Retest** → Tester xác nhận sẽ test lại lỗi.
- **Verified** → Lỗi đã được khắc phục, không tái diễn và không phát sinh lỗi mới.
- **Closed** → Kết thúc vòng đời lỗi.
- **Reopen** → Lỗi tái diễn hoặc phát sinh lỗi mới.

---

## 3. Các trạng thái đặc biệt

- **Duplicate**: Trùng với lỗi đã tồn tại.
- **Rejected**: Không hợp lệ, mô tả sai, thiếu thông tin hoặc không tái hiện được.
- **Deferred / Pending**: Lỗi hợp lệ nhưng không ưu tiên sửa ngay, để phiên bản sau.
- **Not a Bug**: Không phải lỗi, chỉ là đề xuất cải tiến hoặc vấn đề UI/UX.

---

## 4. Báo cáo lỗi (Bug Report)

Thông tin quan trọng cần có:

1. **Bug ID** – Mã định danh.
2. **Description** – Mô tả chi tiết, module chức năng, phiên bản ứng dụng.
3. **Steps to Reproduce** – Các bước tái hiện lỗi kèm hình ảnh/video.
4. **Expected Result** – Kết quả mong muốn.
5. **Actual Result** – Kết quả thực tế.
6. **Attachments** – File, ảnh, tài liệu liên quan.
7. **Status**, **Severity**, **Priority**.

---

## 5. Độ nghiêm trọng & Độ ưu tiên

- **Severity (Độ nghiêm trọng)**: Mức ảnh hưởng đến chức năng phần mềm.
  - Xác định bởi tester.
  - Mang tính khách quan, ít thay đổi.

- **Priority (Độ ưu tiên)**: Thứ tự cần xử lý.
  - Xác định bởi PM/khách hàng.
  - Mang tính chủ quan, thay đổi theo tình hình dự án.

**Khác biệt chính**:
- **Severity** → Liên quan đến **tầm quan trọng** của lỗi.
- **Priority** → Liên quan đến **thời điểm** cần sửa lỗi.
