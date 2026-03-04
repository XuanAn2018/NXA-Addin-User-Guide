---
layout: default
---

# 🚀 Addin-DeepL – Dịch văn bản bằng DeepL trong Excel

Add-in VBA tích hợp DeepL API (Free 500k chars/tháng hoặc Pro).  
Key lưu local registry (không trong file Excel).  
Endpoint: `https://api-free.deepl.com/v2/translate` (sửa code nếu Pro).

## Tổng hợp cách dùng chính

| 🚀 Công thức gõ vào ô Excel                        | 📌 Mô tả                                      | 🎯 Kết quả mong đợi                           |
|----------------------------------------------------|-----------------------------------------------|-----------------------------------------------|
| `=NNCT_TRANSLATE_DEEPL(A1,"auto","VI")`           | Dịch ô A1 (tự động nguồn → tiếng Việt)        | Văn bản dịch sạch sẽ                          |
| `=NNCT_TRANSLATE_DEEPL(A1,"EN","VI")`             | Dịch từ Anh → Việt                            | Văn bản dịch                                  |
| `=NNCT_ZConfigAPI_DEEPL()`                        | Xem API key hiện tại (masked)                 | "Current API Key: ******************abcd"     |
| `=NNCT_ZConfigAPI_DEEPL("your_key")`              | Lưu key mới                                   | "API Key saved: ******************wxyz"       |
| `=NNCT_ZConfigAPI_DEEPL("DEL")`                   | Xóa key                                       | "API Key has been successfully deleted."      |
| `=NNCT_TRANSLATE_HELP()`                          | Mở trang hướng dẫn này                        | Mở browser đến trang này                      |

### Lưu ý
- Key lưu tại `HKEY_CURRENT_USER\Software\MyExcelTools\DeepL\APIKey`.  
- Nếu chưa có key: Hàm dịch tự hỏi InputBox.  
- Xem chi tiết: [Cấu hình API Key](setup/ConfigAPI.html) | [Các hàm khác](functions.md)

Cập nhật: Tháng 3/2026 – Chí Công
