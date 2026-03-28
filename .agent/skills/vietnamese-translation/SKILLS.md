# SKILL: Vietnamese Writing & Translation

## Purpose
Write or translate text into Vietnamese that reads as naturally written by an educated Vietnamese native speaker. The output must never feel like translated English. Every sentence must pass the native reader test: would a Vietnamese journalist, essayist, or analyst write this sentence?

---

## The Core Problem: English Mindset in Vietnamese Clothes

The most common failure is **writing English sentences using Vietnamese words**. This produces text that is grammatically parseable but unnatural — a Vietnamese reader immediately senses something is wrong without being able to pinpoint it.

This happens in three ways:

1. **Direct calques** — translating English compound nouns literally into Vietnamese compounds that don't exist
2. **Borrowed noun-stacking** — piling modifiers before a noun the way English does, which Vietnamese does not
3. **Register confusion** — mixing bureaucratic, academic, and journalistic tones within the same passage

All three must be eliminated.

---

## Rule 1: Never Coin a Vietnamese Compound Noun

English creates new concepts by stacking nouns: "machine brain," "data warehouse," "interface surface." Vietnamese **does not work this way**. Vietnamese builds new concepts through short descriptive clauses, not stacked nouns.

**The test:** If a compound noun does not appear in Vietnamese journalism, Wikipedia, or published books — do not use it.

**WRONG (invented calques):**
- "não bộ máy móc" (machine brain)
- "kho não bộ LLM" (LLM brain warehouse)
- "bề mặt giao diện" (interface surface)
- "sinh học định hướng" (directional biology)
- "nhân sự lai ghép" (hybrid personnel)
- "trực ban máy móc" (machine shift duty)

**RIGHT (natural Vietnamese):**
- "hệ thống AI" or simply "AI"
- "nơi lưu trữ dữ liệu của LLM"
- "giao diện" (alone — no extra modifier needed)
- "yếu tố sinh học"
- "đội ngũ kết hợp người và máy"
- "nhóm vận hành"

**Rule:** When you want to say [English compound noun], write it as a short Vietnamese clause instead: replace the stack with a verb.

---

## Rule 2: Do Not Stack More Than One Modifier Before a Noun

In English: "fast automated high-throughput data processing system"
In Vietnamese, this becomes unreadable. Vietnamese places modifiers **after** the noun, not before. One pre-noun modifier is acceptable. Two is the maximum. Three or more is always wrong.

**WRONG:**
- "các thuật toán truy cập nhanh tốc độ cao" (3 modifiers before noun)
- "mỏ kho dữ liệu báo cáo dạng văn bản sẵn" (4 modifiers stacked)
- "vận tốc xử lý siêu hạng" (invented superlative modifier)

**RIGHT:**
- "các thuật toán xử lý dữ liệu nhanh"
- "kho dữ liệu văn bản"
- "tốc độ xử lý cao"

**Rule:** Write `[noun] + [single short modifier]`. Move everything else into a relative clause or a separate sentence.

---

## Rule 3: Keep Technical Terms in Their Established Vietnamese Form

Some technical terms have accepted Vietnamese translations used in journalism and publishing. Others are always kept in English. Do not invent new translations.

**Terms kept in English (do not translate):**
- API, GUI, LLM, AI, CAPTCHA, MFA, RPA, URL, UI
- Product names: iPhone, Salesforce, GitHub, Copilot, Touch ID

**Terms with accepted Vietnamese translations (use these, not inventions):**
- Mouse → "con chuột" (not "chuột định vị")
- Keyboard → "bàn phím" (not "dãy bàn phím")
- Interface → "giao diện" (not "bề mặt giao diện")
- Password → "mật khẩu" (not "dãy mật khẩu văn bản")
- Authentication → "xác thực" (not "sát hạch")
- Bottleneck → "điểm nghẽn" (not "nút thắt cổ chai" in technical contexts)
- Human-in-the-loop → keep in English or "con người trong vòng lặp" — never "con người xen kẽ" or "trực phòng hệ thống"
- Workflow → "quy trình" (not "chuỗi thao tác vận hành")
- Legacy system → "hệ thống cũ" or "hệ thống kế thừa"

**Rule:** When uncertain, ask: "Does this Vietnamese phrase appear in Tuổi Trẻ, VnExpress, or a university textbook?" If no → revert to the English term.

---

## Rule 4: Match Register — Choose One and Hold It

Vietnamese has distinct registers. An essay mixes them at its peril.

| Register | Typical use | Markers |
|---|---|---|
| **Báo chí** (journalistic) | News, op-eds, popular essays | Short sentences, active verbs, plain connectors |
| **Hàn lâm** (academic) | Research papers, university texts | Longer sentences, passive constructions, formal connectors |
| **Hành chính** (bureaucratic) | Government documents, reports | Formal noun phrases, passive voice, set phrases |

**For essays and articles: use báo chí register throughout.**

Báo chí markers to use:
- Short sentences (15–25 words)
- Active verbs: "tạo ra," "buộc," "dẫn đến," "cho phép," "ngăn chặn"
- Plain connectors: "vì vậy," "do đó," "tuy nhiên," "nhưng," "từ đó"
- Subject-first sentences

Hành chính markers to **avoid** in essays:
- "phương án," "cơ chế," "triển khai," "đơn vị," "bộ phận" (unless literally correct)
- Passive constructions: "được thực hiện bởi," "đã được tiến hành"
- Invented compound nouns ending in "-hóa," "-tính," "-lực"

---

## Rule 5: Write in Vietnamese Sentence Rhythm, Not English

English rhythm: Subject → Verb → Object → Modifiers (rigid SVO)
Vietnamese rhythm: Topic → Comment, or Cause → Effect, with flexibility

Vietnamese naturally uses:
- **Topic-comment structure:** "Về vấn đề bảo mật, các hệ thống hiện đại đều yêu cầu xác thực sinh trắc học."
- **Cause-before-effect:** "Vì giao diện đồ họa không cung cấp API, AI buộc phải mô phỏng hành động của người dùng."
- **Implicit subject continuation:** once a subject is established, Vietnamese drops it in subsequent sentences — do not repeat it mechanically like English does

**WRONG (English rhythm imposed on Vietnamese):**
> "Các LLM xử lý văn bản thuần túy. Các LLM thiếu khả năng nhận thức thị giác tích hợp. Các LLM không thể vượt qua CAPTCHA."

Three sentences, subject repeated three times — English habit.

**RIGHT (Vietnamese rhythm):**
> "LLM chỉ xử lý văn bản thuần túy, không có khả năng nhận thức thị giác. Vì vậy, chúng không thể tự vượt qua CAPTCHA."

Subject stated once, continued implicitly, connector made explicit.

---

## Rule 6: Prefer Short Native Verbs Over Invented Noun Phrases

A common failure is converting verbs into long noun phrases — an English bureaucratic habit that sounds unnatural in Vietnamese prose.

**WRONG (noun phrase where a verb belongs):**
- "thực hiện quá trình xử lý" → just say "xử lý"
- "tiến hành việc phân tích" → just say "phân tích"
- "đưa ra quyết định" → just say "quyết định" (as verb)
- "có khả năng thực hiện" → just say "có thể"
- "tạo lập sự kết nối" → just say "kết nối"

**Rule:** If a sentence contains "thực hiện," "tiến hành," "đưa ra," or "có khả năng" followed by a noun, collapse it into the verb alone.

---

## Practical Rewrite Protocol

When writing or translating into Vietnamese, apply this sequence:

**Step 1: Write the idea in plain Vietnamese first**
Do not translate English. Ask: "How would a Vietnamese journalist say this in one sentence?" Write that sentence.

**Step 2: Check for calques**
Scan every noun phrase. Does each compound noun exist in published Vietnamese? If not, break it into a clause.

**Step 3: Check modifier stacking**
Count modifiers before each noun. More than one pre-noun modifier → move extras after the noun or into a new sentence.

**Step 4: Check technical terms**
Is each technical term in its established form? Revert inventions to English or the accepted Vietnamese form.

**Step 5: Check register consistency**
Are all sentences in the same register (báo chí for essays)? Remove bureaucratic noun phrases and passive constructions.

**Step 6: Check sentence rhythm**
Is the subject repeated unnecessarily across consecutive sentences? Drop the repeated subject. Is the connector explicit? Add it.

---

## Before/After: Full Sentence Examples

### Example 1: Calque removal

**WRONG:** "Kho não bộ LLM tiếp nhận dữ liệu siêu văn bản qua đường API máy."
(LLM brain warehouse receives hypertext data via machine API path)

**RIGHT:** "LLM nhận dữ liệu qua API."
(LLM receives data via API)

---

### Example 2: Modifier stack removal

**WRONG:** "Bộ não máy móc được phân tách này sau đó chuyên tâm xử lý các mỏ kho dữ liệu báo cáo dạng văn bản sẵn."

**RIGHT:** "AI khi đó tập trung hoàn toàn vào việc phân tích kho dữ liệu văn bản."

---

### Example 3: Register correction

**WRONG (hành chính):** "Phương án phân bổ đội ngũ này giao thẳng việc xử lý khung hình giao diện cho mắt thường người."

**RIGHT (báo chí):** "Mô hình này giao cho con người xử lý giao diện đồ họa — thứ mà AI không thể tự điều hướng."

---

### Example 4: Verb restoration

**WRONG:** "Thiết kế vận hành lai trên loại bỏ trực diện nghịch lý tương thích giao diện cũ."

**RIGHT:** "Mô hình kết hợp này giải quyết trực tiếp vấn đề tương thích với các hệ thống giao diện cũ."

---

### Example 5: Rhythm correction

**WRONG:** "Mô hình này tạo ra một ranh giới hoạt động rõ ràng. Mô hình này cho phép AI xử lý dữ liệu. Mô hình này đồng thời để con người xử lý giao diện."

**RIGHT:** "Mô hình này tạo ra ranh giới rõ ràng: AI xử lý dữ liệu, còn con người điều hướng giao diện."

---

## Self-Check Before Submission

Read the full Vietnamese text aloud (or mentally). Ask after each sentence:

1. **Calque test:** Does any noun phrase sound like translated English? → Break it into a clause.
2. **Stack test:** Are there 3+ modifiers before a noun? → Move extras after the noun.
3. **Term test:** Are all technical terms in established form? → Revert inventions.
4. **Register test:** Any bureaucratic noun phrases in an essay? → Replace with plain verb.
5. **Rhythm test:** Is any subject repeated three times in a row? → Drop it after first mention.
6. **Native speaker test:** Would a writer at Tuổi Trẻ or Tia Sáng publish this sentence unchanged? → If not, rewrite.

**Only submit when every sentence passes the native speaker test.**

---

## The One Overriding Principle

**Think in Vietnamese. Do not translate.**

Before writing any sentence, ask: "What is the simplest, most direct way a Vietnamese writer would express this idea?" Write that. Do not write the English version and convert it word by word.

If you cannot think of a natural Vietnamese expression → keep the technical term in English and build a plain Vietnamese sentence around it.
