# Pyspark-properties

Thuộc tính Spark kiểm soát hầu hết các cài đặt ứng dụng và được cấu hình riêng cho từng ứng dụng. Các thuộc tính này có thể được đặt trực tiếp trên SparkConf được chuyển đến của bạn SparkContext. SparkConfcho phép bạn định cấu hình một số thuộc tính chung (ví dụ: URL chính và tên ứng dụng), cũng như các cặp khóa-giá trị tùy ý thông qua set()phương thức. Ví dụ, chúng ta có thể khởi tạo một ứng dụng với hai luồng như sau:
Lưu ý rằng chúng tôi chạy với local [2], nghĩa là hai luồng - thể hiện sự song song “tối thiểu”, có thể giúp phát hiện lỗi chỉ tồn tại khi chúng tôi chạy trong bối cảnh phân tán.

![1](https://user-images.githubusercontent.com/64195026/109417294-8d546980-79f5-11eb-9d10-bb8e449fef2b.png)

Lưu ý rằng chúng ta có thể có nhiều hơn 1 luồng ở chế độ cục bộ và trong những trường hợp như Spark Streaming, chúng tôi thực sự có thể yêu cầu nhiều hơn 1 luồng để ngăn chặn bất kỳ loại vấn đề chết đói nào.
Các thuộc tính chỉ định một số khoảng thời gian nên được cấu hình với một đơn vị thời gian. Định dạng sau được chấp nhận:

![2](https://user-images.githubusercontent.com/64195026/109417503-8548f980-79f6-11eb-86f1-9bf8e3490e4f.png)

Thuộc tính chỉ định kích thước byte phải được cấu hình với đơn vị kích thước. Định dạng sau được chấp nhận:

![3](https://user-images.githubusercontent.com/64195026/109417506-867a2680-79f6-11eb-95d2-da179c415dd2.png)

Trong khi các số không có đơn vị thường được hiểu là byte, một số ít được hiểu là KiB hoặc MiB. Xem tài liệu về các thuộc tính cấu hình riêng lẻ. Việc chỉ định đơn vị là mong muốn nếu có thể.

## Thuộc tính có sẵn
Hầu hết các thuộc tính kiểm soát cài đặt nội bộ đều có giá trị mặc định hợp lý. Một số tùy chọn phổ biến nhất để đặt là:

## Thuộc tính ứng dụng
![4](https://user-images.githubusercontent.com/64195026/109417457-57fc4b80-79f6-11eb-8e93-c1513a0454da.png)
![5](https://user-images.githubusercontent.com/64195026/109417463-5a5ea580-79f6-11eb-995f-399050536fc3.png)
![6](https://user-images.githubusercontent.com/64195026/109417465-5c286900-79f6-11eb-8877-1cd7f286f742.png)
![7](https://user-images.githubusercontent.com/64195026/109417468-5e8ac300-79f6-11eb-89ae-2710f8da9109.png)
![8](https://user-images.githubusercontent.com/64195026/109417469-5fbbf000-79f6-11eb-9c97-bd0977ed1e37.png)
![9](https://user-images.githubusercontent.com/64195026/109417471-60ed1d00-79f6-11eb-9537-96ce6bcbb80f.png)
![10](https://user-images.githubusercontent.com/64195026/109417475-62b6e080-79f6-11eb-8468-4ab8bdaa3756.png)
![11](https://user-images.githubusercontent.com/64195026/109417477-63e80d80-79f6-11eb-98c6-15dc96d0d6c3.png)
![12](https://user-images.githubusercontent.com/64195026/109417480-65b1d100-79f6-11eb-8e16-bd499226880f.png)

##Môi trường thực thi

![13](https://user-images.githubusercontent.com/64195026/109417518-9134bb80-79f6-11eb-9317-2e3cf9fc1c1a.png)
![14](https://user-images.githubusercontent.com/64195026/109417519-9265e880-79f6-11eb-9e2a-f493a30b980a.png)
![15](https://user-images.githubusercontent.com/64195026/109417520-93971580-79f6-11eb-9d8d-ffd7b0d1b034.png)
![16](https://user-images.githubusercontent.com/64195026/109417523-94c84280-79f6-11eb-8baa-7220abc07871.png)
![17](https://user-images.githubusercontent.com/64195026/109417524-96920600-79f6-11eb-921a-c4592cca74b4.png)
![18](https://user-images.githubusercontent.com/64195026/109417525-97c33300-79f6-11eb-9aad-bfbf9914d78c.png)
