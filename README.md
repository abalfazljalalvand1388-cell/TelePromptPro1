# TelePrompt Pro — Android wrapper

این پروژه فایل HTML اصلی تله‌پرامپتر را داخل یک اپلیکیشن Android WebView اجرا می‌کند.

## ساخت APK با GitHub
1. محتویات این پوشه را در ریشه یک مخزن GitHub آپلود کن.
2. مطمئن شو فایل `.github/workflows/android.yml` در همان مسیر قرار دارد.
3. به زبانه **Actions** برو.
4. اجرای **Build TelePrompt Pro APK** را باز کن و منتظر تیک سبز بمان.
5. در بخش **Artifacts** فایل `TelePromptPro-debug-apk` را دانلود و ZIP را استخراج کن.
6. فایل `app-debug.apk` را روی گوشی نصب کن.

با هر push به شاخه main یا master هم workflow به‌طور خودکار اجرا می‌شود.

## نکته درباره فرمان صوتی
قابلیت‌های متنی و کنترل حرکت در WebView اجرا می‌شوند. پشتیبانی از Web Speech API در Android WebView به نسخه WebView و دستگاه وابسته است؛ بنابراین فرمان صوتی ممکن است روی بعضی گوشی‌ها کار نکند، حتی با اجازه میکروفون.
