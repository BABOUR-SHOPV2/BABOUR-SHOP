# BABOUR SAMP - موقع سيرفر بابور (متصل بقاعدة بيانات)

## الخطوة 1: إنشاء قاعدة بيانات Firebase (مجانية)
1. ادخل: console.firebase.google.com وسجل بحساب Google
2. اضغط "Add project" وأنشئ مشروع جديد (مثلاً: babour-samp)
3. من القائمة الجانبية: Build > Realtime Database > Create Database
4. اختر أي موقع (مثلاً: europe-west1) ثم ابدأ في وضع التجربة (Test mode)
5. بعد الإنشاء، افتح تبويب Rules والصق:
   { "rules": { ".read": true, ".write": true } } ثم اضغط Publish

## الخطوة 2: نسخ بيانات الاتصال
1. Project settings (علامة التروس) > General
2. انزل لقسم "Your apps" واختر الويب (</>)
3. انسخ: apiKey و authDomain و databaseURL و projectId
4. افتح ملف index.html وابحث عن "firebaseConfig" والصق القيم مكان الكلمات العربية

## الخطوة 3: الرفع على GitHub Pages
1. أنشئ مستودع جديد (Public) على github.com
2. ارفع ملف index.html
3. Settings > Pages > Deploy from a branch > main > Save
4. رابطك جاهز خلال دقيقة: https://اسمك.github.io/اسم-المستودع

## ✅ بعدها: أي تعديل من لوحة التحكم يظهر لكل الزوار فوراً!

## بيانات الدخول: admin / babour123 (غيّرها من ADMIN_USER و ADMIN_PASS في الكود)
## رقم الواتساب: +212 630315122 (غيّره من WHATSAPP في الكود)
