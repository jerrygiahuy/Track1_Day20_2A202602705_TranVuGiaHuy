# Lab Day 20 — Product Metrics cho AI Notes

| Thông tin | Nội dung |
| --- | --- |
| Họ và tên | **Trần Vũ Gia Huy** |
| Mã học viên | **2A202602705** |
| Dự án | **AI Notes — Personal Learning Notes** |
| Use case | Learner cùng AI tổ chức dấu vết học tập, duyệt và lưu một learning note có thể tìm lại cùng ngữ cảnh |

## Bài nộp

- [Metrics Pack — bản trình bày trực quan](metrics-pack.html) — bản HTML tự chứa, mở trực tiếp trên trình duyệt.
- [Metrics Pack — bản nội dung chi tiết](metrics-pack.md) — đầy đủ các mục 00–06, năm gate và phần tự soi lỗi.
- [AI Support Log](ai-support-log.md) — phạm vi AI đã hỗ trợ và các quyết định cần người nộp xác nhận.

Metrics Pack được đặt ngay trong repository để link luôn xem được cùng bài nộp, không phụ thuộc quyền truy cập của một dịch vụ bên ngoài. HTML là định dạng trình bày trực quan được brief cho phép.

## Điều tôi mang về áp dụng cho dự án thật

Điều quan trọng nhất tôi mang về là không đo thành công bằng số lượt hỏi AI hay thời gian ở trong app. Với AI Notes, giá trị chỉ rõ hơn khi learner **duyệt và lưu được một note có nguồn, đủ ngữ cảnh để dùng lại**. Vì vậy metric phải đi từ hành vi này, theo nhịp của từng lượt học; notification chỉ hỗ trợ chứ không tạo ra lý do quay lại.

Tôi cũng sẽ dùng counter-metric về khả năng tìm lại note để tránh tối ưu số lượng note nhưng tạo ra kho ghi chú kém chất lượng. Tracking chỉ giữ các event phục vụ activation, engagement, retention, North Star hoặc kiểm soát chất lượng.

## Nguồn bối cảnh dự án

Metrics Pack kế thừa dự án **Case B — AI Notes: Personal Learning Notes** và hướng **Option B — Cùng tổ chức** từ Lab 18. Những con số chưa được kiểm chứng bằng production data được đánh dấu là **giả định ban đầu** và cần hiệu chỉnh sau khi có telemetry thật.
