# PROJECT---REDUCING CONFUSION IN AERIAL IMAGE ORIENTED OBJECT DETECTION VIA BOUNDING BOX CONSOLIDATION

"Giảm thiểu hộp giới hạn nhầm lẫn trong bài toán phát hiện đối tượng có hướng trong không ảnh" là nghiên cứu giải quyết vấn đề nhiều hộp giới hạn được gán cho cùng một đối tượng trong quá trình phát hiện đối tượng có hướng trong không ảnh, điều có thể dẫn đến sự không chính xác và nhầm lẫn. Nghiên cứu đề xuất một cách tiếp cận hai bước kết hợp các mô hình phát hiện đối tượng có hướng và mô hình phân loại. Các mô hình phát hiện đối tượng có hướng được sử dụng trong nghiên cứu được thiết kế để xử lý các thách thức đặc biệt trong việc phát hiện các đối tượng trong không ảnh, trong khi mô hình phân loại được sử dụng để gán nhãn lại các đầu ra của hộp giới hạn có hướng và giảm sự nhầm lẫn trong kết quả. Kết quả đầu ra từ cả hai mô hình được tổng hợp và non-maximum suppression được áp dụng để loại bỏ các hộp giới hạn dư thừa hoặc không chính xác.

Nghiên cứu sử dụng các mô hình phát hiện đối tượng có hướng như S2Anet, R3Det, ReDet, Oriented RCNN và RoI Transformer và kết hợp nó với mô hình phân loại EfficientNet. Bộ dữ liệu DOTA được sử dụng để chứng minh rằng phương pháp hai bước có hiệu quả trong việc giảm nhầm lẫn và cải thiện độ chính xác của việc phát hiện đối tượng trong không ảnh. Cách tiếp cận của dự án có ý nghĩa thực tế quan trọng đối với các ứng dụng khác nhau, bao gồm ứng phó với thiên tai, quy hoạch đô thị và nông nghiệp.

# Contributors
| Serial | Full name              | Github                                               | Email                   |
| ------ | ----------------------:|-----------------------------------------------------:|-------------------------:
| 1      | Trương Thành Thắng |[erwin24092002](https://github.com/erwin24092002)          |20521907@gm.uit.edu.vn   |
| 2      | Ngô Văn Tấn Lưu |[tanluuuuuuu](https://github.com/tanluuuuuuu)          |20521591@gm.uit.edu.vn   |
