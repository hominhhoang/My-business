# 01. Kiến thức kinh doanh nền tảng

Tài liệu dành cho người chưa từng kinh doanh, đang đi làm full-time và có 7–14 giờ mỗi tuần cho dự án riêng. Đọc hết mất khoảng 25 phút. Các con số trong ví dụ là số minh hoạ để hiểu cách tính; số liệu thị trường thật nằm ở `02-nghien-cuu-thi-truong.md`.

## 1. Kinh doanh là gì, nói gọn

Kinh doanh là **giải quyết lặp đi lặp lại một vấn đề cho một nhóm người cụ thể, với giá bán cao hơn chi phí bỏ ra**.

Mọi ý tưởng, dù là phần mềm, quán nước hay dịch vụ, đều phải trả lời được bốn câu:

1. **Ai** là khách hàng? Càng cụ thể càng tốt. "Chủ shop quần áo có 2–5 nhân viên, bán trên Shopee và Facebook" là câu trả lời dùng được; "doanh nghiệp nhỏ" thì chưa.
2. Họ có **vấn đề gì** đủ đau để chịu trả tiền? Dấu hiệu tin được nhất: hiện họ đang tốn tiền hoặc tốn thời gian để tự xử lý vấn đề đó.
3. Vì sao họ **mua của mình** mà không mua của người khác, hoặc tiếp tục không làm gì cả?
4. Mình **tiếp cận họ bằng cách nào**, với chi phí thấp hơn số tiền kiếm được từ họ?

Người làm kỹ thuật thường bắt đầu từ câu "mình làm được gì". Thứ tự đúng là ngược lại: tìm người có vấn đề trước, rồi mới làm lời giải nhỏ nhất cho họ.

## 2. Bốn loại rủi ro cần gỡ theo thứ tự

| Thứ tự | Rủi ro | Câu hỏi | Cách kiểm tra rẻ nhất |
|---|---|---|---|
| 1 | Nhu cầu | Có ai thật sự cần và chịu trả tiền không? | Phỏng vấn, bán trước |
| 2 | Kênh | Mình có tìm được khách với chi phí chấp nhận được không? | Thử một kênh với 10–20 khách đầu |
| 3 | Kinh tế đơn vị | Mỗi đơn hàng hoặc mỗi khách có lãi không? | Bảng tính trước khi bỏ vốn |
| 4 | Vận hành | Mình có làm nổi với 7–14 giờ/tuần không? | Tự phục vụ 5 khách đầu, đo giờ thật |

Phần lớn người mới làm ngược: lo vận hành trước (đăng ký, logo, website, nhập hàng, viết code) rồi mới phát hiện không ai mua. Rủi ro nhu cầu và rủi ro kênh là hai thứ giết dự án nhiều nhất, và cũng là hai thứ kiểm tra được gần như miễn phí.

## 3. Những con số phải hiểu

### 3.1. Từ doanh thu đến lợi nhuận

- **Doanh thu**: tổng tiền khách trả.
- **Giá vốn / chi phí biến đổi**: chi phí phát sinh theo từng đơn (tiền hàng, phí sàn, phí thanh toán, vận chuyển, đóng gói, quảng cáo cho đơn đó).
- **Lãi gộp trên mỗi đơn** = giá bán − chi phí biến đổi của đơn.
- **Chi phí cố định**: tiền phải trả dù bán được hay không (thuê bao phần mềm, server, mặt bằng, lương).
- **Lợi nhuận** = tổng lãi gộp − chi phí cố định − thuế.

Ví dụ minh hoạ, bán một sản phẩm trên sàn:

| Khoản | Số tiền |
|---|---|
| Giá bán | 200.000đ |
| Tiền hàng | −90.000đ |
| Phí sàn và thanh toán (giả sử 20%) | −40.000đ |
| Đóng gói, hao hụt, hoàn hàng | −10.000đ |
| Quảng cáo chia cho mỗi đơn | −20.000đ |
| **Lãi gộp mỗi đơn** | **40.000đ** |

Giá bán 200.000đ nhưng chỉ giữ lại 40.000đ. Người mới thường chỉ lấy giá bán trừ tiền hàng rồi tưởng lãi 110.000đ.

### 3.2. Điểm hoà vốn

Điểm hoà vốn = chi phí cố định ÷ lãi gộp mỗi đơn.

Với chi phí cố định 3 triệu/tháng và lãi gộp 40.000đ/đơn: cần 75 đơn/tháng chỉ để không lỗ. Muốn lãi 15 triệu/tháng thì cần (3.000.000 + 15.000.000) ÷ 40.000 = 450 đơn/tháng, tức 15 đơn mỗi ngày.

### 3.3. Dòng tiền khác lợi nhuận

Lợi nhuận là con số trên sổ. Dòng tiền là tiền thật trong tài khoản. Một shop có thể đang lãi mà vẫn hết tiền vì vốn nằm trong hàng tồn hoặc sàn chưa đối soát. Với vốn 20–100 triệu, mô hình thu tiền trước rồi mới làm (dịch vụ đặt cọc, thuê bao phần mềm, bán trước) an toàn hơn nhiều so với mô hình ứng tiền trước (nhập hàng, mặt bằng).

### 3.4. Chi phí có khách (CAC) và giá trị một khách (LTV)

- **CAC**: tổng chi phí bán hàng và marketing ÷ số khách mới có được.
- **LTV**: tổng lãi gộp thu được từ một khách trong suốt thời gian họ ở lại.

Ví dụ minh hoạ, phần mềm thuê bao 199.000đ/tháng, khách ở lại trung bình 10 tháng, biên lãi gộp 85%: LTV ≈ 1,7 triệu. Nếu tốn 500.000đ để có một khách thì LTV gấp 3,4 lần CAC và thu hồi chi phí sau khoảng 3 tháng. Mốc tham khảo hay dùng: LTV nên từ 3 lần CAC trở lên. Nếu LTV thấp hơn CAC thì càng bán càng lỗ.

### 3.5. Bài toán ngược từ mục tiêu

Mục tiêu của dự án này là 10–20 triệu lợi nhuận mỗi tháng. Lấy 15 triệu làm mốc, mỗi mô hình cần số khách rất khác nhau:

| Mô hình | Lãi mỗi khách hoặc mỗi đơn | Cần để đạt 15 triệu/tháng |
|---|---|---|
| Dịch vụ theo dự án | 5 triệu/dự án | 3 dự án mỗi tháng |
| Dịch vụ thuê bao (bảo trì, vận hành hộ) | 1,5 triệu/khách/tháng | 10 khách đang trả |
| Phần mềm thuê bao | 170.000đ/khách/tháng | khoảng 90 khách đang trả |
| Bán hàng trên sàn | 40.000đ/đơn | khoảng 375 đơn/tháng, chưa tính chi phí cố định |
| Sản phẩm số bán một lần | 250.000đ/lượt | 60 lượt mua mới mỗi tháng |

Bảng này cho thấy vì sao lựa chọn mô hình quan trọng hơn sự chăm chỉ: 3 khách dịch vụ có thể tìm qua quan hệ, còn 90 khách phần mềm hoặc 375 đơn hàng thì cần một kênh bán hàng chạy đều.

## 4. Kiểm chứng trước khi xây

Nguyên tắc: **bán trước, làm sau**. Mỗi bước dưới đây rẻ hơn bước kế tiếp; chỉ đi tiếp khi bước trước đạt.

### Bước 1. Phỏng vấn 10–15 người thuộc nhóm khách mục tiêu

Quy tắc phỏng vấn (theo sách *The Mom Test*):

- Hỏi về **việc họ đã làm trong quá khứ**, không hỏi ý kiến về ý tưởng của mình. "Lần gần nhất anh chị gặp chuyện này là khi nào, đã xử lý ra sao, tốn bao nhiêu?" cho thông tin thật. "Anh chị thấy ý tưởng này thế nào?" chỉ cho lời khen xã giao.
- Không mô tả sản phẩm cho đến cuối buổi.
- Lời khen và câu "khi nào làm xong báo anh nhé" không phải bằng chứng. Bằng chứng là: họ đang trả tiền cho giải pháp khác, họ tự làm một cách thủ công tốn công, hoặc họ chịu đặt cọc.

Đạt khi: ít nhất một phần ba số người tự kể ra vấn đề mà không cần gợi ý, và họ đang tốn tiền hoặc thời gian thật cho nó.

### Bước 2. Chào bán khi chưa có sản phẩm

Mô tả lời giải bằng một trang hoặc một tin nhắn, có giá cụ thể, rồi đề nghị đặt cọc hoặc đăng ký trả tiền. Đạt khi có 3–5 người trả tiền thật hoặc cam kết bằng văn bản. Nếu 20 người đúng đối tượng đều từ chối, đó là kết quả tốt: bạn vừa tiết kiệm được vài tháng.

### Bước 3. Phục vụ thủ công 3–5 khách đầu

Làm bằng tay, bằng công cụ có sẵn (bảng tính, n8n, script nhỏ), chưa cần sản phẩm hoàn chỉnh. Mục đích là học khách thật sự dùng gì, sẵn sàng trả bao nhiêu, và việc nào lặp lại đủ nhiều để đáng tự động hoá.

### Bước 4. Mới đến lúc xây sản phẩm nhỏ nhất

Chỉ xây phần đã được khách trả tiền ở bước 3. Mọi tính năng khác để sau.

## 5. Định giá

- Định giá theo **giá trị với khách**, không theo công sức của mình. Nếu công cụ tiết kiệm cho chủ shop 20 giờ mỗi tháng, giá 300.000đ/tháng là rẻ với họ dù bạn chỉ mất hai tuần để làm.
- Người mới gần như luôn định giá quá thấp. Giá thấp kéo theo khách khó tính nhất và không đủ tiền để tìm khách tiếp theo.
- Giá là thứ thử được: chào ba khách ba mức giá khác nhau là cách nhanh nhất để biết mức hợp lý.
- Với dịch vụ, bán theo **gói có phạm vi cố định và giá cố định** thay vì theo giờ. Gói cố định dễ bán qua chat, dễ lặp lại và không buộc thu nhập vào số giờ làm.

## 6. Tìm khách khi ngại bán hàng

Bạn đã chọn "chat/email được, ngại bán trực tiếp". Điều đó loại bớt một số mô hình nhưng không phải trở ngại lớn, miễn là chọn kênh phù hợp:

| Kênh | Hợp với người ngại bán? | Ghi chú |
|---|---|---|
| Quan hệ sẵn có (người thân, bạn bè làm chủ shop, quán) | Rất hợp | Nguồn 3–5 khách đầu nhanh nhất. Bạn có lợi thế này. |
| Cộng đồng nơi khách tụ tập (nhóm Facebook, Zalo của chủ shop) | Hợp | Trả lời câu hỏi, chia sẻ cách làm; khách tự nhắn. |
| Nội dung tìm kiếm được (bài hướng dẫn, video ngắn giải quyết một việc cụ thể) | Hợp | Chậm, nhưng tự chạy khi đã có. |
| Sàn và chợ ứng dụng | Hợp | Sàn mang khách đến, đổi lại là phí và cạnh tranh giá. |
| Giới thiệu từ khách cũ | Rất hợp | Chỉ có sau khi phục vụ tốt nhóm khách đầu. |
| Quảng cáo trả tiền | Trung tính | Chỉ dùng sau khi biết chắc LTV lớn hơn CAC. |
| Gọi điện, gặp trực tiếp khách lạ | Không hợp | Bỏ qua ở giai đoạn này. |

Chọn **một kênh** và làm cho tới khi nó hoạt động hoặc chứng minh là không hoạt động. Rải mỏng bốn kênh với 10 giờ mỗi tuần thì không kênh nào đủ sâu.

## 7. Vận hành khi vẫn đi làm

10 giờ mỗi tuần tương đương khoảng một tuần làm việc full-time mỗi tháng. Mọi kế hoạch phải nhân thời gian theo lịch lên gấp bốn so với ước tính "nếu làm toàn thời gian".

Nhịp tuần gợi ý:

| Khung giờ | Thời lượng | Việc |
|---|---|---|
| Hai buổi tối trong tuần | 2 giờ mỗi buổi | Việc cần tập trung: xây, viết, phân tích |
| Một buổi cuối tuần | 4 giờ | Nói chuyện với khách, giao hàng, tổng kết tuần |
| Mỗi ngày | 15 phút | Trả lời tin nhắn khách |

Nguyên tắc:

- Mỗi tuần chỉ có **một mục tiêu**, viết ra từ tối Chủ nhật.
- Ưu tiên việc tạo ra bằng chứng (nói chuyện với khách, chào bán) hơn việc tạo cảm giác tiến triển (logo, tên miền, kiến trúc hệ thống).
- Việc gì lặp lại lần thứ ba thì viết thành quy trình hoặc tự động hoá.
- Chọn mô hình không đòi hỗ trợ khách ngay trong giờ hành chính.

Ranh giới với công ty đang làm:

- Không dùng giờ làm, máy tính, tài khoản, mã nguồn hay dữ liệu của công ty.
- Không bán cho khách hàng của công ty và không làm sản phẩm cạnh tranh với công ty.
- Đọc lại hợp đồng lao động và nội quy về làm thêm, bảo mật, sở hữu trí tuệ trước khi bắt đầu. Chi tiết ở `03-phap-ly-thue.md`.

## 8. Quản trị rủi ro cá nhân

- **Vốn chịu mất**: chỉ dùng số tiền mà mất hết cũng không ảnh hưởng gia đình. Không vay để kinh doanh lần đầu.
- **Giải ngân theo đợt**: chia vốn thành các đợt nhỏ gắn với bằng chứng. Ví dụ đợt 1 tối đa 5 triệu cho kiểm chứng; chỉ mở đợt 2 khi có khách trả tiền.
- **Quỹ dự phòng tách riêng**: nên có 6 tháng chi tiêu gia đình không dính tới vốn kinh doanh, nhất là khi lo mất việc.
- **Tiêu chí dừng viết trước khi bắt đầu**: ví dụ "sau 8 tuần và 20 cuộc trò chuyện mà không ai đặt cọc thì đổi ý tưởng". Viết trước thì lúc đang tiếc công vẫn dừng được.
- **Chưa nghỉ việc** cho tới khi lợi nhuận từ dự án đều đặn nhiều tháng liền và có quỹ dự phòng. Giữ lương là lợi thế, vì nó cho phép thử sai mà không bị áp lực tiền.

## 9. Mười sai lầm phổ biến của người mới

1. Xây sản phẩm xong mới đi tìm khách.
2. Chọn ý tưởng vì thích công nghệ, không vì có người cần.
3. Hỏi ý kiến bạn bè và coi lời khen là bằng chứng.
4. Tính lãi bằng giá bán trừ tiền hàng, bỏ quên phí sàn, quảng cáo, hoàn hàng, thuế và thời gian của chính mình.
5. Nhập nhiều hàng hoặc ký thuê mặt bằng dài hạn trước khi có đơn đầu tiên.
6. Định giá thấp để dễ bán.
7. Làm nhiều ý tưởng cùng lúc.
8. Tin các khoá học và bài quảng cáo hứa thu nhập cao, nhanh, ít công.
9. Không ghi sổ thu chi từ ngày đầu, đến lúc kê khai thuế thì không có số.
10. Không có tiêu chí dừng, nên hoặc bỏ quá sớm hoặc theo đuổi quá lâu.

## 10. Thuật ngữ

| Thuật ngữ | Nghĩa |
|---|---|
| MVP | Phiên bản nhỏ nhất của sản phẩm đủ để khách trả tiền và mình học được điều cần học |
| Bán trước (pre-sell) | Nhận tiền hoặc đặt cọc trước khi sản phẩm hoàn thành |
| Kinh tế đơn vị (unit economics) | Lãi hay lỗ tính trên một đơn hàng hoặc một khách |
| CAC | Chi phí để có một khách mới |
| LTV | Tổng lãi gộp thu được từ một khách trong suốt thời gian họ ở lại |
| Churn | Tỷ lệ khách thuê bao rời đi mỗi tháng |
| Tỷ lệ chuyển đổi | Số người mua chia cho số người xem |
| Ngách (niche) | Nhóm khách hẹp, có chung một vấn đề cụ thể |
| Dịch vụ đóng gói (productized service) | Dịch vụ có phạm vi, giá, thời gian giao cố định, bán như một sản phẩm |
| Tiêu chí dừng (kill criteria) | Điều kiện định trước; chạm tới thì dừng hoặc đổi hướng |

## 11. Đọc thêm

Ba cuốn đủ cho giai đoạn đầu, theo thứ tự nên đọc:

1. *The Mom Test* (Rob Fitzpatrick): cách nói chuyện với khách để lấy được sự thật. Ngắn, đọc trong một buổi tối.
2. *The Lean Startup* (Eric Ries), bản dịch "Khởi nghiệp tinh gọn": vòng lặp xây, đo, học.
3. *The $100 Startup* (Chris Guillebeau), bản dịch "Khởi nghiệp với 100 đô": nhiều ví dụ kinh doanh nhỏ, vốn ít, một người làm.
