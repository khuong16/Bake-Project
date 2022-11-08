# Kỹ thuật flexbox:
- Thay thế cho thuộc tính float và hạn chế vấn đề của float như clear float.
- Tự cân đối kích thước các phần tử trên mọi thiết bị.
- Chỉ nên dùng để chia bố cụ trong phạm vi nhỏ.

1. display: flex. 

2. flex-direction: cho phép đổi hướng sắp xếp của các phần tử.
(Các giá trị đi kèm là: row | column | row-reverse | column-reverse)

3. flex-wrap: cho phép các phần tử được xuống hàng khi không đủ chỗ chứa
(Các giá trị đi kèm là: wrap | nowrap | wrap-reverse)

4. justify-content: canh chỉnh vị trí phần tử theo chiều ngang.
(Các giá trị đi kèm là: flex-start | flex-end | center | space-around | space-between | space-evenly)

5. align-items: canh chỉnh vị trí phần tử theo chiều dọc. 
(Các giá trí đi kèm là: flex-start | flex-end | center)

# CSS3 Transition:
- Giúp cho chúng ta nhìn thấy được quá trình chuyển đổi của css.
- Để thực hiện transition cần có:
    + Thuộc tính CSS chúng ta cần thực hiện transition.
    + Duration của hiệu ứng.
- Ngoài ra chúng ta có các thuộc tính khác (có thể có hoặc không)
    + Timing-function
    + delay

# Transition property
- Chỉ định thuộc tính css chúng ta muốn thực hiện.
Cú pháp:
   - Transition-property: [Tên thuộc tính] / all;

Ví dụ:
    - Transition-property: width;
    - Transition-property: all;

# Transtion duration
- Thời gian thực hiện transition.
- Cú pháp:
    - Transition-duration: [time]

Ví dụ: Transition-duration: 2s;

# Transition timing function
- Thuộc tính transition-timing-function xác định tốc độ của hiệu ứng.
- Bao gồm các giá trị:
    - Ease - Hiệu ứng ban đầu chậm, sau đó nhanh và chậm dần.
    - Linear - Tốc độ giữ nguyên từ đầu tới cuối.
    - Ease-in - Bắt đầu chậm, sau đó nhanh.
    - Ease-out - Bắt đầu nhanh, sau đó chậm.
    - Ease-in-out - Bắt đầu và kết thúc chậm.

# Transition delay:
- Khoảng thời gian delay trước khi thực hiện hiệu ứng.
- Cú pháp:
    - Transition-delay: [Time];

VD: transition-delay: 2s;

# Grid
## Grid là gì ?
- Cung cấp một hệ thống lưới cơ bản.
- Bao gồm các cột và các hàng.
- Dàn layout dễ hơn mà không phải sử dụng float hay position.

## Các thành phần trong Grid:
- Gồm 2 thành phần chính:
+ Grid container.
+ Grid Item.

- Muốn sử dụng css Grid phải có các thuộc tính:
+ Display: grid.
+ Grid-template-columns: chia cột cho phần tử.

## Các thuộc tính của Grid:
* Grid-template-columns:
- Dùng để chia cột cho phần tử.
- Cú pháp:
    + Grid-template-columns: [col1] [col2] [col3] ...
    + Grid-template-columns: repeat(số cột, kích thước);
- Đơn vị kích thước ưu tiên dùng 'fr'
- Ví dụ: grid-template-columns: 1fr 1fr 2fr;
=> chia phần tử ra thành 4 phần bằng nhau, cột 1 và 2 chiếm 1 phần, cột 3 chiếm 3 phần.

* Grid-template-rows:
- Cú pháp:
    + Grid-template-rows: [row1] [row2] [row3] ...
    + Chỉ nên xét khi muốn chỉnh height cho các rows

* Grid gaps:
- Là khoảng cách giữa các cột và các hàng.
- Cú pháp: Grid-column-gap | grid-row-gap | grid-gap: [khoảng cách];

* Grid-column & Grid-row:
- Dùng để gom cột và hàng tương tự như table.
- Thêm ở item con cần gom.
- Cần xác định line bắt đầu và kết thúc của item đó.
- Ví dụ: Item-a chiếm từ cột 2 đến cột 4 và hàng 1 đến hàng 2 nên sẽ phủ từ [line2] đến [five] và từ [row1-start] đến [third-line].


* Grid-column:
- Cú pháp: grid-column: n / m;
- Trong đó:
    + n là vị trí line bắt đầu của cột đầu tiên mà item con này chiếm.
    + m là vị trí line kết thúc của cột cuối cùng mà item con này chiếm.

# Sử dụng thư viện lightbox để sử dụng việc hiển thị popup hình ảnh.

# HTML Form:
- Được dùng để nhận dữ liệu từ phía người dùng.
- Giúp việc gửi yêu cầu của người dùng đến trang xử lý trong ứng dụng web.
- Tag <form> dùng để chứa các thành phần khác của form.
- Những thành phần nhập liệu được gọi là form field:
    + Text field.
    + Password field.
    + Multi-line text field.

# Multimedia Elements:
<Video>
- THêm video cho trang web với các thuộc tính:
    + Controls: Hiển thị thanh điều khiển video.
    + Preload: load trước video.
    + Loop: lặp video.
    + Muted: tắt âm thanh của video khi load trang web.
    + Autoplay: tự chạy video khi load trang web.

<iframe>
- Dùng để nhúng video vào trang website.

<canvas>
- Vẽ hình ảnh thông qua JS.
- Hình ảnh: đường thẳng, hình tròn, hình hộp, chữ, hình ảnh,...

<svg>
- vẽ hình (không thông qua JS)

# CSS Transform:


