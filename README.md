# Self_timer
🕒 VoiceChat Clock

Automatic Voice Chat Date & Time Updater

فارسی | Persian

پروژه VoiceChat Clock یک ابزار مبتنی بر پایتون برای نمایش خودکار ساعت و تاریخ در عنوان ویس‌چت گروه‌های روبیکا است.

این ابزار با استفاده از کتابخانه MAXRubika به حساب کاربری متصل می‌شود و عنوان ویس‌چت فعال را در بازه‌های زمانی مشخص به‌روزرسانی می‌کند.

هدف پروژه، نمایش ساعت و تاریخ به‌صورت زنده و بدون نیاز به تغییر دستی عنوان ویس‌چت است.

English

VoiceChat Clock is a Python-based tool designed to automatically display the current time and date in Rubika group voice chat titles.

Using the MAXRubika library, the application connects to a Rubika account and periodically updates the title of an active voice chat.

The main purpose is to provide a live clock and date display without manually changing the voice chat title.

---

✨ قابلیت‌ها | Features

- 🕒 نمایش ساعت فعلی (Real-Time Clock)
- 📅 نمایش تاریخ روز
- 🔄 به‌روزرسانی خودکار عنوان ویس‌چت
- ⏱ قابلیت تنظیم فاصله زمانی به‌روزرسانی
- 🌐 پشتیبانی از منطقه زمانی قابل تنظیم
- 👥 پشتیبانی از گروه‌های روبیکا
- 🔌 اتصال از طریق کتابخانه MAXRubika
- ⚙️ تنظیم نام و لینک گروه
- 🖥️ اجرای مداوم در محیط پایتون

---

🛠️ پیش‌نیازها | Requirements

برای اجرای پروژه به موارد زیر نیاز دارید:

- Python 3
- pip
- MAXRubika
- حساب کاربری روبیکا
- دسترسی به ویس‌چت گروه

---

📦 نصب وابستگی‌ها | Installation

ابتدا مخزن را دریافت کنید:

git clone https://github.com/USERNAME/VoiceChat-Clock.git

وارد پوشه پروژه شوید:

cd VoiceChat-Clock

نصب وابستگی‌ها:

pip install -U maxrubika jdatetime

---

⚙️ تنظیمات | Configuration

قبل از اجرا، اطلاعات نشست و گروه موردنظر را تنظیم کنید.

پارامترهای اصلی:

Parameter| Description
SESSION| نام یا مسیر فایل نشست
GROUP| شناسه، لینک یا نام کاربری گروه
UPDATE_INTERVAL| فاصله زمانی به‌روزرسانی
TIMEZONE| منطقه زمانی
DATE_FORMAT| قالب نمایش تاریخ
TIME_FORMAT| قالب نمایش ساعت

---

🕒 نمونه خروجی | Example Output

عنوان ویس‌چت به شکل زیر نمایش داده می‌شود:

🕒 17:10 | 1405/09/05

پس از گذشت یک دقیقه:

🕒 17:11 | 1405/09/05

تاریخ و ساعت متناسب با زمان سیستم به‌روزرسانی خواهند شد.

---

📚 کتابخانه‌های مورد استفاده | Libraries

Library| Usage
MAXRubika| ارتباط با API روبیکا و مدیریت ویس‌چت
jdatetime| تبدیل تاریخ میلادی به شمسی
datetime| مدیریت تاریخ و ساعت
time| مدیریت فاصله زمانی اجرای عملیات

---

🔐 امنیت | Security

- اطلاعات نشست حساب کاربری باید محرمانه نگهداری شوند.
- فایل‌های نشست نباید در مخزن عمومی GitHub قرار بگیرند.
- از انتشار اطلاعات احراز هویت خودداری کنید.

---

🚧 وضعیت پروژه | Project Status

در حال توسعه | Under Development

این پروژه در مرحله توسعه قرار دارد و قابلیت‌های آن ممکن است در نسخه‌های آینده تغییر کنند.

---

⚖️ مجوز استفاده | License

این پروژه با هدف آموزشی و توسعه نرم‌افزار ایجاد شده است.

استفاده از پروژه باید مطابق قوانین و شرایط استفاده روبیکا و کتابخانه‌های مورد استفاده باشد.

---

Developed with Python 🐍
