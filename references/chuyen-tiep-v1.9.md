# Chuyển tiếp Auto365 Writer V1.8 → V1.9 R1

## Nguồn, ưu tiên và phạm vi

- Baseline GitHub: `a058b26b17c3e5bc5dcf17a4836fb6007d0d5b02`, V1.8 ngày06/10/2026.
- Nguồn mới: [Auto365 V1.9 R1 nguyên văn](Auto365_V1_9_R1_Mot_Bai_Dich_Vu_Phu_Dia_Phuong_20261026.md), ban hành26/10/2026, do người dùng cung cấp. SHA-256 bản nguồn được sao chép: `2146f6217343b45149a7983155b285b29f76dbffba03f8bd315e640262c5d9f4`.
- [Quy chuẩn V1.8](Auto365_Quy_chuan_SEO_GEO_HTML_V1_8_2026-10-06.md), [grading_spec.json](grading_spec.json) V1.7 và [chuyển tiếp V1.8](chuyen-tiep-v1.8.md) giữ làm nguồn nền/lịch sử. Không sửa phiên bản JSON hoặc đổi điểm lịch sử.

R1 điều khiển phần bổ sung/thay đổi; nền V1.8 áp cho phần còn lại. Phụ lục local nhắm tư vấn bi gầm theo xe, case, cơ sở và dịch vụ địa phương; mở ngành khác bằng dữ liệu tương ứng, không biến mọi tin tức/cẩm nang thành landing mạng lưới. SKILL/mẫu diễn giải cách dùng để giải quyết các va chạm dưới đây, không sửa nguyên văn tài liệu nguồn.

## Hai bộ mã N khác nghĩa

| Hệ trong nguồn | Cách ghi trong hồ sơ hiện hành | Nội dung |
| --- | --- | --- |
| V1.8 N1 | V18-N1 | Dữ kiện có nguồn và phạm vi |
| V1.8 N2 | V18-N2 | Câu trả lời hỗ trợ quyết định |
| V1.8 N3 | V18-N3 | Bằng chứng năng lực theo phát ngôn |
| V1.8 N4 | V18-N4 | Thực thể nhất quán |
| V1.8 N5 | V18-N5 | Vai trò URL và liên kết |
| V1.9 N1 | V19-N1 | Đúng thực thể/vai trò |
| V1.9 N2 | V19-N2 | Thông tin cơ sở sử dụng được |
| V1.9 N3 | V19-N3 | Dịch vụ xác nhận qua chuẩn/điểm/ngoại lệ |
| V1.9 N4 | V19-N4 | Bằng chứng đúng phạm vi |
| V1.9 N5 | V19-N5 | Giá và hậu mãi thống nhất |
| V1.9 N6 | V19-N6 | Nguồn/người duyệt/ngày rõ |
| V1.9 N7 | V19-N7 | Truy cập dữ liệu công khai |
| V1.9 N8 | V19-N8 | Hồ sơ nghiệm thu/theo dõi |

Tiền tố là quy ước phân biệt, không đổi ID lịch sử trong nguồn. Không gộp nghĩa, bỏ hướng dẫn nền hoặc tăng điểm/tiêu chí. V19-N dùng ĐẠT/CHƯA ĐẠT/CX; NA có lý do khi không phát sinh theo vai trò, không cho thiếu công cụ. Kiểm R1 mục15.8 gắn N2/N3/N4/N7/N8 của V1.9 theo nguồn, không thêm thang điểm.

## Đầu ra: áp đúng thay đổi R1

Mục10 R1 viết “giữ bộ ba ... V1.8” nhưng liệt kê PDF bài, MD full/SEO Pack, MD CMS; mục18 V1.8 trong repo thực tế là nội dung MD/HTML, CMS/SEO, phiếu đánh giá. Không coi hai danh sách là giống nhau.

V1.9 R1 hiện hành mặc định PDF bài + MD full/SEO Pack **tích hợp phiếu đánh giá/U3/Live** + MD CMS. Không bỏ đánh giá nền chỉ vì không còn file đánh giá riêng và không bắt file thứ tư. Tên file quy ước trong mẫu bàn giao, không phải tên bắt buộc do nguồn R1 đặt. Revision nội dung là R1 dù tên file dùng hậu tố V1.9.

Yêu cầu đầu ra cụ thể của người dùng ưu tiên. Nhiệm vụ HTML dùng HTML làm phần01 thay PDF trong phạm vi được giao; chỉ đoạn/dàn ý không áp đủ bộ. Thiếu công cụ PDF báo chưa hoàn tất, không giả đã tạo. Đối chiếu toàn bài và bản render PDF/HTML cùng các phần SEO/đánh giá/CMS để xác nhận U3.

## Chuyển cách vận hành địa phương

| Nội dung | Cách áp V1.9 R1 |
| --- | --- |
| Bài dịch vụ | Một trang chính/chủ đề; danh bạ/tỉnh/cơ sở bổ sung thông tin nơi tiếp nhận, không90 bản sao |
| Dịch vụ | Chuẩn đã duyệt và thực triển khai + phạm vi điểm + ngoại lệ; không đòi case/xác nhận lại mỗi cặp bài–điểm |
| Đã thi công | Cần case đúng nơi/xe/cấu hình; case nơi khác chỉ tham khảo ghi rõ |
| Quy mô | Điểm hoạt động và số tỉnh là hai trường được kiểm riêng; hơn90 do chủ hệ thống cung cấp chưa là kiểm kê |
| Bộ tìm điểm | Có link/văn bản trước chọn tỉnh, đường xem khi JS lỗi; không toàn bộ90 hồ sơ ở mỗi bài |
| Nhượng quyền | Đúng pháp nhân/đơn vị vận hành, brand, quan hệ thành viên khi có nguồn; không mặc định parent/subOrganization |
| Nghiệm thu | Kiểm cụm trang/dữ liệu/lead/CTA; mẫu ba điểm không đại diện toàn hệ thống |
| Maps | Đối chiếu riêng, không CMS tự đồng bộ, không ảnh trụ sở thành evidence mọi điểm |

## Điểm số, kết luận và ranh giới Live

12 tiêu chí/100 điểm, C30/S30/G25/U15 và ngưỡng≥95/S≥28,5/G≥23,75 giữ nguyên. Không mức phạt hoặc điểm local ngoài thang. Giữ logic CX V1.8: cận trên chỉ cộng phần mở; lỗi chặn nội dung xác nhận hoặc ngưỡng không thể đạt thì chưa đạt; còn CX trọng yếu có thể đổi kết luận thì chưa đủ bằng chứng; đủ ngưỡng/không blocker/U3 đồng bộ/không CX trọng yếu mới đạt nội dung.

R1 diễn đạt U1 thành đa thiết bị và U2 thành hành động/tracking. Đánh giá thiết kế/chỉ dẫn ở lớp nội dung phù hợp; chức năng trên website cần bằng chứng L5/L7. Không dùng điểm bản thảo để nhận nghiệm thu bản triển khai, cũng không tự đổi CX GSC/WAF/AI thành C1 CX.

Nhãn nội dung hiện hành ghi V1.9 R1; không đổi nhãn lịch sử. Tách sẵn sàng CMS, đạt V1.9 theo phạm vi nghiệm thu trên triển khai và đã quan sát AI đề xuất. L1–L8 giữ Pass/Fail/CX/NA có lý do; chỉ kiểm một phần thì kết luận đúng phần. Index có trạng thái riêng, không dùng AI đề xuất làm điều kiện xuất bản hoặc điểm nội dung để nhận sẵn sàng Ads.

## AI, lịch và số mẫu

Giữ Found/Understood/Cited/Mentioned/Recommended của V1.8. Bốn kết quả R1 bổ sung lớp thương hiệu/cơ sở đúng/nguồn hệ thống/độ chính xác. Không thay năm tín hiệu bằng bốn hoặc coi Mentioned=Cited=Recommended. Tách phép tự nhiên và URL chỉ định, nền tảng/chế độ/tìm kiếm/địa phương.

R1 thí điểm ban đầu/ngày14/ngày30; riêng6 câu×2 nền tảng×3 mốc=36/địa phương,108/ba địa phương. Truy vấn bổ sung mục15.8 không nằm sẵn trong108. V1.8 T0/+7/+14/+28 là đề xuất nhiệm vụ khác, không áp chồng. Không tạo automation/gọi API có phí khi chưa được giao. Không suy ba tỉnh là toàn quốc, dữ liệu GSC là Gemini/ChatGPT hoặc mọi lead là AI.

R1 thêm Google-Extended; giữ tách Googlebot, OAI-SearchBot, GPTBot và ChatGPT-User. Các phát biểu nền tảng trong bản nguồn có ngày/phạm vi nguồn; trước tư vấn đổi chính sách bot cần kiểm tài liệu chính thức hiện hành. Bản cập nhật skill không tự sửa robots/WAF hoặc thực hiện benchmark.

## Tình huống kiểm hành vi trước bàn giao skill

Các tình huống sau kiểm cách áp dụng hướng dẫn, không là dữ liệu website thật hay một cuộc chấm nội dung thực.

| Tình huống | Kết quả cần giữ |
| --- | --- |
| Điểm đang hoạt động, thuộc chuẩn VF6 được phê duyệt/triển khai, chưa có case VF6 tại điểm | Được mô tả tiếp nhận theo chuẩn; không claim đã làm VF6 tại đó |
| Điểm thuộc danh sách chung nhưng có ngoại lệ tạm ngừng | Không hiển thị tiếp nhận bình thường; phản ánh trạng thái hiện hành |
| Một case trụ sở được dùng ở nhiều bài/cơ sở | Nhãn đúng nơi thực hiện; không nhân thành nhiều xe/case địa phương |
| Có con số90 điểm nhưng chưa danh sách tỉnh/điểm hiện hành | Chưa kết luận90 điểm hoạt động hay phủ mọi tỉnh; giữ CX phần kiểm kê |
| Widget có dữ liệu chỉ sau chọn tỉnh, trước thao tác không link vào địa phương | Chưa đáp ứng R1; cần đường khám phá tỉnh/danh bạ, không yêu cầu90 hồ sơ đầy đủ mỗi bài |
| Cơ sở nhượng quyền vận hành độc lập, chưa có bằng chứng là công ty con | Không dùng parent/subOrganization như kết luận; chọn quan hệ có nguồn |
| Brief ghi N3 mà không version | Xác định nghĩa theo nguồn/phiên bản; ghi V18-N3 và V19-N3 riêng trong phiếu |
| Yêu cầu viết bài VF6 hoàn chỉnh | PDF bài + MD full/SEO/đánh giá + MD CMS; có U3, không mặc định file thứ tư |
| Yêu cầu chỉ sửa đoạn hoặc xuất HTML | Theo đúng phạm vi/định dạng; không ép PDF hoặc cả bộ nếu không được yêu cầu |
| 92,6 xác nhận, U3 CX tối đa5, S/G còn có thể đạt, không blocker | Khoảng92,6–97,6, chưa đủ bằng chứng, không tự FAIL/PASS |
| Cận trên tổng94 hoặc S28,49 đã chốt | Chưa đạt nội dung; vẫn báo phần CX khác |
| Nội dung đủ ngưỡng nhưng chưa test lead/mobile/GSC | Chỉ kết luận đúng lớp nội dung; Live giữ CX, không nghiệm thu đầy đủ |
| AI có nhắc Auto365 nhưng sai địa chỉ hoặc không khuyên chọn | Mentioned có thể có; không tính đề xuất đúng cơ sở, ghi sai lệch |
| Bài tin tức không mục tiêu giới thiệu cơ sở | Giữ nền V1.8, không ép sáu khối/local hoặc case VF6 |

## Phạm vi gói cập nhật

Sửa SKILL.md, agents/openai.yaml, assets/phieu-brief.md, assets/ban-giao.md; thêm bản nguồn R1 và hướng dẫn chuyển tiếp này. Giữ quy chuẩn V1.8, JSON V1.7, chuyển tiếp V1.8 và icon để truy nguyên. Repo chưa có mã CMS/bộ chấm thực thi; không tuyên bố đã triển khai kế thừa dữ liệu, widget, Maps, lead hoặc nâng cấp skill đang cài ngoài repo.
