# Giới thiệu 

**Laboratory Information Management System** (viết tắt là **LIMS**) là *Hệ thống phần mềm quản lý thông tin phòng kiểm nghiệm* được xây dựng và phát triển bởi Viện nghiên cứu ứng dụng Khoa học và Công nghệ, Đại học Quy Nhơn với các chức năng chính bao gồm:

**Hệ thống**:
>
  - Quản lý nhân viên; chức vụ.
  - Quản lý khoa; phòng ban.
  - Quản lý người dùng; phân quyền chức năng.

**Danh mục**:
>
  - Quản lý khách hàng.
  - Quản lý các dịch vụ; tiêu chuẩn.
  - Quản lý hoạt chất/ biệt dược.

**Nghiệp vụ**: Quản lý quy trình làm việc và lưu trữ thông tin mẫu kiểm nghiệm:
>
  - Tiếp nhận hồ sơ
  - Dịch vụ kỹ thuật
  - Tiếp nhận và phân mẫu
  - Tổng hợp kết quả kiểm nghiệm
  - Duyệt kết quả kiểm nghiệm

**Cơ sở vật chất**: 
>
  - Quản lý thiết bị.
  - Quản lý hóa chất.
  - Quản lý dụng cụ thủy tinh.

**Báo cáo thống kê**: Tạo báo cáo mẫu kiểm nghiệm theo quý/ tháng…
## Lợi ích mang lại

Mục đích chính của QNLIMS là cải thiện hiệu quả và độ chính xác của phòng thí nghiệm bằng cách giảm các thao tác thủ công. Hệ thống LIMS sẽ thực hiện quản lý toàn bộ quy trình kiểm nghiệm ngày từ bước nhận mẫu kiểm nghiệm cho đến khi hoàn thành kiểm nghiệm. Do vậy quy trình kiểm nghiệm sẽ được nhất quán, chặt chẽ và đem lại những lợi ích như sau:

- Kết quả kiểm nghiệm chính xác hơn, ít sai sót hơn
- Kiểm soát được tiến độ kiểm nghiệm
- Giảm thời gian kiểm nghiệm và hạn chế các chi phí phát sinh
- Lưu trữ được dữ liệu kiểm nghiệm lâu dài
- Truy xuất dữ liệu nhanh chóng, bảo mật
- Quy trình kiểm nghiệm linh hoạt, đồng bộ

## Vai trò của các module trong hệ thống
![](https://i.imgur.com/hMubvlU.png "Vai trò của các module trong hệ thống")

### Module Tiếp nhận hồ sơ (Nhân viên tiếp nhận)
- Tiếp nhận hồ sơ từ khách hàng bao gồm mẫu lấy và mẫu gửi.
### Module Dịch vụ kỹ thuật (Nhân viên hành chính tổng hợp)
- Nhận hồ sơ từ bộ phận Tiếp nhận hồ sơ và phân nhóm chỉ tiêu cho các Khoa chuyên môn thực hiện.
- Tổng hợp kết quả từ các Khoa chuyên môn.
- Trình phiếu kết quả cho cho Lãnh đạo xét duyệt.
### Module Tiếp nhận và phân mẫu (Trưởng khoa chuyên môn)
- Nhận nhóm chỉ tiêu từ bộ phận Dịch vụ kỹ thuật và phân từng chỉ tiêu kiểm nghiệm cho từng Kiểm nghiệm viên thực hiện.
- Xác nhận kết quả tổng hợp từ Tổng hợp viên.
### Module Kết quả kiểm nghiệm (Kiểm nghiệm viên)
- Xem chỉ tiêu kiểm nghiệm cần thực hiện.
### Module Tổng hợp kết quả (Tổng hợp viên)
- Nhận kết quả từ các Kiểm nghiệm viên
- Kiểm tra và gửi kết quả cho Trưởng khoa chuyên môn thực hiện xét duyệt.
### Duyệt kết quả (Lãnh đạo)
- Lãnh đạo nhận kết quả từ bộ phận Dịch vụ kỹ thuật sau đó tiến hành xét duyệt.

## Một quy trình nghiệp vụ mẫu của QNLIMS

![](https://i.imgur.com/Cc9RxIe.png "Quy trình nghiệp vụ mẫu QNLIMS")

- **Bước 1**: Khách hàng giao mẫu kiểm nghiệm cho Bộ phận tiếp nhận mẫu -> Bộ phận tiếp nhận mẫu điền thông tin vào hệ thống và in biên bản tiếp nhận mẫu giao cho Khách hàng.
- **Bước 2**: Bộ phận tiếp nhận mẫu gửi thông tin hồ sơ mẫu kiểm nghiệm cho Phòng dịch vụ kỹ thuật.
- **Bước 3**: Phòng dịch vụ kỹ thuật tiếp nhận hồ sơ và tiến hành phân chỉ tiêu kiểm nghiệm cho từng Khoa chuyên môn.
- **Bước 4**: Trưởng Khoa chuyên môn nhận chỉ tiêu kiểm nghiệm và tiến hành phân công từng chỉ tiêu kiểm nghiệm cho các Kiểm nghiệm viên.
- **Bước 5**: Kiểm nghiệm viên sẽ kiểm nghiệm và cho ra kết quả.
- **Bước 6**: Tổng hợp viên thuộc khoa chuyên môn sẽ gặp các Kiểm nghiệm viên để tổng hợp kết quả -> sau đó gửi kết quả cho Trưởng khoa chuyên môn.
- **Bước 7**: Trưởng khoa chuyên môn duyệt các kết quả kiểm nghiệm: Nếu đạt yêu cầu chất lượng thì gửi lại cho phòng dịch vụ kỹ thuật, Nếu không đạt yêu cầu chất lượng thì cho kiểm nghiệm viên làm lại.
- **Bước 8**: Phòng dịch vụ kỹ thuật nhận kết quả từ Khoa chuyên môn -> nhập kết luận và in phiếu kết quả cho Giám đốc duyệt.
- **Bước 9**: Giám đốc duyệt phiếu kết quả: Nếu đạt yêu cầu thì ký tên và gửi trả lại cho Phòng dịch vụ kỹ thuật -> Phòng dịch vụ kỹ thuật trả cho Khách hàng. Nếu không đạt yêu cầu thì cho tiến hành làm lại theo quy trình.
