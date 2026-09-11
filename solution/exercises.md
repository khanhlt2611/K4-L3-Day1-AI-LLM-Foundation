# K4 — Ngày 1: Bài Tập & Phản Ánh
## Khám Phá LLM API | Phiếu Thực Hành

**Thời lượng:** 4 tiếng
**Cách làm:** Trả lời từng câu ngay sau khi hoàn thành block tương ứng —
đừng để dồn hết về cuối buổi. Thay dòng `*Câu trả lời của bạn*` bằng câu
trả lời thật (chấm tự động sẽ đếm số câu đã trả lời).

---

## Block 1 — API Cơ Bản (trả lời sau Checkpoint 1)

### Câu 1.1 — Độ nhạy của temperature
Gọi `call_openai` với temperature 0.0, 0.5, 1.0 và 1.5 dùng prompt
**"Hãy kể cho tôi một sự thật thú vị về Việt Nam."**

**Bạn nhận thấy quy luật gì qua bốn phản hồi?** (2–3 câu)

**0.0:** Một trong những sự thật thú vị và đáng tự hào nhất về Việt Nam chính là: **Việt Nam sở hữu hang động tự nhiên lớn nhất thế giới – Hang Sơn Đoòng.**

Dưới đây là những điều kỳ diệu về hang động này mà có thể bạn chưa biết:

1. **Rộng lớn đến mức khó tin:** Hang Sơn Đoòng lớn đến mức người ta ước tính nó có thể chứa vừa một **khu phố ở Manhattan, New York với những tòa nhà chọc trời 40 tầng**, hoặc có thể xếp vừa 68 chiếc máy bay Boeing 747.
2. **Có thời tiết và hệ sinh thái riêng:** Do kích thước khổng lồ và có những khoảng trần hang bị sập (gọi là hố sụt) đón ánh sáng mặt trời vào, bên trong hang Sơn Đoòng có cả một **khu rừng nguyên sinh** phát triển tươi tốt (được gọi là "Vườn địa đàng") và một dòng sông ngầm chảy xiết. Thậm chí, sự chênh lệch nhiệt độ giữa bên trong và bên ngoài hang tạo ra những đám mây và sương mù lơ lửng ngay trong lòng hang.
3. **Được phát hiện một cách tình cờ:** Hang được tìm thấy lần đầu tiên vào năm 1990 bởi một người dân địa phương tên là Hồ Khanh khi ông đi rừng lánh mưa. Tuy nhiên, do tiếng nước chảy ầm ầm và gió rít mạnh từ cửa hang, ông đã không dám vào sâu. Phải đến năm 2009, khi ông dẫn đoàn thám hiểm Hoàng gia Anh trở lại, hang mới chính thức được khám phá và công bố ra thế giới.

**Một "bonus" sự thật thú vị khác:** 
Khoảng **39% dân số Việt Nam mang họ Nguyễn**. Đây là tỷ lệ một họ phổ biến nhất tại một quốc gia trên thế giới (vượt qua cả họ Kim ở Hàn Quốc hay họ Smith ở các nước nói tiếng Anh).

**0.5:** Một sự thật cực kỳ thú vị và đáng tự hào về Việt Nam chính là: **Việt Nam sở hữu hang động tự nhiên lớn nhất thế giới – Hang Sơn Đoòng**, và nó lớn đến mức **sở hữu cả một hệ thống thời tiết và hệ sinh thái riêng biệt bên trong.**

Dưới đây là những chi tiết kinh ngạc về hang động này:

1. **Kích thước khổng lồ:** Hang Sơn Đoòng (nằm tại Vườn quốc gia Phong Nha - Kẻ Bàng, Quảng Bình) lớn đến mức có thể chứa vừa một tòa nhà chọc trời 40 tầng của thành phố New York, hoặc một chiếc máy bay Boeing 747 có thể bay qua phần rộng nhất của hang mà không chạm cánh.
2. **Có thời tiết riêng:** Do kích thước quá lớn và có những hố sụt (nơi trần hang bị sập xuống đón ánh nắng mặt trời), bên trong hang hình thành nên những đám mây, sương mù và hệ thống thời tiết hoàn toàn tách biệt với thế giới bên ngoài.
3. **Khu rừng nguyên sinh trong lòng đất:** Tại các hố sụt, ánh sáng mặt trời lọt vào đã tạo điều kiện cho một khu rừng nhiệt đới phát triển ngay bên trong hang. Các nhà thám hiểm gọi đây là "Vườn địa đàng" (Garden of Edam), nơi có nhiều loài thực vật và côn trùng quý hiếm mà bên ngoài không có.
4. **Ngọc trai hang động khổng lồ:** Trong hang có những viên "ngọc trai" tự nhiên (hình thành do nước nhỏ giọt tích tụ canxi qua hàng triệu năm) to bằng quả bóng chày, trong khi thông thường chúng chỉ bằng hạt đậu.

**Một chi tiết thú vị khác:** Hang động vĩ đại này không phải do các nhà khoa học tìm ra trước, mà được phát hiện tình cờ vào năm 1991 bởi một người dân địa phương đi hái củi tên là **Hồ Khanh**. Đến năm 2009, khi đoàn thám hiểm Hoàng gia Anh đến khảo sát, thế giới mới chính thức biết đến kỳ quan này.

**1.0:** Một sự thật cực kỳ thú vị và đáng tự hào về Việt Nam chính là: **Việt Nam sở hữu hang động tự nhiên lớn nhất thế giới – Hang Sơn Đoòng**, và bên trong hang có cả một hệ sinh thái riêng biệt với thời tiết và rừng rậm riêng!

Dưới đây là những chi tiết "kinh ngạc" về kỳ quan này:

* **Rộng lớn đến mức không tưởng:** Hang Sơn Đoòng (nằm tại tỉnh Quảng Bình) lớn đến mức có thể chứa vừa một **khu phố của thành phố New York với các tòa nhà chọc trời cao 40 tầng**. Thậm chí, một chiếc máy bay Boeing 747 cũng có thể bay vừa qua những đoạn rộng nhất của hang.
* **Có thời tiết và mây riêng:** Do kích thước khổng lồ và sự chênh lệch nhiệt độ giữa bên trong và bên ngoài, hang Sơn Đoòng tự tạo ra hệ thống thời tiết riêng. Du khách khi khám phá hang có thể nhìn thấy những đám mây sương mù bay lơ lửng ngay trong lòng hang.
* **Có cả một khu rừng nguyên sinh:** Tại những nơi trần hang bị sập xuống (gọi là hố sụt), ánh sáng mặt trời lọt vào đã tạo điều kiện cho một khu rừng nhiệt đới phát triển ngay bên trong hang. Các nhà thám hiểm gọi đây là "Vườn địa đàng" (Garden of Edam).
* **Số lượng người từng đặt chân vào đây còn ít hơn số người từng leo lên đỉnh Everest:** Vì lý do bảo tồn, số lượng khách du lịch được phép vào hang Sơn Đoòng cực kỳ hạn chế (chỉ khoảng 1.000 người mỗi năm) và chi phí cho một tour thám hiểm là khoảng 3.000 USD (gần 75 triệu VNĐ). 

Đây thực sự là một "thế giới bị lãng quên" đầy kỳ vĩ nằm ngay tại Việt Nam!

**Việt Nam là nơi sở hữu hang động tự nhiên lớn nhất thế giới – Hang Sơn Đoòng.**

Hang Sơn Đoòng nằm trong quần thể di sản thiên nhiên thế giới Phong Nha - Kẻ Bàng (tỉnh Quảng Bình) và ẩn chứa những điều kỳ diệu tưởng chừng như chỉ có trong phim viễn tưởng:

* **Rộng lớn đến mức không tưởng:** Hang lớn đến mức người ta ước tính có thể chứa vừa cả một **khu phố ở Manhattan, Mỹ với các tòa nhà chọc trời 40 tầng**. Thậm chí, một chiếc máy bay Boeing 747 cũng có thể bay qua phần rộng nhất của hang.
* **Sở hữu hệ thời tiết riêng:** Do kích thước khổng lồ và sự chênh lệch nhiệt độ, bên trong hang Sơn Đoòng có cả **mây, sương mù và gió** tựa như một thế giới hoàn toàn tách biệt với bên ngoài.
* **Có rừng nguyên sinh trong lòng đất:** Tại những nơi trần hang bị sập xuống tạo thành các "hố sụt", ánh sáng mặt trời lọt vào đã tạo điều kiện cho cả một **khu rừng nhiệt đới phát triển ngay bên trong hang**. Người ta gọi đây là "Vườn Địa Đàng".
* **Ngọc trai khổng lồ:** Trong hang có những viên "ngọc trai hang động" (hình thành từ nước nhỏ giọt tích tụ canxi qua hàng vạn năm) có kích thước to bằng quả bóng chày, lớn hơn rất nhiều so với ngọc trai hang động thông thường ở các nơi khác.

Điều thú vị là hang động vĩ đại này mới chỉ được một người dân địa phương tên là Hồ Khanh tình cờ phát hiện vào năm 1991, và mãi đến năm 2009 mới được các nhà thám hiểm Anh công bố rộng rãi ra thế giới!

**1.5:** Một trong những sự thật thú vị và

### Câu 1.2 — Chọn temperature cho sản phẩm
**Bạn sẽ đặt temperature bao nhiêu cho chatbot hỗ trợ khách hàng, và tại sao?**

Đối với ứng dụng chatbot cho khách hàng, tôi sẽ ưu tiên sử dụng temperature thấp (0,1-0,3) để câu trả lời sinh ra bám sát tài liệu của doanh nghiệp, tránh việc mô hình sáng tạo và bịa đặt thông tin. Cũng không để 0.0 để tránh quá cứng nhắc

### Câu 1.3 — Đánh đổi chi phí
Kịch bản: 10.000 người dùng hoạt động mỗi ngày, mỗi người gọi API 3 lần,
mỗi lần trung bình ~350 token đầu ra.

**Ước tính GPT-4o đắt hơn GPT-4o-mini bao nhiêu lần cho workload này? Nêu một
trường hợp GPT-4o xứng đáng với chi phí và một trường hợp nên dùng mini:**

GPT-4o sẽ đắt hơn khoảng 16 lần. 
GPT-4o sẽ đắt hơn khoảng 16 lần. GPT-4o sẽ xứng đáng với những tác vụ cần suy luận nhiều còn mô hình mini phù hợp để làm những tác vụ không cần suy nghĩ nhiều như chào hỏi, nói chuyện phiếm, viết hàm hello world,...

---

## Block 2 — System Prompt & Token (trả lời sau Checkpoint 2)

### Câu 2.1 — Sức mạnh của persona
Gọi `chat_with_system_prompt` hai lần với cùng câu hỏi
**"Giải thích blockchain là gì?"** nhưng hai system prompt khác nhau:
- "Bạn là giáo viên tiểu học, giải thích thật đơn giản cho trẻ 8 tuổi."
- "Bạn là chuyên gia tài chính, trả lời chuyên sâu bằng thuật ngữ kỹ thuật."

**Hai phản hồi khác nhau như thế nào (độ dài, từ vựng, ví dụ)? System prompt
ảnh hưởng đến hành vi model ra sao?** (3–4 câu)

Hai phản hồi có độ dài tương đồng tuy nhiên cách sử dụng từ vựng và ví dụ thì rất khác nhau. Prompt 1 sẽ sinh ra câu trả lời bằng cách kể chuyện, lấy ví dụ bằng các câu chuyện thường ngày dễ hiểu. Prompt 2 sinh ra theo hướng diễn giải học thuật, các từ ngữ cũng khó hiểu hơn

### Câu 2.2 — tiktoken vs đếm từ
Chọn một đoạn văn tiếng Việt ~100 từ. So sánh số token theo `count_tokens`
(tiktoken) với ước lượng `số từ / 0.75` mà Part 1 đã dùng.

**Hai con số chênh nhau bao nhiêu phần trăm? Vì sao tiếng Việt thường tốn
nhiều token hơn tiếng Anh cùng độ dài?**

Số từ: 100
tiktoken: 125 token
Ước lượng từ/0.75: 133.33 token
Chênh lệch: 6.25%

Hai cách tính chênh nhau 6,25%. Tiếng Việt thường tốn nhiều token hơn tiếng Anh có cùng độ dài vì các dấu thanh, ký tự unicode có thể khiến một từ được biểu diễn bằng nhiều token.


---

## Block 3 — Streaming & Độ Bền (trả lời sau Checkpoint 3)

### Câu 3.1 — Trải nghiệm người dùng với streaming
**Streaming quan trọng nhất trong trường hợp nào, và khi nào thì
non-streaming lại phù hợp hơn?** (1 đoạn văn)

Streaming quan trọng nhất khi model cần tạo phản hồi dài hoặc có độ trễ cao, chẳng hạn chatbot hội thoại, vì người dùng có thể đọc nội dung ngay khi từng phần được sinh ra thay vì phải chờ toàn bộ câu trả lời. Non-streaming phù hợp hơn khi cần kiểm tra và định dạng toàn bộ nội dung trước khi hiển thị cho người dùng.

### Câu 3.2 — Vì sao backoff theo cấp số nhân?
**So với delay cố định (ví dụ luôn chờ 1 giây), exponential backoff có lợi
thế gì khi API bị quá tải? Điều gì xảy ra nếu hàng nghìn client cùng retry
với delay cố định giống nhau?**

Exponential backoff tăng dần thời gian chờ sau mỗi lần thất bại, nhờ đó giảm số request gửi đến API đang quá tải và cho hệ thống thêm thời gian phục hồi. Nếu hàng nghìn client cùng retry sau một khoảng delay cố định, chúng có thể đồng loạt gửi lại request tại cùng thời điểm sẽ khiến API tiếp tục quá tải. 

---

## Block 4 — Mini-Project (trả lời sau Checkpoint 4)

### Câu 4.1 — Thiết kế persona
**Bạn chọn persona gì cho trợ lý của mình? Viết lại system prompt đó và giải
thích 1–2 lựa chọn từ ngữ quan trọng trong prompt (ví dụ: vì sao yêu cầu
"trả lời ngắn gọn", vì sao chỉ định ngôn ngữ...):**

Tôi chọn persona là trợ giảng AI thân thiện với system prompt: "Bạn là trợ giảng thân thiện của khóa AI, trả lời ngắn gọn, chính xác bằng tiếng Việt và giải thích bằng ví dụ đơn giản khi cần." Cụm "ngắn gọn, chính xác" giúp phản hồi tập trung vào câu hỏi và hạn chế nội dung lan man; yêu cầu "bằng tiếng Việt" bảo đảm câu trả lời phù hợp với người học trong khóa.

### Câu 4.2 — Hạn chế & cải thiện
**Trợ lý của bạn hiện có hạn chế lớn nhất là gì (ví dụ: history chỉ 3 lượt,
không có bộ nhớ dài hạn, không kiểm duyệt nội dung...)? Đề xuất một cải
thiện cụ thể và mô tả ngắn cách triển khai:**

Hạn chế lớn nhất của trợ lý là chỉ giữ ba lượt hội thoại gần nhất nên có thể quên thông tin quan trọng đã xuất hiện trước đó. Tôi sẽ cải thiện bằng cách tóm tắt các lượt cũ trước khi loại chúng khỏi history, lưu bản tóm tắt vào một message riêng và gửi message này cùng ba lượt gần nhất trong mỗi lần gọi API. Cách này giúp duy trì ngữ cảnh dài hạn tương đối tốt mà vẫn kiểm soát được số token và chi phí.

---

## Danh Sách Kiểm Tra Nộp Bài

- [ ] `python grade.py` — xem điểm tự động, mục tiêu ≥ 75/100
- [ ] Cả 4 checkpoint pytest đều pass
- [ ] Tất cả 9 câu trong file này đã được trả lời
- [ ] Đã copy bài làm vào folder `solution/`, push lên fork và dán link trên trang bài Lab ở VLearn trước 23:59 ngày 11/09/2026
