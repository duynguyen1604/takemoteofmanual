# Tổng quan về kiểm thử phần mềm

## 1. Giới thiệu tổng quan
- Kiểm thử phần mềm là quá trình đánh giá một hệ thống phần mềm để xác định xem nó có đáp ứng đúng yêu cầu hay không và phát hiện lỗi nếu có.
- Kiểm thử không chỉ tìm lỗi mà còn **đánh giá chất lượng phần mềm**.

---

## 2. Mục tiêu của kiểm thử phần mềm
- Đảm bảo phần mềm hoạt động đúng theo yêu cầu.
- Phát hiện lỗi sớm nhất có thể.
- Nâng cao chất lượng sản phẩm trước khi release.
- Giảm chi phí bảo trì và sửa lỗi về sau.
- Tăng niềm tin của người dùng cuối vào phần mềm.

---

## 3. Phân biệt Error – Bug – Failure

| Thuật ngữ  | Định nghĩa                                                                 | Ví dụ                                      |
|------------|----------------------------------------------------------------------------|---------------------------------------------|
| **Error**  | Sai sót do con người gây ra trong quá trình phát triển phần mềm            | Lập trình viên code sai logic               |
| **Bug**    | Lỗi được tìm thấy trong phần mềm, hậu quả của **Error**                     | Lỗi hiển thị hoặc chức năng sai trong ứng dụng |
| **Failure**| Khi phần mềm không hoạt động đúng, gây ra sự cố trong thực tế               | Hệ thống bị crash khi người dùng sử dụng    |

---

## 4. Quy trình phát triển phần mềm (SDLC)

1. **Requirement Analysis** – Phân tích yêu cầu  
2. **System Design** – Thiết kế hệ thống  
3. **Implementation (Coding)** – Lập trình  
4. **Testing** – Kiểm thử  
5. **Deployment** – Triển khai  
6. **Maintenance** – Bảo trì  

---

## 5. Quy trình kiểm thử phần mềm (STLC)

1. **Requirement Analysis** – Phân tích yêu cầu kiểm thử  
2. **Test Planning** – Lập kế hoạch kiểm thử  
3. **Test Case Design** – Viết test case  
4. **Test Environment Setup** – Chuẩn bị môi trường kiểm thử  
5. **Test Execution** – Thực thi test case  
6. **Test Closure** – Kết thúc kiểm thử, báo cáo  

---

## 6. Bảy nguyên tắc kiểm thử phần mềm

1. **Kiểm thử giúp phát hiện lỗi**, không đảm bảo phần mềm hoàn toàn không có lỗi.  
2. **Không thể kiểm thử hết tất cả trường hợp** – cần chọn lọc và ưu tiên.  
3. **Bắt đầu kiểm thử càng sớm càng tốt** trong SDLC.  
4. Một số module thường chứa **nhiều lỗi hơn** các phần khác.  
5. **Dùng mãi một bộ test** sẽ khó phát hiện lỗi mới → cần cập nhật test case.  
6. **Kiểm thử phụ thuộc vào bối cảnh dự án** (web, mobile, banking…).  
7. **Phần mềm không có lỗi chưa chắc đã đúng yêu cầu** của người dùng.  
