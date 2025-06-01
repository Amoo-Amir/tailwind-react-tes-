# Tailwind React Test

## 🔍 Problem Description (English)

This is a minimal reproduction project to report a bug related to Tailwind CSS not applying color-related classes when used with Vite and React.

### ❗ What’s the issue?
When using Tailwind CSS in this Vite + React project, most utility classes (such as margin, padding, border, etc.) work correctly, **but color classes like `bg-red-500`, `text-blue-600`, etc. do not work at all**.

### ⚠️ Additional Info
I also encountered this error when trying to initialize Tailwind using the CLI:

npx tailwindcss init -p
npm ERR! could not determine executable to run

yaml
Copy
Edit

So, I manually created `tailwind.config.js` and `postcss.config.js` using ChatGPT and Tailwind’s documentation.

Despite that, the issue with color classes persists.

---

## 📝 توضیح مشکل (فارسی)

این یک پروژه ساده‌ی تستی هست برای گزارش یک باگ در استفاده از Tailwind CSS همراه با Vite و React.

### ❗ مشکل چیه؟
زمانی که از Tailwind توی این پروژه استفاده می‌کنم، بیشتر کلاس‌ها مثل فاصله‌ها (`m-4`, `p-2`) و بردرها درست کار می‌کنن، ولی **کلاس‌های مربوط به رنگ مثل `bg-red-500` یا `text-blue-600` هیچ تاثیری ندارن** و اعمال نمی‌شن.

### ⚠️ اطلاعات بیشتر
زمانی که خواستم با دستور CLI تنظیمات تیلویند رو بسازم، با این ارور روبه‌رو شدم:

npx tailwindcss init -p
npm ERR! could not determine executable to run

arduino
Copy
Edit

برای همین مجبور شدم با کمک ChatGPT فایل‌های `tailwind.config.js` و `postcss.config.js` رو دستی بسازم.

ولی با این‌که بقیه کلاس‌ها کار می‌کنن، کلاس‌های رنگی هنوز کار نمی‌کنن.
