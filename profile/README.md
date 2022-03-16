### Hi there 👋

Lại là **Tuộc** đây và mời bạn cùng tham gia ✨ _hành trình_ ✨ áp dụng lập trình hệ thống vào xử lý ngôn ngữ tiếng Việt và cải tiến bộ gõ Telex 🐙 🐙 🐙

* Bạn thấy thích và tham gia liền thì bấm [vào đây](https://github.com/telexyz#t%C3%B4i-c%C3%B3-th%E1%BB%83-tham-gia-%C4%91%C6%B0%E1%BB%A3c-kh%C3%B4ng-v%C3%A0-n%C3%AAn-b%E1%BA%AFt-%C4%91%E1%BA%A7u-t%E1%BB%AB-%C4%91%C3%A2u)

* Còn không thì bỏ chút thời gian đọc tiếp phần hỏi đáp dưới đây nhé:

- - -

### Các bạn có thể hỏi tại sao lại là lập trình hệ thống với những ngôn ngữ cơ bản như C/C++ hay Zig mà không sử dụng ngôn ngữ bậc cao như Python hay Julia? 


Đơn giản là vì:

🔭 Cài đặt lại từ đầu các giải thuật bằng một ngôn ngữ bậc thấp, tối ưu hóa cho hệ thống chương trình đang chạy sẽ giúp người pháp triển hiểu sâu hơn rất nhiều về giải thuật cũng như hệ thống mà chương trình sẽ được triển khai. Biết được ưu điểm, nhược điểm của từng giải thuật và các cách để cải tiến chúng ra sao. Điều này chỉ có thể làm được với lập trình hệ thống.

⚡ Tốc độ ưu việt: đương nhiên rồi, vì lập trình hệ thống mà. Không những cả tốc độ mà bộ nhớ nữa. Điều này rất quan trọng khi triển khai trên các thiết bị không mạnh như mobile chẳng hạn.

🌱 Triển khai đa dạng: Qua website bằng web assembly hoặc nhúng vào những hệ thống phần cứng khác không phải PC, deploy trên mobile cũng dễ dàng. Ở đâu có hỗ trợ C compiler thì ở đó chúng ta có thể triển khai được ứng dụng viết bằng C/C++/Zig.

- - -

### Tại sao lại code từ đầu mà không dùng thư viện có sẵn? 

Muốn có kết quả ngay và ra được ứng dụng ăn liền thì bạn nên dùng thư viện có sẵn, hiện có cực nhiều những thư viện như thế với chất lượng tuyệt vời, kể cả những models đã được train bằng những phần cứng chuyên dụng mà bạn không thể tự làm ở nhà được. Tuy nhiên đấy là với pro (người chuyên nghiệp đã có kinh nghiệm làm thực tế nhiều năm), còn với người mới thì riêng việc đọc hiểu và lựa chọn công cụ thôi cũng nổ đầu rồi. Cũng công sức như thế sao ta không bỏ ra để cài đặt lại theo kiểu #nhà_làm, theo cái cách mà ta muốn, phù hợp với bài toán đang giải quyết, khớp với mục đích ta theo đuổi?


- - -

### Mục tiêu của dự án là gì?

Không đuổi theo kết quả tốt nhất mà là hiệu năng tốt nhất (độ chính xác / công sức lập trình và độ tốn kém của phần cứng khi chạy giải thuật). Vì nếu bỏ ra 1 tháng trời để cài đặt hoặc bỏ vài ngàn đô để mua phần cứng về chạy giải thuật mới để độ chính xác tăng lên 5% chẳng hạn thì có lẽ chưa thỏa đáng, trừ trường hợp mục tiêu tối thượng của bạn là độ chính xác.

Trong quá trình triển khai ứng dụng nhiều lúc phải loay hoay với những bài toán con phát sinh. Nếu giải thuật khó hiểu, cài đặt phức tạp, chạy trên phần cứng thông thường mất nhiều thời gian thì sẽ gây ra nhiều cản trở cho quá trình #thử_sai đó. Thời gian chạy càng ngắn, code càng dễ hiểu ta; càng thử sai được nhiều lần và rút kinh nghiệm nhanh hơn.

Như vậy, có trong tay một baseline ✨ ĐỦ TỐT ✨ là một vũ khí rất quan trọng.

- - -

### Baseline đủ tốt là gì?

Baseline là các giải thuật dễ hiểu và cách cài đặt đơn giản nhưng kết quả đủ tốt và hiệu năng cao. Vì dễ hiểu, đơn giản, và hiệu năng cao nên có thể chỉnh sửa, cải tiến, chạy thử nghiệm liên tục mà không phải chờ đợi hàng giờ, hàng ngày, hàng tuần ... hoặc vò đầu bứt tai vì không hiểu đoạn code này để làm cái gì và chỗ này nên chỉnh sửa như thế nào.

Baseline là một nền móng rất quan trọng để phát triển dự án. Sau khi đã kết thúc quá trình thử nghiệm có thể chúng ta không dùng trực tiếp baseline nhưng đó vẫn là dấu mốc để xem chúng ta đã đi được bao xa và liệu bỏ ra thêm công sức và tiền bạc để cài đặt và triển khai một giải thuật mới có đáng hay không? Baseline tốt sẽ giúp trả lời câu hỏi CÓ ĐÁNG HAY KHÔNG đó nhanh chóng, chính xác!


- - -

### Tại sao lại là `telexyz`?

Người dùng tương tác mới máy tính chủ yếu qua bàn phím. Và để gõ tiếng Việt thì phổ biến nhất là kiểu gõ Telex. Sao không khai thác ngay điểm khởi của cả dữ liệu và tương tác người dùng đó? Chẳng hạn có thể áp dụng NLP ngay trong lúc người dùng đang gõ tiếng Việt được không? Làm thế nào để vừa gõ tiếng Việt vừa gõ tiếng Anh hiệu quả? Có thể gõ không dấu và máy tính tự bỏ dấu tiếng Việt dựa trên những văn bản người dùng đã gõ được không? ... Vậy nên `telexyz` nghĩa là bắt đầu ngay ở bộ gõ/cửa ngõ (`telex`) và gia tăng giá trị cho nó (`xyz`).

- - -

### Tiến độ tới đâu rồi Tuộc?

Tuy còn nhiều việc phải làm thêm nhưng baseline đã tạm đủ tốt để triển khai ứng dụng. Xem `README.md` và `docs` của từng `repo` để biết thêm chi tiết.


- - -

### Tôi có thể tham gia được không và nên bắt đầu từ đâu?

Welcome bạn. Ai cũng có thể tham gia được, không cần kiến thức lập trình hệ thống cũng như NLP. Bởi:

1/ Ngôn ngữ lập trình Tuộc chọn là https://ziglang.org/documentation/master nó vô cùng đơn giản và nhất quán nên dễ học viết ít khi bị mắc lỗi; biên dịch nhanh, chạy lẹ, khả chuyển với C, cài đặt chỉ cần download 1 file zip về là đủ.


2/ Các giải thuật của baseline là cơ bản, cài đặt rõ ràng; code dễ hiểu, dễ bắt lỗi và dễ phát triển tiếp.

Cụ thể hơn:

A/ Bạn chưa biết bất cứ thứ gì code / math ... thì bắt đầu ở đây https://github.com/telexyz/ml4coders. Tập hợp các bài học vỡ lòng, take note cẩn thận, comments chi tiết để bạn có thể hiểu và tự làm từ A-Z. Tham gia hỏi đáp, thảo luận, cùng học và làm bài tập tại https://discord.gg/SZnnFG6v.


B/ Bạn muốn thứ gì đó thật đơn giản nhưng ✨ _fancy_ ✨ thì làm https://github.com/telexyz/embed. Bạn sẽ hiểu thế nào là vector space model, re-distributed representation, word embedding, hiểu cách cài đặp một neural network đơn giản để tạo ra word vectors từ text corpus trong chưa tới 200 dòng mã. Dựa trên word embedding có thể mở ra nhiều biến thể  như topic embedding, document embedding, sense embedding ... và ứng dụng vào nhiều bài toán khác nhau từ NLP cơ bản cho tới text mining và semantic search. Đây thục sự là một baseline rất ngầu mà ai cũng có thể vọc được.


C/ Bạn đã có kinh nghiệm lập trình hệ thống thì cùng vọc https://github.com/telexyz/engine. Là phần nền tảng nhất và có nhiều mẹo tối ưu khi triển khai các giải thuật kinh điển cho tiếng Việt như bộ tách token cho âm tiết tiếng Việt và out-of-âm-tiết-tiếng-Việt (sử dụng sub-word). Làm thế nào chỉ cần `15-bits` là đủ để biểu diễn cho toàn bộ vài GB corpus đầu vào? Khi cần ép số lượng tokens xuống để làm nhẹ đi mô hình ngôn ngữ thì ép kiểu gì? Với `16-bits` chúng ta có thể và nên định danh những gì của tiếng Việt (âm tiết, từ 2 âm tiết, từ 3 âm tiết ...) để các bước xử lý tiếp theo được thuận lợi hơn và vẫn tiết kiệm tối đa bộ nhớ và CPU? Rồi với âm tiết là thành phần chủ đạo, nên cài đặt n-gram language model và làm inverted indexing để làm full-text-searh như thế nào? ... phần này hơi nhức đầu tí nhưng mà vui!


D/ Bạn thích deep learning thì bắt đầu bằng https://github.com/telexyz/nnlm - mô hình ngôn ngữ sử dụng mạng nơ ron. Bạn có thể cài đặt lại `rnnlm` đơn giản và tìm hiểu cách tối ưu mà chưa cần dùng tới GPU. Tiếp theo bạn thay `embedding layer` thành `projection layer` để trở thành kiến trúc tinh gọn pRNN. Làm tương tự với các kiến trúc khác như QRNN, SHA-QRNN, qMLP, HyperMixer ...
