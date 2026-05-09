# HR_Dashboard
Theo dõi định biên và tình hình tuyển dụng nhân sự

**1. Tổng quan**
Dự án này tập trung vào việc xây dựng một hệ thống báo cáo thông minh giúp bộ phận Tuyển dụng và Ban Giám đốc giám sát toàn diện tình hình nhân sự và hiệu suất tuyển dụng theo thời gian thực. Dashboard giúp trả lời các câu hỏi: Chúng ta còn thiếu bao nhiêu nhân sự so với định biên? Tiến độ tuyển dụng của từng vị trí đang ở đâu trong phễu?

**Công cụ sử dụng**: Power BI, Power Query, DAX.

**Đối tượng sử dụng**: HR Manager, Ban Giám đốc.

**2. Các chỉ số đo lường chính (Key Metrics)**
Dashboard được thiết kế theo cấu trúc từ Tổng quan đến Chi tiết (Drill-down):

**Tình trạng nhân sự:**

Tổng định biên (Budgeted Headcount): Số lượng nhân sự được phép tuyển theo ngân sách.

Nhân sự hiện có (Current Staff): Số lượng thực tế đang làm việc.

Tỷ lệ lấp đầy (Fill Rate): Đánh giá mức độ đáp ứng nguồn lực (Hiện tại đạt 99.65%).

**Quản trị tuyển dụng:**

Vị trí đang tuyển: Tổng số job đang mở.

Phễu tuyển dụng (Recruitment Funnel): Theo dõi ứng viên qua các vòng (Hồ sơ -> Vòng 1 -> Vòng 2 -> Thỏa thuận -> Tiếp nhận).

Tiến độ tuyển dụng (%): So sánh số lượng đã tuyển so với nhu cầu thực tế của từng bộ phận.

**3. Các tính năng nổi bật (Key Features)**
Phân tích Chênh lệch (Variance Analysis): Hệ thống tự động tính toán số nhân sự thừa/thiếu so với định biên (Chênh lệch -1) để cảnh báo kịp thời cho bộ phận tuyển dụng.

Theo dõi Tiến độ Chi tiết: Bảng chi tiết cho phép lọc theo Khối và Bộ phận, giúp quản lý cấp trung theo dõi sát sao tình hình nhân sự của đơn vị mình.

Lọc thời gian linh hoạt: Cho phép xem báo cáo theo bất kỳ khoảng thời gian nào để đánh giá hiệu suất của mùa tuyển dụng cao điểm.

**4. Phân tích Insight (Strategic Insights)**
- Sự mất cân đối cấu trú: Mặc dù tổng định biên chỉ thiếu 01 nhân sự, dữ liệu cho thấy sự bất thường lớn trong việc phân bổ. Hiện trạng đang xảy ra tình trạng khối thừa, khối thiếu đan xen. Do đặc thù chuyên môn cao, nhân sự giữa các khối không thể luân chuyển qua lại để bù đắp khoảng trống, dẫn đến việc thiếu hụt cục bộ vẫn gây áp lực nặng nề lên vận hành thực tế.

- Rủi ro từ chỉ số lấp đầy: Tỷ lệ lấp đầy 99.65% là con số "ảo" nếu nhìn trên góc độ quản trị rủi ro. Việc thừa nhân sự ở một số bộ phận đang làm tăng chi phí quỹ lương (Budget), trong khi những bộ phận thiếu người lại đang bị quá tải, gây ảnh hưởng trực tiếp đến chất lượng dịch vụ và đào tạo.

- Nghịch lý tuyển dụng: Mặc dù tổng định biên gần như đã đủ, nhưng vẫn có tới 67 vị trí đang mở. Điều này phản ánh hai vấn đề: một là sự mở rộng quy mô vào các khối mới, hai là tỷ lệ biến động nhân sự (Turnover rate) ở các vị trí cốt lõi đang cao, buộc phải tuyển dụng liên tục để thay thế dù định biên trên giấy tờ vẫn đang hiển thị "đã lấp đầy".

- Hiệu quả phễu theo đặc thù: Tình trạng "lạm phát" ứng viên ở một số vị trí (ví dụ: Giáo viên Tiếng Anh đạt 300%) đối lập hoàn toàn với các vị trí đang "khát" nhân sự ở khối vận hành/kỹ thuật. Điều này cho thấy nguồn lực tuyển dụng đang bị phân bổ không đều hoặc chưa có chiến lược thu hút hiệu quả cho các vị trí đặc thù khó thay thế.
