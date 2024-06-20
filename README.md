
# DỰ BÁO CHẤT LƯỢNG KHÔNG KHÍ CỦA THÀNH PHỐ HÀ NỘI, ĐÀ NẴNG, VIỆT TRÌ DỰA VÀO CÁC MÔ HÌNH THỐNG KÊ, HỌC MÁY VÀ HỌC SÂU
## THÀNH VIÊN NHÓM
| MSSV | Họ và tên |
| --- | --- |
| 21521623 | Đoàn Ngọc Tuấn (Nhóm trưởng) |
| 21520492 | Doãn Công Trí |
| 21520264 | Nguyễn Phước Huy|
| 21522127 | Trần Quốc Hưng |
| 21522746 | Trần Lê Tứ|

## GIỚI THIỆU
Repository chứa source code và những tài nguyên liên quan đến project về Dự báo chất lượng không khí của Hà Nội, Đà Nẵng, Hài Phòng dựa vào các mô hình thống kê, học máy và học sâu. Trong sự án này, nhóm sử dụng các mô hình như Linear Regression, VAR, DLinear, SES, NBEATS, Linear Regression CalendarFourier and DeterminissticProcess, ARIMA, RNN, GRU, LSTM để dự đoán về chất lượng không khí ba thành phố Hà Nội, Đà Nẵng, Việt Trì.

## BỘ DỮ LIỆU
Bộ dữ liệu sử dụng trong project này được thu thập từ trang web aqicn.org, chứa dữ liệu về chất lượng không khí của các thành phố Hà Nội, Đà Nẵng, Việt Trì từ 01/01/2019 đến 01/06/2024. Bộ dữ liệu bao gồm các thuộc tính Date, PM2.5, PM10, O3, NO2, SO2 và CO.

## Feature Engineering
Để cải thiện hiệu suất mô hình, nhóm đã sử dụng một số các phương pháp cũng như các tham số tối ưu để mang lại kết quả tốt nhất cho mô hình.


## CÁC MÔ HÌNH
Các mô hình được triển khai và đánh giá trong dự án này: 

- Linear Regression
- VAR
- DLinear
- SES
- NBEATS
- Linear regression CalendarFourier and DeterministicProcess
- ARIMA
- RNN
- GRU
- LSTM

## ĐÁNH GIÁ
Các mô hình được đánh giá bằng nhiều chỉ số khác nhau. Trong dự án này, nhóm sử dụng các chỉ số: Root Mean Squared Error (RMSE), Mean absolute error (MAE), Mean absolute percentage error (MAPE) để đánh giá và so sánh các mô hình trên các tập dữ liệu. Tỉ lệ train test được sử dụng là 7:3, 8:2, 9:1. Thông qua đó, tìm ra mô hình có độ chính xác cao nhất để dự đoán AQI.

## PHÂN CHIA CÔNG VIỆC
| Member | Responsibilities |
| --- | --- |
| Đoàn Ngọc Tuấn | Triển khai mô hình Linear Regression, VAR. Đóng góp báo cáo phần: Dataset, Tiền xử lý dữ liệu, Thống kê mô tả, Phương pháp nghiên cứu, Triển khai và đánh giá mô hình, Kết luận.|
| Doãn Công Trí | Triển khai mô hình ARIMA, Linear regression CalendarFourier and DeterministicProcess. Đóng góp báo cáo phần: Tóm tắt, Phương pháp nghiên cứu, Triển khai và đánh giá mô hình|
| Trần Quốc Hưng | Triển khai mô hình DLinear, VAR. Đóng góp báo cáo phần: Các nghiên cứu liên quan, Phương pháp nghiên cứu, Triển khai và đánh giá mô hình|
| Nguyễn Phước Huy | Triển khai mô hình NBEATS, LSTM. Đóng góp báo cáo phần: Các nghiên cứu liên quan, Phương pháp nghiên cứu, Triển khai và đánh giá mô hình, Lý thuyết các chỉ số đánh giá, Kết luận|
| Trần Lê Tứ | Triển khai mô hình SES, RNN. Đóng góp báo cáo phần: Giới thiệu, Công cụ, Phương pháp nghiên cứu, Triển khai và đánh giá mô hình, Kết luận.|


## Contributing
Những đóng góp cho dự án này đều được chào đón. Nếu bạn tìm thấy bất kỳ vấn đề nào hoặc có đề xuất cải tiến, vui lòng mở một vấn đề hoặc gửi pull request.

## Acknowledgments
Nhóm chúng em xin gửi lời cảm ơn sâu sắc đến Phó Giáo sư Tiến sĩ Nguyễn Đình Thuân và Trợ giảng Nguyễn Minh Nhựt vì kiến thức chuyên môn vô giá, sự hướng dẫn tận tâm trong suốt thời gian thực hiện đồ án này. Đồ án nà không chỉ cung cấp cho nhóm chúng em cơ hội nâng cao kỹ năng làm việc nhóm, kỹ năng hợp tác, học hỏi lẫn nhau mà còn cho phép chúng em áp dụng kiến thức của mình vào các lĩnh vực thực tế.
Trong suốt quá trình thực hiện đồ án, nhóm chúng em đã tận dụng kiến thức đã có và nghiên cứu các khái niệm mới để mang lại kết quả tốt nhất. Mặc dù đã cố gắng hết sức, chúng em thừa nhận rằng không thể tránh khỏi những thiếu sót. Do đó, chúng em rất mong nhận được phản hồi, nhận xét của các thầy, điều này sẽ giúp nhóm chúng em hoàn thiện kiến thức và nâng cao các nỗ lực trong tương lai.
Ngoài ra, chúng em muốn bày tỏ lòng biết ơn đến các thành viên trong nhóm và bạn bè đã hỗ trợ , giúp đồ án được thực hiện thành công. Lời cảm ơn chân thành của chúng em xin gửi đến tất cả những người đã đồng hành cùng chúng em trong suất thời gian hoàn thành đồ án này.
