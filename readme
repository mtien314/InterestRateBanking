## I. Xử lý dữ liệu
- Làm sạch:
  * Loan_Amount_Requested: mang kiểu object -> xóa dấu ',' rồi ép kiểu về float.
  * Home_Owner: Có giá trị 'None' mang ý nghĩa không xác định và có giá trị nan. -> Thay thế tất cả giá trị 'None' = nan -> thay nan bằng gía trị ước lượng.
  * Length_Employed: có giá trị nan -> Thay bằng giá trị ước lượng với các giá trị nan, chuẩn hóa giá trị cột về format 1,2,3...,10,.
  * Annual_Income và Months_Since_Deliquency: nan sẽ được thay bằng giá trị ước lượng.
  * Dùng IterativeImputer để điền các giá trị nan.
- Xử lý outlier: Dùng phương pháp z-score cho toàn bộ dữ liệu để loại bỏ các outlier.
- Trích xuất đặc trưng: Loại bỏ cột ID.

## II. Xây dựng mô hình:
- Chia data thành tập train và tập test theo tỉ lệ 8 : 2. Đồng thời oversampling data bằng SMOTE.
- Nhóm các mô hình máy học Decision tree, Xgboost, Catboost: Chúng tôi đã sử dụng các mô hình phân loại này để đào tạo, kiểm tra dữ liệu và chỉnh sửa các thông số như max_depth, learning_rate và n_estimators để đạt được kết quả tốt nhất.
- Mô hình deeplearning MLP: Đối với mô hình MLP, chúng tôi đã tùy chỉnh các tham số như số lượng tầng ẩn và số lượng nơ-ron trong mỗi tầng để tối ưu hóa hiệu suất. Mô hình này đã cho kết quả phân loại tốt.

## III. Kết luận:
- Xử lý được imbalace trong label -> cân đối giữa các độ đo.
- Tập train và tập test tương tự nhau về accuracy.
- Các model không có hiện tượng overfitting.  
