# clothing_discount_prediction
1. Tìm hiểu dữ liệu 
2. Xử lý dữ liệu 
  - Fill giá trị rỗng
  - Thêm cột mới, thực hiện thay đổi trên cột
  - Xử lý chuỗi
  - Ép kiểu
3. Chuẩn bị dữ liệu cho model
  - Sử dụng thư viện sklearn để chia dữ liệu train, test, validation
  - Chuyển dữ liệu đầu vào thành số (do các thuật toán sử dụng đẻ xây dựng model là linear regression, kneighbors regression, random forest với đầu ra là % giảm giá là 1 số )
4. Biểu diễn dữ liệu
  - Sử dụng thư viện matplotlib và seaborn
  - Biểu diễn sự tương quan dữ liệu.
  - Biểu diễn dữ liệu xem có tính hồi quy giữa các thuộc tính với nhau không
5. Đưa features vào model và dùng thuật toán train model và tính hiệu suất
  - Sử dụng thư viện sklearn tiến hành train model với các thuật toán linear regression, kneighbors regression, random forest
  - Đánh giá hiệu suất model với r2 score, so sánh % discount dự đoán với % discount thực tế trong cả test set và validation set
6. Đưa mô hình vào tính % discount cho những sản phẩm có discount = 0
