# Mô tả data:

### 1. Đường link: https://shopee.vn/Th%E1%BB%9Di-Trang-Nam-cat.11035567

### 2. Cách thức lấy: 
Chủ yếu là sử dụng API để lấy về.

### 3. Data schema:

|STT| Tên cột    | Mô tả| Kiểu dữ liệu mong muốn |
|---|:-----------:|:-------------:|:---|
|1| itemid| Id của sản phẩm| String|
|2| shopid| ID của shop| string|
|3| stock| Số lượng sản phẩm trong kho| int |
|4| sold| Số lượng sản phẩm đã bán| int|
|5| liked_count| Số lượt thích sản phẩm| int|
|6| cmt_count| Số lượt bình luận| int|
|7| item_status| trạng thái sản phẩm| bool|
|8| price| giá sản phẩm| float|
|9| price_min|giá tối thiểu| float|
|10| price_max| giá tối đa| float|
|11| price_min_before_discount| giá tối thiểu trước discount| float|
|12| price_max_before_discount| giá tối đa trước discount| float|
|13| price_before_discount| giá trước discount| string|
|14| tier_variations| kích thước, màu sắc và các đặc tính khác của sản phẩm| dict|
|15| item_rating| các đánh giá của sản phẩm(bao gồm đánh giá trung bình và số đánh giá của từng sao)| dict|
|16| show_free_shipping| shop có free ship hay không| bool|
|17| shop_location|vị trí của shop| string|
|18| is_on_flash_sale| sản phẩm có đang sale hay không| bool|
|19| shop_name| tên shop| string|
|20| shop_rating| Rating cho shop| float|
|21| global_sold_count| số lượng sản phẩm được bán trên thế giới trên shoppe| int|
|22| flash_sale_stock| số lượng sản phẩm còn lại trong đợt flash sale| string|
|23| crawl_time| thời điểm crawl data| date time|
|24| historical _sold| Số lượng đã bán trong quá khứ| int|
|25| name| tên sản phẩm| string|

### 4. Những category được sử dụng chủ yếu:

|STT| Tên cột    | Mô tả| Kiểu dữ liệu mong muốn |
|---|:-----------:|:-------------:|:---|
|1| itemid| Id của sản phẩm| String|
|2| shopid| ID của shop| string|
|3| stock| Số lượng sản phẩm trong kho| int |
|4| sold| Số lượng sản phẩm đã bán| int|
|5| liked_count| Số lượt thích sản phẩm| int|
|6| cmt_count| Số lượt bình luận| int|
|8| price| Giá sản phẩm| float|
|15| item_rating| Các đánh giá của sản phẩm(bao gồm đánh giá trung bình và số đánh giá của từng sao)| dict|
|18| is_on_flash_sale| Sản phẩm có đang sale hay không| bool|
|19| shop_name| Tên shop| string|
|20| shop_rating| Rating cho shop| float|
|22| flash_sale_stock| số lượng sản phẩm còn lại trong đợt flash sale| string|
|23| crawl_time| thời điểm crawl data| date time|
|25| name| tên sản phẩm| string|

Ngoài ra, thì còn có description thu thập được từ 1000 sản phẩm top đầu của 20 shop mall