# Auto365 V1.9 R1 — Một bài dịch vụ chung, kết nối hệ thống nhượng quyền tại địa phương

Ngày ban hành: 26/10/2026. Phạm vi: tuyến tư vấn bi gầm theo xe, hồ sơ thi công, trang cơ sở và trang dịch vụ địa phương của Auto365. Có thể mở rộng sang phim cách nhiệt, camera và các hạng mục khác bằng dữ liệu chuyên ngành tương ứng.

Cập nhật R1 ngày 26/10/2026: bổ sung mô hình dùng chung danh mục và quy trình dịch vụ cho hệ thống nhượng quyền theo xác nhận của chủ hệ thống. Nội dung kỹ thuật được biên tập tại một trang chính cho mỗi chủ đề; dữ liệu địa phương lấy từ hồ sơ tỉnh và cửa hàng. Không yêu cầu viết lại bài VF6 cho từng điểm hoặc có case VF6 riêng tại mọi điểm mới được tiếp nhận dịch vụ.

Thông tin Auto365 có hơn 90 điểm do chủ hệ thống cung cấp. Lần cập nhật tiêu chuẩn này chưa kiểm kê toàn bộ điểm hoặc số tỉnh có cơ sở; số liệu công khai cần lấy từ danh mục đang hoạt động. Đây là đặc tả triển khai, chưa phải biên bản nghiệm thu website, Maps hoặc kết quả tìm kiếm của toàn mạng lưới.

V1.9 giữ khung chất lượng V1.8 và bổ sung việc xác minh cơ sở thực hiện. Mỗi thông tin giới thiệu cửa hàng phải giúp người đọc kiểm tra được: cửa hàng nào, làm dịch vụ gì, cho xe/cấu hình nào, tại địa chỉ nào, có bằng chứng gì và ai tiếp nhận sau thi công.

Chuỗi thông tin cần liên kết là: **Dòng xe → nhu cầu → giải pháp → sản phẩm → cơ sở thực hiện → bằng chứng → đầu mối hỗ trợ**.

Các yêu cầu, mã kiểm tra, mốc thời gian và chỉ tiêu vận hành dưới đây là tiêu chuẩn nội bộ Auto365. Chúng không phải tiêu chuẩn chấm điểm của Google/OpenAI hoặc cam kết AI sẽ đề xuất thương hiệu.

## 1. Giữ nền V1.8 và thay đổi cách nghiệm thu

Giữ ngưỡng tổng ≥95/100, SEO ≥28,5/30 và GEO ≥23,75/25, đồng thời không còn lỗi trọng yếu trong phạm vi nghiệm thu. Giữ cấu trúc, yêu cầu kỹ thuật, nội dung hữu ích và bộ hồ sơ bàn giao của V1.8.

| Nhóm | Điểm tối đa | Bằng chứng bổ sung trong V1.9 |
|---|---:|---|
| C1 Chính xác | 10 | Tên cơ sở, đời/phiên bản xe, mã sản phẩm, giá và bảo hành khớp nguồn |
| C2 Đầy đủ theo vai trò | 10 | Có cơ sở tiếp nhận, phạm vi dịch vụ và thông tin quyết định phù hợp loại trang |
| C3 Tự nhiên và hữu ích | 10 | Viết cho khách hàng, giải thích trường hợp nên cân nhắc và chưa cần nâng cấp |
| S1 Intent và URL | 10 | Mỗi trang có vai trò rõ; ưu tiên URL production đã chốt |
| S2 On-page và tổ chức | 10 | Thông tin quan trọng đọc được; case và cơ sở liên quan đặt đúng vị trí |
| S3 Liên kết và triển khai | 10 | Liên kết bài–case–cơ sở, khả năng truy cập và dữ liệu chuẩn hóa được kiểm tra |
| G1 Trả lời rõ | 10 | Trả lời ai thực hiện, ở đâu, phạm vi chi phí và điều kiện áp dụng |
| G2 Lập luận và giới hạn | 10 | Phân biệt thông số công bố, phép đo, kinh nghiệm từng case và khả năng tiếp nhận |
| G3 Nguồn và truy nguyên | 5 | Có nguồn, người xác nhận, thời điểm kiểm và hồ sơ đối chiếu |
| U1 Đa thiết bị | 5 | Trang, bản đồ, bảng và CTA dùng được trên thiết bị được nghiệm thu |
| U2 Hành động và tương tác | 5 | Gọi/đặt lịch/chọn cơ sở/lead đến đúng nơi; tracking được kiểm tra |
| U3 Hồ sơ bàn giao | 5 | Các file cùng phiên bản, có nguồn và người duyệt theo phạm vi |
| **Tổng** | **100** | **Không cộng điểm ngoài thang để bù lỗi xác minh** |

Ghi rõ phần đã chấm và phần CX, nghĩa là chưa xác minh. Không quy đổi điểm của phần đã chấm thành điểm tổng. Không kết luận đủ điều kiện chạy Ads chỉ từ điểm nội dung.

Ba trạng thái báo cáo phải tách riêng:

1. **Sẵn sàng đưa lên CMS:** nội dung và dữ liệu đã được duyệt theo phạm vi; các phép kiểm sau xuất bản được liệt kê riêng.
2. **Đạt V1.9 theo phạm vi nghiệm thu:** đủ bằng chứng, điểm số và các điều kiện liên quan đã kiểm trên bản triển khai.
3. **Đã quan sát được AI đề xuất:** có bản ghi câu hỏi và câu trả lời thực tế; đây là kết quả theo dõi, không phải điều kiện bắt buộc để được xuất bản.

## 2. Tám điều kiện xác minh cửa hàng

Dùng trạng thái ĐẠT, CHƯA ĐẠT hoặc CX cho từng mục. Chỉ ghi không áp dụng khi vai trò trang không có nội dung đó và nêu lý do; không dùng không áp dụng để bỏ thông tin cơ sở trên trang có mục tiêu giới thiệu cửa hàng.

| Mã | Điều kiện | Cách đóng | Chủ trì |
|---|---|---|---|
| N1 | Đúng thực thể và vai trò | Phân biệt hệ thống, từng cơ sở, thương hiệu sản phẩm và người rà soát; quan hệ có nguồn xác nhận | Operations + SEO |
| N2 | Cơ sở có thông tin sử dụng được | Tên, địa chỉ, điện thoại, giờ, trang cơ sở và Maps được đối chiếu đúng địa điểm | Quản lý cơ sở |
| N3 | Dịch vụ được xác nhận | Ghi cơ sở nhận tư vấn/kiểm tra/thi công hạng mục nào và giới hạn theo xe/cấu hình | Kỹ thuật + cơ sở |
| N4 | Bằng chứng đúng phạm vi | Claim đã thi công có case truy nguyên; năng lực tiếp nhận có người xác nhận; case nơi khác được ghi rõ | Kỹ thuật + Media |
| N5 | Giá và hậu mãi thống nhất | Mã đèn, đơn vị tính, VAT, công/phụ kiện, thời hạn, đầu mối và phạm vi bảo hành khớp chính sách | Commercial + bảo hành |
| N6 | Nguồn và người duyệt rõ | Claim quan trọng có nguồn, ngày kiểm, người xác nhận; ngày sửa và ngày thi công tách riêng | Reviewer + Content |
| N7 | Dữ liệu công khai truy cập được | Nội dung, liên kết, robots/CDN, canonical và schema được kiểm theo nền tảng; index ghi trạng thái riêng | IT + SEO |
| N8 | Có hồ sơ nghiệm thu và theo dõi | Lưu phiên bản dữ liệu, checklist, kiểm CTA và bộ câu hỏi AI có điều kiện đo rõ | Reviewer + SEO |

Nếu chưa đủ bằng chứng cho một claim, thu hẹp hoặc bỏ claim đó. Một cơ sở có thể được công bố thông tin liên hệ dù chưa có case của mọi dòng xe. Chưa có case VF6 thì không mô tả cơ sở đó như đã thi công VF6.

Với mô hình nhượng quyền có cùng danh mục dịch vụ, N3 được đóng bằng chuẩn dịch vụ được hệ thống phê duyệt, danh sách điểm đang áp dụng và cơ chế ghi ngoại lệ. Không yêu cầu xin lại xác nhận riêng cho mọi cặp cơ sở–bài viết. Phân biệt **đang tiếp nhận theo chuẩn chung** với **đã thi công mẫu xe cụ thể tại cơ sở**; chỉ vế thứ hai cần case tại đúng nơi đó. Số lượng điểm không thay cho hồ sơ áp dụng chuẩn dịch vụ.

## 3. Tạo một nguồn dữ liệu dùng chung cho cơ sở

Cường/IT triển khai bản ghi cơ sở dùng chung trong CMS. Trang chi nhánh, thẻ cơ sở trong bài, form chọn nơi tiếp nhận và schema lấy thông tin từ cùng bản ghi đã duyệt. Dữ liệu trên Maps được quản lý cơ sở đối chiếu riêng; không giả định CMS tự đồng bộ với Maps.

| Trường | Quy tắc |
|---|---|
| Mã cơ sở | Ổn định, không đổi khi thay tên hiển thị |
| Tên thực tế | Khớp tên được sử dụng tại cửa hàng và các kênh chính thức |
| Quan hệ với hệ thống | Phân biệt điểm trực thuộc, điểm nhượng quyền và đối tác; ghi đúng đơn vị vận hành và thương hiệu |
| Tình trạng | Hoạt động, tạm ngừng, chuyển địa điểm hoặc ngừng tiếp nhận hạng mục |
| URL cơ sở | Một URL production chính cho địa điểm đó |
| Địa chỉ | Địa chỉ hiện hành; ghi lịch sử chuyển địa điểm ở hồ sơ quản trị nếu cần |
| Điện thoại | Đúng đầu mối cơ sở; hotline hệ thống ghi vai trò hỗ trợ riêng |
| Giờ làm việc | Bao gồm thay đổi hoặc yêu cầu đặt hẹn |
| Bản đồ | Đúng Google Maps URL, Place ID nếu đã xác nhận, vị trí tọa độ khi sử dụng |
| Dịch vụ | Kế thừa danh mục đã phê duyệt của hệ thống; chỉ ghi riêng phần ngoại lệ tại cơ sở |
| Chuẩn dịch vụ áp dụng | Mã, phiên bản, ngày hiệu lực và người phê duyệt triển khai; phạm vi điểm được áp dụng |
| Ngoại lệ tại cơ sở | Tạm ngừng, cần đặt trước, thiếu phụ kiện hoặc phạm vi cấu hình khác chuẩn chung |
| Phạm vi theo xe | Đời/phiên bản/cấu hình đã có bằng chứng hoặc cần kiểm tra |
| Hậu mãi | Nơi tiếp nhận, điều kiện, quy trình chuyển tiếp giữa cơ sở nếu có |
| Bằng chứng | Case, ảnh cơ sở, tài liệu kỹ thuật hoặc chứng nhận còn giá trị |
| Người xác nhận | Quản lý cơ sở và người xác nhận chuyên môn theo hạng mục |
| Ngày xác minh | Thời điểm kiểm dữ liệu thực tế, không chỉ ngày sửa câu chữ |

Với trụ sở, giữ đúng tên đã khóa: **Auto365.vn - Trụ Sở Chính**. Trang địa phương dùng tên của chính cơ sở đó. Không gán tên trụ sở chính cho mọi điểm trong hệ thống.

Định danh 3M Pro Shop hoặc 3M Training Center chỉ dùng đúng cơ sở và phạm vi có xác nhận. Không thêm thực thể 3M vào bài bi gầm để đủ mẫu.

## 4. Chuẩn hóa dịch vụ và case theo đúng xe

Mỗi cặp cơ sở–dịch vụ có trạng thái hiệu lực từ quy tắc kế thừa hoặc ngoại lệ: đang tiếp nhận, cần khảo sát cấu hình, tạm ngừng hoặc chưa áp dụng. Trạng thái có thể được xác nhận tập trung bằng đợt triển khai chuẩn dịch vụ; cơ sở quản lý lịch và ngoại lệ. Việc đã nhận lắp một mã đèn trên một xe không tự chứng minh mọi mã khác đều phù hợp.

Mỗi case cần có các thông tin sau trong nội dung hoặc hồ sơ đối chiếu của reviewer:

- Đời và phiên bản xe theo nguồn thực tế; không tự áp một cách gọi phiên bản cho mọi năm sản xuất.
- Mã, phiên bản sản phẩm, vị trí lắp và nhu cầu của chủ xe.
- Cơ sở thực hiện; ngày thi công tách với ngày đăng/cập nhật bài.
- Phương án pát/mặt dưỡng, nguồn điện, điều khiển, căn chỉnh và mức can thiệp đã xác nhận.
- Nguồn thông số; phân biệt số hãng công bố với số đo thực tế, kèm điều kiện nếu có đo.
- Phạm vi chi phí và chính sách hậu mãi tương ứng với cấu hình.
- Ảnh/video thật có caption đúng xe, đúng nơi, đúng thao tác. Ảnh minh họa ghi rõ là minh họa.
- Người kiểm hồ sơ và liên kết nguồn để truy nguyên.

Nhiều bài viết về cùng một xe không được tính thành nhiều xe độc lập. Case tại trụ sở có thể làm tài liệu tham khảo cho chi nhánh, nhưng phải ghi đúng nơi thực hiện.

Không bắt buộc công khai phiếu có thông tin cá nhân khách hàng. Hồ sơ nội bộ phải đủ đối chiếu; bản công khai bỏ dữ liệu cá nhân không cần thiết.

## 5. Sáu phần bổ sung trong bài tư vấn

Giữ bố cục bài đã hữu ích; chèn các phần sau vào vị trí phù hợp thay vì kéo dài bài theo số chữ.

| Vị trí | Nội dung cần thêm | Điều kiện chất lượng |
|---|---|---|
| Sau trả lời nhanh | Ai tư vấn, ai thi công, ai hỗ trợ bảo hành; thương hiệu nào cung cấp thiết bị | Vai trò rõ và đúng phạm vi |
| Bảng cấu hình | Mã/version, đối tượng phù hợp, giá thiết bị, phụ kiện/công, bảo hành, trạng thái kiểm chứng | Không biến danh sách tham khảo thành cam kết phù hợp mọi xe |
| Khối case | Xe, cấu hình, cơ sở thực hiện, ngày và ảnh/video liên quan | Dẫn đến hồ sơ thật |
| Khối lắp ở đâu | Bộ chọn địa phương, cơ sở tiếp nhận, trang cơ sở, Maps và đặt hẹn | Lấy danh sách đang áp dụng chuẩn chung, trừ ngoại lệ; có liên kết đọc được khi chưa thao tác |
| Nguồn và rà soát | Tài liệu sản phẩm, chính sách, người kiểm kỹ thuật, ngày xác nhận | Có thể truy nguyên; không đẩy ngày cho mới |
| FAQ và hỗ trợ | Nơi đến, thông tin xe cần gửi, chi phí, bảo hành và khi nào chưa cần nâng cấp | Trả lời quyết định của khách; không viết câu lệnh yêu cầu AI giới thiệu |

Nhóm năm câu hỏi FAQ có thể dùng:

1. Có thể kiểm tra và lắp bi gầm cho xe này tại cơ sở nào?
2. Cấu hình và mức can thiệp nào cần kiểm tra trước khi thi công?
3. Báo giá gồm những gì và áp dụng theo thời điểm nào?
4. Xem bằng chứng thi công và nguồn kỹ thuật ở đâu?
5. Ai tiếp nhận bảo hành; khi nào xe chưa cần nâng cấp?

Mẫu câu xác định vai trò cho trang trụ sở:

> Auto365.vn - Trụ Sở Chính thuộc hệ sinh thái 365Group, tư vấn, lắp đặt và hỗ trợ bảo hành các dòng bi gầm theo nhu cầu và cấu hình xe thực tế. Các hồ sơ thi công trên trang ghi rõ sản phẩm và cơ sở thực hiện. Phương án cuối cần được xác nhận sau khi kiểm tra xe.

Điều chỉnh câu cho đúng trang và dữ liệu. Không sao chép đoạn này vào tất cả chi nhánh rồi thay mỗi tên địa phương.

## 6. Liên kết trang và phân vai giữa các website

Mỗi cơ sở có một trang hồ sơ chính. Trang dịch vụ tại địa phương chỉ mở thêm khi có thông tin tiếp nhận, quy trình, bằng chứng và nội dung phục vụ nhu cầu riêng.

| Loại trang | Vai trò | Liên kết cần có |
|---|---|---|
| Hub bi gầm | Tư vấn nhóm giải pháp | Hãng xe, dòng xe, kiến thức và lựa chọn địa điểm |
| Landing theo dòng xe | Chọn phương án theo xe và nhu cầu | Case đúng xe, sản phẩm đúng mã, cơ sở phù hợp |
| Danh bạ toàn hệ thống | Công khai quy mô và các điểm hoạt động theo địa phương | Các trang tỉnh, hồ sơ cơ sở và danh mục dịch vụ chung |
| Trang tỉnh/thành | Danh sách điểm tại tỉnh, dịch vụ và cách chọn nơi tiếp nhận | Trang cơ sở trong tỉnh và bài dịch vụ chính dùng chung |
| Trang case | Bằng chứng thực hiện trên xe cụ thể | Cơ sở thực hiện, trang tư vấn đúng xe, sản phẩm đã dùng |
| Trang cơ sở | Địa chỉ, năng lực, dịch vụ, lịch hẹn và đầu mối | Maps, dịch vụ, case đúng địa điểm |
| Trang dịch vụ địa phương | Giải quyết nhu cầu tại địa phương | Trang cơ sở, case, phạm vi báo giá và hậu mãi |
| Website thương hiệu đèn | Nguồn sản phẩm và điểm tiếp nhận được xác nhận | Thông số đúng version và liên kết nơi lắp phù hợp |

Ưu tiên URL live đã chốt. Ví dụ, nếu trang cơ sở đang theo cấu trúc /chi-nhanh/quang-ninh/ha-long, tiếp tục dùng URL đó và liên kết nhất quán. Không mở thêm một bản gần trùng ở /he-thong chỉ để thêm từ khóa. Khi cần đổi kiến trúc, SEO/IT lập kế hoạch chuyển hướng và canonical riêng.

Trên X-Light, ưu tiên vai trò nguồn sản phẩm; trên Auto365, ưu tiên lựa chọn giải pháp, thi công và cơ sở. Các website cùng hệ sinh thái không được trình bày như những đơn vị kiểm chứng độc lập. Nguồn bên ngoài chỉ dẫn khi thật sự hỗ trợ thông tin của bài.

## 7. Đồng bộ Google Maps và Google Business Profile

Gemini Apps có thể dùng thông tin công khai từ Google Maps để tìm địa điểm và các chi tiết liên hệ. Do đó, hồ sơ cơ sở trên website cần được đối chiếu với Maps. [Nguồn Google về Gemini và Maps](https://support.google.com/gemini/answer/16622866?hl=en)

Quản lý cơ sở thực hiện:

1. Kiểm tra tên thực tế, địa chỉ, pin bản đồ, số điện thoại và giờ mở cửa.
2. Chọn danh mục phù hợp hoạt động chính trong danh sách Google cung cấp.
3. Ghi dịch vụ và đăng case thật đúng nơi thực hiện.
4. Dẫn website đến trang đại diện đúng địa điểm.
5. Tiếp nhận và trả lời phản hồi khách hàng bằng thông tin thực tế.

Tên Business Profile phải phản ánh tên sử dụng ngoài thực tế. Đặt thông tin dịch vụ ở trường phù hợp; không thêm chuỗi từ khóa vào tên cửa hàng. [Hướng dẫn đại diện doanh nghiệp](https://support.google.com/business/answer/3038177?hl=en)

Việc nhúng bản đồ giúp khách định vị; không dùng thao tác nhúng làm bằng chứng đã tăng xếp hạng. Google nêu các yếu tố địa phương gồm mức liên quan, khoảng cách và độ nổi bật. [Hướng dẫn xếp hạng địa phương](https://support.google.com/business/answer/7091?hl=en)

## 8. Schema mô tả đúng cơ sở và nội dung

Google hướng dẫn định nghĩa từng địa điểm bằng LocalBusiness hoặc loại con phù hợp. [Tài liệu LocalBusiness](https://developers.google.com/search/docs/appearance/structured-data/local-business)

Quy ước triển khai nội bộ:

- Mỗi cơ sở có định danh ổn định, URL, tên, địa chỉ, điện thoại, giờ và Maps khớp phần người dùng đọc.
- Chỉ dùng loại con như AutoRepair khi phản ánh đúng hoạt động; không chọn loại chỉ vì tên có vẻ tối ưu.
- Quan hệ tổ chức mẹ/con chỉ khai báo khi phản ánh đúng quan hệ tổ chức thực tế; hợp đồng nhượng quyền không tự chứng minh cửa hàng là đơn vị con. Với đơn vị vận hành độc lập, khai thương hiệu và quan hệ thành viên phù hợp, không biến toàn bộ bên nhận nhượng quyền thành công ty con bằng schema.
- Trang case mô tả bài và xe/sản phẩm được đề cập; cơ sở thực hiện có liên kết rõ trong nội dung.
- Product, Offer hoặc VideoObject chỉ dùng khi có dữ liệu và nội dung tương ứng; giá phải đúng mã, đơn vị và thời điểm.
- FAQ nếu đánh dấu phải khớp câu hỏi, câu trả lời hiển thị.
- Không tạo điểm sao hoặc đánh giá giả để tăng độ uy tín.

Kiểm cú pháp, kiểu dữ liệu và đối chiếu nội dung. Dùng Rich Results Test cho loại Google hỗ trợ; kết quả kiểm hợp lệ không đồng nghĩa AI sẽ giới thiệu cửa hàng.

## 9. Khả năng truy cập cho Google và ChatGPT

Google yêu cầu trang được index và có thể hiển thị snippet để đủ điều kiện làm liên kết hỗ trợ trong AI Overviews/AI Mode; không có schema AI đặc biệt bắt buộc. Đây là hướng dẫn cho Google Search, cần phân biệt với Gemini Apps. [Tài liệu AI features](https://developers.google.com/search/docs/appearance/ai-features)

| Phạm vi | Kiểm tra và hành động |
|---|---|
| Google Search | Kiểm robots, noindex, giới hạn snippet, canonical, sitemap và khả năng truy cập qua CDN |
| ChatGPT Search | Cho phép OAI-SearchBot truy cập phần nội dung muốn được tìm thấy; rà WAF/CDN theo hướng dẫn và dải IP chính thức |
| GPTBot | Phục vụ dữ liệu có thể dùng huấn luyện; thiết lập độc lập với OAI-SearchBot, không phải điều kiện bắt buộc của ChatGPT Search |
| ChatGPT-User | Có thể truy cập theo yêu cầu người dùng; không thay thế việc kiểm OAI-SearchBot |
| Gemini Apps | Rà Google-Extended và khả năng tìm thấy nội dung; ghi rõ lựa chọn sử dụng dữ liệu hiện hành |
| Preview/staging | Giữ noindex phù hợp môi trường; không dùng URL preview làm đích công khai chính của cơ sở |

Vai trò các bot OpenAI theo [official OpenAI documentation](https://developers.openai.com/api/docs/bots).

Google-Extended kiểm soát việc dùng nội dung cho huấn luyện và grounding của một số sản phẩm Gemini; không quyết định xếp hạng Google Search. IT phải ghi nhận tác động này khi đề xuất thay đổi, không tự gộp với Googlebot. [Tài liệu Google-Extended](https://developers.google.com/crawling/docs/crawlers-fetchers/google-common-crawlers)

Nội dung tên cơ sở, dịch vụ và liên hệ phải đọc được bằng văn bản, không chỉ có trong ảnh hoặc popup. Kiểm link thật và nội dung trả về; chỉ đổi user-agent trong một lệnh thử không chứng minh bot chính thức đã truy cập được.

Ghi trạng thái index riêng. Bản mới có thể xuất bản theo quy trình đã duyệt trong khi chờ xác minh index; chưa có bằng chứng thì giữ CX, không ghi đã index hoặc đủ điều kiện Google AI. Không có dữ liệu GSC không được tự thay bằng một kết luận từ tìm kiếm site:.

## 10. Quy trình duyệt và hồ sơ bàn giao

| Bước | Công việc | Người/nhóm phụ trách |
|---|---|---|
| 1 | Xác định vai trò trang, dòng xe, địa phương và cơ sở liên quan | SEO |
| 2 | Xác nhận cơ sở, phạm vi tiếp nhận, đầu mối và chính sách | Operations + quản lý cơ sở |
| 3 | Xác minh cấu hình, dữ liệu sản phẩm và hồ sơ xe | Product + kỹ thuật |
| 4 | Thu thập, định danh và đối chiếu ảnh/video/case | Media |
| 5 | Chèn sáu phần bổ sung, viết FAQ, dẫn nguồn | Content |
| 6 | Kiểm claim, tên cơ sở, nguồn, ngày và phiên bản | Reviewer |
| 7 | Triển khai CMS, liên kết, schema, form và tracking | IT + SEO |
| 8 | Kiểm bản production, ghi phần đạt/CX và theo dõi AI | Reviewer + SEO |

Giữ bộ ba file bàn giao theo quy trình bài viết V1.8: PDF bài hoàn chỉnh; MD full kèm SEO Pack; MD CMS. Các file phải cùng phiên bản và nội dung quyết định không mâu thuẫn.

Bổ sung vào SEO Pack và phiếu U3:

- Mã và URL cơ sở liên quan.
- Phiên bản dữ liệu cơ sở/dịch vụ/sản phẩm đã dùng.
- Nguồn và người xác nhận claim trọng yếu.
- Kết quả N1–N8, điểm đã chấm và mục CX.
- Kiểm gọi, đặt lịch, nơi nhận lead và tracking.
- URL production, thời điểm kiểm và trạng thái index có bằng chứng.
- Bộ câu hỏi AI, bản ghi gốc và kết quả theo dõi nếu đã có.

Không bắt buộc tạo thêm một file thứ tư chỉ để chứa những trường này. Không sửa toàn bộ bài đã đạt nếu chỉ cần vá đúng khối và dữ liệu liên quan.

## 11. Thí điểm trong 30 ngày

Đây là lộ trình công việc; kết quả AI không có hạn chắc chắn.

| Thời gian | Công việc | Đầu ra |
|---|---|---|
| Ngày 1–3 | Chọn ba cơ sở đủ hồ sơ, ghi dữ liệu hiện hành và đo mẫu ban đầu trước khi sửa | Danh sách cơ sở–dịch vụ được xác nhận, câu trả lời AI ban đầu |
| Ngày 4–7 | Tạo bản ghi dùng chung và sửa các khối CMS; rà bot, schema, form | Mẫu dữ liệu, template và checklist QA |
| Ngày 8–14 | Áp dụng trước cho VF6: landing, case liên quan và các trang cơ sở thực sự tiếp nhận; quản lý cơ sở đối chiếu Maps | Cụm trang đã duyệt, nguồn và dữ liệu thống nhất |
| Ngày 15–21 | Kiểm triển khai, index khi có quyền, nơi nhận lead và đo lại | Phiếu lỗi, hạng mục CX và kết quả quan sát |
| Ngày 22–30 | Sửa phần còn lệch, đo lần tiếp theo; mở rộng sang VF3/VF7 hoặc tuyến khác khi đủ hồ sơ | Báo cáo trước–sau và danh sách trang mở rộng |

Phân công đề xuất: Trân/SEO quản lý ma trận trang và đo lường; Cường/IT quản lý CMS và kỹ thuật; Tâm/Media quản lý bằng chứng hình ảnh; Content vá các khối; kỹ thuật/Product và quản lý cơ sở xác nhận dữ kiện; reviewer được phân công nghiệm thu đúng bản.

## 12. Đo việc được AI nhắc tên và giới thiệu đúng cửa hàng

Dùng hội thoại mới, không đưa tên Auto365 vào câu hỏi dùng để đánh giá khả năng được đề xuất tự nhiên. Đây không tự động là phép thử ẩn danh: vẫn cần ghi vị trí được cung cấp, chế độ tìm kiếm, tài khoản/cá nhân hóa nếu ảnh hưởng và phiên bản giao diện hiển thị.

Đo sáu câu hỏi dưới đây trên cả Gemini và ChatGPT, tại mốc ban đầu, khoảng ngày 14 và ngày 30. Với một địa phương, bộ mẫu gồm 6 × 2 × 3 = 36 câu trả lời; ba địa phương tương ứng 108 câu trả lời. Câu trả lời không có công cụ tìm kiếm ghi thành nhóm riêng, không trộn với nhóm có nguồn web.

| Mã | Câu hỏi mẫu |
|---|---|
| Q1 | Lắp bi gầm VF6 ở đâu tại {địa phương}? |
| Q2 | Tìm nơi tư vấn nâng cấp ánh sáng cho xe điện tại {địa phương}, cho tôi địa chỉ và nguồn tham khảo. |
| Q3 | Nâng cấp bi gầm VF6 gồm những khoản chi phí nào và cần kiểm tra gì trước khi lắp? |
| Q4 | Ở {địa phương}, có nơi nào công khai hồ sơ VF6 lắp bi gầm thực tế không? |
| Q5 | Tôi cần kiểm tra vùng sáng gần đầu xe VF6 tại {địa phương}; nên đến đâu và cần gửi thông tin gì? |
| Q6 | Khi cần hỗ trợ bảo hành đèn gầm VF6 tại {địa phương}, nên liên hệ đâu và kiểm tra chính sách gì? |

Thay địa phương bằng địa danh thật trước khi đo. Lưu nguyên câu hỏi, thời điểm, nền tảng, điều kiện tìm kiếm, câu trả lời và các URL được viện dẫn.

Tách bốn chỉ số:

1. **Nhắc tên thương hiệu:** có Auto365 trong câu trả lời; chưa tự tính là giới thiệu một cơ sở.
2. **Giới thiệu cơ sở đúng:** có cơ sở phù hợp và thông tin định danh khớp hồ sơ hiện hành.
3. **Dẫn nguồn thuộc hệ thống:** có URL Auto365 hoặc nguồn sản phẩm liên quan; phân biệt dẫn làm tài liệu với giới thiệu nơi thi công.
4. **Chất lượng thông tin:** địa chỉ, điện thoại, phạm vi dịch vụ và bảo hành có đúng không.

Mỗi tỷ lệ phải có tử số/mẫu số, theo từng nền tảng và nhóm câu hỏi. Không tính một câu trả lời lặp tên nhiều lần thành nhiều lượt. Câu hỏi có sẵn tên Auto365 chỉ dùng kiểm độ chính xác thông tin, không đưa vào tỷ lệ được đề xuất tự nhiên.

Chỉ tiêu kiểm soát nội bộ ban đầu: dữ liệu công bố được xác minh đầy đủ; claim trọng yếu truy nguyên được; không còn mâu thuẫn tên/địa chỉ/giá/version/bảo hành trong cụm trang thí điểm. Tỷ lệ AI đề xuất là số quan sát, chưa đặt cam kết trước khi có dữ liệu ban đầu.

Theo dõi riêng lượt gọi, đặt lịch và lead. Ghi nhận nguồn khi có bằng chứng; không quy mọi lead tìm kiếm thành lead từ AI. Mẫu nhỏ và thay đổi nội dung cùng lúc không đủ chứng minh quan hệ nhân quả.

## 13. Các lỗi phải chặn khi duyệt

| Lỗi | Cách xử lý |
|---|---|
| Mỗi phần bài ghi một địa chỉ, giá hoặc thời hạn khác nhau | Đồng bộ từ nguồn đã duyệt rồi kiểm cả bảng, popup, FAQ và schema |
| Claim mọi xe đều Plug & Play hoặc không can thiệp điện/cản | Viết theo cấu hình đã kiểm; chưa có bằng chứng thì yêu cầu kiểm xe |
| Gắn cách thi công với cam kết đăng kiểm | Bỏ cam kết; đối chiếu cấu hình và yêu cầu hiện hành khi tư vấn |
| Khẳng định mọi chi nhánh đều đã làm cùng mẫu xe | Dùng đúng danh sách cơ sở và case có nguồn |
| Bảo hành liên tỉnh hoặc đổi mới không có phạm vi chính sách | Ghi đầu mối và cách xác nhận; không mở rộng quyền lợi bằng câu chữ |
| Lấy ảnh minh họa làm bằng chứng thi công | Đổi nhãn hoặc thay bằng ảnh thật có hồ sơ |
| Khai đại lý/ủy quyền/chứng nhận không có nguồn còn giá trị | Thu hẹp đúng vai trò hoặc bổ sung tài liệu xác nhận |
| Chèn tên đối thủ hoặc câu lệnh cho AI để mong được giới thiệu | Thay bằng câu trả lời hữu ích và bằng chứng liên quan |
| Dùng schema, số chữ hoặc điểm nội bộ làm bảo đảm được AI chọn | Ghi đúng phạm vi chất lượng nội bộ và kết quả quan sát |

## 14. Checklist chốt mỗi cụm trang

- [ ] Vai trò trang và cơ sở liên quan được xác định.
- [ ] N1–N8 có kết quả và bằng chứng theo phạm vi.
- [ ] Tên, địa chỉ, điện thoại và Maps đúng cơ sở.
- [ ] Phạm vi tiếp nhận theo dịch vụ/xe/cấu hình có người xác nhận.
- [ ] Case ghi đúng nơi thi công; không đếm trùng xe.
- [ ] Giá, VAT, phụ kiện/công và chính sách hậu mãi thống nhất.
- [ ] Nguồn, người kiểm và ngày xác nhận khớp nội dung.
- [ ] Liên kết, schema và bản CMS mô tả đúng phần khách đọc.
- [ ] Gọi/đặt lịch/chọn cơ sở và nơi nhận lead đã kiểm trong phạm vi bàn giao.
- [ ] Điểm số và trạng thái CX được ghi trung thực.
- [ ] Đã lưu mẫu ban đầu hoặc đánh dấu chưa có; chưa bịa kết quả AI.
- [ ] Bộ hồ sơ bài viết và bản production cùng phiên bản.
- [ ] Bài chung, danh bạ, trang tỉnh và trang cơ sở được nối bằng liên kết thật.
- [ ] Quy mô điểm và số tỉnh có mặt lấy từ dữ liệu hoạt động, không suy từ một con số tổng.
- [ ] Danh mục dịch vụ kế thừa chuẩn đã duyệt, có xử lý ngoại lệ và không giả định case địa phương.
- [ ] Bộ lọc không phải lối duy nhất để khám phá hồ sơ địa phương.

V1.9 được áp dụng bằng việc làm rõ bằng chứng và nơi thực hiện ở từng trang. Mở rộng theo cụm đã nghiệm thu, bắt đầu từ VF6, rồi dùng lại dữ liệu cơ sở cho các tuyến tiếp theo.

## 15. Quy định R1: một bài dịch vụ kết nối nhiều địa phương

### 15.1. Quyết định đưa vào V1.9

Đưa vào V1.9 mô hình **một bài chính cho mỗi dịch vụ/dòng xe + danh bạ hệ thống + hồ sơ tỉnh + hồ sơ từng cửa hàng thật**. Có thể dùng cùng template và dữ liệu dịch vụ cho toàn chuỗi. Phần địa phương phục vụ tìm địa chỉ, chọn cơ sở, gọi và đặt lịch; không lặp lại toàn bộ nội dung tư vấn kỹ thuật.

| Ý kiến đã nêu | Kết luận R1 |
|---|---|
| Dùng một bài VF6 cho hệ thống nhượng quyền | Áp dụng; tập trung thông số, cấu hình, FAQ và kiến thức tại bài chính |
| Nhúng bộ chọn tỉnh và cửa hàng | Áp dụng kèm danh mục HTML, URL địa phương và liên kết có thể khám phá khi chưa chọn |
| Cùng danh mục dịch vụ nên tự động dùng chung dữ liệu | Áp dụng bằng chuẩn dịch vụ, phạm vi triển khai và ngoại lệ; không nhập lại tại 90 điểm |
| Mỗi nơi phải có case VF6 trước khi được giới thiệu tiếp nhận | Không yêu cầu; case là bằng chứng đã làm tại nơi đó, khác với quyền tiếp nhận theo chuẩn chung |
| Bot tự đọc được 90 cơ sở trong bất kỳ widget nào | Không mặc định; phải kiểm dữ liệu trả về và liên kết khi không tương tác |
| Maps quyết định 80% và luôn được Gemini quét trước website | Không có cơ sở chính thức trong các nguồn đã kiểm để dùng con số hoặc thứ tự này |
| Khai 90 subOrganization một lần sẽ phủ mọi tỉnh | Không dùng làm phương án thay thế hồ sơ địa phương; quan hệ phải đúng mô hình nhượng quyền |
| Có nhiều trang địa phương tự động gây cannibalization | Không mặc định; phân biệt hồ sơ cửa hàng thật với nhiều bản sao bài dịch vụ cạnh tranh cùng nhu cầu |

Google nêu mức liên quan, khoảng cách và độ nổi bật trong xếp hạng địa phương, không công bố trọng số 80%. Gemini có thể dùng thông tin công khai từ Maps; tài liệu đó không xác lập thứ tự luôn tra Maps trước website. Các đề xuất cấu trúc R1 là quyết định triển khai của Auto365, không phải công thức xếp hạng của Google/OpenAI. [Xếp hạng địa phương](https://support.google.com/business/answer/7091?hl=en) · [Gemini và địa điểm](https://support.google.com/gemini/answer/16622866?hl=en)

### 15.2. Các trang cần có và công việc biên tập

| Thành phần | Số lượng theo thực tế | Nội dung quản lý | Khi bổ sung bài VF6 |
|---|---|---|---|
| Bài dịch vụ/dòng xe chính | Một trang chính cho mỗi chủ đề | Kỹ thuật, cấu hình, giá tham khảo, FAQ, case và nguồn | Content sửa tại đây một lần |
| Danh bạ hệ thống | Một trang trung tâm | Quy mô, tỉnh có mặt, điểm hoạt động và bộ tìm địa điểm | Dữ liệu dịch vụ dùng chung |
| Trang tỉnh/thành | Một hồ sơ cho mỗi tỉnh thực sự có điểm | Các cửa hàng trong tỉnh, địa chỉ, dịch vụ, liên hệ | Hiển thị dịch vụ và link bài chính từ CMS |
| Trang cơ sở | Một hồ sơ cho mỗi địa điểm thật | Định danh, quan hệ nhượng quyền, địa chỉ, Maps, giờ, ảnh, lịch, dịch vụ | Hiển thị thẻ VF6 từ dữ liệu chung; chỉ nhập ngoại lệ |
| Case thi công | Theo số hồ sơ xe thật | Xe, sản phẩm, nơi làm, ngày và bằng chứng | Xuất hiện tại bài chính và đúng cơ sở thực hiện |
| Google Business Profile | Theo địa điểm đủ điều kiện của Google | Thông tin, dịch vụ và hình ảnh đúng nơi | Cập nhật theo chức năng hiện có và quyền quản lý |

Ví dụ luồng với trang VF6 hiện có: bài chính `/nang-cap-anh-sang-bi-gam/vinfast/vf6` liên kết đến danh bạ; danh bạ liên kết trang tỉnh; trang tỉnh liên kết cơ sở và bài VF6; cơ sở hiển thị dịch vụ VF6 và liên kết trở lại bài chính. Case liên kết bài VF6 và đúng nơi thi công.

Giữ URL production hiện có. Không tạo thêm một hệ URL song song chỉ để phù hợp ví dụ. Trang cơ sở và tỉnh có mục đích riêng thì canonical về chính URL của trang; không canonical mọi hồ sơ địa phương về bài VF6. Không mở tự động mọi tổ hợp dòng xe × tỉnh × cơ sở. Chỉ thêm landing dịch vụ địa phương khi có nhu cầu và thông tin địa phương đủ hữu ích để có vai trò riêng.

Truy vấn tại một tỉnh có thể dẫn tới bài VF6, trang tỉnh, hồ sơ cơ sở hoặc Maps. Mục tiêu là khách tìm được đúng điểm Auto365, không ép cùng một URL VF6 phải xếp hạng ở mọi tỉnh.

### 15.3. Chuẩn dịch vụ dùng chung cho mô hình nhượng quyền

Tách ba lớp dữ liệu để công việc mở rộng không tăng theo số bài nhân số cửa hàng:

1. **Chuẩn hệ thống:** dịch vụ, quy trình, bài hướng dẫn, cấu hình tham khảo, chính sách, phiên bản và phạm vi áp dụng.
2. **Cơ sở:** địa chỉ, đơn vị vận hành, tư cách nhượng quyền, liên hệ, giờ và tình trạng hoạt động.
3. **Ngoại lệ:** cần hẹn trước, đang thiếu phụ kiện, tạm ngừng, chưa áp dụng phiên bản mới hoặc khác biệt chi phí thực tế.

Quy tắc hiển thị nội bộ: một điểm được liệt kê tiếp nhận khi điểm còn hoạt động, thuộc phạm vi áp dụng chuẩn dịch vụ và không có ngoại lệ ngừng tiếp nhận. Không dùng phép nối dữ liệu để tự chứng nhận một chuẩn chưa được hệ thống triển khai.

Khi thêm một bài mới, Content chọn mã dịch vụ và chuẩn áp dụng. CMS nối bài đó với các điểm đang áp dụng chuẩn; không yêu cầu Content viết 90 đoạn giới thiệu mới. Với hạng mục mới chỉ triển khai ở một phần mạng lưới, giữ đúng nhóm điểm được áp dụng đến khi chuyển giao xong.

Năng lực chung có thể dựa trên quy trình được ban hành, hồ sơ chuyển giao/đào tạo và phạm vi điểm áp dụng. Bằng chứng từng địa phương gồm hồ sơ cơ sở, tình trạng và lịch tiếp nhận. Case VF6 tại trụ sở được dùng chung như **case tham khảo của hệ thống, thực hiện tại trụ sở**; không đổi chú thích thành case của một điểm khác.

Cùng dịch vụ và quy trình không tự có nghĩa mọi xe dùng cùng pát, điện hoặc mã đèn. Giá trọn gói và bảo hành chỉ kế thừa như nhau nếu có chính sách hệ thống tương ứng; lịch, phụ kiện và chi phí bổ sung hiển thị đúng điều kiện.

### 15.4. Hiển thị quy mô hơn 90 điểm và độ phủ tỉnh

Danh bạ công khai cần có tổng điểm đang hoạt động, số tỉnh có điểm, danh sách địa phương và thời điểm cập nhật dữ liệu. Một địa điểm chuyển chỗ không được đếm hai lần; điểm tạm đóng hoặc ngừng hợp tác xử lý theo trạng thái thực tế. Không cộng số điểm trên các website cùng hệ sinh thái thành nhiều mạng lưới độc lập.

Số điểm và số tỉnh là hai trường riêng. Chỉ dùng câu “có mặt tại tất cả tỉnh/thành” sau khi danh sách hiện hành xác nhận có cơ sở tại từng tỉnh. Nếu một nơi chưa có điểm, ghi rõ điểm gần nhất hoặc hình thức hỗ trợ thực tế; không tạo địa chỉ hoặc hồ sơ Maps tại nơi đó.

Địa chỉ và mã tỉnh theo dữ liệu hiện hành; có thể lưu địa danh quen tìm như tên khu vực trước thay đổi hành chính để khách tra cứu. Không tạo hai cửa hàng hoặc hai bản landing trùng nhau vì cùng một nơi có hai cách gọi.

Quy mô được công bố bằng văn bản, có danh bạ để đối chiếu. Không cần nhồi tên mọi tỉnh trong đoạn mở đầu của mọi bài, và không dùng `numberOfEmployees` làm số cơ sở.

### 15.5. Bộ tìm cửa hàng phải có dữ liệu đọc được khi chưa thao tác

Trên bài VF6, khối “Lắp bi gầm VF6 tại Auto365 ở đâu?” gồm:

- Giới thiệu ngắn quy mô và việc tiếp nhận theo chuẩn hệ thống.
- Bộ chọn tỉnh/thành và tìm theo khu vực; định vị thiết bị là tùy chọn, không bắt buộc mới xem được danh sách.
- Liên kết văn bản đến các trang tỉnh đang có điểm tiếp nhận và đến danh bạ đầy đủ. Danh sách có thể trình bày gọn bằng nhóm hoặc accordion với nội dung đã có sẵn.
- Thẻ cơ sở có tên, địa chỉ, giờ, điện thoại, trang riêng, Maps và đặt lịch; hiển thị trạng thái cần đặt trước nếu có.
- Link case tham khảo, có ghi đúng nơi thực hiện; tách khỏi trạng thái tiếp nhận tại cửa hàng.

IT ưu tiên render văn bản và liên kết quan trọng từ máy chủ hoặc lúc dựng trang. JavaScript dùng để lọc/sắp xếp cho khách. Không để API chỉ tải dữ liệu sau khi khách chọn tỉnh trở thành lối duy nhất để đọc cơ sở. Không cần nhét toàn bộ chi tiết của 90 điểm vào mọi bài: bài có liên kết tỉnh; trang tỉnh có danh sách cơ sở; từng cơ sở có hồ sơ đầy đủ.

Google hướng dẫn liên kết bằng phần tử `<a href="…">`; liên kết được chèn bằng JavaScript cũng có thể được đọc nếu triển khai đúng. Tuy nhiên Google Search không thao tác chọn/bấm như người dùng để làm xuất hiện dữ liệu. Vì vậy R1 chọn cách cung cấp thông tin trước thao tác và kiểm thực tế, thay vì mặc định mọi bot đều đọc được widget. [Liên kết có thể thu thập](https://developers.google.com/search/docs/crawling-indexing/links-crawlable) · [Nội dung tải chậm](https://developers.google.com/search/docs/crawling-indexing/javascript/lazy-loading)

Không nhân bản vô hạn URL từ bộ lọc, vị trí và sắp xếp. Dùng URL tỉnh/cơ sở ổn định cho nội dung cần tìm thấy; tham số giao diện có chính sách index/canonical riêng do SEO duyệt. Cung cấp cùng nội dung thực tế cho khách và bot, không tạo danh sách địa phương riêng chỉ cho crawler.

### 15.6. Mô tả dịch vụ tại trang cơ sở

Trang cơ sở cần trả lời trực tiếp dịch vụ gì, cho xe nào, ở đâu và đặt lịch thế nào. Thẻ dịch vụ lấy từ dữ liệu chung có thể gồm tên “Nâng cấp bi gầm VinFast VF6”, trạng thái tiếp nhận, link bài tư vấn, nút gọi/đặt lịch và ghi chú chuẩn áp dụng. Nội dung chung có thể lặp trong thẻ dịch vụ khi giúp khách hiểu; phần hồ sơ địa điểm phải đúng cửa hàng thật.

Không bắt buộc sáng tác một đoạn tư vấn VF6 riêng tại mỗi cơ sở. Không ghi “đã hoàn thiện VF6 tại cửa hàng” khi chưa có hồ sơ. Nếu có case, bổ sung ảnh/cấu hình/ngày thật và chỉ gắn vào nơi thực hiện. Có thể khai trương dịch vụ theo chuẩn chung trước khi có case tại địa phương đó.

Google Business Profile của từng điểm đối chiếu tên thực tế, địa chỉ, số điện thoại, giờ, danh mục và dịch vụ. Liên kết website dẫn tới hồ sơ đúng cơ sở; liên kết đặt lịch dẫn tới nơi nhận hẹn đúng cơ sở. Google có hướng dẫn duy trì tên và danh mục nhất quán trong chuỗi khi phù hợp hoạt động, đồng thời tên phải phản ánh nhận diện thực tế. Không thêm các từ khóa VF6/X-Light/bi gầm vào tên Maps để tạo tín hiệu địa phương. [Hướng dẫn chuỗi và thương hiệu](https://support.google.com/business/answer/3038177?hl=en)

Có thể chuẩn bị dữ liệu hàng loạt từ CMS, nhưng xuất bản qua chức năng/công cụ hiện có của tài khoản và kiểm kết quả từng điểm. Không coi đăng cùng một Post lên mọi Maps là điều kiện đủ để được đề xuất. Không hứa một thao tác sẽ cập nhật mọi trường thông tin hoặc mọi hồ sơ; không dùng ảnh tại trụ sở như ảnh thi công tại tất cả điểm.

### 15.7. Schema cho mạng lưới nhượng quyền

| Đối tượng | Cách mô tả | Giới hạn |
|---|---|---|
| Thương hiệu Auto365 | Định danh thương hiệu dùng chung, liên kết đơn vị quản lý hệ thống đúng hồ sơ | Không đồng nhất thương hiệu, pháp nhân vận hành hệ thống và mọi bên nhận nhượng quyền |
| Điểm trực thuộc | LocalBusiness hoặc loại con phù hợp, định danh riêng; quan hệ tổ chức đúng thực tế | Không dùng một địa chỉ trụ sở cho mọi điểm |
| Điểm nhượng quyền độc lập | LocalBusiness, thương hiệu Auto365; có thể dùng `memberOf` nếu quan hệ thành viên phản ánh đúng mạng lưới | Không mặc định `parentOrganization`/`subOrganization` chỉ vì cùng nhượng quyền |
| Danh bạ/trang tỉnh | Có thể dùng CollectionPage/ItemList mô tả danh sách đang hiển thị, tham chiếu hồ sơ từng nơi | Không khai 90 điểm vô hình chỉ trong JSON-LD |
| Bài dịch vụ chung | Mô tả đúng nội dung trang, dịch vụ và nơi tiếp nhận liên quan khi có dữ liệu | Không khẳng định Google hỗ trợ rich result riêng cho mọi thuộc tính dịch vụ |

Google hướng dẫn định nghĩa từng địa điểm bằng `LocalBusiness` hoặc loại con phù hợp. Schema.org định nghĩa `subOrganization` là quan hệ một tổ chức bao gồm một tổ chức khác; `memberOf` mô tả quan hệ thành viên. Lựa chọn quan hệ cho Auto365 phải theo mô hình vận hành đã công bố, không tối ưu bằng cách gán mọi cửa hàng thành công ty con. [LocalBusiness](https://developers.google.com/search/docs/appearance/structured-data/local-business) · [subOrganization](https://schema.org/subOrganization) · [memberOf](https://schema.org/memberOf) · [brand](https://schema.org/brand)

Schema là phần bổ sung cho nội dung và liên kết công khai. Google không yêu cầu schema AI đặc biệt cho AI Overviews/AI Mode; quy định này không phải một cam kết về Gemini Apps. Với ChatGPT Search, kiểm OAI-SearchBot và CDN/WAF; quyền GPTBot phục vụ mục đích khác. Không có nguồn chính thức đã kiểm nào bảo đảm một khai báo chuỗi sẽ tạo đề xuất ở mọi tỉnh. [Google AI features](https://developers.google.com/search/docs/appearance/ai-features) · [OpenAI Crawlers](https://developers.openai.com/api/docs/bots)

### 15.8. Điều kiện nghiệm thu bổ sung và cách triển khai

Giữ N1–N8 và thang 100 điểm. Bổ sung kiểm tra R1 vào N2, N3, N4, N7, N8 thay vì cộng thêm điểm.

| Kiểm tra R1 | Điều kiện đóng | Phụ trách |
|---|---|---|
| Quy mô và độ phủ | Danh bạ thống kê được điểm hoạt động và tỉnh có điểm; khớp câu công bố | Operations + Trân/SEO |
| Kế thừa dịch vụ | Một chuẩn dịch vụ được duyệt nối được tới nhóm cơ sở; ngoại lệ hoạt động đúng | Kỹ thuật + Operations + Cường/IT |
| Liên kết địa phương | Mọi điểm công bố đi tới được từ danh bạ/tỉnh bằng link thật; bài chính có đường dẫn vào mạng lưới | Cường/IT + SEO |
| Không phụ thuộc chọn tỉnh | Kiểm trước thao tác vẫn có văn bản và liên kết cần thiết; JS lỗi không làm mất lối xem hồ sơ | Cường/IT |
| Case đúng nơi | Danh mục tiếp nhận và bộ case tách riêng; không phát sinh 90 claim đã làm từ một case | Reviewer + Tâm/Media |
| Chọn nơi và nhận lead | Gọi/đặt lịch ghi đúng mã cơ sở, dịch vụ và thông tin xe | IT + quản lý cơ sở |
| Đo kết quả từng tỉnh | Lưu truy vấn không gợi thương hiệu, nền tảng, địa phương và URL nguồn | Trân/SEO |

Lộ trình R1 sử dụng kế hoạch 30 ngày ở mục 11, với ba điểm để kiểm mẫu kỹ thuật. Trong cùng đợt, chuẩn hóa dữ liệu tất cả điểm đang hoạt động; sau khi mẫu đạt, đưa các điểm đủ dữ liệu vào template chung theo lô, không chờ viết thêm bài dịch vụ cho từng địa phương.

- Ngày 1–3: chốt danh sách điểm, tỉnh, chuẩn dịch vụ và ngoại lệ; lưu kết quả tìm kiếm ban đầu ở ba địa phương mẫu.
- Ngày 4–7: Cường triển khai kế thừa dữ liệu, khối tìm cửa hàng và template tỉnh/cơ sở; kiểm mẫu ba điểm.
- Ngày 8–14: Content sửa bài VF6 một lần; nhập/đối chiếu dữ liệu cơ sở theo lô; cơ sở cập nhật Maps; reviewer duyệt kết quả.
- Ngày 15–30: kiểm khả năng khám phá, index khi có quyền, thông tin đúng và nơi nhận lead; đo lại trên Gemini/ChatGPT; mở rộng bài theo xe khác bằng cùng dữ liệu.

Ngoài bộ câu hỏi ở mục 12, với từng tỉnh thí điểm dùng ba nhóm “lắp bi gầm VF6 ở đâu tại {địa phương}?”, “lắp {mã đèn đang có trong danh mục} cho VF6 tại {địa phương} ở đâu?” và “cửa hàng nâng cấp ánh sáng ô tô tại {địa phương}”. Không gợi tên Auto365. Đo hai nền tảng có tìm kiếm, ghi điều kiện và lặp tại các mốc đã chốt. Tách nhắc thương hiệu, đề xuất đúng cơ sở, dẫn website và thông tin sai. Ghi số tỉnh có ít nhất một lần đề xuất đúng trên tổng tỉnh đã đo; không dùng kết quả ba tỉnh làm bằng chứng phủ toàn quốc.

Không hứa mọi truy vấn tại mọi tỉnh đều có Auto365. Mục tiêu quản trị là dữ liệu toàn mạng lưới đầy đủ và truy cập được; mục tiêu kết quả là tăng số địa phương, truy vấn và lượt khách tìm thấy đúng cửa hàng, được kiểm bằng số quan sát.

