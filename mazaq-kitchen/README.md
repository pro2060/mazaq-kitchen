# مَذاق | MAZAQ KITCHEN

اكتب الخامات اللي في بيتك واعرف تطبخ إيه. موقع ثابت (HTML واحد) بيشتغل على GitHub Pages بدون سيرفر.

## النشر على GitHub Pages
1. اعمل Repository جديد اسمه `mazaq-kitchen` (Public).
2. ارفع كل محتويات المجلد ده (index.html و images/ و .nojekyll).
3. Settings ← Pages ← Source: Deploy from a branch ← Branch: main / root ← Save.
4. بعد دقيقة الموقع يظهر على: https://pro2060.github.io/mazaq-kitchen/

## إضافة صور الوصفات
حط صورة كل وصفة في `images/recipes/` باسم الوصفة بالظبط (مثلا `tray.jpg`). الموقع بيعرضها لوحده، ولو مفيش صورة بيعرض الإيموجي.
الأسماء: tray, cheese, cpasta, kosh, lsoup, mouss, bolo, shak, humm, panc

## إضافة وصفة جديدة
أضف سطر في مصفوفة `R` جوه index.html بنفس صيغة الوصفات الموجودة، وأي خامة جديدة تتضاف في `ING`.

## مهم
- ما تحطش أي باسورد أو مفتاح API في الـ repo. أي مفاتيح تتحط في ملف `.env` (متجاهل في .gitignore) أو في GitHub Secrets.
- الصور الموجودة في images/ (guide-*.webp وصور الـ hero) مأخوذة من الإنترنت. قبل ما تستخدم الموقع تجاريا استبدلها بصور ملكك أو مرخصة أو مولّدة بالذكاء الاصطناعي.
