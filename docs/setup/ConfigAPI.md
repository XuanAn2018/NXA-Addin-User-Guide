---
layout: default
---

# ⚙️ Cấu hình API Key DeepL

Hàm quản lý key: `NNCT_ZConfigAPI_DEEPL(apiKey)`

## Tổng hợp cách dùng

| Trường hợp                  | Mô tả                              | Công thức gõ vào ô Excel                  | Kết quả mong đợi                              |
|-----------------------------|------------------------------------|-------------------------------------------|-----------------------------------------------|
| Xem key hiện tại            | Hiển thị key masked (ẩn giữa)      | `=NNCT_ZConfigAPI_DEEPL()`               | "Current API Key: ******************abcd"     |
| Lưu key mới                 | Validate >20 ký tự → lưu registry  | `=NNCT_ZConfigAPI_DEEPL("your_key")`     | "API Key saved: ******************wxyz"       |
| Xóa key                     | Xóa registry nếu tồn tại           | `=NNCT_ZConfigAPI_DEEPL("DEL")`          | "API Key has been successfully deleted."      |

### Cách lấy key DeepL
1. Vào https://www.deepl.com/pro-api → Đăng ký Free.  
2. Copy key → gõ công thức lưu ở trên.  
3. Nếu lần đầu: Tự hỏi InputBox khi dịch.

{: .warning }
Key chỉ lưu local máy này. Không chia sẻ file Excel.

Xem thêm: [Hàm dịch chính](functions.md)
