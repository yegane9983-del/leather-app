# Leather App - Cloud Build Ready

این نسخه برای ساخت APK بدون نصب Flutter روی کامپیوتر آماده شده است.

## روش 1: Codemagic
1. پروژه را در GitHub آپلود کنید.
2. وارد Codemagic شوید و Repository را Add کنید.
3. Workflow به نام `android-release` را اجرا کنید.
4. بعد از موفق شدن Build، فایل زیر را از Artifacts دانلود کنید:
   `build/app/outputs/flutter-apk/app-release.apk`

## روش 2: GitHub Actions
1. پروژه را در GitHub آپلود کنید.
2. از تب Actions، workflow با نام `Build Android APK` را Run کنید.
3. بعد از تمام شدن، از Artifacts فایل `leather-app-apk` را دانلود کنید.

## نصب روی گوشی Android
APK را به گوشی منتقل کنید، بازش کنید و اگر پیام امنیتی آمد، گزینه Install unknown apps را برای File Manager/Browser فعال کنید.
