# نکات و ترفندهای لینوکس
نکات و ترفندهای کلی لینوکس که تو اکثر یا همه توزیع ها وجود دارند اینجا گفته میشه. برای هر توزیع هم یه فایل یا پوشه ایجاد خواهد شد که نکات و ترفندهای همون توزیع در اون فایل یا پوشه گفته میشه.

## فایل‌ یا پوشه مربوط به هر توزیع

- [اوبونتو | Ubuntu](ubuntu_tips_and_tricks.md)

## ترفندها

### ترفندهای خط فرمان (Terminal و Bash)

#### اجرا یک دستور یا برنامه کاملا در پس زمینه از طریق خط فرمان

```bas
nohup command_or_program &> /dev/null &
```

مثال:

اجرا AppImage برنامه Postman

```bash
nohup /home/ali/apps/Postman/Postman &> /dev/null &
```

منبع: https://askubuntu.com/questions/106351/running-programs-in-the-background-from-terminal
