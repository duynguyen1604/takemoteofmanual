# Bài học: Test Scenario & Test Case

## 1. Khái niệm
- **Test Scenario** (Kịch bản kiểm thử)  
  - Mô tả *cái gì* cần kiểm thử dựa trên requirement.  
  - Không mô tả chi tiết từng bước hay dữ liệu test.  
  - Kiểm tra luồng từ đầu tới cuối, bao quát nhiều trường hợp.

- **Test Case** (Trường hợp kiểm thử)  
  - Mô tả *cách* thực hiện kiểm thử.  
  - Gồm các bước thao tác, điều kiện tiên quyết, dữ liệu test, kết quả mong đợi.  
  - Mỗi test case chỉ kiểm tra **1 tình huống duy nhất**.

## 2. Mối quan hệ
Requirement → **Test Scenario** → **Test Case**  
(Test Case là tập con của Test Scenario)

## 3. Thành phần của Test Case Template
- **Test Case ID**: Mã định danh (mã dự án + số thứ tự).
- **Priority**: Độ ưu tiên (Cao / Trung bình / Thấp).
- **Module Name**: Tên module hoặc chức năng kiểm thử.
- **Test Designed By / Date**: Người viết và ngày viết.
- **Precondition**: Điều kiện tiên quyết.
- **Dependence**: Phụ thuộc vào test case khác.
- **Test Steps**: Các bước thao tác.
- **Test Data**: Dữ liệu kiểm thử.
- **Expected Result**: Kết quả mong đợi (từ tài liệu yêu cầu).
- **Post-condition**: Trạng thái hệ thống sau khi test.
- **Status**: Pass / Fail / Not Run / Pending.
- **Notes**: Ghi chú đặc biệt (môi trường, browser, OS…).

## 4. Lưu ý khi viết Test Case
- Mỗi test case chỉ test **1 tình huống duy nhất**.
- Test Data nên đa dạng để tăng độ bao phủ.
- Expected Result phải rõ ràng, đo được.
- Ghi chú các yêu cầu môi trường hoặc điểm đặc biệt.

