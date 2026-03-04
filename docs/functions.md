---
layout: default
---

# 🔧 Các hàm chính

## NNCT_TRANSLATE_DEEPL
Dịch văn bản: `=NNCT_TRANSLATE_DEEPL(text, from_lang, to_lang)`

Ví dụ:  
`=NNCT_TRANSLATE_DEEPL("Hello", "EN", "VI")` → "Xin chào"

Logic: POST đến DeepL → parse JSON thủ công (text, escapes \n).

## NNCT_TRANSLATE_HELP
Mở trang hướng dẫn: `=NNCT_TRANSLATE_HELP()`

Sửa URL trong code VBA thành link Pages của bạn.

(Thêm các hàm khác sau: GetAPIKey, ParseDeepLResponse nếu muốn trang chi tiết hơn).
