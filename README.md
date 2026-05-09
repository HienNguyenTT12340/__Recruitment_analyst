# Recruitment analyst
Theo dõi chỉ tiêu và tình hình tuyển dụng nhân sự

**1. Tổng quan**

Dự án này tập trung vào việc xây dựng một hệ thống báo cáo thông minh giúp bộ phận Tuyển dụng và Ban Giám đốc giám sát toàn diện tình hình nhân sự và hiệu suất tuyển dụng theo thời gian thực. Dashboard giúp trả lời các câu hỏi: Chúng ta còn thiếu bao nhiêu nhân sự so với định biên? Tiến độ tuyển dụng của từng vị trí đang ở đâu trong phễu?

**Công cụ sử dụng**: Power BI, Power Query, DAX.

**Đối tượng sử dụng**: HR Manager, Ban Giám đốc, quản lý các khối

**Phân quyền**: Phân quyền xem tương ứng: cấp phòng ban, khối, công ty

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

**4.1. Khủng hoảng thiếu hụt trên toàn hệ thống (System-wide Shortage)**

Dữ liệu tại bảng tổng hợp Khối cho thấy 100% các Khối đều đang thiếu nhân sự và ở trạng thái "Cần tuyển":  Division D & E: Có tỷ lệ lấp đầy thấp nhất, lần lượt là 89.09% và 90.00%.

Division C: Tuy có tỷ lệ lấp đầy cao (96.95%) nhưng lại là nơi thâm hụt số lượng người lớn nhất (thiếu 6 nhân sự)

**4.2. Nghịch lý "Over-hiring" tại các vị trí cục bộ**

Dù tất cả các Khối tổng đều thiếu người, nhưng khi soi vào chi tiết từng vị trí tại trang 3, ta phát hiện một sự bất ổn trong phân bổ nguồn lực:  

Nhân sự ra vào liên tục, tuyển xong nghỉ : Tại Dept B, một vị trí Level 3 đã tuyển được 4 người trong khi chỉ cần 1 (Tiến độ 400%)  tức là có 3 người đã nghỉ ngày sau khi vào và một vị trí khác tuyển được 9 người trong khi cần 3 (Tiến độ 300%- tức có 6 người nghỉ ngay sau khi tuyển vào). Dept A cũng ghi nhận vị trí tuyển được 3 người dù chỉ cần 1 (Tiến độ 300%- 2 người nghỉ ngay sau khi vào).  

Hệ quả: Việc tuyển dụng liên tục tại các vị trí này đang "ngốn" ngân sách nhân sự của Khối, nhưng không thể bù đắp cho các vị trí đang thiếu hụt trầm trọng khác trong cùng Khối (như Dept D chỉ mới đạt 23.08% tiến độ). Điều này minh chứng cho việc quản lý chỉ tiêu đang bị lệch pha giữa nhu cầu thực tế và thực thi tuyển dụng. Đồng thời cho thấy bất ổn của vị trí, bộ phận hiện tại khi nhân sự ra vào liên tục

**4.3. Hiệu quả Kênh & Phễu**

Điểm nghẽn: Tỷ lệ chuyển đổi từ Vòng 1 sang Vòng 2 chỉ đạt 51.25%, là giai đoạn sàng lọc gắt gao nhất trong quy trình.

Kênh dẫn đầu: Nguồn nội bộ đóng góp cao nhất (26.42%), cho thấy văn hóa giới thiệu nội bộ đang hoạt động hiệu quả hơn các sàn tuyển dụng bên ngoài.

**5. Đề xuất hành động**

Kiểm soát chặt chẽ vị trí đã đủ định biên: Dừng ngay việc tuyển dụng tại các vị trí đã đạt hoặc vượt 100% tiến độ (đặc biệt là tại Dept B, A, C) để dồn nguồn lực cho các vị trí đang thiếu hụt.  

Ưu tiên Division D & E: Tập trung ngân sách truyền thông và nguồn lực HR cho 2 khối đang có tỷ lệ lấp đầy dưới 90% để đảm bảo an toàn vận hành.
