# ريناد دويدي للتصميم الداخلي

## النشر على GitHub Pages
1. أنشئ مستودع جديد (Repository) عام — Public
2. ارفع **محتوى** المجلد (مو المجلد نفسه): `index.html` و `images/` و `.nojekyll` و `README.md`
   — `index.html` لازم يكون في جذر المستودع مباشرة
3. Settings ← Pages ← Source: **Deploy from a branch** ← Branch: `main` / `(root)` ← Save
4. بعد دقيقة أو دقيقتين يصير الموقع على: `https://USERNAME.github.io/REPO/`
5. افتح `index.html` وعدّل سطر `og:image` بالرابط الحقيقي حتى تطلع معاينة الرابط في واتساب

## قواعد أسماء الملفات (مهم على GitHub)
- GitHub يفرّق بين الحروف الكبيرة والصغيرة: `Cover.png` غير `cover.png`
- كل الأسماء بحروف إنجليزية صغيرة، بدون مسافات ولا حروف عربية
- الاسم المكتوب في البيانات لازم يطابق اسم الملف حرفياً مع الامتداد

## هيكل الصور
```
images/
├── share.jpg                      معاينة الرابط (1200×630)
├── logo.png                       اختياري — ثم اكتب "images/logo.png" في البيانات
├── about/renad.jpg                صورة ريناد
├── projects/project-01/cover.jpg  غلاف المشروع + 1.jpg 2.jpg ... للصور الإضافية
└── collection/piece-01/cover.jpg  غلاف القطعة + 1.jpg ... للصور الإضافية
```
- إضافة صور لمشروع: ضعها في مجلده، ثم اكتب أسماءها في `photos:["1.jpg","2.jpg"]`
- قبل الرفع حوّل صور PNG الكبيرة إلى JPG (أخف وأسرع بكثير)

## روابط مباشرة
- مشروع: `https://USERNAME.github.io/REPO/#p/project-01`
- قطعة: `https://USERNAME.github.io/REPO/#c/piece-01`

## قبل الإعلان عن الموقع
- [ ] رقم الواتساب الحقيقي (`whatsapp` و `whatsappDisplay`)
- [ ] أسماء المشاريع ووصفها
- [ ] أسماء القطع وأسعارها ووصفها
- [ ] حاسبة التكلفة: ضع الأسعار ثم `enabled: true`
- [ ] رأي عميل حقيقي (`testimonial`) — اختياري
