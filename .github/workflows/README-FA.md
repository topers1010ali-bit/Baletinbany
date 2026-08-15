# Tinbany Scanner v1.0.1

اپلیکیشن Native اندروید برای اسکن چند بارکد و ارسال آن‌ها به افزونه Tinbany Bale Agent v1.9.0.

## روش ۱ — ساخت APK با Android Studio
1. Android Studio را نصب کن.
2. پوشه پروژه را با Open باز کن.
3. صبر کن Gradle Sync کامل شود.
4. از منوی Build گزینه Build APK(s) را بزن.
5. فایل خروجی معمولاً اینجاست:
   `app/build/outputs/apk/debug/app-debug.apk`

## روش ۲ — ساخت خودکار در GitHub
1. یک Repository جدید در GitHub بساز.
2. تمام محتویات این پوشه را داخل Repository قرار بده.
3. وارد تب Actions شو.
4. Workflow با نام `Build Tinbany Scanner APK` را اجرا کن.
5. بعد از پایان Build، در بخش Artifacts فایل `TinbanyScanner-debug-apk` را دانلود کن.
6. داخل آن `app-debug.apk` قرار دارد.

## اتصال به بله
1. افزونه `Tinbany Bale Agent v1.9.0` را روی سایت نصب کن.
2. در بله با کاربری که دسترسی بروزرسانی قیمت دارد، گزینه «اتصال اسکنر اندروید» را بزن.
3. کد ۶ رقمی را داخل اپ وارد کن.
4. آدرس سایت: `https://tinbany.ir`
5. پس از اتصال، بارکدها را اسکن کن و «ارسال به بله و تعیین قیمت» را بزن.

## نکته
این پروژه از Google Code Scanner استفاده می‌کند و برای اسکن Native به Google Play Services روی گوشی نیاز دارد.
