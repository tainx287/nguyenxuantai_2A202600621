# 01 — Individual Problem Scan

## Scan rộng

Dưới đây là bảng 10 vấn đề tôi đã scan từ trải nghiệm thực tế của bản thân:

| # | Lăng kính | Problem quan sát được | Ai đang đau? | Dấu hiệu thật |
|---|---|---|---|---|
| 1 | Lặp lại | Xếp hàng đóng viện phí và chờ nhận kết quả xét nghiệm | Bệnh nhân & Người nhà | Mất trung bình 2 - 3 tiếng di chuyển, chờ đợi |
| 2 | Tốn thời gian | Phân loại độ chín sầu riêng bằng cách gõ thanh tre | Chủ vựa đóng gói | Phụ thuộc thợ gõ sầu riêng, rủi ro đền hàng trăm triệu/xe |
| 3 | AI tốt hơn | Nhận xét học sinh cuối năm thủ công cho 40-50 học sinh | Giáo viên chủ nhiệm | Mất 20-30 tiếng cuối kỳ, mệt mỏi tinh thần |
| 4 | Tốn thời gian | Tìm nguồn xe/hàng ghép chiều về của chành xe liên tỉnh | Điều phối viên, lái xe | 70% xe chạy rỗng chiều về, lãng phí 40-50% xăng dầu |
| 5 | Lặp lại | Đào tạo menu & quy trình cho nhân viên part-time mới | Quản lý nhà hàng F&B | Tỷ lệ biến động nhân sự đạt 70-80% mỗi năm |
| 6 | AI tốt hơn | Phát hiện ùn ứ, mất cân bằng chuyền may mặc | Quản đốc phân xưởng | Năng suất hụt 15-20%, tốn chi phí tăng ca bù tiến độ |
| 7 | Lặp lại | Tính tiền điện nước & đối soát thanh toán phòng trọ | Chủ nhà trọ, quản lý | Mất 2-3 ngày đầu tháng để cộng dồn thủ công |
| 8 | Lặp lại | Khách bùng hẹn hoặc đến trễ giờ vàng tại Spa | Lễ tân, kỹ thuật viên | Tỷ lệ bùng lịch đạt 20-25%, trống phòng dịch vụ |
| 9 | Tốn thời gian | Nhập liệu hóa đơn giấy/ảnh chụp mờ cho hộ kinh doanh | Kế toán viên dịch vụ | Mất 5-7 phút/hóa đơn viết tay, dễ sai số liệu |
| 10 | AI tốt hơn | Cập nhật giá phòng & xe trống từ nhà cung cấp du lịch | Nhân viên điều hành tour | Mất 3-4 tiếng để chốt một lịch trình đơn giản |

## Top 3

Tôi lựa chọn Top 3 vấn đề có tính cấp thiết và khả năng giải quyết bằng AI cao nhất:

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Thanh toán & kết quả Y tế công | Quy trình rõ, nút thắt thanh toán và lấy kết quả chờ lâu | Khả năng tích hợp thời gian thực với hệ thống HIS cũ |
| 2 | Phân loại độ chín sầu riêng | Rủi ro kinh tế cao, thiếu thợ gõ lành nghề vào mùa vụ | Tiếng ồn môi trường vựa và độ dày vỏ sầu riêng |
| 3 | Trích xuất hóa đơn hộ kinh doanh | Quy định thuế mới bắt buộc làm sổ sách, số lượng nhập tay lớn | Việc xử lý hóa đơn viết tay bằng mực mờ, ảnh chụp lóa |

## Problem Card #1 — Thanh toán & kết quả Y tế công

**Problem 1 câu:**  
Bệnh nhân tại bệnh viện công Việt Nam mất trung bình 2-3 tiếng xếp hàng thủ công chỉ để đóng viện phí chỉ định và chờ nhận kết quả xét nghiệm bản giấy, gây quá tải sảnh chờ.

**Actor:**  
Bệnh nhân và Người nhà bệnh nhân đi khám chữa bệnh tại các bệnh viện công tuyến Trung ương.

**Thời điểm / bối cảnh:**  
Khung giờ cao điểm khám bệnh buổi sáng từ 6h00 đến 11h00 hằng ngày.

**Current workflow:**

```text
1. Xếp hàng đăng ký khám bệnh và nhận số khám.
2. Gặp bác sĩ lâm sàng khám sơ bộ và nhận phiếu chỉ định cận lâm sàng.
3. Mang phiếu chỉ định sang quầy thu viện phí xếp hàng đóng tiền phí xét nghiệm.
4. Di chuyển sang khu vực xét nghiệm, xếp hàng làm xét nghiệm.
5. Ngồi chờ tại sảnh để nhận kết quả xét nghiệm bản giấy tại quầy trả kết quả.
6. Cầm tập kết quả giấy quay lại phòng khám ban đầu, xếp hàng chờ gọi tên đọc kết quả và nhận đơn.
```


**Bottleneck:**  
Khâu xếp hàng đóng viện phí (chờ 45-60 phút) và khâu chờ lấy kết quả xét nghiệm bản giấy tại quầy (chờ 60-90 phút).

**Impact:**  
Thời gian khám bệnh kéo dài trung bình 4-5 tiếng cho một ca. Sảnh chờ quá tải gây rủi ro lây nhiễm chéo cao và áp lực đè nặng lên nhân viên hành chính.

**Success metric:**  
Giảm tổng thời gian chờ đóng tiền và nhận kết quả từ 120 phút xuống dưới 15 phút.

**Non-AI alternative:**  
Đặt các Kiosk tự động đóng tiền bằng thẻ ngân hàng hoặc cài app riêng của bệnh viện. (Hạn chế: Người lớn tuổi khó dùng app; kiosk tự động vẫn yêu cầu xếp hàng vật lý).

**AI hypothesis:**  
Hệ thống AI Workflow Automation tự động sinh mã QR động gửi qua Zalo/SMS cho bệnh nhân thanh toán tại chỗ qua Mobile Banking. Sau khi đóng tiền, AI gợi ý phòng lab vắng nhất để xét nghiệm, dự báo thời gian có kết quả động và tự động gửi file kết quả số hóa qua Zalo kèm số phòng đọc kết quả khi có kết quả trên hệ thống.

**Quick gut:**  
Workflow.

### Draft current workflow

```text
CURRENT STATE — 270 phút

[Bác sĩ in chỉ định]
→ [Xếp hàng đóng viện phí: 60'] <-- bottleneck
→ [Xếp hàng lấy mẫu: 20']
→ [Chờ kết quả giấy: 90'] <-- bottleneck
→ [Nhận kết quả tại quầy: 10']
→ [Xếp hàng phòng đọc: 30']
```

### Draft future workflow

```text
FUTURE STATE — 85 phút

[AI sinh QR động: 1']
→ [Quét mã thanh toán tại chỗ: 2']
→ [AI gợi ý phòng lab vắng nhất & lấy mẫu: 20']
→ [Bệnh nhân đi lại tự do, AI báo kết quả số hóa qua Zalo: 1']
→ [AI chỉ định phòng đọc & xếp hàng phòng đọc: 30']

Fallback: Zalo lỗi → Bệnh nhân nhận kết quả giấy tại quầy như cũ.
```

## Problem Cards #2 và #3 — tóm tắt

| Card | Actor | Bottleneck | Metric | Quick gut | Vì sao chưa chọn làm #1 |
|---|---|---|---|---|---|
| **Phân loại độ chín sầu riêng** | Chủ vựa đóng gói | Thợ gõ sầu riêng thủ công dễ bị ù tai, phân loại sai | Độ chính xác đạt >95%, giảm tỷ lệ container bị trả về <2% | AI Model | Khó làm thử nghiệm nhanh (pilot) trực tiếp trong thời gian lab hơn y tế |
| **Trích xuất hóa đơn hộ kinh doanh** | Kế toán dịch vụ | Nhập tay thông tin từ hóa đơn giấy/ảnh chụp mờ mất 5-7 phút/tờ | Giảm xuống <20 giây/hóa đơn, độ chính xác >98% | Workflow + AI Model | Tác động xã hội diện rộng và mức độ ùn tắc cấp bách của y tế công cao hơn |
