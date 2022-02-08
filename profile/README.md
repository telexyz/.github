### Hi there 👋

Lại là **Tuộc** đây và mời bạn cùng tham gia ✨ _hành trình_ ✨ áp dụng lập trình hệ thống vào xử lý ngôn ngữ tiếng Việt và cải tiến bộ gõ Telex của 🐙 🐙 🐙

Q: Các bạn có thể hỏi tại sao lại là lập trình hệ thống với những ngôn ngữ cơ bản như C/C++ hay Zig mà không sử dụng ngôn ngữ bậc cao như Python hay Julia? 


A: Đơn giản là vì:

🔭 Cài đặt lại từ đầu các giải thuật bằng một ngôn ngữ bậc thấp, tối ưu hóa cho hệ thống chương trình đang chạy trong đó sẽ giúp người pháp triển hiểu sâu hơn rất nhiều về giải thuật cũng như hệ thống mà chương trình sẽ được triển khai. Biết được ưu điểm, nhược điểm của từng giải thuật và các cách để cải tiến chúng ra sao và có thể tối ưu tới hết mức. Điều này chỉ có thể làm được với lập trình hệ thống.

⚡ Tốc độ ưu việt: đương nhiên rồi, vì lập trình hệ thống mà. Không những cả tốc độ mà bộ nhớ nữa. Điều này rất quan trọng khi triển khai trên các thiết bị đầu cuối phần cứng không mạnh mẽ như mobile chẳng hạn.

🌱 Triển khai đa dạng: có thể biên dịch và triển khai trên nền web thông qua web assembly hoặc nhúng vào những hệ thống phần cứng khác không phải PC, deploy trên mobile cũng dễ dàng. Ở đâu có hỗ trợ C compiler thì ở đó chúng ta có thể triển khai được ứng dụng viết bằng ngôn ngữ bậc thấp.

- - -

Q: Tại sao lại code từ đầu mà không dùng thư viện có sẵn? 

A: Muốn có kết quả ngay và ra được ứng dụng ăn liền thì bạn nên dùng thư viện có sẵn, hiện có cực nhiều những thư viện như thế với chất lượng tuyệt vời, kể cả những models đã được train bằng những phần cứng chuyên dụng mà bạn không thể tự làm ở nhà được. Đấy là cả một kho tàng quý giá để bạn khai thác. Tuy nhiên đấy là với các pro (người chuyên nghiệp đã có kinh nghiệm làm thực tế nhiều năm), còn với người mới thì riêng việc đọc hiểu và lựa chọn công cụ thôi cũng nổ đầu rồi. Cũng công sức như thế sao ta không bỏ ra để cài đặt lại theo kiểu homemade theo cách mà ta muốn, khớp với mục đích ta đang theo đuổi?


- - -

Q: Mục tiêu của dự án là gì?

A: Không đuổi theo kết quả tốt nhất mà theo đuổi hiệu năng tốt nhất (độ chính xác / công sức lập trình và độ tốn kém của phần cứng khi chạy giải thuật). Vì nếu bỏ ra 1 tháng trời để cài đặt hoặc bỏ vài ngàn đô để mua phần cứng về chạy giải thuật mới để độ chính xác tăng lên 5-10% thì có lẽ chưa thỏa đáng, trừ trường hợp mục tiêu tối thượng của bạn là độ chính xác.

Trong quá trình triển khai ứng dụng có nhiều bài toán con phát sinh hay đơn giản là customize cho từng domain. Nếu giải thuật khó hiểu, cài đặt phức tạp, chạy trên phần cứng thông thường mất nhiều thời gian thì sẽ gây ra nhiều cản trở cho quá trình customize hoặc kết hợp dùng những giải thuật những model đang có để giải quyết bài toán cón.

Vì thế một baseline ✨ ĐỦ TỐT ✨ là rất quan trọng.

- - -

Q: Baseline đủ tốt là gì?

Baseline là các giải thuật dễ hiểu và cách cài đặt đơn giản nhưng kết quả đủ tốt và hiệu năng cao. Vì dễ hiểu, đơn giản, và hiệu năng cao nên có thể chỉnh sửa, cải tiến, chạy thử nghiệm liên tục mà không phải chờ đợi hàng giờ, hàng ngày, hàng năm hoặc vò đầu bứt tai vì không hiểu đoạn code này để làm cái gì và chỗ này nên chỉnh sửa như thế nào.

Baseline là một nền móng rất quan trọng để phát triển dự án. Sau khi đã kết thúc quá trình thử nghiệm có thể chúng ta không dùng baseline khi triển khai ứng dụng nhưng baseline vẫn có giá trị là dấu mốc để so sánh xem chúng ta đã đi được bao xa và liệu bỏ ra thêm công sức và tiền bạc (thuê hay mua phần cứng) để cài đặt và triển khai một giải thuật mới có đáng hay không?

Baseline là để trả lời câu hỏi CÓ ĐÁNG HAY KHÔNG đó!


- - -

Q: Tiến độ tới đâu rồi Tuộc?

A: Đang dần hoàn thiện baseline đó bạn. Xem phân `README.md` và tài liệu trong thư mục `docs` của từng dự án để biết thêm chi tiết.