# House-price-prediction

**Nhóm: Anadata**

***Thành viên:***

- 20120089 - Lê Xuân Hoàng
- 20120422 - Nguyễn Thị Ánh Tuyết
- 20120460 - Lê Nguyễn Hải Dương
- 20120494 - Lê Xuân Huy
- 20120521 - Trần Thị Phương Linh

# Đóng khung vấn đề
Bài toán này yêu cầu dự đoán giá cuối cùng của mỗi căn nhà dựa trên 79 biến mô tả (hầu như) mọi khía cạnh của các căn nhà ở Ames, Iowa. Bài toán được giao trong một cuộc thi tìm hiểu về dữ liệu, nơi mà những yếu tố khác ngoài số lượng phòng ngủ hoặc hàng rào trắng được chọn để ảnh hưởng đến thương lượng giá.

# Thu thập dữ liệu
Trong thư mục của cuộc thi này, có các tệp tin sau:

1. train.csv: Đây là tập dữ liệu huấn luyện, được sử dụng để xây dựng mô hình dự đoán giá nhà. Tệp này chứa thông tin về các căn nhà, bao gồm các biến giải thích và giá cuối cùng của từng căn nhà.

2. test.csv: Đây là tập dữ liệu kiểm tra, được sử dụng để đánh giá hiệu suất của mô hình dự đoán. Tệp này cũng chứa thông tin về các căn nhà, nhưng không có giá cuối cùng. Mục tiêu là dự đoán giá của các căn nhà này bằng mô hình đã huấn luyện trên tập train.csv.

3. data_description.txt: Đây là tệp mô tả đầy đủ về từng cột dữ liệu trong tập dữ liệu. Ban đầu, tệp này được chuẩn bị bởi Dean De Cock, nhưng đã được chỉnh sửa nhẹ để phù hợp với tên các cột được sử dụng trong cuộc thi này. Tệp này cung cấp thông tin chi tiết về các biến giải thích và giải thích ý nghĩa của chúng.

4. sample_submission.csv: Đây là một tệp nộp mẫu, chứa một mẫu nộp đơn dùng làm tham khảo để tạo ra định dạng chính xác cho kết quả dự đoán trên tập test.csv.
