# 📄 سياسة الخصوصية - BMI Calculator

## 📁 الملفات الموجودة

| الملف | الوصف |
|------|-------|
| `PRIVACY_POLICY_EN.md` | سياسة الخصوصية بالإنجليزية (Markdown) |
| `PRIVACY_POLICY_AR.md` | سياسة الخصوصية بالعربية (Markdown) |
| `index.html` | صفحة اختيار اللغة (HTML) |
| `HOW_TO_HOST_PRIVACY_POLICY.md` | دليل الاستضافة الكامل |

## 🚀 خطوات سريعة للاستضافة

### الطريقة الموصى بها: GitHub Pages

1. **إنشاء Repository على GitHub**
   ```
   اسم Repository: bmi-calculator-privacy
   نوع: Public
   ```

2. **رفع الملفات**
   - ارفع جميع الملفات من هذا المجلد
   - أو استخدم Git:
   ```bash
   git init
   git add .
   git commit -m "Add privacy policy"
   git remote add origin https://github.com/yourusername/bmi-calculator-privacy.git
   git push -u origin main
   ```

3. **تفعيل GitHub Pages**
   - Settings → Pages
   - Source: main branch
   - Save

4. **الحصول على الرابط**
   ```
   https://yourusername.github.io/bmi-calculator-privacy/
   ```

## 📝 قبل النشر

### تحديث معلومات الاتصال

في كلا الملفين (`PRIVACY_POLICY_EN.md` و `PRIVACY_POLICY_AR.md`):

```markdown
## Contact Us / اتصل بنا

- **Email**: your-email@example.com  ← غيّر هذا
- **Website**: https://your-website.com  ← غيّر هذا
```

استبدل بمعلوماتك الحقيقية:
- البريد الإلكتروني الخاص بك
- موقعك الإلكتروني (إن وجد)

## 🔗 استخدام الرابط

بعد الاستضافة، استخدم الرابط في:

### 1. Google Play Console
```
Store Listing → Privacy Policy
URL: https://yourusername.github.io/bmi-calculator-privacy/
```

### 2. في التطبيق (اختياري)
يمكنك إضافة زر في التطبيق:
```dart
TextButton(
  onPressed: () async {
    final url = 'https://yourusername.github.io/bmi-calculator-privacy/';
    if (await canLaunchUrl(Uri.parse(url))) {
      await launchUrl(Uri.parse(url));
    }
  },
  child: Text('Privacy Policy'),
)
```

## ✅ قائمة التحقق

قبل إرسال التطبيق لـ Google Play:

- [ ] تم رفع سياسة الخصوصية على الإنترنت
- [ ] الرابط يعمل ويفتح بشكل صحيح
- [ ] تم تحديث معلومات الاتصال
- [ ] الرابط يستخدم HTTPS
- [ ] كلا اللغتين متاحتين
- [ ] تم إضافة الرابط في Play Console

## 📚 مزيد من المعلومات

راجع ملف `HOW_TO_HOST_PRIVACY_POLICY.md` للحصول على:
- دليل مفصل خطوة بخطوة
- طرق استضافة بديلة
- حل المشاكل الشائعة
- نصائح وأفضل الممارسات

## 🆘 تحتاج مساعدة؟

إذا واجهت أي مشكلة:
1. راجع `HOW_TO_HOST_PRIVACY_POLICY.md`
2. ابحث عن "GitHub Pages tutorial"
3. اطلب المساعدة من مجتمع المطورين

---

**ملاحظة**: سياسة الخصوصية هذه مطلوبة من Google Play لأن التطبيق يستخدم AdMob.
