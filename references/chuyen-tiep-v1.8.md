# Đối chiếu và chuyển tiếp Auto365 Writer sang V1.8

## Nguồn và phạm vi cập nhật

Nguồn chính: [quy chuẩn V1.8 nguyên văn](Auto365_Quy_chuan_SEO_GEO_HTML_V1_8_2026-10-06.md), hiệu lực 06/10/2026. SHA-256 của file: `a91f818508cd868f52b593ef5b4d243c3eb3e7cad052318da9d6b389aac80c7f`.

[grading_spec.json](grading_spec.json) giữ nguyên byte, content_standard_version 1.7, làm **nguồn kế thừa V1.7** theo mục 19.6 V1.8. SHA-256: `3128412fe6f2ac4e77be686bb51d58efa819d1c611d3a22940ca52a359339323`. Không đổi version hoặc gọi file này là cấu hình JSON V1.8. ID, trọng số, dải chấm và yêu cầu cũ chỉ kế thừa khi phù hợp; số mục cũ là số mục lịch sử.

Baseline repo để đối chiếu: commit `6deed9bf357b7e2fed7eba506ac76bf70b2a5c0a`, sáu file: SKILL.md, agents/openai.yaml, assets/ban-giao.md, assets/phieu-brief.md, assets/icon.svg và references/grading_spec.json. Không có README, AGENTS.md, mã chấm thực thi hoặc mã CMS ở baseline này. Cập nhật hướng dẫn Writer và mẫu, bổ sung quy chuẩn/đối chiếu; không thay icon hoặc JSON kế thừa. Không tuyên bố đã nâng cấp CMS, bộ chấm bên ngoài hoặc skill đang cài trong ChatGPT Work.

## Thay đổi so với bộ skill V1.7 kế thừa

| Phần | Baseline V1.7 kế thừa | Áp dụng V1.8 | Mục V1.8 |
| --- | --- | --- | --- |
| Nguồn chính | JSON làm nguồn quy chuẩn chính | Markdown V1.8 ưu tiên, JSON là nguồn kế thừa nguyên bản | 19.6 |
| Vai trò | Writer viết/sửa/tự kiểm/bàn giao | Giữ vai trò; không chuyển thành bot chỉ chấm | 13, 17, 18 |
| Loại trang | Sáu nhóm trong SKILL | Đủ tám, bổ sung landing page/HTML Ads và tin tức/hoạt động/thương hiệu; làm rõ dịch vụ/trụ cột/danh mục | 3 |
| Khóa dữ kiện | Bảng năm cột, phân biệt nguồn cơ bản | Bảng tám trường; thêm phạm vi/phiên bản/người xác nhận/quyền dùng; nguồn hãng, năng lực cơ sở, ca thật khác nhau | 5 |
| N1–N5 | Chưa có bảng áp dụng chính thức trong mẫu Writer | Chính thức đối chiếu vào tiêu chí hiện có, không tiêu chí mới hoặc phạt cố định | 4, 19.7 |
| Ngành hàng | Hướng dẫn tuyến cơ bản | Chi tiết điều kiện đo ánh sáng; Parking Mode/nguồn; định nghĩa phim; vật liệu/độ dày/điều kiện PPF; cơ sở đúng điểm, không hard-code ví dụ | 7 |
| Điểm | 12 tiêu chí, 100; nhóm C30/S30/G25/U15 | Giữ nguyên; tổng ≥95, S ≥28,5, G ≥23,75, so trước làm tròn | 11 |
| CX và thứ tự quyết định | pseudo_code/fail_conditions có nhánh điểm xác minh dưới ngưỡng trước CX, có thể bị đọc thành FAIL từ tổng chưa chốt | Báo điểm xác nhận và khoảng; chỉ FAIL do blocker nội dung xác nhận hoặc cận trên chứng minh ít nhất một ngưỡng không thể đạt; CX còn có thể đổi kết luận thì chưa đủ bằng chứng | 11.3, 13.3 |
| HTML và liên kết | Hướng dẫn SEO/CMS chung | Chỉ HTML khi được yêu cầu; bảng ngữ nghĩa/render/anchor; 301 hợp lệ và thiếu caption không tự blocker; ghi đích/canonical/ngày kiểm | 9, 19.4 |
| Ngày và môi trường | Không đổi ngày tạo cảm giác mới | datePublished gốc, dateModified khi sửa thật, ngày kiểm/giá/crawl/T0 riêng; staging khác production | 9, 13, 16, 18 |
| Thực thể/schema | Phù hợp loại trang, không review giả | Publisher/provider/brand/SKU/xe đúng quan hệ, registry/@id; nhiều script đúng quan hệ không tự blocker | 10, 19.4 |
| Live | Mẫu dùng Đạt/Cần sửa/CX/Không áp dụng | L1–L8 dùng Pass/Fail/CX/NA, trạng thái con và bằng chứng; thiếu công cụ/quyền là CX; ba kết luận live độc lập | 14 |
| Crawler/Local | Theo dõi trong phạm vi kiểm | OAI-SearchBot/GPTBot/ChatGPT-User riêng, WAF/bot xác minh; GBP/NAP đúng cơ sở, không hệ số Gemini | 15 |
| Hiệu quả AI | Đọc/hiểu/trích/đề xuất chưa đủ năm trường trong mẫu | Found, Understood, Cited, Mentioned, Recommended độc lập; nhật ký nguyên văn, nền tảng/điều kiện và URL thật; không chuỗi bắt buộc/điểm Content | 16 |
| Bàn giao/U3 | Ba phần mang tên phiên bản kế thừa, tên file 01 có “hoan_chinh” | Tên ba file V1.8 theo mục 18, HTML có điều kiện; U3 đối chiếu cùng bản thực, không dùng phiếu cũ | 18 |
| Lịch sử | Giữ phiên bản giữa vòng viết/chấm | Điểm đã duyệt V1.7 giữ lịch sử; sửa/rà soát được giao thì lưu baseline và đánh giá V1.8 phạm vi hiện hành | 19 |

Các bảng này là hướng dẫn chuyển tiếp, không sửa nguyên văn quy chuẩn hoặc tạo luật/điểm mới. Bài V1.7 lịch sử không bị tự đổi nhãn hay tự hạ điểm.

## Quy tắc ưu tiên đối với logic kế thừa

V1.8 thắng mọi hướng dẫn cũ mâu thuẫn. Đặc biệt không chạy nhánh `verified_scores_below_threshold` của `final_decision_logic.pseudo_code`, câu “điểm xác minh dưới ngưỡng” trong `fail_conditions` hay quy tắc GATE_SCORE theo cách coi tổng các tiêu chí đã xác nhận là tổng điểm chốt khi còn CX. Giữ JSON nguyên bản để truy nguyên, áp dụng mục 11.3/13.3 qua SKILL và mẫu bàn giao hiện hành.

Thứ tự: blocker nội dung xác nhận → chưa đạt; hoặc cận trên tổng/S/G chứng minh ngưỡng không thể đạt → chưa đạt; còn CX trọng yếu có thể đổi kết luận → chưa đủ bằng chứng; đủ ngưỡng xác nhận/không blocker/U3 đồng bộ/không CX trọng yếu → đạt nội dung. Không suy kịch bản đạt thật chỉ vì từng cận trên độc lập đều qua ngưỡng. Phần CX phải có nguồn cần bổ sung/điều kiện đóng. Cận trên chỉ cộng phần còn mở, không cộng lại điểm xác nhận.

## Tình huống kiểm quyết định CX và số chưa làm tròn

Các số dưới đây là **dữ liệu kiểm phương pháp**, không điểm của bài/khách thực. Khoảng ghi điểm xác nhận–cận trên; số đơn là đã chốt. Không có blocker nội dung, U3 đã đối chiếu và không CX trọng yếu trừ khi dòng nêu khác. C và U bổ sung để tổng khớp trong từng kịch bản, tối đa vẫn C30/U15. Không làm tròn trước quyết định.

| ID | Tổng /100 | S /30 | G /25 | Điều kiện | Kết luận nội dung |
| --- | --- | --- | --- | --- | --- |
| CX01 | 92,6–97,6 | 28,8 | 24,3 | U3 CX 0–5; C29,5/U xác nhận10 | CHƯA ĐỦ BẰNG CHỨNG |
| CX02 | 96,6 | 28,8 | 24,3 | Đóng CX01: U3 xác nhận4, đồng bộ | ĐẠT NỘI DUNG V1.8 |
| CX03 | 89–94 | 30 | 25 | C25/U xác nhận9/U3 CX 0–5; tổng tối đa94 | CHƯA ĐẠT NỘI DUNG V1.8 |
| CX04 | 98,49 | 28,49 | 25 | S đã chốt dưới ngưỡng, C30/U15 | CHƯA ĐẠT NỘI DUNG V1.8 |
| CX05 | 98,49–100 | 28,49–30 | 25 | S3 còn mở1,51; CX trọng yếu | CHƯA ĐỦ BẰNG CHỨNG |
| CX06 | 98,749 | 30 | 23,749 | G đã chốt; hiển thị làm tròn23,75 không đổi quyết định | CHƯA ĐẠT NỘI DUNG V1.8 |
| CX07 | 98,74–100 | 30 | 23,74–25 | G3 còn mở1,26; CX trọng yếu | CHƯA ĐỦ BẰNG CHỨNG |
| CX08 | 95 | 28,5 | 23,75 | C28/U14,75, đủ ngưỡng chính xác | ĐẠT NỘI DUNG V1.8 |
| CX09 | 100 | 30 | 25 | Có blocker nội dung đã xác nhận | CHƯA ĐẠT NỘI DUNG V1.8 |
| CX10 | 95 | 28,5 | 23,75 | Như CX08, chỉ GSC/WAF/hiệu năng/AI chưa kiểm | ĐẠT NỘI DUNG V1.8; báo CX đúng lớp riêng |
| CX11 | 94,999 | 28,5 | 23,75 | C27,999/U14,75, không CX; hiển thị95 không đủ | CHƯA ĐẠT NỘI DUNG V1.8 |
| CX12 | 95–100 | 30 | 25 | C25/U15; C còn mở5 về chứng cứ trọng yếu | CHƯA ĐỦ BẰNG CHỨNG |

CX05/CX07 phải giữ điểm xác nhận và chỉ cộng phần mở, không cộng lại toàn bộ10/5 điểm tiêu chí. CX09 chứng minh blocker đúng lớp thắng điểm cao. CX10 kiểm tách lớp: nội dung đạt không nhận live đã nghiệm thu; thiếu công cụ/quyền giữ CX, không Pass/NA. CX12 chứng minh điểm xác nhận cao không thắng CX trọng yếu.

Kiểm Live riêng: tất cả mục áp dụng Pass/NA có lý do → ĐÃ NGHIỆM THU LIVE; không Fail nhưng còn CX → CÁC MỤC ĐÃ KIỂM TRA ĐẠT; CÒN CX TẠI…; có Fail → CHƯA ĐẠT NGHIỆM THU LIVE, vẫn liệt kê CX. HTTP Pass + WAF áp dụng CX không cho toàn L2 Pass. Năm tín hiệu AI độc lập, không lấy Recommended chưa quan sát làm FAIL nội dung.

Repo không có bộ chấm thực thi/CMS ở baseline; các tình huống trên kiểm tính nhất quán của hướng dẫn và mẫu, không phải bằng chứng đã triển khai một engine chấm V1.8 hoặc nghiệm thu URL live. Nếu hệ thống ngoài repo đọc trực tiếp JSON kế thừa, cần được giao sửa/kiểm riêng trước khi nhận nâng cấp.
