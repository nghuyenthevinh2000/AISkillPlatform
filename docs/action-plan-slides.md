---
marp: true
theme: default
paginate: true
style: |
  section {
    font-family: 'Segoe UI', sans-serif;
    background: #ffffff;
    color: #1a1a2e;
  }
  section.cover {
    background: #1a1a2e;
    color: #ffffff;
    text-align: center;
  }
  section.cover h1 { font-size: 2.4rem; margin-bottom: 0.2em; }
  section.cover p { font-size: 1rem; color: #aaaacc; }
  section.section-title {
    background: #16213e;
    color: #ffffff;
    text-align: center;
    justify-content: center;
  }
  section.section-title h2 { font-size: 2rem; }
  h2 { border-bottom: 3px solid #e94560; padding-bottom: 0.3em; }
  table { width: 100%; font-size: 0.8rem; }
  th { background: #1a1a2e; color: #ffffff; }
  tr:nth-child(even) { background: #f0f0f0; }
  .blocker { color: #c0392b; font-weight: bold; }
  .p1 { color: #e67e22; font-weight: bold; }
  .p2 { color: #f1c40f; font-weight: bold; }
  .p3 { color: #27ae60; font-weight: bold; }
---

<!-- _class: cover -->

# Nền Tảng AI Execution Squad
## Kế Hoạch Hành Động

**Dựa trên kết quả BMAD Brainstorming + Adversarial Review**
Tháng 3 năm 2026

---

## Bộ slide này là gì

Kế hoạch hành động này được rút ra từ hai kết quả BMAD:

1. **Phiên brainstorming** `2026-03-26` — Kế hoạch thực thi Lean Startup bao gồm khám phá vấn đề, xác thực sản phẩm, PMF và mở rộng quy mô
2. **Phiên adversarial review** `2026-03-28` — Kiểm tra phản biện toàn diện kế hoạch thực thi, làm rõ các điểm nghẽn và giả định rủi ro cao

> **Mục tiêu:** Chuyển hóa các kết quả đó thành một chuỗi hành động được ưu tiên — để không có việc quan trọng nào bị bỏ sót giữa lúc lập kế hoạch và thực thi.

---

<!-- _class: section-title -->

## 🗺 Tầm Nhìn Nền Tảng

---

## Ý Tưởng Cốt Lõi

**AI Execution Squads** — các nhóm nhỏ gồm những người vận hành AI chia sẻ tệp `SKILLS.md` theo lĩnh vực, cung cấp đầu ra chất lượng chuyên gia thông qua quy trình peer review tích hợp sẵn.

| Tầng | Chức năng |
|---|---|
| **SKILLS.md** | Mã hóa lý luận chỉ đạo AI của chuyên gia, giúp kỹ thuật tồn tại lâu hơn bất kỳ phiên làm việc nào |
| **Mô hình Squad** | Peer review đảm bảo chất lượng mà không một người vận hành đơn lẻ nào có thể đảm bảo được |
| **Lớp vỏ con người** | Khách hàng trả giá agency cho sản phẩm có người đứng sau; AI là hạ tầng nội bộ |
| **Bánh đà lặp lại** | SKILLS.md được dùng trên 500 tác vụ thực tế tốt hơn về bản chất so với dùng trên 5 tác vụ |

**Cửa sổ cơ hội:** Hạ tầng internet lấy con người làm trung tâm (xác thực, crawling, phiên làm việc) mất nhiều thập kỷ để thiết kế lại cho AI — lợi thế cấu trúc kéo dài 3–7 năm.

---

## Lộ Trình Thực Thi 6 Giai Đoạn

| Giai đoạn | Thời gian | Mục tiêu |
|---|---|---|
| **Cổng 0** | Trước khi ra mắt ✅ | Đầu mối chính phủ đã sẵn sàng — bỏ qua tiếp cận lạnh |
| **Giai đoạn 1** Concierge MVP | Tuần 1–6 | Xác thực khả năng bàn giao của squad trên tài liệu chính phủ thực tế |
| **Giai đoạn 2** Xây SKILLS.md | Tuần 4–16 | Đạt ≥90% độ chính xác, thông lượng cao hơn 5× so với thủ công |
| **Giai đoạn 3** Hợp đồng neo | Tuần 10–20 | Ký hợp đồng định kỳ hoặc độc quyền với chính phủ |
| **Giai đoạn 4** Mở rộng trong Chính phủ | Tháng 5–9 | Thêm loại tài liệu mới, thêm phòng ban |
| **Giai đoạn 5** Thương mại | Tháng 12–24 | Marketing nội dung cho startup/SME |
| **Giai đoạn 6** Mở rộng quy mô | Tháng 18+ | Thêm squad mới, địa lý mới, marketplace nền tảng |

> **Điểm tấn công:** Số hóa và dịch tài liệu chính phủ — kiểm tra chất lượng nhị phân, tồn đọng khổng lồ, không yêu cầu sáng tạo.

---

<!-- _class: section-title -->

## 🔴 P0 — Điểm Nghẽn
### Phải giải quyết trước khi bắt đầu bất cứ điều gì

---

## 🔴 P0-1 — Xác Minh Thẩm Quyền Ngân Sách

**Rủi ro:** Một lời hứa thiện chí ≠ năng lực mua sắm. Cổng 0 đã được xác thực về khả năng tiếp cận, chưa xác thực về tiền.

**Hành động:**
Trong buổi họp tiếp theo, hỏi thẳng:

> *"Anh/chị có dòng ngân sách dành cho việc thuê ngoài số hóa/dịch thuật không, hay điều này cần một quy trình phê duyệt mới? Ai là người ký hợp đồng?"*

**Tín hiệu thành công:**
Đầu mối nêu ra được một ngân sách, một phòng ban, hoặc một cán bộ mua sắm mà bạn có thể liên hệ.

**Nếu bị chặn:**
Tìm người ra quyết định mua sắm thực sự thông qua đầu mối đó — hoặc coi Cổng 0 là chưa xác thực và song song tiến hành tiếp cận lạnh.

---

## 🔴 P0-2 — Chọn Một Loại Tài Liệu

**Rủi ro:** Tài liệu giấy sang số và dịch thuật đòi hỏi SKILLS.md khác nhau, kỹ năng khác nhau, QA khác nhau — làm cả hai cùng lúc sẽ phân tán tất cả.

**Hành động:**
Hỏi đầu mối:

> *"Loại tài liệu nào có tồn đọng lớn nhất hoặc nhu cầu cấp bách nhất hiện tại?"*

Chọn loại đó. Bắt đầu **chỉ** ở đó.

**Tín hiệu thành công:**
Bạn đã chọn được một loại tài liệu cụ thể **trước** buổi họp squad đầu tiên — ví dụ: *"mẫu viết tay sang văn bản số"* hoặc *"tài liệu chính sách tiếng Việt sang tiếng Anh."*

---

<!-- _class: section-title -->

## 🟠 P1 — Trước Khi Ra Mắt Concierge MVP
### Tuần 1–3

---

## 🟠 P1-1 — Xác Định Giá

**Rủi ro:** Bản pitch 1 trang bạn mang đến cuộc họp chính phủ cần có con số cụ thể. "Chúng tôi sẽ báo giá sau" không phải là một pitch.

**Hành động:**
Nghiên cứu giá thị trường hiện tại — các nhà cung cấp số hóa/dịch thuật tính phí bao nhiêu mỗi trang, mỗi tài liệu, hoặc mỗi giờ tại Việt Nam?

Đặt giá của bạn thấp hơn thị trường một tỷ lệ % để thắng, với sàn đủ bù chi phí.

**Đầu ra:**
Một bảng giá đơn giản — ví dụ: chi phí mỗi trang cho số hóa, chi phí mỗi từ cho dịch thuật.

---

## 🟠 P1-2 — Xây Dựng Mô Hình Tài Chính

**Rủi ro:** Không biết thời gian duy trì được, bạn không thể đưa ra quyết định hợp lý về tốc độ hoặc thời điểm pivot.

**Hành động:**
Xây dựng bảng tính với ba cột:

| Cột | Câu hỏi cần trả lời |
|---|---|
| Chi phí hàng tuần (thời gian + API + công cụ) | Mỗi tuần tốn bao nhiêu? |
| Quy mô hợp đồng hòa vốn | Hợp đồng đầu tiên phải lớn bao nhiêu? |
| Số tháng duy trì được | Duy trì được bao lâu trước khi cần doanh thu? |

**Tín hiệu thành công:**
Bạn có thể trả lời *"tôi duy trì được bao lâu trước khi cần doanh thu?"* mà không do dự.

---

## 🟠 P1-3 — Viết Hồ Sơ Tuyển Dụng Squad

**Rủi ro:** "2–3 người" không phải là tiêu chí tuyển dụng. Tiêu chí mơ hồ tạo ra squad mơ hồ.

**Hành động:**
Xác định các tiêu chuẩn tối thiểu:
- Thành thạo công cụ AI — cụ thể là công cụ nào?
- Năng lực ngôn ngữ — tiếng Việt + tiếng Anh?
- Thời gian rảnh — số giờ/tuần?
- Sẵn sàng làm công việc lặp lại trong một quy trình có cấu trúc

**Đầu ra:**
Một đoạn văn mô tả bạn có thể gửi cho ứng viên ngay tuần này.

---

## 🟠 P1-4 — Tạo Tiêu Chí Chất Lượng

**Rủi ro:** Peer review không có tiêu chuẩn không bắt được lỗi gì. "Có người kiểm tra rồi" không phải là đảm bảo chất lượng.

**Hành động:**
Xác định thế nào là *"đúng"* đối với loại tài liệu bạn chọn.

Ví dụ cho số hóa:
- Tỷ lệ chính xác ký tự %
- Khớp định dạng với bản gốc
- Xử lý văn bản không đọc được (đánh dấu? thay thế? để trống?)

**Đầu ra:**
Danh sách kiểm tra QA 1 trang mà bất kỳ thành viên squad nào cũng có thể sử dụng mà không cần giải thích thêm.

---

## 🟠 P1-5 — Xác Định Phương Pháp Đo Độ Chính Xác

**Rủi ro:** "Độ chính xác ≥90%" là mục tiêu vô nghĩa nếu không có công cụ đo lường.

**Hành động:**
Quyết định cách đo độ chính xác:
- Kiểm tra mẫu bởi người đánh giá so với bản gốc?
- Công cụ so sánh ký tự?
- Số lần khách hàng từ chối?

Ghi lại: **ai** đo, **như thế nào**, và **bao lâu một lần**.

**Đầu ra:**
Một quy trình đo lường được ghi lại (dù chỉ 1 đoạn) trước khi batch Concierge MVP bắt đầu.

---

## 🟠 P1-6 — Kiểm Tra Yêu Cầu Công Khai AI

**Rủi ro:** Chiến lược "lớp vỏ con người" thông minh về mặt chiến lược nhưng có thể cấu thành sai lệch thông tin theo quy định mua sắm công của chính phủ Việt Nam.

**Hành động:**
Nghiên cứu (hoặc hỏi một đầu mối am hiểu pháp lý) liệu hợp đồng mua sắm công tại Việt Nam có **yêu cầu công khai việc sử dụng công cụ AI** trong cung cấp dịch vụ hay không.

**Tín hiệu thành công:**
Bạn biết:
1. Liệu bạn có phải công khai sự tham gia của AI không
2. Nếu có — cách trình bày mà không làm giảm giá trị định giá của bạn

---

<!-- _class: section-title -->

## 🟡 P2 — Trước Khi Chào Hàng Hợp Đồng Neo
### Tuần 6–12

---

## 🟡 P2-1 — Bổ Sung Logic Dự Phòng

**Rủi ro:** Kế hoạch thực thi giả định kịch bản tốt nhất ở mọi giai đoạn. Mua sắm công tại Việt Nam có thể mất **12–18 tháng**.

**Hành động:**
Với mỗi cổng giai đoạn, bổ sung ba cột:

| Cột | Nội dung |
|---|---|
| Thời hạn dự kiến | Thời gian trong kịch bản tốt nhất |
| Thời hạn tệ nhất | Trần trễ hạn thực tế |
| Điều kiện dừng | "Nếu trễ X tuần, chúng ta làm Y" |

**Đầu ra:**
Kế hoạch cập nhật với quy tắc quyết định rõ ràng ở mỗi giai đoạn — khi nào chờ, khi nào pivot.

---

## 🟡 P2-2 — Xây Dựng Kế Hoạch Pivot Dự Phòng AGI

**Rủi ro:** Rủi ro "Tuyệt Chủng Tự Trị" đã được nhận ra nhưng chưa được lên kế hoạch. Rủi ro hiện hữu chưa có kế hoạch chỉ là điểm mù.

**Hành động:**
Xác định tín hiệu sẽ kích hoạt một pivot — ví dụ:

> *"Nếu một nền tảng AI agent lớn loại bỏ con người trong quy trình xử lý tài liệu, chúng tôi sẽ [hành động pivot] trong vòng [thời hạn]."*

**Đầu ra:**
Một tuyên bố dự phòng gồm 3 câu:
1. **Tín hiệu:** *Nếu [sự kiện quan sát được]…*
2. **Hành động:** *…chúng tôi sẽ [pivot cụ thể]…*
3. **Thời hạn:** *…trong vòng [X tuần/tháng].*

---

<!-- _class: section-title -->

## 🟢 P3 — Trước Khi Ra Mắt Thương Mại
### Tháng 9–18

---

## 🟢 P3-1 — Xác Định Kênh Thu Hút Khách Hàng

**Rủi ro:** *"Danh tiếng squad như tín hiệu mạng lưới"* không phải là một kênh. Đó là một hi vọng không có cơ chế.

**Hành động:**
Xác định 1–2 kênh cụ thể để tiếp cận startup/SME cần marketing nội dung — ví dụ:
- Chuỗi tiếp cận LinkedIn
- Nhóm Slack/Facebook của startup Việt Nam
- Hợp tác với các accelerator cụ thể
- Chuỗi email lạnh

Xác định kênh **trước khi Giai đoạn 5 bắt đầu**, không phải trong khi đó.

**Đầu ra:**
Một kênh phân phối được đặt tên kèm một chiến thuật tiếp cận có thể kiểm tra được.

---

## 🟢 P3-2 — Thực Hiện Customer Discovery cho Phân Khúc Thương Mại

**Rủi ro:** Marketing nội dung cho startup/SME đã bị hoãn mà **không có khám phá nào** được thực hiện với phân khúc đó. Kinh nghiệm số hóa chính phủ không tự động chuyển đổi được.

**Hành động:**
Trước khi Giai đoạn 5 ra mắt, thực hiện **ít nhất 5 cuộc trò chuyện customer discovery** với người sáng lập startup hoặc chủ SME về nỗi đau marketing nội dung của họ.

Hỏi:
- Nỗi đau thực sự là gì?
- Họ hiện tại đang trả bao nhiêu?
- Điều gì sẽ khiến họ chuyển sang?

**Đầu ra:**
Tóm tắt ngắn gọn về 5 cuộc trò chuyện.

---

<!-- _class: section-title -->

## 📋 Tóm Tắt Ưu Tiên

---

## Tổng Quan Tất Cả Hành Động

| Mã | Hành động | Ưu tiên | Thời điểm |
|---|---|---|---|
| P0-1 | Xác minh đầu mối chính phủ có thẩm quyền ngân sách | 🔴 P0 | Trước tất cả |
| P0-2 | Chọn chỉ một loại tài liệu | 🔴 P0 | Trước tất cả |
| P1-1 | Xác định giá | 🟠 P1 | Trước Concierge MVP |
| P1-2 | Xây dựng mô hình tài chính / thời gian duy trì | 🟠 P1 | Trước Concierge MVP |
| P1-3 | Viết hồ sơ tuyển dụng squad | 🟠 P1 | Trước Concierge MVP |
| P1-4 | Tạo danh sách QA / tiêu chí chất lượng | 🟠 P1 | Trước Concierge MVP |
| P1-5 | Xác định phương pháp đo độ chính xác | 🟠 P1 | Trước Concierge MVP |
| P1-6 | Kiểm tra yêu cầu pháp lý công khai AI | 🟠 P1 | Trước Concierge MVP |
| P2-1 | Bổ sung logic dự phòng / vùng đệm thời gian | 🟡 P2 | Trước khi chào hàng hợp đồng neo |
| P2-2 | Xây dựng kế hoạch pivot dự phòng AGI | 🟡 P2 | Trước khi chào hàng hợp đồng neo |
| P3-1 | Xác định kênh thu hút khách hàng thương mại | 🟢 P3 | Trước Giai đoạn 5 |
| P3-2 | Thực hiện 5 cuộc customer discovery (thương mại) | 🟢 P3 | Trước Giai đoạn 5 |

---

<!-- _class: section-title -->

## ⚡ Bắt Đầu Ngay

---

## Hai Hành Động Đầu Tiên Của Bạn

Không có gì nên bắt đầu cho đến khi hai câu hỏi này được trả lời.

### Tuần này — P0-1

**Hỏi đầu mối chính phủ của bạn:**
> *"Anh/chị có dòng ngân sách cho việc thuê ngoài không, hay điều này cần phê duyệt mới? Ai là người ký hợp đồng?"*

---

### Tuần này — P0-2

**Hỏi đầu mối chính phủ của bạn:**
> *"Loại tài liệu nào — số hóa hay dịch thuật — có tồn đọng cấp bách nhất hiện tại?"*

---

Chọn một. Bắt đầu ở đó. Mọi thứ còn lại sẽ theo sau.

---

<!-- _class: cover -->

## Nguồn tài liệu

- `_bmad-output/brainstorming/brainstorming-session-2026-03-26-162717.md`
- `_bmad-output/action-items-adversarial-review.md`

*Hiển thị bằng [Marp](https://marp.app)*
