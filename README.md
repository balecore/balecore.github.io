# 🚀 Bale Core 
**کتابخانه مدرن ساخت ربات‌های پیام‌رسان برای پلتفرم بله**  
[![نسخه](https://img.shields.io/badge/نسخه-1.0.0_alpha-blue)](https://github.com/balecore)
[![لایسنس](https://img.shields.io/badge/لایسنس-MIT-green)](LICENSE)
[![پایتون](https://img.shields.io/badge/پایتون-3.8%2B-blue)](https://python.org)

<div align="center">
  <img src="logo.png" width="200" alt="لوگوی Bale Core">
</div>

## 🌟 ویژگی‌های کلیدی
- ✅ ساخت ربات‌های پیشرفته با کمترین کدنویسی
- ✅ پشتیبانی از مفاهیم **آسنکرون** (Async/Await)
- ✅ سیستم مدیریت رویدادهای ماژولار
- ✅ پیکربندی آسان با فایل `config.yml`
- ✅ پشتیبانی از Webhook و Long Polling
- ✅ معماری مبتنی بر پلاگین (Plug & Play)
- ✅ مستندات کامل با مثال‌های عملی

## 📦 نصب
```bash
pip install git+https://github.com/balecore/balecore.git
```

## 🛠️ استفاده سریع
```python
from balecore import Bot, Message

bot = Bot(token="YOUR_BOT_TOKEN")

@bot.on_message(command="/start")
async def start_handler(message: Message):
    await message.reply("سلام! به ربات خوش آمدید 👋")

if __name__ == "__main__":
    bot.run()
```

## 🤝 مشارکت در توسعه
1. ریپو را Fork کنید
2. برنچ جدید ایجاد کنید:  
   `git checkout -b feature/your-feature`
3. کامیت تغییرات:  
   `git commit -m 'اضافه کردن ویژگی جدید'`
4. Push به برنچ:  
   `git push origin feature/your-feature`
6. Pull Request ارسال کنید

## 📜 لایسنس
این پروژه تحت لایسنس [MIT](LICENSE) منتشر شده است.

## 📞 ارتباط با ما
- گزارش باگ و درخواست ویژگی: [ایجاد Issue](https://github.com/balecore/balecore/issues)
- پشتیبانی فنی: [@farde](http://ble.ir/farde)
- کانال رسمی: [@balecore](https://t.me/balecore)

---

<div align="center">
  با ❤️ ساخته شده برای جامعه توسعه‌دهندگان ایرانی
</div>
```

### 🗂️ ساختار پروژه:
```
📁 BaleCore/
├── 📄 index.html
├── 📄 README.md
└── 🖼️ logo.png
```
