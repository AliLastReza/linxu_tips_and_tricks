# نکات و ترفندهای اوبونتو (Ubuntu)

<!-- vscode-markdown-toc -->

- [نکات](#)
- [ترفندها](#-1)
  - [چطور رمز کوتاه و ساده تو اوبونتو بذاریم.](#.)

<!-- vscode-markdown-toc-config
	numbering=false
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->

## <a name=''></a>نکات

## <a name='-1'></a>ترفندها

### <a name='.'></a>چطور رمز کوتاه و ساده تو اوبونتو بذاریم.

از دستور زیر در ترمینال استفاده کنید:

```bash
sudo passwd <user>
```

به جای `<user>` نام کاربری‌ای را قرار دهید که می‌خواهید رمز عبورش را تغییر دهید.

این دستور کار می‌کند زیرا `passwd` زمانی که با دسترسی روت (root) اجرا می‌شود، تمام بررسی‌های مربوط به طول یا پیچیدگی رمز عبور را نادیده می‌گیرد.

**هشدار:** اگر کاربر هدف دارای پوشه Home رمزگذاری شده باشد، این کار می‌تواند باعث بروز مشکل شود! ([نظرات رو بخونید](https://askubuntu.com/questions/180402/how-to-set-a-short-password-on-ubuntu#comment522410_180428))

منبع: https://askubuntu.com/a/180428
