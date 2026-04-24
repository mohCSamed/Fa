ضع هنا الصور المشتركة التي تريد ظهورها على كل الأجهزة بعد الرفع على GitHub.

الخطوات:
1) أنشئ فولدر لكل شخص داخل هذا المسار:
   - shared-media/Yoma
   - shared-media/Janjan
   - shared-media/Mo
   - shared-media/Domdom
   - shared-media/Fozda2a
   - shared-media/Dad

2) ضع الصور داخل كل فولدر.

3) عدل ملف shared-media/manifest.json وأضف مسارات الصور لكل شخص.
   مثال:
   "Yoma": [
     "shared-media/Yoma/img1.jpg",
     "shared-media/Yoma/img2.png"
   ]

ملاحظات:
- الصور القادمة من هذا المجلد تظهر بدون تعليقات.
- الصور تعتبر ثابتة (Static) ولن تُحذف من داخل الموقع؛ احذفها من الملف/الـ manifest.
