# 5 Kỹ Thuật Làm Chủ AI

### Tài liệu được viết dựa trên chia sẻ của  Giáo sư Jeremy Utley từ Đại học Stanford, một chuyên gia với 16 năm kinh nghiệm giảng dạy về sáng tạo, sẽ thay đổi hoàn toàn tư duy của bạn về việc cộng tác với AI.

## 1. Context Engineering (Kỹ thuật ngữ cảnh)
Đây được coi là phiên bản nâng cấp của "prompt engineering"
Thay vì chỉ đưa ra những câu lệnh ngắn gọn, bạn cần cung cấp đầy đủ tất cả * thông tin, tài liệu và chỉ dẫn cần thiết* để AI có thể thực hiện nhiệm vụ một cách chính xác nhất

### Ví dụ:
Thay vì chỉ yêu cầu "viết email bán hàng", bạn nên tải lên các tài liệu về hướng dẫn thương hiệu, phong cách cá nhân hoặc bản ghi chép cuộc gọi với khách hàng để AI hiểu rõ bối cảnh
Bài kiểm tra tính nhân văn: Nếu bạn đưa yêu cầu đó cho một đồng nghiệp mà họ không thể thực hiện được vì thiếu thông tin, thì bạn cũng không nên mong đợi AI làm tốt hơn

## 2. Chain of Thought Reasoning (Lập luận theo chuỗi tư duy)

Kỹ thuật này yêu cầu AI phải "lập luận & suy nghĩ theo từng bước" trước khi đưa ra câu trả lời cuối cùng. Việc này giúp cải thiện đáng kể chất lượng đầu ra vì AI sẽ xử lý logic từng bước một THAY VÌ chỉ dự đoán từ tiếp theo một cách ngẫu nhiên

### Ví dụ cách thực hiện:
 Thêm câu lệnh "Trước khi trả lời yêu cầu của tôi, hãy trình bày cho tôi quy trình suy nghĩ của bạn theo từng bước"
 --> Lợi ích: Bạn có thể kiểm tra các giả định và logic mà AI đang sử dụng để đánh giá độ tin cậy của kết quả

 ## 3. Few-shot Prompting (Cung cấp ví dụ)
AI là một "cỗ máy bắt chước" xuất sắc. Nếu bạn không đưa ra ví dụ, nó sẽ bắt chước những nội dung trung bình trên internet

Cách thực hiện: Đưa vào prompt những ví dụ thực tế về kết quả mà bạn cho là tốt. Bằng cách đưa ra các ví dụ (như 5 email tốt nhất của bạn - Text, docs, Hình ảnh,...), bạn đang cung cấp dữ liệu ngữ cảnh để AI không phải "bắt chước internet" một cách chung chung

Mẹo nâng cao: Bạn cũng có thể cung cấp thêm các ví dụ xấu và yêu cầu AI tránh phong cách đó. Nếu khó nghĩ ra ví dụ xấu, bạn có thể yêu cầu AI tự tạo ra một phiên bản đối lập với ví dụ tốt của bạn để làm mẫu

## 4. Reverse Prompting (Nhắc nhở ngược)
Thay vì để AI tự suy diễn và đưa ra thông tin sai lệch khi thiếu dữ liệu, hãy cho phép AI đặt câu hỏi ngược lại cho bạn

### Cách thực hiện: 
   Thêm vào cuối prompt câu lệnh: "Trước khi bắt đầu, hãy hỏi tôi bất kỳ thông tin nào bạn cần để hoàn thành tốt công việc này"
   --> Lợi ích: Điều này giúp AI xác định được các lỗ hổng thông tin (như số liệu bán hàng thực tế) thay vì tự ý bịa đặt

## 5. Assigning a Role (Gán vai trò) & Roleplaying (Đóng vai): Hai kỹ thuật này tạo ra ngữ cảnh về tư duy và hành vi
Việc gán cho AI một vai trò cụ thể giúp nó khoanh vùng kiến thức và tập trung vào những kết nối thông tin phù hợp trong kho dữ liệu khổng lồ của nó
. Khi gán vai bạn đang khoanh vùng các nguồn kết nối thông tin mà AI nên ưu tiên sử dụng
. Roleplaying là ứng dụng thực tế cao nhất của việc thiết lập một ngữ cảnh tương tác phức tạp

### Cách thực hiện: 
Yêu cầu AI đóng vai là một chuyên gia trong lĩnh vực cụ thể (như nhà tâm lý học, biên tập viên chuyên nghiệp) hoặc thậm chí là một nhân vật nổi tiếng (như Dale Carnegie hay Elon Musk) để áp dụng tư duy và nguyên tắc của họ vào công việc

Ứng dụng: Bạn có thể sử dụng kỹ thuật này để mô phỏng các cuộc hội thoại khó khăn, trong đó AI đóng vai người đối thoại để bạn thực hành trước khi giao tiếp thực tế
