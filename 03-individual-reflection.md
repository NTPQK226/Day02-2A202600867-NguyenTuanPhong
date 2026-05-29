# Phase 7 — Individual Reflection (Nguyễn Tuấn Phong)

## Tôi đã tham gia vào phần nào?

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng |
|---|---|---|
| Scan cá nhân | Đưa ra 3 bài toán tập trung vào mảng học tập/hỗ trợ Lab. | Nhóm có nguồn candidate sát với trải nghiệm học viên. |
| Pitch Problem Card | Pitch bài toán "Giải thích logic & Debug (Vibe code chuẩn)". | Bài toán được cả nhóm thống nhất chọn làm Problem Statement chính. |
| Workflow nhóm | Hỗ trợ định nghĩa các bước trong Future Workflow, đặc biệt là phần "Human Boundary". | Tạo ra được ranh giới rõ ràng: AI chỉ gợi ý, sinh viên phải tự gõ code. |
| Problem Statement | Viết định nghĩa cho phần "Bottleneck" và "Boundary". | Làm rõ được rủi ro Prompt Injection và cách phòng tránh bằng Rule. |
| Decision | Bảo vệ quan điểm chọn mức "Workflow" thay vì "Agent" khi nhóm phân vân. | Nhóm chốt được giải pháp an toàn, khả thi để làm Prototype. |

## Bảng dùng AI trong reflection

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Problem Card | Nhờ AI (ChatGPT) rà soát lại lỗi logic trong các Problem cá nhân. | Giúp câu văn gãy gọn, chuyên nghiệp hơn. | AI tự động thêm các bước "dùng Tool X, Tool Y" vào quy trình hiện tại. | xóa bỏ các tool lạ, chỉ giữ lại hành vi thực tế là "copy ném vào ChatGPT". |
| Workflow | Dùng AI sinh mã Mermaid vẽ sơ đồ Before/After. | Vẽ rất nhanh và đẹp, đúng chuẩn cú pháp. | AI gộp bước "Đưa hint" và "Sinh viên sửa" vào làm một. | bắt AI tách ra vì đó là human boundary quan trọng nhất. |
| Rule / Workflow / Agent | Nhờ AI liệt kê rủi ro khi dùng Agent cho giáo dục. | Đưa ra được rủi ro về "ảo giác kiến thức". | AI khuyên nên dùng Agent để tăng tính tự động hóa. | chọn Workflow vì giáo dục cần sự kiểm soát, không cần tự động hóa hoàn toàn. |

## Reflection câu hỏi mở

- **Tôi học được gì khi nghe top 3 problems của các bạn khác?** Tôi nhận ra mỗi người có một "nỗi đau" cực kỳ đặc thù. Minh đau vì vận hành, Duy Anh đau vì chuyên môn hẹp. Việc scan rộng giúp mở mang tư duy rất nhiều.
- **Nhóm có lúc nào bị solution-first không?** Có, lúc đầu nhóm rất háo hức muốn biến Socratic Tutor thành một Agent tự chấm điểm, tự gửi mail cho giảng viên. May mắn là đã kịp phanh lại ở Phase 6.
- **Có thay đổi ý kiến sau khi bị challenge không?** Có. Ban đầu tôi nghĩ cài Prompt cấm xuất code là đủ. Nhưng sau khi Duy Anh challenge về Prompt Injection, tôi nhận ra cần tích hợp thêm Rule/Regex ở khâu output để an toàn 100%.
- **Đóng góp gì thật sự vào artifact cuối?** Ý tưởng cốt lõi của bài toán, định hình cấu trúc Socratic và thiết kế Human Boundary.
- **Điều khó nhất khi viết Problem Statement là gì?** Là việc phân biệt giữa Lagging Metric (điểm số cuối kỳ) và Leading Metric (tỷ lệ tương tác thành công với bot trong buổi học).
- **Nếu làm lại, sẽ challenge nhóm mạnh hơn ở điểm nào?** Tôi sẽ yêu cầu nhóm làm rõ hơn về việc "thu thập dữ liệu log lỗi thô" ở đâu để train hoặc làm RAG cho hệ thống.

