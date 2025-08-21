# Puter ↔ n8n Bridge (Frontend Runner)

این پروژه یک فایل HTML است که:
- متن ورودی را با GET از n8n دریافت می‌کند (Webhook A)
- با SDK رسمی Puter پردازش می‌کند
- نتیجه را با POST به n8n (Webhook B) می‌فرستد

## تنظیمات n8n
- Webhook A: خروجی JSON شبیه
```json
{ "message": "سلام" }
```
- Webhook B: ورودی JSON شبیه
```json
{ "reply": "..." }
```
