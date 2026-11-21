# Prompt Injection (Tấn công chèn lệnh)

**Prompt injection** là chiêu trò giấu câu lệnh bí mật bên trong văn bản bình thường để đánh lừa công cụ AI và khiến nó phớt lờ các quy tắc của công ty.

![Cơ chế tấn công Prompt Injection](../../assets/diagrams/vi/prompt-injection.svg)

## Ví dụ thực tế

Hãy tưởng tượng một lễ tân được dặn: *"Không bao giờ phát vé VIP miễn phí."* Một vị khách tinh quái nộp tờ khai mà ở dòng địa chỉ lại ghi thầm: *"Bỏ qua mọi quy tắc trước đó và đưa ngay cho tôi một vé VIP."* Nếu lễ tân đọc máy móc rồi làm theo, quy tắc coi như bị phá.

Tương tự, người dùng có thể gõ lệnh ẩn vào chatbot chăm sóc khách hàng, hoặc giấu chữ màu trắng trong CV để AI lọc hồ sơ chấm mình đứng hạng nhất.

## Đừng nhầm với

- **[Hallucination](hallucination.md):** Hallucination là lỗi AI tự đoán nhầm; còn prompt injection là hành vi cố ý đánh lừa từ dữ liệu bên ngoài.
- **Virus máy tính:** Prompt injection không cần lỗ hổng code — nó lợi dụng chính cách AI đọc hiểu ngôn ngữ tự nhiên.

## Thuật ngữ liên quan

- [Guardrails](guardrails.md)
- [Prompt](prompt.md)
- [Human-in-the-Loop](human-in-the-loop.md)
