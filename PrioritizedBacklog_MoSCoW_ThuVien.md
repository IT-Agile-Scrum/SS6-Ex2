# SS6-Ex2: Xây dựng Product Backlog có thứ tự bằng MoSCoW

## 1. Cách phân loại

Tôi dùng MoSCoW theo giá trị cốt lõi của bản MVP, mức độ phụ thuộc và khả năng xử lý tạm thời. Tôi cố giữ nhóm Must ở khoảng 60% năng lực Release 1.

| Mục | Hạng mục | Điểm | Nhóm | Lý do ngắn gọn |
|---:|---|---:|---|---|
| 1 | Đăng nhập/đăng ký tài khoản độc giả | 2 | **Must** | Cần biết ai đang mượn sách và lưu đúng lịch sử của người đó. |
| 2 | Tìm kiếm sách theo tên/tác giả | 2 | **Must** | Người dùng phải tìm được sách thì mới sử dụng được hệ thống. |
| 3 | Mượn sách online, có giới hạn số sách | 3 | **Must** | Đây là chức năng chính của hệ thống mượn sách. |
| 4 | Gia hạn mượn sách online | 1 | **Should** | Có ích nhưng giai đoạn đầu có thể gia hạn tại quầy. |
| 5 | Đặt trước sách khi hết, kèm thông báo | 2 | **Must** | Giúp người đọc tiếp tục sử dụng dịch vụ khi sách đang hết. |
| 6 | Đánh giá và bình luận sách | 2 | **Could** | Có giá trị tham khảo nhưng không cần để MVP hoạt động. |
| 7 | Gợi ý sách theo sở thích cá nhân | 3 | **Won't this time** | Tính năng nâng cao, có thể làm sau khi có dữ liệu sử dụng. |
| 8 | Email khi sắp đến hạn trả sách | 1 | **Should** | Có thể nhắc tại quầy hoặc trên hệ thống ở bản đầu. |
| 9 | Xem lịch sử mượn sách | 1 | **Should** | Hữu ích cho người dùng nhưng chưa chặn luồng mượn sách. |
| 10 | Thủ thư quản lý kho sách | 3 | **Must** | Không có dữ liệu kho chính xác thì người dùng không biết sách còn hay hết. |
| 11 | Chat trực tiếp với thủ thư | 3 | **Could** | Có thể liên hệ thủ thư bằng điện thoại hoặc email trong thời gian đầu. |
| 12 | Đăng nhập bằng Google/Facebook | 2 | **Won't this time** | Có thể dùng tài khoản thư viện; đăng nhập mạng xã hội là tiện ích thêm. |

## 2. Tổng điểm nhóm Must

Nhóm Must gồm các mục **1, 2, 3, 5 và 10**:

`2 + 2 + 3 + 2 + 3 = 12 điểm`

Năng lực Release 1 là khoảng 20 điểm, nên Must chiếm `12/20 = 60%`. Đây là đúng mức mục tiêu. Các nhóm Should và Could là vùng đệm nếu nhóm còn thời gian; nhóm Won't vẫn được giữ trong backlog cho Release sau.

## 3. Product Backlog có thứ tự

| Thứ tự | Mục | Hạng mục | Nhóm | Điểm |
|---:|---:|---|---|---:|
| 1 | 1 | Đăng nhập/đăng ký tài khoản độc giả | Must | 2 |
| 2 | 10 | Thủ thư quản lý kho sách | Must | 3 |
| 3 | 2 | Tìm kiếm sách theo tên/tác giả | Must | 2 |
| 4 | 3 | Mượn sách online, có giới hạn số sách | Must | 3 |
| 5 | 5 | Đặt trước sách khi hết, kèm thông báo | Must | 2 |
| 6 | 8 | Email khi sắp đến hạn trả sách | Should | 1 |
| 7 | 9 | Xem lịch sử mượn sách | Should | 1 |
| 8 | 4 | Gia hạn mượn sách online | Should | 1 |
| 9 | 6 | Đánh giá và bình luận sách | Could | 2 |
| 10 | 11 | Chat trực tiếp với thủ thư | Could | 3 |
| 11 | 7 | Gợi ý sách theo sở thích cá nhân | Won't | 3 |
| 12 | 12 | Đăng nhập bằng Google/Facebook | Won't | 2 |

Mục 1 đứng trước các mục cần biết danh tính người dùng. Mục 10 đứng trước mục 2, 3 và 5 vì thủ thư cần quản lý dữ liệu sách. Mục 3 đứng trước mục 5 vì phải có luồng mượn sách cơ bản trước khi đặt trước sách hết hàng.

## 4. Tự phản biện

Một người khác có thể xếp mục 8 “Thông báo email khi sắp đến hạn” vào Must vì nó giúp giảm sách trả muộn. Tuy nhiên, trong MVP vẫn có thể nhắc trên hệ thống hoặc tại quầy nên tôi để Should. Mục 11 “Chat với thủ thư” cũng có thể được xem là Should nếu thư viện ít nhân viên trực điện thoại. Tôi để Could vì hệ thống vẫn có thể hoạt động bằng email hoặc số điện thoại. Mục 12 có thể là Should để đăng nhập nhanh hơn, nhưng tài khoản thư viện đã đủ cho phiên bản đầu.
