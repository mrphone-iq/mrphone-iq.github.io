# متجر مستر فون

صفحة تطبيقات للبوكسات والتلفزيونات: https://mrphone-iq.github.io/

## إضافة تطبيق
1. ارفع ملف الـ APK على الإصدار **apps** (Releases → apps → Edit → Attach files).
2. ارفع أيقونة التطبيق لمجلد `img`.
3. أضف سطر للتطبيق بملف `apps.json`:
   - `file`: رابط التحميل الكامل، مثل `https://github.com/mrphone-iq/mrphone-iq.github.io/releases/download/apps/اسم-الملف.apk`
   - `icon`: مسار الأيقونة، مثل `img/اسم-الصورة.jpg`
   - `category`: `العراق` أو `أدوات`

## تحديث تطبيق
1. بالإصدار **apps** احذف الملف القديم وارفع الجديد **بنفس الاسم**.
2. غيّر رقم `version` بملف `apps.json`.

إذا تغيّر اسم ملف الـ APK، غيّر رابط `file` بملف `apps.json` حتى يطابقه.

الرابط يبقى نفسه، فالزبائن ما يحتاجون شي جديد.
