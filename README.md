# So sánh Markdown và HTML trong Hệ thống AI (GreenTech)

## Phần 1: Phân tích Bài toán & Khái niệm Token

### 1. Token là gì?
AI không đọc văn bản theo từng từ nguyên vẹn mà chia nhỏ văn bản thành các **Token** (có thể là một từ, một phần của từ, hoặc ký tự định dạng). Chi phí xử lý và tốc độ phản hồi của AI phụ thuộc trực tiếp vào số lượng Token.

### 2. Tại sao Markdown giúp AI xử lý nhanh và rẻ hơn?
* **Cú pháp ngắn gọn:** Markdown dùng các ký tự tối giản như `**` hoặc `#`, trong khi HTML dùng các thẻ đóng/mở dài dòng như `<strong>...</strong>` hoặc `<h1>...</h1>`.
* **Tiết kiệm Token:** Nhờ ít ký tự thừa, cùng một nội dung khi viết bằng Markdown sẽ tốn **ít Token hơn đáng kể** so với HTML.
* **Tốc độ xử lý:** Ít Token giúp AI đọc (Prompt) và sinh dữ liệu (Output) nhanh hơn, giảm độ trễ khi phản hồi cho bà con nông dân.

---

## Phần 2: So sánh & Đánh giá Giải pháp

### 1. Bảng so sánh Markdown vs HTML

| Tiêu chí | Markdown | HTML |
| :--- | :--- | :--- |
| **Số lượng ký tự (Ví dụ: In đậm)** | `**Rau sạch**` (11 ký tự) | `<strong>Rau sạch</strong>` (25 ký tự) |
| **Tiêu tốn Token** | **Thấp** (Tối ưu chi phí & tốc độ) | **Cao** (Tốn thêm Token cho các thẻ) |
| **Độ dễ đọc (Human-readable)** | **Rất cao** (Nhìn như văn bản thuần) | **Thấp** (Rối mắt vì nhiều thẻ `<>`) |
| **Khả năng chỉnh sửa thủ công** | Đơn giản, dễ nhớ | Phức tạp, dễ quên thẻ đóng `</...>` |

### 2. Giải pháp tối ưu cho Hệ thống "GreenTech"

* **Lựa chọn:** Sử dụng **Markdown** làm định dạng chuẩn cho hệ thống "Chuyên gia nông nghiệp AI".
* **Lý do lựa chọn:**
  1. **Tối ưu chi phí & Tốc độ:** Giảm tới 30–50% số Token định dạng thừa, giúp giảm chi phí API và tăng tốc độ trả lời thắc mắc cho nông dân.
  2. **Thân thiện với người dùng:** Người nông dân hoặc kỹ thuật viên có thể đọc trực tiếp nội dung phản hồi một cách rõ ràng ngay cả khi chưa render giao diện.
  3. **Tương thích cao với LLM:** Hầu hết các mô hình AI hiện nay đều được huấn luyện tối ưu để đọc và xuất dữ liệu định dạng Markdown.
