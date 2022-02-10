### Hi there 👋

Lại là **Tuộc** đây và mời bạn cùng tham gia ✨ _hành trình_ ✨ áp dụng lập trình hệ thống vào xử lý ngôn ngữ tiếng Việt và cải tiến bộ gõ Telex 🐙 🐙 🐙

Các bạn có thể hỏi tại sao lại là lập trình hệ thống với những ngôn ngữ cơ bản như C/C++ hay Zig mà không sử dụng ngôn ngữ bậc cao như Python hay Julia? 


Đơn giản là vì:

🔭 Cài đặt lại từ đầu các giải thuật bằng một ngôn ngữ bậc thấp, tối ưu hóa cho hệ thống chương trình đang chạy sẽ giúp người pháp triển hiểu sâu hơn rất nhiều về giải thuật cũng như hệ thống mà chương trình sẽ được triển khai. Biết được ưu điểm, nhược điểm của từng giải thuật và các cách để cải tiến chúng ra sao. Điều này chỉ có thể làm được với lập trình hệ thống.

⚡ Tốc độ ưu việt: đương nhiên rồi, vì lập trình hệ thống mà. Không những cả tốc độ mà bộ nhớ nữa. Điều này rất quan trọng khi triển khai trên các thiết bị không mạnh như mobile chẳng hạn.

🌱 Triển khai đa dạng: ền web thông qua web assembly hoặc nhúng vào những hệ thống phần cứng khác không phải PC, deploy trên mobile cũng dễ dàng. Ở đâu có hỗ trợ C compiler thì ở đó chúng ta có thể triển khai được ứng dụng viết bằng C/C++/Zig.

- - -

### Tại sao lại code từ đầu mà không dùng thư viện có sẵn? 

A: Muốn có kết quả ngay và ra được ứng dụng ăn liền thì bạn nên dùng thư viện có sẵn, hiện có cực nhiều những thư viện như thế với chất lượng tuyệt vời, kể cả những models đã được train bằng những phần cứng chuyên dụng mà bạn không thể tự làm ở nhà được. Đấy là cả một kho tàng quý giá để bạn khai thác. Tuy nhiên đấy là với các pro (người chuyên nghiệp đã có kinh nghiệm làm thực tế nhiều năm), còn với người mới thì riêng việc đọc hiểu và lựa chọn công cụ thôi cũng nổ đầu rồi. Cũng công sức như thế sao ta không bỏ ra để cài đặt lại theo kiểu homemade theo cách mà ta muốn, khớp với mục đích ta đang theo đuổi?


- - -

### Mục tiêu của dự án là gì?

Không đuổi theo kết quả tốt nhất mà theo đuổi hiệu năng tốt nhất (độ chính xác / công sức lập trình và độ tốn kém của phần cứng khi chạy giải thuật). Vì nếu bỏ ra 1 tháng trời để cài đặt hoặc bỏ vài ngàn đô để mua phần cứng về chạy giải thuật mới để độ chính xác tăng lên 5-10% thì có lẽ chưa thỏa đáng, trừ trường hợp mục tiêu tối thượng của bạn là độ chính xác.

Trong quá trình triển khai ứng dụng có nhiều bài toán con phát sinh hay đơn giản là cần customize cho từng domain. Nếu giải thuật khó hiểu, cài đặt phức tạp, chạy trên phần cứng thông thường mất nhiều thời gian thì sẽ gây ra nhiều cản trở cho quá trình đó. 

Khi đó, có trong tay một baseline ✨ ĐỦ TỐT ✨ là rất quan trọng.

- - -

### Baseline đủ tốt là gì?

Baseline là các giải thuật dễ hiểu và cách cài đặt đơn giản nhưng kết quả đủ tốt và hiệu năng cao. Vì dễ hiểu, đơn giản, và hiệu năng cao nên có thể chỉnh sửa, cải tiến, chạy thử nghiệm liên tục mà không phải chờ đợi hàng giờ, hàng ngày, hàng tuần ... hoặc vò đầu bứt tai vì không hiểu đoạn code này để làm cái gì và chỗ này nên chỉnh sửa như thế nào.

Baseline là một nền móng rất quan trọng để phát triển dự án. Sau khi đã kết thúc quá trình thử nghiệm có thể chúng ta không dùng trực tiếp baseline nhưng đó vẫn là dấu mốc để xem chúng ta đã đi được bao xa và liệu bỏ ra thêm công sức và tiền bạc để cài đặt và triển khai một giải thuật mới có đáng hay không? Baseline tốt sẽ giúp trả lời câu hỏi CÓ ĐÁNG HAY KHÔNG đó nhanh chóng, chính xác!


- - -

### Tại sao lại là `telexyz`?

Người dùng tương tác mới máy tính chủ yếu qua bàn phím. Và để gõ tiếng Việt thì phổ biến nhất là kiểu gõ Telex. Sao không khai thác ngay điểm khởi của cả dữ liệu và tương tác người dùng đó? Chẳng hạn có thể áp dụng NLP ngay trong lúc người dùng đang gõ tiếng Việt được không? Làm thế nào để vừa gõ tiếng Việt vừa gõ tiếng Anh hiệu quả? Có thể gõ không dấu và máy tính tự bỏ dấu tiếng Việt dựa trên những văn bản người dùng đã gõ được không? ... Vậy nên `telexyz` nghĩa là bắt đầu bằng bộ gõ `telex` gia tăng giá trị cho nó(`+ xyz`).

- - -

### Tiến độ tới đâu rồi Tuộc?

Tuy còn nhiều việc phải làm thêm nhưng baseline đã tạm đủ tốt để triển khai ứng dụng. Xem `README.md` và `docs` của từng `repo` để biết thêm chi tiết.


- - -

### Tôi có thể tham gia được không và nên bắt đầu từ đâu?

Welcome bạn. Ai cũng có thể tham gia được, không cần kiến thức lập trình hệ thống cũng như NLP. Bởi:

1/ Ngôn ngữ lập trình Tuộc lựa chọn là https://ziglang.org/documentation/master nó vô cùng đơn giản, biên dịch nhanh, chạy lẹ, khả chuyển với C, và cài đặt chỉ cần download 1 file zip về là đủ.


2/ Các giải thuật của baseline là kinh điển, cài đặt rõ ràng, tối ưu trong sáng để code trở nên dễ hiểu, dễ bắt lỗi và dễ độ tiếp.

Cụ thể hơn:

3/ Bạn thích làm ứng dụng thì chiến https://github.com/telexyz/fingers là bộ gõ telex trên nền javascript và tương tác với nlp engine thông qua web assembly.


4/ Bạn muốn thứ gì đó thật đơn giản nhưng vẫn ✨ _fancy_ ✨ thì làm https://github.com/telexyz/embed. Bạn sẽ hiểu thế nào là vector space model, re-distributed representation, word embedding, hiểu cách cài đặp một neural network đơn giản để tạo ra word vectors từ text corpus trong chưa tới [200 dòng mã](https://github.com/telexyz/embed/blob/main/src/model.zig). Dựa trên word embedding có thể mở ra nhiều biến thể  như topic embedding, document embedding, sense embedding ... và ứng dụng vào nhiều bài toán khác nhau từ NLP cơ bản cho tới text mining và semantic search. Đây là một baseline rất ngầu mà ai cũng có thể vọc được.

Mọi người hay nói word vectors là đầu vào cho deep learning nhưng bản thân nó đã là cả một thế giới rồi. Và biết đâu đôi khi deep learning lại là công cụ để bạn xây dựng nên thế giới đó!


5/ Bạn đã có kinh nghiệm lập trình hệ thống thì cùng vọc https://github.com/telexyz/engine. Là phần nền tảng nhất và có nhiều mẹo tối ưu khi triển khai các giải thuật kinh điển cho tiếng Việt như bộ tách token cho âm tiết tiếng Việt và out-of-âm-tiết-tiếng-Việt (sử dụng sub-word). Làm thế nào chỉ cần `15-bits` là đủ để biểu diễn cho toàn bộ vài GB corpus đầu vào? Khi cần ép số lượng tokens xuống để làm nhẹ đi mô hình ngôn ngữ thì ép kiểu gì? Với `16-bits` chúng ta có thể và nên định danh những gì của tiếng Việt (âm tiết, từ 2 âm tiết, từ 3 âm tiết ...) để các bước xử lý tiếp theo được thuận lợi hơn và vẫn tiết kiệm tối đa bộ nhớ và CPU? Rồi với âm tiết là thành phần chủ đạo, nên cài đặt n-gram language model và làm inverted indexing để làm full-text-searh như thế nào? ... phần này hơi nhức đầu tí nhưng mà vui!


6/ Bạn thích deep learning thì vọc https://github.com/telexyz/rnnlm, mô hình ngôn ngữ sử dụng mạng nơ ron hồi quy. Bạn có thể cài đặt lại `rnnlm` như là một bước cải tiến của `word2vec`, rồi LSTM ...  Một câu hỏi quan trọng là __"deep tới đâu là đủ?"__. Ví dụ một rnnlm đơn giản là đủ cho hậu xử lý của tác vụ tách từ. Với một language model có độ ứng dụng và hiệu năng cao thì có lẽ LSTM là đủ ...