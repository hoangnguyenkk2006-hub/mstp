FOOD DRYER SCADA - GIAO DIỆN MÔ PHỎNG

Cách mở:
1. Giải nén file ZIP.
2. Mở thư mục food_dryer_scada.
3. Nhấp đúp index.html để mở bằng Chrome hoặc Edge.

Các chức năng trong bản này:
- Hiển thị nhiệt độ, độ ẩm và áp suất (dữ liệu giả lập).
- Biểu đồ thời gian riêng cho từng thông số.
- Bật/tắt quạt chính, quạt dự phòng, PTC chính và PTC dự phòng.
- Điều chỉnh tốc độ hai quạt bằng thanh trượt 0-100% (giá trị PWM dự kiến).
- Nhập nhiệt độ mục tiêu.
- Mô phỏng quá nhiệt, chuyển sang thiết bị dự phòng và ghi nhật ký cảnh báo.
- Hiển thị trạng thái giả lập của các Slave Modbus.

LƯU Ý QUAN TRỌNG:
Đây mới là giao diện frontend mô phỏng. Chưa kết nối USB-RS485 và chưa điều khiển phần cứng thật.
Giá trị 0-100% hiện là mức PWM đặt, không phải RPM đo được. Muốn hiển thị RPM thực tế cần có tín hiệu/cảm biến phản hồi tốc độ.
Chart.js được tải từ CDN nên cần Internet để hiển thị biểu đồ.
Trước khi tích hợp phần cứng cần đúng model module Waveshare, tài liệu thanh ghi Modbus,
địa chỉ Slave, baud rate, parity, stop bit và sơ đồ kết nối đã được kiểm tra.
Không dùng website/phần mềm làm bảo vệ quá nhiệt khẩn cấp; cần mạch bảo vệ nhiệt độc lập.
