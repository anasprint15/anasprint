# Anas Print — Outil Comptable

نسخة Web/PWA خاصة بـ Anas Print.

## الملفات
- `index.html` — التطبيق الكامل
- `manifest.webmanifest` — إعدادات تثبيت التطبيق على الهاتف
- `service-worker.js` — العمل أوفلاين بعد أول فتح

## حفظ المعلومات
الفواتير، المصاريف/الديون والبيانات المحفوظة داخل الأداة يتم تخزينها في `localStorage` الخاص بالمتصفح/التطبيق.
يوجد داخل الأداة أيضاً زر **Exporter les données** لإنشاء نسخة احتياطية JSON، و **Importer les données** لاسترجاعها.

**مهم:** عند تغيير الهاتف أو حذف بيانات التطبيق، يجب استرجاع نسخة الـ JSON حتى لا تضيع البيانات.

## GitHub Pages
1. أنشئ Repository جديد في GitHub.
2. ارفع الملفات الثلاثة.
3. من Settings → Pages اختر Deploy from branch ثم `main` و`/root`.
4. افتح رابط GitHub Pages من الهاتف.
5. من المتصفح اختر Add to Home Screen / Install App.

