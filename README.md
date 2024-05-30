# JmeterTest
#HTSPORT
![image](https://github.com/huyhoang175/JmeterTest/assets/96982807/c242184b-bc2d-4c59-9501-b67dcb4e4fab)
![image](https://github.com/huyhoang175/JmeterTest/assets/96982807/ee6e6999-9edb-4b14-a368-812ccb97226b)
### Phân Tích Chi Tiết

#### Thời gian phản hồi trung bình:

- **HTSport**: 344.11 ms
- **nike-mecurial**: 241.53 ms
- **about**: 229.82 ms
- **Tổng**: 299.59 ms

#### Số lượng yêu cầu thành công và thất bại:

- Tất cả các yêu cầu đều thành công với tỉ lệ lỗi 0.0% cho cả ba trang web.

#### Thông lượng (Throughput):

- **HTSport**: 4.35 requests/sec
- **nike-mecurial**: 4.37 requests/sec
- **about**: 4.36 requests/sec
- **Tổng**: 12.63 requests/sec

#### Tốc độ xử lý dữ liệu (KB/sec):

- **HTSport**: 4159.22 KB/sec
- **nike-mecurial**: 3070.84 KB/sec
- **about**: 2565.79 KB/sec
- **Tổng**: 9456.66 KB/sec

### Nhận xét về hiệu năng của trang web

Dựa trên kết quả kiểm tra:

- **HTSport** có thời gian phản hồi trung bình cao nhất (344.11 ms) trong số ba trang web, nhưng vẫn dưới ngưỡng chấp nhận được cho một trang web thông thường.
- **nike-mecurial** có thời gian phản hồi trung bình là 241.53 ms, thấp hơn đáng kể so với HTSport, cho thấy hiệu năng tốt hơn.
- **about** có thời gian phản hồi trung bình thấp nhất (229.82 ms), cho thấy đây là trang web có hiệu năng tốt nhất trong ba trang.
- Tất cả các yêu cầu đều thành công với tỉ lệ lỗi 0%, điều này cho thấy cả ba trang web đều hoạt động ổn định và không gặp vấn đề về xử lý yêu cầu.
- Thông lượng và tốc độ xử lý dữ liệu của các trang web đều ở mức tốt, với tổng thông lượng đạt 12.63 requests/sec và tốc độ xử lý dữ liệu đạt 9456.66 KB/sec.

### Kết luận

Dựa trên kết quả phân tích:

- **about** là trang web có hiệu năng tốt nhất với thời gian phản hồi trung bình thấp nhất và ổn định.
- **nike-mecurial** cũng có hiệu năng tốt nhưng kém hơn một chút so với about.
- **HTSport** có thời gian phản hồi trung bình cao nhất, nhưng vẫn nằm trong ngưỡng chấp nhận được và không gặp lỗi.





