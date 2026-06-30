# Pattern rủi ro của ngành Content Creator + Bảng so sánh giữa các ngành

> Người làm: Đỗ Việt Anh · 2A202601008 · Day 24 — Track 1

## A. Pattern rủi ro của ngành (rút từ 2 case)

Nhìn **CNET** (lỗi có kiểm soát của tổ chức uy tín) cạnh **Amazon AI slop** (rác ẩn danh, phi tập trung), nổi lên 4 pattern:

1. **Harm chủ đạo là "harm by volume", không phải "harm by severity".**
   Mỗi nội dung sai thường severity thấp–trung bình, nhưng **Scale × Frequency** cực lớn (CNET: 77 bài, 53% lỗi, phát tán SEO; Amazon: marketplace "flooded") → tổng thiệt hại nặng.

2. **Có spike Critical ở ngách high-stakes.**
   Khi slop lấn vào sức khỏe/tài chính, 1 ca lẻ cũng có thể **Injury/Critical** (foraging guide → ngộ độc, nhập viện).

3. **Layer hay bắt đầu lỗi: Grounding + UX.**
   Nội dung không ground vào nguồn thật (Grounding), **cộng** giao diện làm nó trông "chính thống/đáng tin" — byline chuyên gia (CNET), gắn tên tác giả thật (Amazon) — khiến user **over-trust** (UX). Đây là combo lặp ở cả 2 case.

4. **Failure mode hay lặp:** Hallucination · Misuse/synthetic media (mạo danh, đạo văn) · Over-reliance.

**Guardrail ngành cần nhất** (vì **không có gatekeeper tập trung**):
gắn **nhãn AI/provenance** · **xác thực authorship** · **fact-check & kiểm đạo văn** trước xuất bản · **rate-limit** sản xuất (Amazon đã làm: 3 sách/ngày) · cơ chế **khiếu nại/gỡ nhanh** & bảo vệ danh tính.

## B. Bảng so sánh risk profile giữa các ngành (số liệu thật từ 3 thành viên)
> Mỗi thành viên trình bày 1 ngành; bảng dưới tổng hợp **sau khi cả bàn trình bày**.

| Ngành | Người trình bày | Harm dễ gặp nhất | Failure mode hay lặp | Layer hay khởi lỗi | Risk profile | Đặc trưng |
|---|---|---|---|---|---|---|
| **Content creator** | Đỗ Việt Anh | Misinfo + Dignity loss (mạo danh); spike Injury ở ngách | Hallucination · Misuse/synthetic · Over-reliance | Grounding + UX | **Medium–High** | harm by **volume** |
| **Y tế / health assistant** | (thành viên) | **Injury** (tử vong) | Harmful advice · Escalation failure · Over-reliance | Safety · Grounding · Model | **Critical** | harm by **severity** |
| **Media / news / political** | Nguyễn Viết Du | Misinformation + Dignity loss | Misuse/jailbreak (deepfake) · Hallucination | Safety · Grounding (UX khuếch đại) | **High** | harm by **scale** |

**Case tiêu biểu mỗi ngành:**
- **Content creator:** CNET (đính chính 41/77 bài) · Amazon AI slop (mạo danh Jane Friedman + foraging guide "life or death" → giới hạn 3 sách/ngày)
- **Y tế:** NEDA *Tessa* (gỡ sau vài ngày vì khuyên giảm cân) · Epic Sepsis Model (bỏ sót **67%** ca thật, báo sai **88%**) · Babylon Health (sót nhồi máu cơ tim → phá sản 2023)
- **Media:** Deepfake robocall Biden (FCC phạt **$6M**) · Deepfake bầu cử Slovakia (**>130k** view trong **48h**) · CNET

## C. Tổng hợp — risk profile giữa các ngành

**3 pattern xuyên ngành:**
1. **Trục Severity ⟷ Scale chia ngành làm 2 nhóm:**
   - **Y tế = harm by severity** — Critical, Injury/tử vong, *hẹp & sâu* → bắt buộc human-in-the-loop, bar "được ship" cao nhất, dữ liệu PHI cực nhạy cảm.
   - **Content creator & Media = harm by volume/scale** — *rộng & nông*, severity/ca thấp hơn nhưng blast radius khổng lồ.
2. **Intent của lỗi khác nhau:**
   - Y tế: lỗi **vô ý** của hệ thống (harmful advice, escalation failure, model bỏ sót).
   - Media: lỗi **cố ý** của actor xấu (deepfake / Misuse-jailbreak).
   - Content creator: **pha trộn** — vô ý (CNET hallucination) + lạm dụng có chủ đích (Amazon mạo danh / slop kiếm tiền).
3. **Layer chung hay khởi lỗi: Grounding** (cả 3 ngành); **Safety** nổi bật ở Y tế & Media; **UX** đóng vai khuếch đại (Content/Media).

**Trả lời câu hỏi cả bàn:**
- Severity cao nhất → **Y tế** (Critical/tử vong).
- Scale / Frequency lớn nhất → **Content creator & Media** (slop + deepfake quy mô Internet/quốc gia).
- Cần human-in-the-loop & bar "được ship" cao nhất → **Y tế**.
- Dữ liệu nhạy cảm rõ nhất → **Y tế** (PHI).
- Yếu tố ngoài bản thân AI quyết định mức nguy: **thời điểm** (Media — sát bầu cử) · **tốc độ hậu quả** (Y tế — sepsis tử vong nhanh) · **quy mô phát tán** (Content — SEO/marketplace).

> **Quan sát:** **CNET xuất hiện ở cả 2 ngành** (Content creator của tôi & Media của Du) → ranh giới mờ giữa "publisher/content" và "media", và cả hai đều thuộc nhóm *harm by volume*. Giả thuyết ban đầu của tôi (volume vs severity) được **xác nhận** bằng số liệu 3 ngành.
