### Hi there 👋

Lại là **Tuộc** đây và mời bạn cùng tham gia ✨ _hành trình_ ✨ áp dụng lập trình hệ thống, hiệu năng cao vào xử lý ngôn ngữ tiếng Việt và cải tiến bộ gõ Telex 🐙 🐙 🐙

* Bạn thấy thích và tham gia liền thì bấm [vào đây](https://github.com/telexyz#t%C3%B4i-c%C3%B3-th%E1%BB%83-tham-gia-%C4%91%C6%B0%E1%BB%A3c-kh%C3%B4ng-v%C3%A0-n%C3%AAn-b%E1%BA%AFt-%C4%91%E1%BA%A7u-t%E1%BB%AB-%C4%91%C3%A2u)

* Hoặc bỏ chút thời gian đọc phần hỏi đáp dưới đây nhé:

- - -

### `telexyz` nghĩa là gì?

`telexyz` nghĩa là bắt đầu ở bộ gõ tiếng Việt (`telex`) và gia tăng giá trị cho nó (`xyz`):

Người dùng tương tác mới máy tính chủ yếu qua bàn phím. Và Telex là kiểu gõ tiếng Việt phổ biến nhất. Làm NLP hiệu quả nên khai thác ngay điểm khởi của dữ liệu - là khi người dùng đang gõ bàn phím. Chẳng hạn có thể áp dụng dự đoán từ, sửa chính tả ngay trong lúc người dùng đang gõ không? Làm thế nào để vừa gõ tiếng Việt vừa gõ tiếng Anh hiệu quả? Có thể gõ không dấu và máy tính tự bỏ dấu tiếng Việt không? ...

Nếu làm killer apps cho tiếng Việt thì bộ gõ chắc chắn là lựa chọn số 1 vì ai cũng phải dùng.

- - -

### Tại sao lại là lập trình hệ thống với những ngôn ngữ cơ bản như C/C++/Zig mà không sử dụng ngôn ngữ bậc cao như Python? Là vì:

🔭 Cài đặt từ đầu các giải thuật bằng ngôn ngữ lập trình bậc thấp và sử dụng các kỹ thuật tối ưu hóa ở mức lập trình hệ thống sẽ giúp chương trình chạy NHANH NHẤT - và có sự hiểu sâu hơn về giải thuật, dữ liệu, và hệ thống từ đó biết được ưu điểm, nhược điểm và các cách cải tiến.

⚡ Tốc độ ưu việt: đương nhiên rồi, vì lập trình hệ thống mà. Không những cả tốc độ mà bộ nhớ cũng được sử dụng tối ưu. Điều này rất quan trọng khi triển khai trên các thiết bị không mạnh như mobile.

🌱 Triển khai đa dạng: Qua website (bằng web assembly) hoặc nhúng vào những hệ thống phần cứng khác nhau, từ cloud workers, servers, PC cho tới mobile đều dễ dàng. Ở đâu có hỗ trợ C compiler thì ở đó chúng ta có thể triển khai được ứng dụng viết bằng C/C++/Zig ...

- - -

### Tại sao lại code từ đầu mà không dùng thư viện có sẵn?

Muốn có kết quả ngay thì bạn nên dùng thư viện có sẵn, có nhiều thư viện như thế với chất lượng tuyệt vời, và cả những models đã được train bằng phần cứng chuyên dụng không tự làm ở nhà được. Tuy nhiên đấy là với người chuyên nghiệp đã có kinh nghiệm làm thực tế nhiều năm, còn với người mới thì riêng việc đọc hiểu và lựa chọn công cụ cũng rất mất thời gian. Cũng công sức như thế sao ta không bỏ ra để cài đặt lại theo cách mà ta muốn: hợp với bài toán đang giải quyết - khớp với mục đích ta theo đuổi.

- - -

### Tiêu chí của dự án là gì?

Tối ưu `hiệu năng = độ chính xác / công sức cài đặt * độ tốn kém phần cứng khi chạy giải thuật`. Nếu bỏ ra 1 tháng trời để cài đặt hóc búa hoặc bỏ vài ngàn đô để mua phần để độ chính xác tăng lên 5% chẳng hạn thì hẳn đã là tốt, trừ trường hợp mục tiêu của bạn là độ chính xác.

Trong quá trình triển khai ứng dụng nhiều lúc phải loay hoay với những bài toán con phát sinh. Nếu giải thuật khó hiểu, cài đặt phức tạp, chạy trên phần cứng thông thường mất nhiều thời gian thì sẽ gây ra nhiều cản trở cho quá trình #thử_sai. Thời gian chạy càng ngắn, code càng dễ hiểu ta; càng thử sai được nhiều lần và rút kinh nghiệm nhanh hơn.

Như vậy, có trong tay một baseline ✨ ĐỦ TỐT ✨ là một vũ khí rất quan trọng.

- - -

### Baseline đủ tốt là gì?

Baseline là các giải thuật dễ hiểu và dễ cài đặt, kết quả đủ tốt và hiệu năng cao. Vì dễ hiểu, đơn giản, và hiệu năng cao nên có thể chỉnh sửa, cải tiến, chạy thử nghiệm liên tục mà không phải chờ đợi hàng giờ, hàng ngày, hàng tuần ... hoặc vò đầu bứt tai vì không hiểu đoạn code này làm gì và nên chỉnh sửa thế nào.

Sau khi đã kết thúc quá trình thử nghiệm có thể chúng ta không dùng trực tiếp baseline nhưng đó vẫn là dấu mốc để xem chúng ta đã đi được bao xa và liệu bỏ ra thêm công sức và tiền bạc để cài đặt hoặc triển khai một giải thuật mới có đáng hay không? Baseline tốt sẽ giúp trả lời câu hỏi CÓ ĐÁNG HAY KHÔNG đó nhanh chóng, chính xác!


- - -

### Tiến độ tới đâu rồi Tuộc?

Xem `README.md` và `docs` của từng `repo` để biết thêm chi tiết.


- - -

### Tôi có thể tham gia được không và nên bắt đầu từ đâu?

Welcome bạn. Ai cũng có thể tham gia được, không cần kiến thức lập trình hệ thống cũng như xử lý ngôn ngữ (NLP). Bởi:

1. Ngôn ngữ lập trình Tuộc chọn là [Zig](https://ziglang.org/documentation/master) đơn giản và nhất quán nên dễ học viết ít khi mắc lỗi; biên dịch nhanh, chạy lẹ, sử dụng lại dễ dàng các thư viện viết C/C++, tính độc lập cao vì để code = Zig chỉ cần download 1 file zip về là đủ.

2. Các giải thuật được comment rõ ràng; code dễ hiểu, dễ bắt lỗi và dễ phát triển tiếp.

3. Sự hiểu biết về ngôn ngữ tự nhiên là cái có sẵn trong mỗi chúng ta vậy nên kiến thức NLP nhiều khi không quan trọng bằng `trực giác`.

Vậy nên cứ mạnh dạn tham gia nhé. Cụ thể hơn:

* Bạn đã có kinh nghiệm lập trình thì vọc [mau](https://github.com/telexyz/mau) + [engine](https://github.com/telexyz/engine). Là phần nền tảng có nhiều mẹo tối ưu các giải thuật kinh điển được cài đặt và may đo riêng cho tiếng Việt như tách và phân loại token thành Vietnamese vs non-Vietnamese, phân tích ngữ âm các token là âm tiết Tiếng Việt và định danh không dùng từ điển. Khi cần ép số lượng tokens xuống để làm nhẹ baseline thì nên làm thế nào? Với `16-bits` chúng ta nên định danh những gì (âm tiết, từ 2 âm tiết, từ 3 âm tiết ...) để các bước xử lý tiếp theo được thuận lợi hơn mà vẫn tiết kiệm tài nguyên? Với âm tiết là thành phần chủ đạo, nên làm inverted indexing dùng trong full-text-searh như thế nào? ... có nhiều thứ thú vị để khám phá.

* Quay lại thời sinh viên, học machine learning thật cơ bản và tìm hiểu những mô hình cỡ nhỏ để giải quyết bài toán đặc thù như tách từ, tách câu, thêm dấu ... xem [mlxs](https://github.com/telexyz/mlxs/issues)

* Áp dụng mọi thứ đã tìm hiểu đc để cải tiến bộ gõ thông minh, giúp gõ song ngữ Việt - Anh dễ dàng hơn, trợ giúp người dùng đắc lực hơn [fingers-sublime](https://github.com/telexyz/fingers-sublime)

- - -

> Bạn muốn thứ gì đó thật đơn giản nhưng vẫn ✨ _fancy_ ✨ thì làm [word embedding](https://github.com/telexyz/embed). Bạn sẽ hiểu thêm về vector space model, re-distributed representation, hiểu cách cài đặp một neural network đơn giản để tạo ra word vectors từ text corpus trong chưa tới 200 dòng mã. Dựa trên word vectors có thể mở ra nhiều ứng dụng như topic embedding, document embedding, sense embedding ... và ứng dụng vào text classification, sentiment analysic, text mining và semantic search.

> Bạn thích deep learning thì bắt đầu bằng [nnlm](https://github.com/telexyz/nnlm) - mô hình ngôn ngữ sử dụng mạng nơ-ron. Bạn có thể tìm hiểu và thử nghiệm Transformer hoặc các kiến trúc tinh gọn hơn như QRNN, SHA-QRNN, SRU++, RWKV-LM ...
