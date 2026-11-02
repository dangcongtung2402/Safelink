## Development Workflow
1. Developer nhận task ở đâu?
Developer thường nhận công việc thông qua các công cụ quản lý dự án như Jira, GitHub Issues hoặc Azure DevOps.

Mỗi task thường có mô tả yêu cầu, độ ưu tiên, người phụ trách và tiêu chí hoàn thành.

Trong SafeLink: Chúng ta dùng GitHub Issues.

Tiếng Anh:
Developers receive tasks from GitHub Issues, where requirements and acceptance criteria are documented.

2. Vì sao phải tạo branch riêng?
Branch giúp lập trình viên phát triển một tính năng hoặc sửa lỗi mà không trực tiếp ảnh hưởng đến nhánh main.

Ví dụ:
- main: Code chính, đã được tích hợp.
- feature/login: Phát triển đăng nhập.
- fix/upload-error: Sửa lỗi tải ảnh.
Tiếng Anh:
Developers create separate branches to work on features or bug fixes without directly changing the main branch.

3. Pull Request dùng để làm gì?
Pull Request (PR) là yêu cầu tích hợp những thay đổi từ một branch sang branch khác.

PR cho phép các thành viên:
- Xem những dòng code đã thay đổi.
- Nhận xét và yêu cầu chỉnh sửa.
- Kiểm tra kết quả test.
- Thảo luận trước khi merge.
Tiếng Anh:
A Pull Request allows developers to review, discuss, and test code changes before merging them into the main branch.

4. Khi nào được merge vào main?
Chỉ nên merge khi code đáp ứng các điều kiện của dự án, chẳng hạn:
- Đã hoàn thành yêu cầu của task.
- Code đã được review và phê duyệt theo quy định.
- Các bài kiểm thử bắt buộc đều thành công.
- Không có vấn đề bảo mật nghiêm trọng chưa xử lý.
- Không còn xung đột cần giải quyết.
Tiếng Anh:
Code can be merged into the main branch after it meets the requirements, passes the required tests, and receives approval.