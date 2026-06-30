# Case 2 — Amazon ngập sách AI slop: mạo danh tác giả + guide nguy hiểm (2023)

> Ngành: Content creator (self-publishing marketplace) · Loại: **AI slop ẩn danh, phi tập trung, quy mô marketplace**

## Brief Case

| Field | Nội dung |
|---|---|
| **Tên case** | Amazon Kindle AI-generated book flood (mạo danh + foraging guides) |
| **Ngành** | Content creator / self-publishing (Amazon KDP — Kindle Direct Publishing) |
| **Tổ chức / sản phẩm** | Amazon Kindle Store; vô số seller ẩn danh dùng generative AI |
| **Use case AI** | Tự động sinh sách (ebook) hàng loạt để bán, gồm sách "how-to" và guide chuyên môn |
| **Thời điểm** | **Tháng 8–9/2023** (đỉnh điểm bị phanh phui) |
| **Case xảy ra chuyện gì?** | Hai mặt của cùng làn sóng slop: **(1) Mạo danh** — tác giả thật **Jane Friedman** phát hiện nhiều sách AI bán dưới **tên bà** (vd "Publishing Power…", "Promote to Prosper…") dù bà **không ra sách mới từ 2018**; sách giả còn bị gắn lên trang **Goodreads** chính thức. Amazon **ban đầu từ chối gỡ** (đòi "số đăng ký nhãn hiệu"), chỉ gỡ ~**nửa tá** sách sau khi bị phản ứng trên MXH. **(2) Nguy hiểm tính mạng** — hàng loạt **sách hái nấm/foraging do AI viết** tràn Amazon, định danh nấm sai; chuyên gia nấm học cảnh báo **"life or death"**, đã có người **nhập viện** sau khi tin AI định danh nhầm. Amazon phản ứng bằng cách **giới hạn 3 đầu sách tự xuất bản/ngày**. |
| **Stakeholder bị ảnh hưởng** | Độc giả mua nhầm/đọc sai; **tác giả thật bị mạo danh** (Friedman); **người tập hái nấm** (sức khỏe/tính mạng); cộng đồng nấm học; Amazon (platform & lòng tin). |
| **Số liệu chính** | Friedman: ra sách gần nhất **2018**, phát hiện sách giả 8/2023, Amazon gỡ ~**6** đầu sách sau backlash · Amazon giới hạn **3 sách/ngày/người** (9/2023) · cảnh báo "life or death" của New York Mycological Society · có ca **nhập viện** do nấm độc. |
| **Trích nguồn ngắn** | NY Mycological Society: "Please only buy books of known authors and foragers, it can literally mean **life or death**." Friedman: Amazon từ chối gỡ vì bà không cung cấp được "trademark registration". |
| **Nguồn 1** | The Daily Beast (8/2023): thedailybeast.com/author-jane-friedman-finds-ai-fakes-being-sold-under-her-name-on-amazon · Gizmodo: gizmodo.com/amazon-jane-friedman-ai-generated-books-removed-1850718989 |
| **Nguồn 2** | Fortune (3/9/2023, foraging "potentially deadly"): fortune.com/2023/09/03/ai-written-mushroom-hunting-guides-sold-on-amazon-potentially-deadly · Civil Eats (10/2023) · NPR (3/2024, "AI scam books"): npr.org/2024/03/16/1238983175 · Authors Guild scam alerts. |
| **Ghi chú độ tin cậy** | Đa nguồn high-quality secondary + cảnh báo từ tổ chức chuyên môn (NYMS) + lời chứng của chính nạn nhân (Friedman). Vụ foraging do **404 Media** phát hiện đầu tiên. Không conflict; số "3 sách/ngày" do Amazon công bố. |

## Harm Map Worksheet

### Dòng A — Mạo danh tác giả (slop "harm by volume")
| Cột | Giá trị |
|---|---|
| **High-risk moment** | Độc giả tìm sách "của Jane Friedman" trên Amazon/Goodreads và **mua sách AI mạo danh**. |
| **Stakeholder** | Độc giả (mua nhầm, mất tiền); **tác giả thật bị mạo danh** (uy tín nghề + doanh thu); Amazon. |
| **Failure mode** | **Misuse / synthetic media** (mạo danh) + **Hallucination** (nội dung rỗng/sai). |
| **Layer bắt đầu lỗi** | **UX/governance** (KDP không xác thực authorship, provenance kém) + **Safety system** (thiếu guardrail chống mạo danh; policy gỡ bài yếu — đòi trademark). |
| **Harm lens** | **Dignity loss** (tác giả) + Opportunity loss/Misinformation (độc giả mất tiền, tác giả mất uy tín & thu nhập). |
| **Severity** | **High** — đánh vào danh tính & sinh kế nghề nghiệp. |
| **Scale** | **High** — Amazon bị "flooded"; mạo danh áp dụng được cho mọi tác giả. |
| **Probability** | **Medium** — không phải mọi tác giả đều bị, nhưng dễ lặp lại. |
| **Frequency** | **High** — sản xuất rẻ & hàng loạt; còn lan sang Goodreads. |
| **Vì sao?** | Amazon **ban đầu từ chối gỡ** (lỗi tầng policy/governance), chỉ xử lý sau backlash → cho thấy thiếu cơ chế bảo vệ danh tính & rate-limit. |

### Dòng B — Guide hái nấm AI sai (spike **Critical / Injury**)
| Cột | Giá trị |
|---|---|
| **High-risk moment** | Người mới tập hái nấm mua **"foraging guide" AI** trên Amazon và **định danh nấm theo sách sai**. |
| **Stakeholder** | Người đọc/forager trực tiếp (sức khỏe, tính mạng); người thân; cộng đồng nấm học. |
| **Failure mode** | **Hallucination** + **Harmful advice** (vd khuyên định danh nấm bằng "ngửi/nếm"). |
| **Layer bắt đầu lỗi** | **Grounding** (không có chuyên gia/nguồn thực vật học) + **Safety system** (không guardrail cho domain nguy hiểm) + **UX** (trông như sách chuyên môn). |
| **Harm lens** | **Injury** (ngộ độc, đã có ca nhập viện). |
| **Severity** | **Critical** — nhầm nấm/cây độc (hemlock) có thể **tử vong**. |
| **Scale** | **Low–Medium** — số người hái nấm tương đối ít. |
| **Probability** | **Medium** — phụ thuộc người đọc có thực hành theo không. |
| **Frequency** | **Low–Medium** — ngách nhỏ nhưng sách tràn lan. |
| **Vì sao?** | 1 lần sai = "life or death" (NYMS); chính vì loại harm này mà Amazon phải **giới hạn 3 sách/ngày** — minh hoạ "spike Critical ở ngách" của ngành content creator. |
