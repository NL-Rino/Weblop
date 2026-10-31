# HƯỚNG DẪN SỬ DỤNG WEB LỚP 9E (trường Quang Trung, năm học 2026-2027)

## 1. Các thẻ (tab) và ai làm được gì
Thanh thẻ phía trên gồm: **Tổ 1-4** (bảng ghi điểm), **Tổng hợp**, **Thống kê**, **Trực nhật**, **Lịch sử trực nhật**; riêng admin có thêm **Tài khoản** và **Sự kiện**.
- **Tổ trưởng**: chỉ thấy và sửa được thẻ tổ mình. Ghi điểm và nhận xét tuần cho tổ mình, bấm "đã cập nhật đủ tuần này", xin gia hạn sổ điểm, gửi yêu cầu chuyển học sinh sang tổ khác, ghi nhận xét của tổ mình theo tháng/học kỳ/cả năm trong Tổng hợp. Tổ trưởng KHÔNG thêm/xoá học sinh, KHÔNG xem điểm tổ khác.
- **Lớp trưởng**: xem điểm tất cả các tổ (không sửa điểm), xem Tổng hợp, ghi nhận xét chung của lớp, thêm/xoá học sinh, đặt ngày nghỉ lễ, thêm/bỏ trực bổ sung, khôi phục đã bỏ, xem ai là người xếp, xếp lại lịch trực.
- **Lớp phó lao động**: phụ trách trực nhật. Xem điểm tất cả các tổ (không sửa điểm), xem Tổng hợp; đặt ngày nghỉ lễ, thêm/bỏ trực bổ sung, khôi phục đã bỏ, xem ai là người xếp, xếp lịch trực, xếp chỗ ngồi các tổ. KHÔNG sửa điểm, KHÔNG thêm/xoá học sinh, KHÔNG viết nhận xét chung của lớp. Tài khoản mặc định lpld, lần đầu đăng nhập phải đặt mật khẩu mới.
- **Thầy chủ nhiệm (gvcn)**: xem điểm tất cả các tổ, xem Tổng hợp, chụp ảnh "Phiếu theo dõi tuần", xuất file, thêm/xoá học sinh. Không sửa điểm.
- **Admin**: toàn quyền: sửa mọi thứ (kể cả sổ đã khoá), duyệt gia hạn, đổi cài đặt, quản lý tài khoản, tạo link đăng nhập nhanh, tạo/thu hồi mã đăng nhập tạm thời, chỉnh số trong thẻ Lịch sử trực nhật.
- Mọi người đổi được mật khẩu của mình (trừ khi vào bằng link đăng nhập nhanh). Web tự đăng xuất sau 20 phút không thao tác.

## 2. Ghi điểm hằng tuần
- Mỗi học sinh được phát sẵn **100 điểm mỗi tuần**. Tổ trưởng nhập SỐ LẦN cho từng cột, web tự cộng/trừ theo điểm mỗi lần:
  Đồng phục -10, Bảng tên -10, Khăn quàng -10, Bài cũ -15, Soạn bài -15, Đồ dùng -5, Lộn xộn -10, RN HL -10, Nói chuyện -10, Cúp tiết -30, Đi học muộn -20, Nói tục -10, Phát biểu +2, Điểm 9,10 +10. Ô "Khác" nhập điểm cộng/trừ tự do (số âm là trừ).
- Chọn đúng **tuần** ở ô "Tuần", nhập xong bấm **Lưu thay đổi**. Bật công tắc "Đã cập nhật đủ tuần này" khi tổ đã ghi xong (bấm Lưu cũng tự tính là đã cập nhật).
- Ô **Nhận xét tuần** nằm dưới bảng điểm, lưu cùng lúc với bảng điểm.
- Học sinh dưới 80 điểm trong tuần sẽ được xếp trực bổ sung tự động (xem mục 5).

## 3. Khoá sổ điểm
- Sổ điểm của mỗi tuần tự **khoá lúc 12:00 trưa Chủ nhật**. Tuần 1-3 khoá cùng một lúc (12:00 trưa Chủ nhật 04/10/2026); từ tuần 4 trở đi, mỗi tuần khoá vào 12:00 trưa Chủ nhật ngay cuối tuần đó. Sau khi khoá, tổ trưởng không sửa được điểm, nhận xét, "đã cập nhật" của tuần đó. Web báo trước một lần khi đăng nhập, và dòng trên bảng điểm luôn ghi giờ khoá.
- **Xin gia hạn**: ở tuần đã khoá, tổ trưởng bấm nút xin gia hạn. Mỗi lần xin bị **trừ 5 điểm** của học sinh là tổ trưởng (ghi vào tuần sổ đang mở). Admin duyệt (chọn số giờ gia hạn, mặc định 24 giờ) hoặc từ chối. Được duyệt thì tổ đó sửa lại được tuần đó đến hết hạn.
- Admin (tài khoản chính) vẫn sửa được sổ đã khoá.

## 4. Tổng hợp, Thống kê và nhận xét
- **Tổng hợp**: điểm theo Tuần / Tháng / Học kỳ / Cả năm; xếp hạng tổ; học sinh dưới 80; lớp trưởng, thầy, admin xem cả lớp, tổ trưởng chỉ xem tổ mình. Thầy và admin có nút **📸 Chụp ảnh** tạo "Phiếu theo dõi tuần". Trong hộp chụp ảnh (khi xem theo tuần) có nút **🔗 Tạo link xem**: tạo địa chỉ dạng `/view/tuanN` (N là số tuần) để gửi vào nhóm lớp. Ai mở link cũng xem được điểm, xếp hạng tổ, bạn dưới 80 và nhận xét của tuần đó trên điện thoại hay máy tính, không cần đăng nhập, số liệu tự cập nhật theo sổ. Link có hạn (chọn 1, 3, 7 hoặc 30 ngày), gia hạn hoặc dừng chia sẻ được bất cứ lúc nào; chưa tạo hoặc hết hạn thì trang báo "link chưa mở". Tổ chưa cập nhật điểm thì chưa được xếp hạng trên trang này.
- **Thống kê** (đang thử nghiệm): xem điểm theo khoảng tuần, tổ trưởng chỉ xem tổ mình.
- Có 3 loại nhận xét: (1) **nhận xét tuần của tổ** ở cuối bảng điểm tuần (tổ trưởng viết); (2) **nhận xét của tổ theo kỳ** (tháng/học kỳ/cả năm) trong Tổng hợp khi xem một tổ (tổ trưởng viết); (3) **nhận xét chung của lớp** theo kỳ trong Tổng hợp (lớp trưởng và admin viết).
- Cạnh các ô nhận xét có nút **✨ AI soạn nhận xét** (xem mục 9).

## 5. Trực nhật
- Mỗi tuần một tổ trực theo vòng xoay Tổ 1→2→3→4. Tuần bình thường: mỗi BÀN trực 1 ngày (thứ Hai đến thứ Sáu). Ngày dư thì xếp người trực bù, người đang trực bổ sung, hoặc một bàn của chính tổ đó trực lẻ (+8 điểm).
- Tổ trưởng cần **xác nhận xếp chỗ ngồi** (5 bàn x 2 người) thì web mới chia ngày trực. Thấy hộp xếp chỗ khi đăng nhập thì điền cho xong.
- Lịch trực do hệ thống TỰ XẾP theo bàn, không ai chọn tay người trực. Tổ trưởng chỉ cần xác nhận chỗ ngồi và thêm/bỏ trực bổ sung khi cần.
- **Chốt lịch trực**: tự động lúc **14:00 chiều Chủ nhật** trước tuần trực. Trước giờ chốt, tuần hiện "⏳ Tổ chờ: Tổ N" (còn thay đổi được); sau khi chốt hiện "🧹 Tổ N trực" và là lịch chính thức, không sửa nữa.
- Tab Trực nhật hiển thị tuần này và tuần sau (admin thấy 7 tuần). Có câu thông báo "Hôm nay / Ngày mai ai trực" để sao chép gửi nhóm lớp.
- Nghỉ lễ do lớp trưởng, lớp phó lao động hoặc admin đặt; hệ thống tự xếp lại. Người mất ngày vì nghỉ được xếp trực bù vào ngày dư sau đó; người đang trực bổ sung vẫn trực đủ số ngày.

## 6. Trực bổ sung
- Tổ trưởng xếp trực bổ sung cho học sinh trong tổ mình (chọn bạn và số ngày, tính từ hôm nay); lớp trưởng, lớp phó lao động và admin xếp cho mọi tổ và chọn được ngày bắt đầu. Xếp thêm cho cùng một bạn thì cộng dồn số ngày. Bạn được xếp trực bổ sung trực ngay tuần kế tiếp, mỗi ngày 1 người; quá 6 ngày thì dồn tiếp sang tuần sau.
- **Cả tổ trực bổ sung**: cả tổ cùng trực thêm, mỗi ngày 1 bàn.
- **Số ngày trực bổ sung chiếm trong tuần của tổ đang chờ**: nếu sau khi trừ đi vẫn còn từ 3 ngày trở lên cho tổ (vd 3 bạn trực bổ sung chiếm 3 ngày đầu) thì là **tuần chuẩn**: các bạn đó trực các ngày đầu, các bàn của tổ trực các ngày sau, KHÔNG +8 điểm, tính lượt vòng xoay (bàn chưa có ngày thì trực bù tuần sau). Nếu chỉ còn 1-2 ngày (vd 4 bạn) thì là **tuần trực bổ sung**: tổ dời sang tuần sau, cử đúng số bàn bằng số ngày còn lại vào trực và được +8 điểm.
- **Hai tuần liên tiếp không phải tuần thường**: nếu có 2 tuần liên tiếp không phải tuần thường (tuần trực bổ sung, cả tổ trực bổ sung, nghỉ cả tuần) thì tuần kế tiếp luôn là tuần chuẩn của tổ đến lượt, ngày dư vẫn có 1 bàn của tổ trực nhưng không +8 điểm, phần còn dư dồn tiếp sang sau, và tuần sau nữa là tổ kế tiếp.
- Tổ trưởng chỉ bỏ được mục do chính mình ghi. Mục đã bỏ vẫn khôi phục được nhờ lớp trưởng, lớp phó lao động hoặc admin; phần đã trực xong thì giữ lại.
- Lớp trưởng, lớp phó lao động và admin thấy ✍ tên người đã xếp mỗi khoản trực bổ sung (tổ trưởng không thấy phần này).
- Trực bổ sung KHÔNG làm tăng số lượt trực trong bộ đếm. Người đang hoặc vừa trực bổ sung không được trực lẻ +8 điểm.
- **Trực bổ sung tự động cho HS dưới 80 điểm**: học sinh dưới 80 điểm của tuần học N tự được xếp trực bổ sung 1 ngày ở tuần trực ngay sau, vào lúc chốt lịch (14:00 chiều Chủ nhật). Áp dụng từ tuần 3 trở đi (admin đổi được mốc). Không có nút xếp tay cho việc này. Khi admin duyệt gia hạn sổ cho tổ nào thì phần tự động chưa trực của tổ đó được huỷ và tính lại sau.

## 7. Học sinh và chuyển tổ
- **Thêm hoặc xoá học sinh**: chỉ admin, thầy, lớp trưởng (nút "+ Thêm học sinh" và "Xoá" ở bảng của tổ). Xoá sẽ hỏi lại chắc chắn và mất toàn bộ điểm của bạn đó. Không xoá được học sinh đang là tổ trưởng.
- **Chuyển học sinh sang tổ khác** (tổ trưởng): ở dòng của bạn đó bấm **Chuyển**, chọn tổ nhận, bấm Gửi yêu cầu. Chưa chuyển ngay: nút đổi thành "⏳ Chờ Tổ N", bấm lại để huỷ yêu cầu. Không chuyển được chính tổ trưởng.
- Tổ trưởng tổ nhận đăng nhập sẽ thấy hộp xác nhận: có thể chọn đổi lại 1 bạn trong tổ mình (không bắt buộc), rồi **Đồng ý nhận** hoặc **Từ chối**. Khi đồng ý, toàn bộ dữ liệu của bạn đó (điểm, lượt trực, trực bổ sung) được bàn giao qua; hai bạn đổi nhau thì ngồi đúng chỗ của nhau. Điểm các tuần cũ đi theo học sinh nên tổng điểm tổ trong các tuần đã qua cũng đổi theo.
- Tổ trưởng tổ gửi sau đó thấy thông báo kết quả và bấm **Đồng ý** để tắt.

## 8. Lịch sử trực nhật
- Thẻ "Lịch sử trực nhật" cho mọi tài khoản xem cả lớp: mỗi học sinh đã trực mấy lần, số lần trực lẻ, số lần trực bổ sung. Chọn một bạn ở ô "Tra cứu" để xem chi tiết từng tuần. Chỉ admin có nút −/+ chỉnh số hiển thị (không ảnh hưởng việc xếp lịch).

## 9. Trợ lý AI (khối lập phương xoay ở góc màn hình)
- Bấm khối lập phương để mở khung chat; kéo thanh tiêu đề để dời, kéo góc phải dưới để đổi cỡ, nút ◐ đổi độ trong suốt (để nhìn dữ liệu phía sau), nút ✕ ẩn về khối lập phương. Kéo khối lập phương để dời chỗ.
- Trợ lý đọc được dữ liệu trong phạm vi quyền của người hỏi: **tổ trưởng** thấy điểm, nhận xét của tổ mình; **lớp trưởng, thầy, admin** thấy điểm cả lớp. Lịch trực nhật, trực bổ sung và Lịch sử trực nhật thì cả lớp đều xem được. Trợ lý trả lời, tính toán đơn giản (trung bình, đếm, so sánh), nhận xét nhẹ và soạn nhận xét giúp. **Trợ lý chỉ đọc và soạn chữ, không tự sửa dữ liệu.**
- Hỏi đầy đủ thì trả lời chính xác hơn: nói rõ tuần nào, tổ nào, bạn nào (VD "Tuần 5 tổ mình ai dưới 80 điểm?"). Mặc định trợ lý xem tuần hiện tại và tuần trước; hỏi "cả năm / học kỳ / tháng / so sánh" thì xem tổng hợp nhiều tuần.
- **Soạn nhận xét**: bấm **✨ AI soạn nhận xét** cạnh ô nhận xét (nhận xét tuần của tổ, nhận xét tổ theo kỳ, nhận xét chung của lớp). AI điền bản nháp vào ô, người dùng đọc lại, sửa rồi tự bấm Lưu. AI không tự lưu.
- **Cá nhân hoá**: bấm "Cá nhân hoá" trong khung chat để đặt cách xưng hô, phong cách trả lời (ngắn gọn / chi tiết / thân mật) và ghi chú riêng. Đăng nhập bằng link nhanh thì không lưu được cá nhân hoá.
- **Cuộc mới** bắt đầu cuộc trò chuyện mới (cuộc cũ vẫn được lưu). Mọi cuộc trò chuyện được lưu lại trên máy chủ; admin có thể tải về. Bấm 👍/👎 dưới câu trả lời để đánh giá.
- Admin có thể **khoá trợ lý của từng tài khoản** (⚙️ Cài đặt → Người dùng trợ lý) nếu bị dùng sai hoặc lạm dụng. Tài khoản bị khoá thấy thông báo kèm lý do, không hỏi và không soạn nhận xét được cho đến khi admin mở khoá.
- Mỗi người có số câu hỏi tối đa mỗi ngày (tổ trưởng ít hơn lớp trưởng và thầy), hết thì mai có lại. Tổ trưởng dùng mô hình AI nhanh; lớp trưởng và thầy dùng mô hình mạnh hơn; admin chọn được giữa "Mạnh" và "Nhanh". Mô hình mạnh quá tải thì tự chuyển sang mô hình nhanh.
- Quyền riêng tư: mặc định tên học sinh được thay bằng mã trước khi gửi cho AI và đổi lại khi hiển thị.
- AI có thể sai, hãy kiểm tra lại số liệu quan trọng trên web trước khi dùng.

## 10. Đăng nhập nhanh
- Admin tạo link đăng nhập nhanh (có hạn dùng, thu hồi được). Vào bằng link thì không đổi được mật khẩu, không tạo link khác.
- **Mã đăng nhập thay mật khẩu** (tab Tài khoản, chỉ admin thấy): mỗi tài khoản có sẵn 1 **mã hằng ngày** (6 ký tự chữ, số, ký hiệu, tự đổi lúc 00:00, dùng được nhiều lần trong ngày). Gõ mã này vào đúng ô "Mật khẩu" ở màn hình đăng nhập bình thường (vẫn chọn đúng tài khoản) là vào được, không cần nhớ mật khẩu thật. Admin còn tạo được **mã tạm thời** riêng cho từng tài khoản khi cần: chọn "dùng 1 lần" (tự mất ngay sau khi dùng) hoặc "có hạn" (dùng lại được nhiều lần tới giờ admin chọn), thu hồi được bất cứ lúc nào. Đăng nhập bằng mã không đổi được mật khẩu thật của tài khoản (vẫn cần biết mật khẩu cũ để đổi).

## 11. Khi gặp sự cố
- Trang hiển thị cũ hoặc lỗi lạ: tải lại trang (Ctrl+F5, hoặc kéo xuống để làm mới trên điện thoại).
- Không sửa được sổ điểm: có thể sổ đã khoá, hãy xin gia hạn hoặc nhờ admin.
- Việc không có trong tài liệu này: nhờ admin.
