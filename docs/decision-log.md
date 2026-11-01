# Decision Log — Game "Đi chùa online"

> Ghi lại quyết định, ý tưởng chưa dùng, câu hỏi mở và nghiên cứu, làm nguồn cho bản đặc tả sau này.
> Định hướng hiện tại: xem [product-brief.md](product-brief.md).

---

## A. Quyết định đã chốt

| Ngày | Quyết định | Lý do |
|---|---|---|
| 2026-11-01 | Dùng **2 loại điểm**: công đức và Phật pháp | Phân tách "hành động" và "tu học", tạo vòng lặp có chiều sâu |
| 2026-11-01 | Công đức dùng để mua đồ cúng, bốc quẻ, mở sự kiện với khách hành hương | Theo ý tưởng của chủ dự án |
| 2026-11-01 | Phật pháp dùng để giải quẻ (càng cao càng chi tiết), mở sự kiện với tăng ni | Theo ý tưởng của chủ dự án |
| 2026-11-01 | Phật pháp là mức tích lũy, không bị trừ khi dùng; đạt mốc thì mở nội dung | Nếu tiêu điểm thì điểm tụt và lời giải quẻ lại kém chi tiết đi |
| 2026-11-01 | Bản đầu có tụng kinh ở mức đơn giản | Nếu không, bản đầu không có cách kiếm điểm Phật pháp |
| 2026-11-01 | Điểm công đức tích lũy cả khi offline | Theo ý tưởng của chủ dự án |
| 2026-11-01 | "Phước đức" và "công đức" là một loại điểm, thống nhất gọi là "công đức" | Chủ dự án xác nhận |
| 2026-11-01 | Cúng dường lỗ điểm ngay, nhưng được tăng tốc kiếm công đức trong một khoảng thời gian | Giải quyết việc vừa "kiếm nhanh hơn" vừa "tiêu nhiều hơn kiếm về"; ví dụ cúng 100 nhận lại 60, x2 trong 10 phút (số minh họa) |
| 2026-11-01 | Phạm vi bản đầu gồm 7 trải nghiệm: nén hương làm đồng hồ, tụng kinh gõ theo nhịp, sổ quẻ, nhiệm vụ vui, cúng dường có tăng tốc, công đức trùng tu, bộ mõ và hiệu ứng chữ | Chủ dự án đồng ý; đây là các ý làm chặt vòng lặp chính và tạo cá tính |
| 2026-11-01 | Nếu quá sức thì bỏ công đức trùng tu trước, rồi đến bộ mõ và hiệu ứng chữ | Trùng tu tốn công vẽ; năm ý còn lại là cốt lõi |
| 2026-11-01 | Mỗi ngày có vài nén hương miễn phí | Người chơi luôn gõ mõ được, kể cả khi hết công đức |
| 2026-11-01 | Rủi ro trong nhiệm vụ chỉ mất phần thưởng, không trừ điểm đang có | Giữ nguyên tắc nhẹ và thư giãn |
| 2026-11-01 | Lộ trình sau bản đầu: lịch âm, hồi hướng, check-in, hai nhánh sự kiện, ghi việc tốt | Chủ dự án đồng ý |
| 2026-11-01 | Gác lại Chùa chung, bảng xếp hạng, cốt truyện phiêu lưu, cozy game đầy đủ | Tốn công hoặc dễ khiến người chơi ngại tiêu điểm |
| 2026-11-01 | Không dùng tiền thật cho cúng dường, không đặt cược công đức | Tránh tranh cãi đạo đức, pháp lý và cảm giác cờ bạc |
| 2026-11-01 | Chỉ gõ mõ trong lúc thắp hương và tụng kinh | Theo ý tưởng của chủ dự án |
| 2026-11-01 | Người chơi tùy chỉnh được chữ "Công đức +1" | Tăng cá tính, dễ lan truyền (bài học từ mõ điện tử) |

---

## B. Phần chưa dùng — để đặc tả sau

### B1. Cơ chế cần đặc tả chi tiết
- **Công thức tích lũy offline:** tốc độ, trần tối đa, cách tính khi người chơi không mở app lâu.
- **Tỷ lệ cân bằng kinh tế:** số điểm kiếm được so với giá hoa quả, hương, hiện vật và quẻ.
- **Hệ thống cấp bậc:** ví dụ Phật tử → Cư sĩ → "Đại gia chùa", mốc điểm và phần thưởng.
- **Danh mục vật phẩm cúng:** hoa, quả, hương, hiện vật và hiệu ứng của từng loại.
- **Bộ quẻ:** số lượng quẻ, cấu trúc lời giải theo nhiều cấp chi tiết, giới hạn bốc mỗi ngày, tính sưu tập.
- **Nhiệm vụ vui:** độ khó, phần thưởng và kịch bản thất bại vui của từng nhiệm vụ, ví dụ quét xong gió thổi lá bay lại, tìm nhầm dép của khách, bê ba mâm cùng lúc dễ đổ, bị chen hàng thì nhịn hay đôi co.
- **Nén hương:** thời gian cháy, số nén miễn phí mỗi ngày, các loại hương tốt hơn (hương trầm cháy lâu hơn).
- **Tụng kinh gõ theo nhịp:** độ khó, cách chấm nhịp, lượng Phật pháp nhận được.
- **Sổ quẻ:** số cấp lời giải và các mốc Phật pháp tương ứng.
- **Cúng dường có tăng tốc:** tỷ lệ lỗ, hệ số và thời gian tăng tốc.
- **Công đức trùng tu:** các hạng mục (mái, sân, ao sen, tháp chuông) và số trạng thái cần vẽ của chùa.
- **Bộ mõ và hiệu ứng chữ:** các loại mõ (tre, gỗ mít, gỗ trắc), âm thanh, kiểu chữ, màu.
- **Nội dung tụng kinh, niệm Phật, sám hối, pháp thoại:** nguồn nội dung, độ dài, âm thanh, bản quyền.
- **Sự kiện với khách hành hương** (tiêu công đức): loại sự kiện, quy mô, tần suất.
- **Sự kiện với tăng lữ, thầy chùa, ni cô** (đạt mốc Phật pháp): loại sự kiện, cách thể hiện nhân vật, mức độ nhạy cảm.
- **Check-in và sổ hành hương:** dùng GPS trước, thêm QR ở chùa hợp tác sau. Lần đầu đến một chùa thưởng nhiều Phật pháp, các lần sau thưởng ít và tối đa một lần mỗi ngày. Mỗi chùa có một con dấu, ngày rằm và lễ lớn có dấu riêng. Check-in xong mở một đoạn giới thiệu ngắn về chùa. Đây là phần cộng thêm, không phải điều kiện để mở nội dung chính.
- **Hồi hướng:** tặng công đức cho người thân kèm thiệp để gửi.
- **Lịch âm:** nội dung riêng cho mùng 1, rằm, Tết.
- **Ghi một việc tốt mỗi ngày:** người chơi tự ghi, nhận chút công đức.

### B2. Ý tưởng đã gợi ý nhưng chưa chọn
- **Idle/Clicker "tích đức":** đã được hấp thụ một phần vào định hướng hiện tại.
- **Simulator "một ngày đi chùa":** gửi xe, mua đồ, xếp hàng, ăn chè cổng chùa, các tình huống hài hước.
- **Adventure/giải đố:** chùa cổ có bí ẩn, các NPC như sư thầy, cụ bà bán hoa, chú tiểu.
- **Social "Chùa chung":** nhiều người chơi cùng thắp hương, treo nguyện ước, sự kiện Tết và rằm. Cần backend và kiểm duyệt.
- **Cozy game:** quét sân, chăm vườn, tiếng mưa, thiền ngắn.
- **Chia sẻ quẻ lên mạng xã hội.**
- **Mô hình quản lý chùa kiểu tycoon** (như "Trụ Trì Online"): chưa đưa vào.
- **Hoạt động kiếm công đức khác:** nhổ cỏ, tưới cây, thay nước và cắm hoa, rửa bát sau bữa cơm chùa, cho cá ăn, gói bánh chưng dịp Tết, chỉ đường cho khách, tìm trẻ lạc, trả lại ví, nhường chỗ khi xếp hàng, nhặt rác đường lên chùa, phát cơm từ thiện, trồng cây quanh chùa.
- **Hoạt động tiêu công đức khác:** dụng cụ nhiệm vụ (chổi xịn, đèn pin), nhờ chú tiểu trông hộ để tăng trần offline, bốc thêm quẻ trong ngày, trồng cây lưu niệm, trang phục đi chùa, mời cơm chay hoặc chè, mua nước cho khách leo núi, thuê xe đưa cụ đi lễ, thả đèn hoa đăng, treo lời nguyện (câu chữ cố định), thỉnh chuông cầu an, vé gửi xe, chụp ảnh check-in.
- **Trò đùa xuyên suốt về đôi dép:** dép của thầy lạc nhiều nơi, người chơi sưu tập các đôi lạ.

### B3. Chưa quyết định
- Nền tảng: web hay mobile.
- Đối tượng chính: Gen Z, người đi làm hay người lớn tuổi.
- Phong cách hình ảnh và âm thanh.
- Mô hình kiếm tiền: tạm nghiêng về bán đồ trang trí và hiệu ứng âm thanh, không đổi tiền thật lấy cúng dường.
- Có cần tài khoản và đồng bộ đám mây không (cần cho tích lũy offline chính xác).
- Ngôn ngữ: chỉ tiếng Việt hay có thêm ngôn ngữ khác.

---

## C. Điểm cần làm rõ trong ý tưởng gốc
1. **Gõ mõ khi tụng kinh:** brief hiện ghi gõ mõ khi thắp hương cộng công đức, gõ đúng nhịp khi tụng kinh cộng Phật pháp. Cần xác nhận gõ mõ khi tụng kinh có cộng thêm công đức không.
2. **"Mở sự kiện":** chưa rõ người chơi tự tổ chức sự kiện, hay tham gia sự kiện do game tạo, hay là mở khóa sự kiện.
3. **"Khách hành hương" và "tăng lữ":** đây là NPC hay là người chơi khác. Nếu là người chơi thì cần tính năng xã hội.
4. **Điểm "tăng dần" khi offline:** là tự động chạy nền hay là phần thưởng khi quay lại.

---

## D. Rủi ro và lưu ý
- **Nhạy cảm tôn giáo:** giữ giọng vui nhưng tôn trọng, tránh trêu giáo lý và hình tượng thiêng liêng. Nên cân nhắc nhờ người hiểu Phật giáo xem lại nội dung.
- **Không dùng tiền thật cho cúng dường:** tránh tranh cãi và quy định, đặc biệt nếu có yếu tố ngẫu nhiên như bốc quẻ.
- **Nội dung "giải quẻ" và "pháp thoại":** cần ghi rõ là mang tính giải trí. Cần kiểm tra bản quyền cho kinh, bài giảng và âm thanh.
- **Vùng xám pháp lý ở Trung Quốc:** các app mõ điện tử hoạt động trong vùng xám. Nếu sau này mở rộng thị trường thì phải xem lại.
- **Chữ tùy chỉnh:** người chơi có thể gõ nội dung phản cảm rồi chụp màn hình trong cảnh chùa. Cần lọc từ, hoặc không cho chữ tùy chỉnh xuất hiện trên ảnh chia sẻ.
- **Tên điểm:** trong Phật giáo, "công đức" và "phước đức" có phân biệt. Game tạm dùng một tên vì quen thuộc, nên nhờ người am hiểu xem lại.
- **Bảng vinh danh theo điểm cúng:** dễ bị xem là châm biếm việc khoe của ở chùa. Nếu sau này có bảng xếp hạng, nên tính theo tổng điểm đã tích lũy, không theo số điểm đang có.
- **Phóng sinh:** chưa nên đưa vào game vì đang gây tranh cãi về môi trường.
- **Check-in:** chỉ xin quyền vị trí khi người chơi bấm check-in, chỉ lưu tên chùa, kiểm tra quy định về dữ liệu cá nhân trước khi ra mắt. Không khuyến khích dùng điện thoại hoặc chụp ảnh trong chính điện. Phần giới thiệu chùa thật phải trung lập, có cách để chùa yêu cầu sửa hoặc gỡ. Phần thưởng chỉ nằm trong game, không đổi quà thật. GPS có thể bị giả nên không gắn với giải thưởng thật. Người ở xa chùa không được thua thiệt quá nhiều.

---

## E. Nghiên cứu đối thủ (2026-11-01)
Nguồn là kết quả tìm kiếm web, chưa kiểm chứng từng sản phẩm. Số liệu chưa chắc đủ ngày tháng.

- **Việt Nam:** app [Đi Chùa Online](https://apps.apple.com/us/app/-/id6747811325) (thắp hương, cầu an, tụng kinh, pháp thoại, ít đánh giá); game [Trụ Trì Online](https://fptshop.com.vn/tin-tuc/giai-tri/tru-tri-online-171970) (quản lý chùa); website Chùa Online có nút "Burn Incense" ([Saigoneer](https://saigoneer.com/saigon-culture/13801-for-vietnam-s-busy-buddhists,-spiritual-teaching-is-just-a-click-away-with-online-temples)). Chưa thấy sản phẩm nào có xin quẻ kèm nhiều lớp điểm.
- **Trung Quốc:** các app mõ điện tử ("Công đức +1", tùy chỉnh chữ, bảng xếp hạng bạn bè, bán âm thanh) lan rộng trong giới trẻ ([Sixth Tone](https://www.sixthtone.com/news/1011740/young-chinese-are-still-seeking-serenity-—-now-through-digital-fish), [Daoinsights](https://daoinsights.com/news/muyu-becomes-chinese-gen-zs-new-obsession-for-relieving-stress/)). App [一炷香](https://mwm.ai/apps/app/6443640433) cho chọn số nhang và thời gian cháy.
- **Ấn Độ, Nhật, Hồng Kông, Đài Loan:** [Little Ganesha Virtual Temple](https://apps.apple.com/us/app/-/id1398925825), [Sri Mandir](https://techcrunch.com/2024/09/09/sri-mandir-is-on-a-quest-to-digitize-indias-devotional-journey/), [app tích điểm đi chùa của Nhật](https://soranews24.com/2022/06/07/earn-points-by-visiting-temples-throughout-japan-with-buddhist-sects-upcoming-app/amp/), [nghiên cứu gamification tôn giáo ở Đài Loan](https://bjocs.site/index.php/bjocs/article/view/189/229).

**Bài học:**
1. Vòng lặp một hành động một phản hồi là đủ hấp dẫn.
2. Bán cảm xúc, không bán tín ngưỡng.
3. Tùy biến và so sánh với bạn bè giúp lan truyền.
4. Kiếm tiền bằng đồ trang trí và âm thanh.
5. Ở Việt Nam còn khoảng trống cho game vui về trải nghiệm đi chùa đời thường.
