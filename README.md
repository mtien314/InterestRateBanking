Dưới đây là giải thích các cột trong Banking dataset:

1. 'Loan_ID': ID của mỗi khoản vay

2. 'Loan_Amount_Requested': Đây là số tiền mà khách hàng yêu cầu vay từ ngân hàng.

3. 'Length_Employed': Đây là thời gian đã làm việc của khách hàng tính bằng năm. Cột này cho biết thời gian khách hàng đã làm việc trong công ty hiện tại hoặc tổ chức trước đó.

4. 'Home_Owner': Đây là tình trạng sở hữu nhà của khách hàng, ví dụ như sở hữu nhà riêng, thuê nhà, sống cùng người khác hoặc không có thông tin về tình trạng sở hữu nhà.

5. 'Annual_Income': Đây là thu nhập hàng năm của khách hàng, được tính bằng đơn vị tiền tệ.

6. 'Income_Verified': Đây là chỉ số cho biết xác minh thu nhập của khách hàng đã được thực hiện hay chưa. Có thể có các giá trị như "VERIFIED - income đã xác minh", "VERIFIED - income đã xác minh bằng tài liệu", hoặc "NOT VERIFIED - thu nhập chưa được xác minh".

7. 'Purpose_Of_Loan': Đây là mục đích vay tiền của khách hàng.

8. 'Debt_To_Income': Đây là tỷ lệ giữa tổng số nợ hiện tại và thu nhập hàng tháng của khách hàng. Đây là một chỉ số quan trọng để đánh giá khả năng thanh toán nợ của khách hàng.

9. 'Inquiries_Last_6Mo': Đây là số lần kiểm tra tín dụng trong vòng 6 tháng gần nhất. Chỉ số này cho biết số lần ngân hàng đã kiểm tra hồ sơ tín dụng của khách hàng trong khoảng thời gian đó.

10. 'Months_Since_Deliquency': Đây là số tháng kể từ lần vi phạm trước đó của khách hàng. Nếu khách hàng không có bất kỳ vi phạm nào, cột này có thể chứa giá trị thiếu (NaN).

11. 'Number_Open_Accounts': Đây là số lượng tài khoản mở của khách hàng tại ngân hàng hoặc tổ chức tín dụng khác.

12. 'Total_Accounts': Đây là tổng số tài khoản tín dụng mà khách hàng đang sở hữu, bao gồm cả tài khoản đã đóng và tài khoản đang hoạt động.

13. 'Gender': Đây là giới tính của khách hàng.

14. 'Interest_Rate': Đây là mức lãi suất được áp dụng cho khoản vay. Cột này chứa các giá trị dưới dạng phân loại để chỉ định mức lãi suất áp dụng cho khoản vay của khách hàng.
* Số 1: Đại diện cho mức lãi suất thấp (Low interest rate).
* Số 2: Đại diện cho mức lãi suất trung bình (Medium interest rate).
* Số 3: Đại diện cho mức lãi suất cao (High interest rate).
