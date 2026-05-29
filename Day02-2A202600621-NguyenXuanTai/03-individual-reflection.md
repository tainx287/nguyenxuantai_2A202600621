# 03 — Individual Reflection

## Đóng góp của Nguyễn Xuân Tài trong nhóm

Dưới đây là bảng ghi nhận cụ thể những gì tôi đã thực hiện và đóng góp vào kết quả bài nộp chung của nhóm:

| Hoạt động | Tôi đã làm gì? | Kết quả / Ảnh hưởng |
|---|---|---|
| **Scan cá nhân** | Khảo sát 10 nỗi đau thuộc các lĩnh vực y tế, nông nghiệp, logistics, kế toán dịch vụ... | Giúp nhóm có nguồn candidate problems phong phú để thảo luận |
| **Pitch đề tài** | Pitch chi tiết đề tài chốt đơn đa kênh Social Commerce | Đề tài được nhóm đưa vào shortlist để thảo luận sâu |
| **Challenge bài** | Phản biện đề tài "Slack search" của các bạn về quyền bảo mật dữ liệu doanh nghiệp | Giúp nhóm loại bỏ các đề tài quá rộng, không khả thi trong buổi lab |
| **Workflow** | Vẽ chi tiết sơ đồ workflow trước/sau tối ưu hóa của quy trình chốt đơn | Nhóm dùng làm sơ đồ workflow chính thức cho bài nộp |
| **Research** | Tìm hiểu các tool Pancake, Haravan, Chatfuel, Slack AI để tìm khoảng trống tính năng | Xác định được hướng đi Chrome Extension kết hợp RAG Engine tối ưu nhất |
| **Rule / Workflow / Agent** | Lập luận chọn giải pháp mức độ Workflow thay vì Agent tự động hoàn toàn | Nhóm thống nhất được ranh giới an toàn (Human Boundary) kiểm duyệt |

## Bảng dùng AI trong reflection

Bảng ghi nhận thực tế cách tôi tương tác và sử dụng trợ lý AI hỗ trợ trong suốt bài làm Day 02:

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì |
|---|---|---|---|---|
| **Scan** | Gợi ý thêm các pain points thực tế theo lăng kính | Gợi ý được một số từ khóa ngành nông nghiệp sầu riêng, chành xe | Đưa ra các giải pháp quá rộng và mang tính lý thuyết | Bỏ các ý tưởng lý thuyết xa vời thực tế, thu hẹp vào y tế công và kế toán hộ kinh doanh |
| **Workflow** | Nhờ AI chuyển đổi mô tả luồng công việc thành sơ đồ ASCII | Giúp định dạng sơ đồ văn bản nhanh chóng | AI tự ý gộp bước soạn thảo và gửi đi, bỏ quên ranh giới con người kiểm duyệt | Tôi tách riêng bước "Duyệt & Gửi" làm ranh giới an toàn |
| **Research** | Tìm kiếm thông tin về các công cụ quản lý chat sẵn có | Tổng hợp nhanh các tính năng cốt lõi của Pancake, Haravan | Tự bịa ra các số liệu phần trăm tiết kiệm thời gian không nguồn | Lọc bỏ số liệu giải định của AI, chỉ giữ lại phân tích khoảng trống tính năng |
| **Problem Statement** | Nhờ AI phản biện các trường thông tin trong Problem Statement v0 | Chỉ ra được phần metric còn chung chung và thiếu định lượng | AI đề xuất chuyển hướng sang giải pháp Agent tự động quá sớm | Tôi giữ nguyên định hướng Workflow lai Hybrid an toàn |

## Bài học của Nguyễn Xuân Tài

- **Bài học về "Problem-first" vs. "Solution-first":** Có những lúc nhóm muốn ứng dụng các công nghệ AI phức tạp nhất như AI Agent tự động nói chuyện và lên đơn trực tiếp cho khách hàng. Tôi đã kéo nhóm về thực tế bằng cách chỉ ra rằng nếu AI tự gửi và báo sai giá/kho sẽ gây thiệt hại tài chính nghiêm trọng cho shop, do đó bắt buộc phải giữ bước duyệt thủ công của con người và tập trung tối ưu khâu soạn thảo trước.
- **Bài học về Lựa chọn Công nghệ phù hợp (Rule vs. Workflow vs. Agent):** Tôi nhận ra rằng Agent tự lập kế hoạch rất dễ bị lỗi lặp và không an toàn cho các shop online vừa và nhỏ. Mô hình Hybrid (AI soạn nháp, người duyệt gửi) thuộc mức độ Workflow Automation vừa đạt hiệu suất tốc độ vừa kiểm soát được rủi ro 100%.

Nếu làm lại:

```text
Nếu được làm lại từ đầu, tôi sẽ chủ động phỏng vấn trực tiếp 3-4 nhân viên trực chat thực tế tại các shop online để lấy số liệu thực tế về thời gian phản hồi trung bình (ART) thay vì tự ước lượng, giúp phần metric của Problem Statement thuyết phục hơn nữa.
```
