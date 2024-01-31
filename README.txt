Project case no 2: Sale Analysis
Nguồn dữ liệu: datadad.io
Link Dataset (After transform): https://docs.google.com/spreadsheets/d/1aNPMBCc8HfnI0tA7yR0WR3jT2vYIoLhch4J_iWvUiZA/edit#gid=1956311044
===
Data Cleaning Process:
1 - Định dạng các trường thông tin 
2 - Điều chỉnh dữ liệu về đúng format (Cột B format thời gian lại thành YYYY - MM - DD + Cột L & M format lại thành đơn vị tiền tệ $ Đô la Mỹ) 
3 - Thêm các trường tính toán mới về doanh thu (Doanh thu = Giá bán * Số lượng), chi phí (Chi phí = Giá nhập * Số lượng), lợi nhuận (Lợi nhuận = Doanh thu - Chi phí) và formart theo đơn vị tiền tệ Đô la Mỹ $
4 - Thêm các trường tính toán mới về AOV (AOV = Tổng Doanh thu / Tổng số lượng đơn hàng) - formart theo đơn vị tiền tệ Đô la Mỹ $ và Tỷ suất lợi nhuận (Tỷ suất lợi nhuận = Lợi nhuận/Doanh thu * 100%)
5 - Format chỉ lấy 2 số thập phân đầu tiên của các cột liên quan tới doanh thu, chi phí, lợi nhuận 
