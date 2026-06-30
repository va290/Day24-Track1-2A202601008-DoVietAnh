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

## B. Bảng so sánh risk profile giữa các ngành (template — điền trên lớp)
> Bảng này **chỉ có số liệu sau khi từng thành viên trình bày case của họ**. Tôi chỉ điền sẵn **dòng của mình** (Content creator); các dòng khác để trống, cả bàn cùng điền & chốt trực tiếp.

| Ngành | Harm dễ gặp nhất | Failure mode hay lặp | Layer hay bắt đầu lỗi | Risk profile tổng thể | Vì sao? |
|---|---|---|---|---|---|
| **Content creator** *(của tôi)* | Misinformation + Dignity loss (mạo danh); spike Injury ở ngách | Hallucination · Misuse/synthetic · Over-reliance | **Grounding + UX** | **Medium–High** (harm by volume) | Severity/ca thấp nhưng Scale×Frequency khổng lồ; không có gatekeeper |
| HR / tuyển dụng | — điền trên lớp — | — | — | — | — |
| Giáo dục / AI tutor | — điền trên lớp — | — | — | — | — |
| Y tế / health assistant | — điền trên lớp — | — | — | — | — |
| Mobility / autonomous | — điền trên lớp — | — | — | — | — |
| Media / political · … | — điền trên lớp — | — | — | — | — |

## C. Câu hỏi để cả bàn chốt (sau khi mọi người trình bày)
- Ngành nào **Severity** cao nhất?
- Ngành nào **Scale / Frequency** lớn nhất?
- Ngành nào cần **human-in-the-loop** rõ nhất?
- Ngành nào cần **bar "được ship"** cao nhất?

> **Giả thuyết của tôi (để kiểm chứng khi so sánh):** Content creator/Media nghiêng *harm by volume* (rộng & nông, đôi khi spike Critical); Y tế/Mobility nghiêng *harm by severity* (hẹp & sâu). Cần số liệu của các bạn để xác nhận.
