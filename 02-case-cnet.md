# Case 1 — CNET dùng AI viết bài tài chính (2022–2023)

> Ngành: Content creator (publisher có quy trình) · Loại: **lỗi có kiểm soát của tổ chức uy tín**

## Brief Case

| Field | Nội dung |
|---|---|
| **Tên case** | CNET AI-written finance articles |
| **Ngành** | Content creator / digital publishing |
| **Tổ chức / sản phẩm** | CNET (thuộc Red Ventures) — "internally designed AI engine" |
| **Use case AI** | Tự động viết bài explainer tài chính cá nhân (lãi kép, overdraft, CD…) |
| **Thời điểm** | Bắt đầu ~**tháng 11/2022**; bị phát hiện & xử lý **tháng 1/2023** |
| **Case xảy ra chuyện gì?** | CNET âm thầm đăng **77 bài** dưới byline "CNET Money" do AI viết. Sau khi bị soi, CNET phải **đính chính 41/77 bài (~53%)** vì sai dữ kiện tài chính; một số bài bị phát hiện **đạo văn** (lặp cấu trúc/câu từ một bài Forbes Advisor về overdraft fees). CNET **tạm dừng** tool. |
| **Stakeholder bị ảnh hưởng** | (1) Độc giả ra quyết định tiền bạc theo bài sai; (2) nhà báo/biên tập viên CNET (uy tín nghề); (3) thương hiệu CNET/Red Ventures; (4) tác giả gốc bị đạo văn (Forbes Advisor). |
| **Số liệu chính** | **77** bài AI · **41** bài phải đính chính (**~53%**) · khởi đầu từ 11/2022 · phanh phui 1/2023. |
| **Trích nguồn ngắn** | CNET "issued corrections on 41 of the 77 stories… written using an AI tool" (~53% correction rate); một số bài có ghi chú "We've replaced phrases that were not entirely original" (dấu hiệu đạo văn). |
| **Nguồn 1** | Futurism (Jon Christian) — **đơn vị phá vỡ tin** (primary investigation). |
| **Nguồn 2** | CNN Business (25/1/2023): cnn.com/2023/01/25/tech/cnet-ai-tool-news-stories · Engadget: engadget.com/cnet-corrected-41-of-its-77-ai-written-articles-201519489.html · Washington Post (17/1/2023). |
| **Ghi chú độ tin cậy** | High-quality secondary nhiều chiều (CNN, WaPo, Engadget) + nguồn gốc Futurism; **con số 41/77 do chính CNET thừa nhận**. Không conflict giữa các nguồn. |

## Harm Map Worksheet

### Dòng A — Độc giả tin bài tài chính sai (moment chính)
| Cột | Giá trị |
|---|---|
| **High-risk moment** | Độc giả đọc bài explainer tài chính (vd lãi kép / phí overdraft) do AI viết và **tin để ra quyết định tiền bạc**. |
| **Stakeholder bị ảnh hưởng** | Độc giả trực tiếp; biên tập viên/nhà báo CNET; thương hiệu CNET. |
| **Failure mode** | **Hallucination** (sai dữ kiện tài chính) + **Over-reliance** (biên tập tin tool, xuất bản như bài chuẩn). |
| **Layer bắt đầu lỗi** | **Grounding** (không ground vào nguồn tài chính chuẩn) + **UX** (đăng dưới byline trông như chuyên gia, nhãn AI mờ → reader over-trust). |
| **Harm xảy ra là gì?** | Độc giả nhận **kiến thức tài chính sai**, có thể ra quyết định tiền sai; uy tín CNET tổn hại. |
| **Harm lens** | Misinformation (+ reputation loss). |
| **Severity** | **High** — sai tài chính tác động quyết định tiền của người đọc. |
| **Scale** | **High** — CNET traffic lớn, bài phát tán qua SEO tới đại chúng. |
| **Probability** | **High** — **41/77 (~53%)** bài có lỗi → lỗi mang tính **hệ thống**, không ngẫu nhiên. |
| **Frequency** | **High** — sản xuất hàng loạt 77 bài; lỗi lặp đều. |
| **Vì sao?** | Hơn nửa số bài phải đính chính chứng tỏ đây là lỗi quy trình; kênh SEO khuếch đại tới số đông → harm-by-volume điển hình. |

### Dòng B — Đạo văn tác giả gốc (moment phụ)
| Cột | Giá trị |
|---|---|
| **High-risk moment** | Bài AI **lặp câu từ/cấu trúc** từ bài Forbes Advisor → đạo văn được xuất bản. |
| **Stakeholder** | Tác giả/đơn vị gốc bị đạo (Forbes Advisor); nhà báo CNET. |
| **Failure mode** | **Misuse** (đạo văn) + **Over-reliance** (quy trình kiểm đạo văn thất bại). |
| **Layer bắt đầu lỗi** | **Model** (tái tạo training data) + **Grounding/governance** (kiểm đạo văn không chạy đúng). |
| **Harm lens** | Dignity loss (tác giả gốc) + reputation. |
| **Severity** | Medium–High · **Scale** Medium · **Probability** Medium · **Frequency** Medium. |
| **Vì sao?** | CNET thừa nhận "replaced phrases that were not entirely original"; lỗi tầng quy trình con người dùng tool kiểm tra sai. |
