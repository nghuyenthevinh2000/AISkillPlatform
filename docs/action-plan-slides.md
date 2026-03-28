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

Tháng 3 năm 2026

---

## Mục Đích

Kế hoạch này chắt lọc từ phiên brainstorming `2026-03-26` và adversarial review `2026-03-28`. Mỗi hành động được ưu tiên theo thứ tự cần làm — không phải danh sách ước muốn, mà là chuỗi điều kiện tiên quyết.

---

<!-- _class: section-title -->

## 🗺 Tầm Nhìn

---

## Ý Tưởng Cốt Lõi

Các nhóm nhỏ người vận hành AI chia sẻ một `SKILLS.md` theo lĩnh vực, cung cấp đầu ra chất lượng chuyên gia qua peer review tích hợp. Khách hàng trả giá agency; AI là hạ tầng nội bộ. Hạ tầng internet được xây dựng lấy con người làm trung tâm (xác thực, phiên đăng nhập, CAPTCHA) sẽ mất nhiều thập kỷ để thiết kế lại cho AI — đây là cửa sổ lợi thế 3–7 năm mà nền tảng này khai thác.

---

## Lộ Trình 6 Giai Đoạn

| Giai đoạn | Thời gian | Mục tiêu |
|---|---|---|
| **Cổng 0** | Hiện tại ✅ | Đầu mối chính phủ đã sẵn sàng |
| **Giai đoạn 1** Concierge MVP | Tuần 1–6 | Bàn giao thực tế trên tài liệu chính phủ |
| **Giai đoạn 2** Xây SKILLS.md | Tuần 4–16 | ≥90% độ chính xác, 5× thông lượng |
| **Giai đoạn 3** Hợp Đồng Neo | Tuần 10–20 | Hợp đồng định kỳ với chính phủ |
| **Giai đoạn 4** Mở Rộng Chính Phủ | Tháng 5–9 | Thêm loại tài liệu, thêm phòng ban |
| **Giai đoạn 5** Thương Mại | Tháng 12–24 | Startup/SME |
| **Giai đoạn 6** Mở Rộng Quy Mô | Tháng 18+ | Thêm squad, thêm thị trường |

---

<!-- _class: section-title -->

## 🔴 P0 — Điểm Nghẽn
### Giải quyết trước khi bắt đầu bất cứ điều gì

---

## 🔴 P0-1 — Xác Minh Thẩm Quyền Ngân Sách

Đầu mối chính phủ đã ấm, nhưng lời hứa thiện chí không phải là năng lực mua sắm. Cổng 0 mới chỉ xác thực khả năng tiếp cận — chưa xác thực tiền.

> *"Anh/chị có dòng ngân sách cho thuê ngoài số hóa/dịch thuật không? Ai ký hợp đồng?"*

Nếu không có câu trả lời rõ ràng, Cổng 0 chưa thực sự được xác thực — cần tiếp cận song song.

---

## 🔴 P0-2 — Chọn Một Loại Tài Liệu

Số hóa và dịch thuật đòi hỏi SKILLS.md khác nhau, kỹ năng khác nhau, và QA khác nhau. Làm cả hai đồng thời sẽ không hoàn thành được cái nào.

> *"Loại tài liệu nào có tồn đọng cấp bách nhất hiện tại?"*

Chọn một loại duy nhất trước buổi họp squad đầu tiên. Mọi thứ khác phải chờ.

---

<!-- _class: section-title -->

## 🟠 P1 — Trước Concierge MVP
### Tuần 1–3

---

## 🟠 P1-1 + P1-2 — Tài Chính

Bản pitch chính phủ cần một con số cụ thể — "sẽ báo giá sau" không phải là pitch. Nghiên cứu giá thị trường tại Việt Nam và đặt giá thấp hơn thị trường với sàn đủ bù chi phí.

Bên cạnh đó, xây một bảng tính đơn giản: chi phí hàng tuần, quy mô hợp đồng hòa vốn, và số tháng duy trì được. Không biết runway, không thể quyết định hợp lý về nhịp độ hay pivot.

---

## 🟠 P1-3 — Hồ Sơ Tuyển Dụng Squad

"2–3 người" không phải tiêu chí tuyển dụng. Viết một đoạn văn gửi được cho ứng viên ngay tuần này — bao gồm công cụ AI cụ thể, năng lực ngôn ngữ (Việt + Anh), giờ làm việc, và mức độ chấp nhận công việc lặp lại trong quy trình có cấu trúc.

---

## 🟠 P1-4 + P1-5 — Chất Lượng & Đo Lường

Peer review không có tiêu chuẩn không bắt được lỗi gì. Xác định "đúng" có nghĩa là gì cho loại tài liệu đã chọn và viết thành một danh sách QA 1 trang bất kỳ thành viên squad nào cũng dùng được.

Song song đó, ghi lại ai đo độ chính xác, bằng cách nào, và bao lâu một lần — trước khi batch Concierge MVP đầu tiên bắt đầu. Mục tiêu "≥90%" vô nghĩa nếu không có công cụ đo.

---

## 🟠 P1-6 — Công Khai AI Với Chính Phủ

Chiến lược "lớp vỏ con người" hợp lý về kinh doanh, nhưng có thể cấu thành sai lệch thông tin theo quy định mua sắm công Việt Nam. Xác nhận với một đầu mối am hiểu pháp lý: hợp đồng chính phủ có yêu cầu công khai việc dùng AI không? Nếu có, cần biết cách trình bày mà không làm mất lợi thế định giá.

---

<!-- _class: section-title -->

## 🟡 P2 — Trước Hợp Đồng Neo
### Tuần 6–12

---

## 🟡 P2-1 — Logic Dự Phòng Theo Giai Đoạn

Kế hoạch hiện tại giả định kịch bản tốt nhất ở mọi giai đoạn. Mua sắm công Việt Nam có thể mất 12–18 tháng. Mỗi cổng giai đoạn cần thêm ba thông tin: thời hạn dự kiến, thời hạn tệ nhất, và điều kiện dừng rõ ràng — *"nếu trễ X tuần, chúng ta làm Y."*

---

## 🟡 P2-2 — Kế Hoạch Pivot AGI

Rủi ro tự động hóa hoàn toàn đã được nhận ra nhưng chưa được lên kế hoạch — một rủi ro hiện hữu không có phản ứng chỉ là điểm mù. Viết một tuyên bố dự phòng 3 câu: tín hiệu kích hoạt, hành động pivot cụ thể, và thời hạn hành động.

---

<!-- _class: section-title -->

## 🟢 P3 — Trước Ra Mắt Thương Mại
### Tháng 9–18

---

## 🟢 P3-1 + P3-2 — Phân Khúc Thương Mại

"Danh tiếng squad như tín hiệu mạng lưới" là hi vọng, không phải kênh phân phối. Xác định 1–2 kênh tiếp cận cụ thể (LinkedIn, nhóm startup Việt Nam, accelerator, cold email) trước khi Giai đoạn 5 bắt đầu.

Phân khúc startup/SME cũng chưa có bất kỳ khám phá nào — kinh nghiệm số hóa chính phủ không tự động chuyển đổi được. Thực hiện ít nhất 5 cuộc customer discovery với founder hoặc chủ SME về nỗi đau marketing nội dung của họ trước khi ra mắt.

---

<!-- _class: section-title -->

## 📋 Tóm Tắt

---

## Tất Cả Hành Động

| Mã | Hành động | Ưu tiên | Khi nào |
|---|---|---|---|
| P0-1 | Xác minh ngân sách & người ký hợp đồng | 🔴 P0 | Ngay bây giờ |
| P0-2 | Chọn một loại tài liệu duy nhất | 🔴 P0 | Ngay bây giờ |
| P1-1 | Xác định giá thị trường | 🟠 P1 | Tuần 1 |
| P1-2 | Mô hình tài chính & runway | 🟠 P1 | Tuần 1 |
| P1-3 | Hồ sơ tuyển dụng squad | 🟠 P1 | Tuần 1 |
| P1-4 | Danh sách QA / tiêu chí chất lượng | 🟠 P1 | Tuần 2 |
| P1-5 | Quy trình đo độ chính xác | 🟠 P1 | Tuần 2 |
| P1-6 | Xác nhận yêu cầu công khai AI | 🟠 P1 | Tuần 3 |
| P2-1 | Bổ sung điều kiện dừng từng giai đoạn | 🟡 P2 | Tuần 6 |
| P2-2 | Tuyên bố pivot AGI 3 câu | 🟡 P2 | Tuần 6 |
| P3-1 | Kênh tiếp cận thương mại | 🟢 P3 | Tháng 9 |
| P3-2 | 5 cuộc customer discovery (SME) | 🟢 P3 | Tháng 9 |

---

<!-- _class: section-title -->

## ⚡ Bắt Đầu Ngay

---

## Hai Câu Hỏi Đầu Tiên

Không có gì nên bắt đầu cho đến khi hai câu hỏi này được trả lời trực tiếp với đầu mối chính phủ:

> *"Anh/chị có dòng ngân sách cho thuê ngoài không? Ai ký hợp đồng?"*

> *"Loại tài liệu nào — số hóa hay dịch thuật — có tồn đọng cấp bách nhất?"*

Một câu trả lời rõ ràng cho mỗi câu hỏi là điều kiện tiên quyết của toàn bộ kế hoạch.

---

<!-- _class: cover -->

## Nguồn

- `_bmad-output/brainstorming/brainstorming-session-2026-03-26-162717.md`
- `_bmad-output/action-items-adversarial-review.md`

*Hiển thị bằng [Marp](https://marp.app)*
