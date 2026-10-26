# Mẫu bộ bàn giao Auto365 V1.9 R1

Áp [R1 nguyên văn](../references/Auto365_V1_9_R1_Mot_Bai_Dich_Vu_Phu_Dia_Phuong_20261026.md), [nền V1.8](../references/Auto365_Quy_chuan_SEO_GEO_HTML_V1_8_2026-10-06.md) và [chuyển tiếp](../references/chuyen-tiep-v1.9.md). Mẫu của WRITER: viết/sửa rồi tự kiểm. Không giả nghiệm thu độc lập, xác nhận thương mại/kỹ thuật hoặc chữ ký.

## Phiên bản chung và bộ ba hiện hành

| Trường | Nội dung thực tế |
| --- | --- |
| Tiêu chuẩn | V1.9 R1, nền chất lượng V1.8 |
| Chủ đề/loại trang/intent/phạm vi R1 | Theo nhiệm vụ thật |
| Version bài và bản nguồn | Cùng revision ở ba file; lưu baseline nếu sửa |
| URL/môi trường | Draft/preview/production, đích thực tế hoặc đề xuất ghi rõ |
| Ngày tháng | Xuất bản/sửa/thi công/hiệu lực giá/ngày kiểm riêng, múi giờ |
| Vai trò xác nhận | Người thật, phạm vi và bằng chứng; chưa có ghi CX |

Nhiệm vụ hoàn chỉnh mặc định ba file theo mục10 R1:

1. `01_Noi_dung_[Chu_de]_V1.9.pdf`: bản hoàn chỉnh cho khách.
2. `02_Full_SEO_Pack_[Chu_de]_V1.9.md`: toàn bài, SEO Pack và phiếu tự đánh giá tích hợp.
3. `03_Huong_dan_CMS_[Chu_de]_V1.9.md`: triển khai và phần chờ.

Thay chủ đề thật trong tên. R1 ghi bộ này là “giữ V1.8”, nhưng bộ V1.8 trong repo cũ khác; đây là quy ước đầu ra hiện hành theo R1, không sửa lịch sử. Phiếu đánh giá/U3 nằm trong file02, không bắt file thứ tư. Nếu nhiệm vụ yêu cầu HTML làm phần01, thay PDF bằng `.html` theo phạm vi yêu cầu; không tự tạo thêm HTML/PDF/bản sao khi người dùng đã chốt định dạng khác. Yêu cầu chỉ bài/đoạn/dàn ý thì giao đúng phạm vi, không nhận bộ ba đủ. Thiếu công cụ PDF phải báo chưa hoàn thành file01.

## File01 — Bản cho khách

- H1 và trả lời chính sớm, rõ chủ thể/cấu hình/phạm vi/điều kiện; heading theo vai trò trang, không giọng báo cáo nội bộ.
- Dữ kiện có nguồn/đơn vị/giới hạn gần nhận định; ảnh/caption/ALT đúng tài sản đã xem, link thật đúng ngữ cảnh.
- Với tư vấn R1: vai trò tư vấn/thi công/bảo hành; cấu hình/giá; case; lắp ở đâu; nguồn/người rà soát; FAQ/hỗ trợ, đặt vào bố cục hữu ích. Không tạo case/giá/người duyệt để đủ mục, không ép mẫu này cho mọi loại bài.
- Phân biệt đang tiếp nhận theo chuẩn chung và đã thi công tại điểm. Case tham khảo ghi đúng nơi làm. Bản công khai không chứa điểm, CX, mã N/BLOCK, placeholder hoặc dữ liệu cá nhân không cần thiết.
- PDF phải được render và xem để kiểm tiếng Việt, bảng, ảnh, link, ngắt trang và khớp toàn bài MD. HTML nếu được yêu cầu cần kiểm render/thiết bị trong phạm vi có công cụ; không suy bản PDF chứng minh widget đã chạy.

## File02 — Full, SEO Pack và tự đánh giá

### A. Toàn bài

Đặt toàn bộ nội dung khách đọc, cùng chữ/dữ kiện/bảng/caption/link với file01. Tách rõ hết phần bài trước hồ sơ nội bộ bên dưới, không để chép điểm/CX vào CMS như bài công khai.

### B. Brief và SEO Pack

Dùng [phiếu brief](phieu-brief.md). Ghi URL/title/meta/H1/heading, vai trò cụm trang, từ khóa theo intent, ảnh/ALT/caption/link/CTA, canonical/schema/@id, môi trường và chỉ dẫn CMS liên quan; đối chiếu file03 để không mâu thuẫn.

| Dữ kiện/phát ngôn và vị trí | Giá trị/đơn vị/phạm vi | Nguồn đúng cấp | Phiên bản/ngày nguồn | Ngày đối chiếu | Người xác nhận | Trạng thái | Quyền/cách sử dụng |
| --- | --- | --- | --- | --- | --- | --- | --- |

Khi áp R1 thêm mã/URL cơ sở, đơn vị vận hành, trạng thái, Maps và ngày đối chiếu; mã/version/ngày hiệu lực/người duyệt chuẩn dịch vụ, danh sách điểm áp dụng và ngoại lệ; version dữ liệu sản phẩm/giá/hậu mãi/case; kiểm lead; URL production/thời điểm/index có bằng chứng; nhật ký AI hoặc chưa đo.

Không bịa mã chuẩn/hồ sơ. Năng lực tiếp nhận có thể kế thừa bằng chuẩn đã triển khai và danh sách điểm, không đòi case mỗi cặp xe–điểm. Claim đã làm tại điểm cần đúng case. Công bố quy mô từ danh bạ hiện hành, không suy hơn90 là mọi tỉnh.

### C. Phiếu tự đánh giá Writer

Ghi **Tự đánh giá Writer — không thay nghiệm thu độc lập**, URL/version/phạm vi/nguồn/ngày/công cụ, người xác nhận thật và ngoại lệ. Không đổi nhãn điểm cũ thành V1.9.

| Mã | Tiêu chí nền | Tối đa | Điểm xác nhận | Phần CX/cận trên | Bằng chứng/vị trí/tác động/cách sửa |
| --- | --- | ---: | --- | --- | --- |
| C1 | Chính xác và nhất quán | 10 | | | |
| C2 | Đầy đủ theo vai trò | 10 | | | |
| C3 | Tự nhiên và hữu ích | 10 | | | |
| S1 | Intent và vai trò URL | 10 | | | |
| S2 | On-page và tổ chức | 10 | | | |
| S3 | Liên kết và hồ sơ triển khai | 10 | | | |
| G1 | Trả lời rõ, đủ ngữ cảnh | 10 | | | |
| G2 | Lập luận/đánh đổi/giới hạn | 10 | | | |
| G3 | Nguồn và truy nguyên | 5 | | | |
| U1 | Dễ đọc; đa thiết bị theo phạm vi R1 | 5 | | | |
| U2 | Hành động phù hợp; CTA/lead theo phạm vi R1 | 5 | | | |
| U3 | Hồ sơ cùng phiên bản | 5 | | | |

C30/S30/G25/U15, tổng100. Tổng/10=tổng÷10; SEO/10=S÷30×10; GEO/10=G÷25×10. So tổng≥95, S≥28,5, G≥23,75 **trước làm tròn**; không bắt từng mã≥9,5. Dải100%/90–99%/50–89%/0–49% theo tác động và bằng chứng; không phạt cố định.

| Nhóm | Điểm đã xác nhận | Phần mở | Khoảng có thể đạt | Ngưỡng |
| --- | --- | --- | --- | --- |
| C/30 | | | | Không riêng |
| S/30 | | | | ≥28,5 |
| G/25 | | | | ≥23,75 |
| U/15 | | | | Không riêng |
| Tổng/100 | | | | ≥95 |

CX không tự cho0/điểm đạt; cận trên chỉ cộng điểm phần còn mở. 92,6 xác nhận + U3 CX tối đa5 →92,6–97,6, chưa đủ bằng chứng nếu còn có thể đạt, không FAIL chỉ từ92,6. Cận trên94 thì chưa đạt; S28,49/G23,749 đã chốt vẫn dưới ngưỡng. Cực đại các phần liên thuộc không tự đồng thời đạt.

### D. Hai bộ N và kiểm R1

| Mã | Phạm vi đối chiếu | Kết quả/bằng chứng/nguồn/ngày/người/điều kiện đóng |
| --- | --- | --- |
| V18-N1 | Dữ kiện/nguồn/điều kiện/giá/bảo hành | |
| V18-N2 | Trả lời/căn cứ/đánh đổi/quyết định | |
| V18-N3 | Năng lực theo phát ngôn/case/người duyệt | |
| V18-N4 | Tổ chức/cơ sở/brand/SKU/xe nhất quán | |
| V18-N5 | Intent/URL/link/canonical | |
| V19-N1 | Đúng thực thể và vai trò | |
| V19-N2 | Thông tin cơ sở sử dụng được | |
| V19-N3 | Dịch vụ xác nhận: chuẩn triển khai/nhóm điểm/ngoại lệ | |
| V19-N4 | Bằng chứng tiếp nhận/đã làm đúng phạm vi | |
| V19-N5 | Giá và hậu mãi thống nhất | |
| V19-N6 | Nguồn/người duyệt/ngày tách đúng | |
| V19-N7 | Nội dung/link/robots/CDN/canonical/schema truy cập được | |
| V19-N8 | Hồ sơ/phiên bản/CTA/nhật ký theo dõi | |

V18-N giữ hướng dẫn nền; V19-N dùng ĐẠT/CHƯA ĐẠT/CX, NA có lý do theo vai trò. Không gộp nghĩa hai bộ, không thêm tiêu chí/điểm/phạt. Tách phần N7/N8 bản thảo và phần chỉ kiểm trên triển khai.

| Kiểm R1 mục15.8 | Bằng chứng/phạm vi/ĐẠT–CHƯA ĐẠT–CX/điều kiện đóng |
| --- | --- |
| Quy mô và số tỉnh khớp danh bạ hoạt động | |
| Chuẩn dịch vụ nối đúng điểm, ngoại lệ hiệu lực | |
| Bài chính–danh bạ–tỉnh–cơ sở có link thật | |
| Có đường khám phá trước chọn tỉnh/khi JS lỗi | |
| Tiếp nhận tách case, ảnh/case đúng nơi | |
| Gọi/đặt hẹn/lead đúng mã cơ sở/dịch vụ/xe | |
| Đo từng tỉnh với câu hỏi không mớm thương hiệu | |

### E. Blockers và quyết định nội dung

| Mã nền | Nội dung lỗi cần kiểm | Trạng thái/vị trí/bằng chứng/lớp/cách sửa |
| --- | --- | --- |
| BLOCK_01 | Sai xe/version/sản phẩm/ảnh/cấu hình quan trọng | |
| BLOCK_02 | Giá/đơn vị/VAT/công/phạm vi/bảo hành mâu thuẫn | |
| BLOCK_03 | Bịa phép đo/trải nghiệm/lời khách/người duyệt/bằng chứng | |
| BLOCK_04 | Tư vấn kỹ thuật thiếu căn cứ có thể dẫn lắp sai | |
| BLOCK_05 | Sai điểm liên hệ | |
| BLOCK_06 | Nội bộ/placeholder/dữ kiện trọng yếu chưa xác minh vào bản đăng | |
| BLOCK_07 | Production có truy cập/noindex/canonical sai mục tiêu | |
| BLOCK_08 | Schema sai đáng kể hoặc đánh giá giả | |

Lỗi địa phương mục13 R1 đối chiếu vào mã/tiêu chí thích hợp, không tự sinh phạt. Dữ kiện chưa rõ giữ CX, không cáo buộc bịa. Không tự blocker vì thiếu video/caption/Service,301 hợp lệ, nhiều JSON-LD đúng quan hệ, AI chưa đề xuất hoặc mới chờ index. BLOCK_07 thuộc live, BLOCK_08 ghi đúng lớp. Thiếu quyền GSC/WAF/hiệu năng không tự làm C1 CX khi nội dung đủ nguồn.

| Đối chiếu U3 | Version và phần đã kiểm | Còn lệch/điều kiện đóng |
| --- | --- | --- |
| File01 PDF/HTML ↔ toàn bài file02 | | |
| SEO Pack/đánh giá file02 ↔ CMS file03 | | |
| Dữ kiện/ảnh/link/nguồn/giá/cơ sở giữa cả ba | | |

Chỉ xác nhận U3 sau đối chiếu bản thực, kể cả PDF render; không từ tên file hoặc phiếu cũ. Sửa các lệch liên quan trước kết luận.

Thứ tự: blocker nội dung xác nhận hoặc cận trên tổng/S/G không thể đạt → **CHƯA ĐẠT NỘI DUNG V1.9 R1**; chưa có căn cứ chưa đạt nhưng CX trọng yếu còn có thể đổi kết luận → **CHƯA ĐỦ BẰNG CHỨNG**; đủ ba ngưỡng xác nhận, không blocker nội dung/CX trọng yếu và U3 đồng bộ → **ĐẠT NỘI DUNG V1.9 R1**. Báo sẵn sàng CMS riêng, không nhận nghiệm thu R1 trên triển khai chỉ từ điểm nội dung hoặc sẵn sàng chạy Ads.

### F. Live L1–L8 và nghiệm thu V1.9 theo phạm vi

| Mã | Phép kiểm | Pass/Fail/CX/NA | URL/version/môi trường/ngày/công cụ/bằng chứng/trạng thái con/cách đóng |
| --- | --- | --- | --- |
| L1 | Bản đăng/ảnh/title/H1/meta so bản duyệt | | |
| L2 | HTTP/redirect/robots/meta/X-Robots/canonical/WAF | | |
| L3 | GSC URL Inspection/crawl/index/canonical Google | | |
| L4 | Schema cú pháp/ngữ nghĩa/@id/quan hệ/hiển thị | | |
| L5 | Desktop/mobile/tablet, bản đồ/bảng/bộ lọc/CTA | | |
| L6 | Hiệu năng theo công cụ/điều kiện, lab khác field | | |
| L7 | Link/liên hệ/chọn cơ sở/form/lead/tracking | | |
| L8 | HTML/render, văn bản/link trước thao tác, snippet/media | | |

Pass cần kiểm và bằng chứng; Fail cần lỗi xác nhận; CX cho chưa kiểm/thiếu quyền/công cụ; NA chỉ khi không phát sinh và có lý do. HTTP Pass + WAF thuộc phạm vi CX không là toàn L2 Pass. GSC không thay bằng site:, đổi UA không chứng minh bot thật, lab không chứng minh CWV field. Bản thảo không chứng minh widget/lead đã chạy; phần chức năng U1/U2 ghi đúng L5/L7.

- Tất cả mục áp dụng Pass, NA có lý do: **ĐÃ NGHIỆM THU LIVE**, ghi phạm vi.
- Không Fail nhưng còn CX: **CÁC MỤC ĐÃ KIỂM TRA ĐẠT; CÒN CX TẠI…**, không nhận đầy đủ.
- Có Fail: **CHƯA ĐẠT NGHIỆM THU LIVE**, ghi Fail/CX và cách kiểm lại.

Chỉ ghi **ĐẠT V1.9 THEO PHẠM VI NGHIỆM THU** khi đủ bằng chứng/điểm số, V19-N và các kiểm R1 liên quan trên đúng bản triển khai. Ghi rõ phạm vi điểm/trang/thiết bị; ba điểm mẫu không chứng minh toàn mạng lưới. “Đã quan sát AI đề xuất” là kết quả độc lập, không điều kiện xuất bản.

### G. AI/SEO/Maps và hiệu quả

| Lượt | Nền tảng/model/chế độ/tìm web | Ngày/giờ/múi giờ/vị trí/điều kiện chưa biết | Câu hỏi nguyên văn/bộ hỏi | Tự nhiên hay URL chỉ định | Toàn phản hồi và nguồn thật | Found | Understood | Cited | Mentioned | Recommended | Cơ sở đúng/sai và sai lệch |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |

Năm tín hiệu độc lập: Found có URL hiển thị; Understood đối chiếu dữ kiện; Cited có thẻ/link đúng đích; Mentioned trong phản hồi; Recommended có khuyên chọn phù hợp, không nhắc trung lập. Không suy truy xuất ngầm/đọc toàn bài. Thêm bốn chỉ số R1: thương hiệu, đề xuất đúng điểm, nguồn thuộc hệ thống và độ đúng thông tin.

R1 thí điểm: Q1–Q6 và truy vấn địa phương mục15.8, không mớm Auto365. Mốc ban đầu/14/30; Q1–Q6:36 phản hồi/địa phương,108/ba địa phương, chưa gồm câu bổ sung. Mốc V1.8 T0/+7/+14/+28 là đề xuất cho nhiệm vụ khác, không áp chồng hai lịch. Chỉ chuẩn bị kế hoạch khi chưa được giao đo/automation/API có phí.

Báo tử số/mẫu hợp lệ/lượt thiếu-lỗi/lý do loại theo nền tảng và nhóm hỏi; nhóm không tìm web riêng. Số tỉnh có đề xuất đúng/tổng tỉnh đã đo khác tỷ lệ lượt. Không suy phủ toàn quốc từ ba tỉnh hoặc quan hệ nhân quả từ mẫu nhỏ. Lead/gọi/lịch hẹn chỉ gắn AI khi có chứng cứ; GSC không đại diện Gemini/ChatGPT. Maps/bot theo dõi riêng; CMS không mặc định đồng bộ GBP, Google-Extended/GPTBot khác Search.

## File03 — Hướng dẫn CMS

- URL production/canonical hiện có, vai trò bài/danh bạ/tỉnh/cơ sở/case; không mọi tổ hợp xe×tỉnh×điểm hoặc canonical mọi địa phương về bài chính.
- Title/meta/H1/heading, tài sản/nguồn/ALT/caption/link/quyền dùng; nội dung khớp file01/02. HTML chỉ khi nhiệm vụ yêu cầu, giữ giao diện được chốt.
- Nguồn dữ liệu chung và phiên bản: chuẩn dịch vụ/nhóm điểm áp dụng, hồ sơ cơ sở và ngoại lệ; phân biệt tiếp nhận và case. Trụ sở đúng tên, nhượng quyền đúng đơn vị vận hành.
- Quy mô/số tỉnh/ngày thống kê từ danh bạ hiện hành. Link tỉnh/danh bạ trước chọn bộ lọc, thẻ điểm/Maps/đặt lịch, phương án JS lỗi/định vị tùy chọn. Không cần90 hồ sơ đầy đủ ở mỗi bài; không crawler-only hoặc URL lọc vô hạn.
- CTA/lead/tracking đúng mã điểm/dịch vụ/xe và đầu mối, quyền kiểm; Maps đối chiếu riêng, chưa thực hiện không nhận đã đồng bộ.
- Schema registry/@id/quan hệ đúng thực tế, danh bạ/tỉnh theo danh sách hiển thị; không nhượng quyền=con mặc định. Một/nhiều script đúng định danh đều được; không review/offer/chứng nhận giả.
- Ngày xuất bản gốc; ngày sửa thật, kiểm nguồn, hiệu lực, thi công và crawl/index riêng. Staging/production đúng cấu hình. Link a href/canonical/HTTP có ngày kiểm;301 hợp lệ không tự blocker.
- Kế hoạch L1–L8, V19-N và kiểm R1 theo phạm vi; phân biệt đề xuất, đã sửa file, đã triển khai và đã kiểm.

| Việc thiếu/lỗi/CX | Lớp Content/triển khai/Live/hiệu quả | Nguồn/cách sửa và điều kiện kiểm lại | Người/vai trò thật | Trạng thái |
| --- | --- | --- | --- | --- |

Khi Reviewer yêu cầu sửa, cập nhật các phần liên quan và U3, giữ phạm vi thực. Repo chỉ chứa gói skill/tài liệu, không tự nâng CMS, Maps, bộ chấm hoặc skill đã cài ngoài repo.
