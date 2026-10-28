# MikroTik Cards Manager (NetCards)

تطبيق PWA عربي لإنشاء دفعات كروت MikroTik Hotspot وطباعتها وتصدير CSV أو أوامر RouterOS بصيغة RSC. يعمل على GitHub Pages دون خادم أو قاعدة بيانات خارجية.

## النشر
1. الملفات موجودة في جذر المستودع `shawady6/Mikronet`.
2. افتح Settings → Pages.
3. اختر Deploy from a branch ثم `main` والمجلد `/(root)`.
4. بعد النشر افتح رابط GitHub Pages. على Android افتح الرابط في Chrome واختر Install app أو Add to Home screen.

## الاستخدام
- أدخل اسم الدفعة والعدد وHotspot Profile والمدة الاختيارية.
- اختر Username=Password أو كلمة مرور منفصلة.
- أنشئ الدفعة، ثم اطبعها أو صدّر CSV أو RSC.
- راجع ملف RSC وجرّبه على راوتر اختبار قبل استخدامه فعليًا.

## تنبيهات
- لا يوجد اتصال مباشر بالراوتر؛ استورد RSC يدويًا بعد مراجعته.
- البيانات محفوظة في localStorage لهذا المتصفح والجهاز فقط؛ استخدم النسخة الاحتياطية.
- التطبيق لا يحتوي على تسجيل دخول، فاحمِ ملفات التصدير لأنها تحتوي على بيانات دخول.
- تحقق من اسم الـ Profile وصيغة limit-uptime قبل الاستيراد.

الملفات: `index.html` التطبيق، `manifest.webmanifest` تعريف PWA، `sw.js` التخزين المؤقت، `assets/icon.svg` الأيقونة.
