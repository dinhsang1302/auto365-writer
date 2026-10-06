# Mẫu bộ bàn giao Auto365 V1.8

Đọc toàn bộ [quy chuẩn hiện hành V1.8](../references/Auto365_Quy_chuan_SEO_GEO_HTML_V1_8_2026-10-06.md). [grading_spec.json](../references/grading_spec.json) là nguồn kế thừa V1.7 nguyên bản theo mục 19.6; khi mâu thuẫn áp dụng V1.8, đặc biệt mục 11.3/13.3 về CX. Không dùng final_decision_logic cũ để FAIL từ tổng điểm xác nhận còn mở. Đây là mẫu làm việc của WRITER: viết/sửa, tự kiểm, bàn giao; không thay bản hoàn chỉnh bằng phiếu chấm.

Thay nhãn mẫu bằng dữ liệu có căn cứ. Không bịa dữ liệu để lấp mẫu; không để placeholder, điểm, CX, rule ID hoặc ghi chú nội bộ trong phần 01. Ghi thiếu dữ kiện ở phần 02/03 và trạng thái ngoài bài. Tự đánh giá Writer không thay nghiệm thu độc lập.

## Hồ sơ đồng bộ

| Trường | Nội dung thực tế |
| --- | --- |
| Tiêu chuẩn | Auto365 SEO/GEO/HTML V1.8 |
| Chủ đề, loại trang, intent | Chọn đúng một nhiệm vụ chính trong 8 loại của mục 3 |
| Phiên bản nội dung, phạm vi sửa | Cùng phiên bản ở cả ba phần |
| Môi trường, URL | Draft / preview / production; URL thực tế hoặc đề xuất |
| Ngày xuất bản, ngày sửa nội dung, ngày kiểm, múi giờ | Ghi riêng, giữ ngày xuất bản gốc |
| Vai trò/người xác nhận | Người thật và phạm vi đã xác nhận; chưa có ghi chưa cung cấp |

## File 01 — Nội dung cho khách

Tên: `01_Noi_dung_[Chu_de]_V1.8.md`.

Chỉ khi nhiệm vụ yêu cầu HTML, phần 01 là `01_Noi_dung_[Chu_de]_V1.8.html`; không bắt thêm Markdown/PDF/bản sao. Thay chủ đề thật trong tên.

- H1 phản ánh nhiệm vụ, trả lời câu hỏi chính ngay phần đầu với chủ thể/điều kiện/phạm vi.
- H2/H3 và luồng đọc phù hợp loại trang: ca thi công, tư vấn, sản phẩm, dịch vụ/trụ cột/danh mục, cẩm nang, chi nhánh, landing page, tin tức/thương hiệu. Không ép cùng dàn bài, FAQ, số ảnh/link hoặc bảng giá.
- Dữ kiện/nguồn/đơn vị/giới hạn gần nhận định; bảng, ảnh/video đúng tài sản và chú thích; link phù hợp.
- Kết luận, đánh đổi và hành động tiếp theo đúng dữ liệu đã xác minh. Không gán tiêu chí tư vấn thành nhu cầu/lời khách thật.

## File 02 — Hướng dẫn CMS/SEO

Tên: `02_Huong_dan_CMS_SEO_[Chu_de]_V1.8.md`.

### Brief, baseline và khóa dữ kiện

Dùng [phiếu brief](phieu-brief.md). Với trang đang hoạt động lưu baseline nội dung/metadata/ảnh/link và phạm vi kỹ thuật đã kiểm, ngày giờ. Đối chiếu URL cùng nhu cầu trước khi đề xuất trang mới.

| Dữ kiện/phát ngôn và vị trí | Giá trị/đơn vị/phạm vi | Nguồn đúng cấp | Phiên bản/ngày nguồn | Ngày đối chiếu | Người xác nhận | Trạng thái | Quyền/cách sử dụng |
| --- | --- | --- | --- | --- | --- | --- | --- |

Phân biệt nguồn hãng đúng SKU/thị trường/điều kiện với nhà phân phối, năng lực đúng chi nhánh, hồ sơ ca thật, biên bản đo và xác nhận Commercial. Công bố hãng không chứng minh đã lắp/đo trên xe hoặc cơ sở có chứng nhận. Mã tự đặt không chứng minh hồ sơ tồn tại. Không bịa thông số, phương pháp đo, khách hàng, trải nghiệm hoặc người duyệt. CX là chưa đủ bằng chứng, không là cáo buộc bịa. Bảo vệ dữ liệu cá nhân.

### Triển khai theo mục 9–10

- URL hiện tại/đề xuất và vai trò, URL liên quan, canonical cuối; phạm vi giao diện cần giữ.
- Title/meta/H1/cây heading; hero, bảng, widget, sticky CTA và thân bài nhất quán về giá/phạm vi.
- Ảnh/video đã xem: nguồn/đúng ca hay minh họa, vị trí/alt/chú thích/quyền dùng; tài sản chưa có ghi riêng, không giả đã quay.
- Chỉ tạo HTML khi yêu cầu. Dữ kiện thiết yếu đọc được trong HTML trả về hoặc render ổn định đã kiểm. Bảng thực dùng table/th/scope theo quan hệ, ưu tiên caption khi làm template mới; đơn vị/nguồn/điều kiện/VAT gần bảng, kiểm mobile. Thiếu caption/scope không tự blocker hoặc mức phạt nếu ngữ cảnh rõ và chưa có tác động chứng minh.
- Link mới dùng a href crawlable, anchor đúng ngữ cảnh, ưu tiên canonical cuối. Ghi HTTP/redirect/đích/canonical và ngày kiểm. 301 hợp lệ đúng đích không tự blocker; chưa kiểm ghi CX. Không đổi slug chỉ để thêm từ khóa; thay URL phải có chuyển hướng/canonical/link và kiểm lại.
- datePublished gốc; dateModified chỉ khi sửa nội dung thực. Ngày kiểm hồ sơ, hiệu lực giá, crawl/index và T0 riêng, múi giờ/hiển thị/khai báo khớp. Preview/staging bảo vệ/noindex phù hợp; không mang noindex sang production cần tìm kiếm.
- Registry thực thể và Schema phù hợp nội dung: publisher Organization, provider cơ sở AutoRepair/LocalBusiness, brand, SKU/xe/about/mentions. Tái dùng @id đúng quan hệ; không gán hãng thành parentOrganization để giả đại lý. Author/reviewedBy chỉ người thật xác nhận. Offer cần chào bán có thật, không lấy giá một ca làm offer chung.
- Có thể nhiều script JSON-LD nối đúng @id; không tự blocker. Kiểm cú pháp, ngữ nghĩa, trùng/mâu thuẫn và khớp hiển thị, không chỉ validator. Không tạo review/rating/chứng nhận giả, không hứa rich result/AI; FAQ/HowTo theo nhiệm vụ.
- CTA/điện thoại/địa chỉ/cơ sở/form thực có và phạm vi kiểm. Tách đề xuất, file đã sửa, đã triển khai và đã xác minh; không nhận CMS/runtime đã nâng cấp chỉ từ tài liệu.

| Link đi ra: vị trí/anchor | Đích khai báo | HTTP/redirect/đích cuối | Canonical/vai trò | Ngày/công cụ/bằng chứng | Trạng thái/cách sửa |
| --- | --- | --- | --- | --- | --- |

| Link dẫn đến bài: trang nguồn | Vị trí/anchor/đích | Đề xuất hay đã có | Ngày kiểm/bằng chứng | Phần chờ |
| --- | --- | --- | --- | --- |

| Thực thể | Type/tên | URL/@id | Quan hệ/phạm vi | Nguồn xác nhận | Trạng thái |
| --- | --- | --- | --- | --- | --- |

### Phần còn thiếu và điều kiện triển khai

| Dữ liệu/công việc | Ảnh hưởng và lớp Content/Live/hiệu quả | Nguồn cần bổ sung | Vai trò/người phụ trách thực tế | Trạng thái/điều kiện đóng |
| --- | --- | --- | --- | --- |

Ghi mức sẵn sàng triển khai riêng với kết luận nội dung. Không nhận đã đăng/kiểm live khi chưa thực hiện.

## File 03 — Tự đánh giá Writer

Tên: `03_Phieu_danh_gia_[Chu_de]_V1.8.md`.

Ghi: **Tự đánh giá của Writer — không thay nghiệm thu độc lập**. Phạm vi gồm tên/URL, loại trang/câu hỏi chính, cùng phiên bản với phần 01/02, V1.8, nguồn/ngày giờ kiểm, ngoại lệ, vai trò/người thực tế. V1.7 chỉ là nguồn kế thừa hoặc điểm/kết luận lịch sử, không đổi nhãn điểm cũ.

### Chất lượng nội dung — 12 tiêu chí, 100 điểm

| Mã | Tiêu chí | Tối đa | Điểm đã xác nhận | CX/phần còn mở và cận trên | Bằng chứng/vị trí/tác động/cách sửa |
| --- | --- | ---: | --- | --- | --- |
| C1 | Chính xác và nhất quán | 10 | | | |
| C2 | Đầy đủ theo vai trò bài | 10 | | | |
| C3 | Tự nhiên và hữu ích | 10 | | | |
| S1 | Nhu cầu tìm kiếm và vai trò URL | 10 | | | |
| S2 | Nội dung SEO trên trang | 10 | | | |
| S3 | Liên kết và hồ sơ triển khai | 10 | | | |
| G1 | Câu trả lời rõ, đủ ngữ cảnh | 10 | | | |
| G2 | Lập luận phục vụ nhu cầu | 10 | | | |
| G3 | Nguồn và khả năng truy nguyên | 5 | | | |
| U1 | Cấu trúc dễ đọc | 5 | | | |
| U2 | Hành động tiếp theo phù hợp | 5 | | | |
| U3 | Bộ bàn giao nhất quán | 5 | | | |

C/30, S/30, G/25, U/15; tổng/100, tổng÷10; SEO=S÷30×10; GEO=G÷25×10. Giữ mẫu số, không loại tiêu chí CX. Dải điểm mục 11.2: 100%, 90–99%, 50–89%, 0–49% theo tác động và bằng chứng; không mức phạt cố định.

| Nhóm/ngưỡng | Điểm đã xác nhận chưa làm tròn | Phần còn mở | Khoảng có thể đạt | So ngưỡng trước làm tròn |
| --- | --- | --- | --- | --- |
| C /30 | | | | Không có ngưỡng riêng |
| S /30 | | | | ≥28,5 |
| G /25 | | | | ≥23,75 |
| U /15 | | | | Không có ngưỡng riêng |
| Tổng /100 | | | | ≥95 |

CX không tự cho 0/điểm đạt. Cận trên chỉ cộng phần tối đa còn mở, không cộng lại điểm đã xác nhận; khoảng S/G riêng nếu liên quan. Giả định và cực đại có điều kiện không là điểm xác nhận hoặc chứng minh các cực đại cùng xảy ra.

**Kết luận mục 11.3/13.3 theo thứ tự:** lỗi chặn nội dung xác nhận → CHƯA ĐẠT NỘI DUNG V1.8; hoặc cận trên tổng <95/S <28,5/G <23,75 chứng minh ngưỡng không thể đạt → CHƯA ĐẠT NỘI DUNG V1.8, vẫn liệt kê CX. Nếu chưa chứng minh chưa đạt và còn CX trọng yếu có thể đổi kết luận → CHƯA ĐỦ BẰNG CHỨNG. Chỉ ĐẠT NỘI DUNG V1.8 khi đủ cả ba ngưỡng đã xác nhận, không blocker nội dung, U3 đồng bộ bản hiện hành, không CX trọng yếu. Không dùng FAIL từ tổng xác nhận thấp khi khoảng còn đủ khả năng đạt.

Ví dụ kiểm phương pháp: tổng xác nhận 92,6; U3 CX tối đa 5 → khoảng 92,6–97,6, không phải điểm đạt giả định. S/G còn khả năng đạt, không blocker xác nhận → CHƯA ĐỦ BẰNG CHỨNG. Ngược lại cận trên tổng 94 → CHƯA ĐẠT dù còn CX. S=28,49 hoặc G=23,749 đã chốt vẫn chưa đạt dù số hiển thị làm tròn chạm ngưỡng. Xem [tình huống chuyển tiếp](../references/chuyen-tiep-v1.8.md).

### N1–N5 — hướng dẫn áp dụng, không thêm điểm/phạt

| Mã | Phạm vi đối chiếu | Tiêu chí hiện có | Đáp ứng/cần sửa/CX/NA có lý do, bằng chứng/cách xử lý |
| --- | --- | --- | --- |
| N1 | Dữ kiện, nguồn, đơn vị, điều kiện, giá/bảo hành | C1, G3 | |
| N2 | Câu trả lời, căn cứ, đánh đổi, hỗ trợ quyết định | C2, G1, G2 | |
| N3 | Năng lực đúng cơ sở, ca thật, quy trình/người duyệt | C3, G3 | |
| N4 | Tổ chức, cơ sở, thương hiệu, SKU/xe nhất quán | S2, S3, G3 | |
| N5 | Intent/vai trò URL, link/canonical | S1, S3 | |

Không thêm tiêu chí thứ 13–17 hoặc cộng nhiều mức phạt cho cùng lỗi. N3 không phát sinh ghi lý do, không tạo ca giả.

### Blockers và phần chưa xác minh

| Mã | Lỗi xác nhận cần kiểm | Phạm vi | Trạng thái/bằng chứng/vị trí/cách sửa/điều kiện đóng |
| --- | --- | --- | --- |
| BLOCK_01 | Sai xe/phiên bản/sản phẩm/ảnh/cấu hình quan trọng | Nội dung/hồ sơ | |
| BLOCK_02 | Giá/đơn vị/VAT/công/phạm vi/bảo hành mâu thuẫn gây hiểu nhầm | Các phần công bố liên quan | |
| BLOCK_03 | Bịa phép đo/trải nghiệm/lời khách/người duyệt/bằng chứng | Nội dung/hồ sơ | |
| BLOCK_04 | Tư vấn kỹ thuật thiếu căn cứ dẫn tới lựa chọn/lắp sai | Tư vấn/kỹ thuật | |
| BLOCK_05 | Sai điểm liên hệ | Nội dung/CTA/liên hệ | |
| BLOCK_06 | Bản đăng còn nội bộ/chỗ trống bắt buộc/dữ kiện trọng yếu chưa xác minh | Bản đăng/dữ kiện quyết định; chưa xác minh giữ CX | |
| BLOCK_07 | Noindex/canonical/truy cập sai mục tiêu đã xác nhận | Production/live; không tự đổi điểm Content | |
| BLOCK_08 | Schema sai đáng kể hiển thị/đánh giá giả | Nội dung khai báo/triển khai, ghi đúng lớp | |

Phân biệt lỗi xác nhận, không phát hiện trong phạm vi đã kiểm, CX trọng yếu, NA có lý do. Thiếu video/caption/Service, 301 hợp lệ hoặc nhiều JSON-LD đúng quan hệ không tự thêm blocker. Không lấy thứ hạng/AI làm blocker nội dung. Dữ kiện trọng yếu chưa xác minh không tự gọi bịa. GSC/WAF/hiệu năng/AI CX không tự thành C1 CX.

### U3 và kết luận nội dung

| Phần 01 | Phần 02 | Phần 03 | Phiên bản chung | Điểm đối chiếu/còn lệch/ngày kiểm |
| --- | --- | --- | --- | --- |

Đối chiếu thực sự cả ba, không suy U3 từ tên file/bài công khai/phiếu cũ. Sửa sau duyệt cập nhật phần liên quan và đánh giá tác động. Ghi kết luận nội dung đúng ba trạng thái bên trên, điểm/khoảng, blocker/CX và điều kiện đóng; mức sẵn sàng triển khai riêng.

### Live — độc lập với điểm Content

| Mã | Hạng mục | Pass/Fail/CX/NA | URL/phiên bản/môi trường/ngày giờ/công cụ/phạm vi/bằng chứng; trạng thái con/điều kiện đóng |
| --- | --- | --- | --- |
| L1 | Bản đăng: nội dung/ảnh/title/H1/meta so bản duyệt | | |
| L2 | HTTP/redirect/robots/meta/X-Robots-Tag/canonical/WAF khi thuộc phạm vi | | |
| L3 | GSC URL Inspection/canonical Google/crawl-index/bản Google đọc | | |
| L4 | Schema: cú pháp/ngữ nghĩa/@id/quan hệ/khớp hiển thị | | |
| L5 | Desktop/mobile/tablet; viewport/cách kiểm, mô phỏng ghi rõ | | |
| L6 | Hiệu năng; lab/field/công cụ/ngày/điều kiện | | |
| L7 | Link đi/đến/liên hệ/form/event trong quyền kiểm | | |
| L8 | HTML trả về/render, văn bản/bảng/a href/snippet/ảnh-video | | |

Pass chỉ khi kiểm thực và có bằng chứng; Fail khi xác nhận lỗi; CX khi thiếu quyền/công cụ/chưa kiểm/chưa đủ bằng chứng. NA chỉ khi không phát sinh ở trang/giai đoạn/phạm vi, có lý do, không dùng cho thiếu công cụ. L nhiều phép kiểm phải ghi trạng thái con: HTTP Pass + WAF thuộc phạm vi CX không là toàn L2 Pass. Tìm công khai không thay GSC; đổi User-Agent không chứng minh bot thật. Lab không tự chứng minh CWV field; không đặt ngưỡng mới. Trước xuất bản ghi đúng giai đoạn, không giả đã kiểm production; index chậm không tự blocker.

- Tất cả mục áp dụng Pass, NA có lý do: **ĐÃ NGHIỆM THU LIVE**, nêu URL/phiên bản/ngày/phạm vi.
- Không Fail ở phần đã kiểm, còn CX: **CÁC MỤC ĐÃ KIỂM TRA ĐẠT; CÒN CX TẠI…**, liệt kê phần đã kiểm, không nhận nghiệm thu đầy đủ.
- Có Fail: **CHƯA ĐẠT NGHIỆM THU LIVE**, liệt kê Fail và CX, cách sửa/kiểm lại.

### Quan sát hiệu quả — tách khỏi Content và Live

Ghi dữ liệu SEO/GBP/crawler/AI thực có hoặc chưa đo, không tự hứa index/citation/đề xuất. Tách OAI-SearchBot, GPTBot, ChatGPT-User và điều kiện kiểm WAF; không tự thay chính sách GPTBot khi chỉ xử lý Search. GBP/NAP/dịch vụ/chứng nhận đúng cơ sở, báo riêng, không hệ số Gemini.

| Lượt thử | Nền tảng/model/chế độ/tìm web | Ngày giờ/múi giờ/vị trí-IP biết được | Câu hỏi nguyên văn/phiên bản bộ câu hỏi | Khám phá tự nhiên hay URL chỉ định | Toàn văn phản hồi và URL nguồn thực tế | Found | Understood | Cited | Mentioned | Recommended | Sai lệch/giới hạn/bằng chứng |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |

Năm tín hiệu độc lập, không chuỗi bắt buộc/điểm chất lượng: Found cần URL auto365.vn hiển thị; Understood đối chiếu dữ kiện đúng/sai/chưa đủ bằng chứng; Cited cần thẻ/link và đúng đích; Mentioned cần nhắc trong câu trả lời, metadata không đủ; Recommended cần khuyên chọn, nhắc trung lập không đủ. Không tự suy truy xuất ngầm hoặc đọc toàn bài từ citation. URL khác không tính là Cited của bài đo.

Tách Google AI Overviews/AI Mode, Gemini, ChatGPT Search; phép khám phá tự nhiên không mớm thương hiệu/URL. Chưa biết điều kiện ghi chưa xác định; chưa đo không điền kết quả giả. Báo số thành công/tổng lượt hợp lệ, mẫu thiếu/lỗi/lý do loại và dữ kiện đủ đánh giá Understood; không suy tỷ lệ mẫu thành toàn người dùng hay quan hệ nhân quả của lần sửa. SEO ghi nguồn/khoảng ngày/truy vấn/URL và quyền báo cáo; không suy GSC thành Gemini/ChatGPT.

T0 là xuất bản/sửa nội dung thật; ngày crawl/index riêng. T0/+7/+14/+28 là lịch theo dõi đề xuất phù hợp nhiệm vụ, không tạo automation nếu chưa được yêu cầu.

### Công việc còn lại và phản hồi Reviewer

| Việc/CX/lỗi | Lớp và ảnh hưởng | Cách sửa/nguồn bổ sung/điều kiện kiểm lại | Vai trò/người thực tế | Trạng thái |
| --- | --- | --- | --- | --- |

Ghi thay đổi thực hiện theo Reviewer và phần chưa thể sửa. Không tự ghi Reviewer PASS/ký. Cập nhật repo GitHub không tự cập nhật skill đang cài trong ChatGPT Work, CMS hoặc mã ngoài repo.
