# Customer_behavior_cinema
**Project title:**
Nâng cao doanh thu rạp phim dựa trên thói quen khách hàng

## 1. Purpose:
Xác định các yếu tố ảnh hưởng tới hành vi mua vé của khách hàng. Để trả lời các câu hỏi sau:
- Khách hàng mua vé dựa trên yếu tố nào?
- Có yếu tố nào ảnh hưởng tới việc mua lại vé của khách hàng.

## 2. Expected Outcome:
Đưa ra những chương trình khuyến mại phù hợp để tăng doanh thu.

## 3. Dataset Overview:
**Source:**

Cinema Hall Ticket Sales and Customer Behavior
https://www.kaggle.com/datasets/himelsarder/cinema-hall-ticket-sales-and-customer-behavior?resource=download

**Description:**
Bộ dữ liệu này ghi lại thông tin chi tiết về doanh số bán vé và hành vi của khách hàng tại rạp chiếu phim, cung cấp thông tin chi tiết về nhiều khía cạnh như nhân khẩu học, sở thích thể loại phim, lựa chọn chỗ ngồi, giá vé và mô hình giữ chân khách hàng. Bộ dữ liệu được thiết kế để giúp phân tích mức độ tương tác của khách hàng, hành vi chi tiêu và các yếu tố ảnh hưởng đến việc quay lại rạp chiếu phim. Dữ liệu hữu ích cho mô hình dự đoán và có thể hỗ trợ các quy trình ra quyết định liên quan đến việc giữ chân khách hàng, chiến lược tiếp thị và tối ưu hóa hoạt động của rạp chiếu phim.

**Structure:**

- Ticket_ID : Mã số duy nhất của mỗi giao dịch mua vé
- Age: tuổi của người mua vé
- Ticket_Price: Giá mà khách hàng phải trả cho vé, thường dao động từ 10 đến 25 đô la
- Movie_Genre: Thể loại phim mà khách hàng đã xem, có thể bao gồm một trong các thể loại sau: Action, Comedy, Horror, Drama, or Sci-Fi.
- Seat_Type: Loại ghế do khách hàng lựa chọn, có ba loại theo thứ tự:
- Standard 
- Premium 
- VIP 
- Number_of_Person: Số lượng người đi cùng khách hàng.
- Purchase_Again: Biến mục tiêu nhị phân cho biết liệu khách hàng có khả năng quay lại và mua vé khác hay không. Biến này có hai giá trị khả thi:
    - Yes
    - No
