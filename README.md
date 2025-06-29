# نظام تمويل وتقسيط السيارات | MAZ Brothers 🚗

نظام متكامل لإدارة تمويل وتقسيط السيارات بكل سهولة وفعالية.

## المميزات 🌟

- معرض السيارات المتاحة للتمويل
- حاسبة التمويل والأقساط
- لوحة تحكم متكاملة
- نظام تقارير شامل
- واجهة مستخدم عربية سهلة الاستخدام
- تصميم متجاوب مع جميع الأجهزة

## التقنيات المستخدمة 💻

- Next.js 14
- TypeScript
- Tailwind CSS
- Prisma
- PostgreSQL

## متطلبات التشغيل 🚀

1. Node.js (v18 أو أحدث)
2. npm أو yarn
3. PostgreSQL

## طريقة التشغيل 🛠️

1. استنساخ المشروع:
```bash
git clone https://github.com/yourusername/car-finance.git
cd car-finance
```

2. تثبيت الاعتمادات:
```bash
npm install
# أو
yarn install
```

3. إعداد ملف البيئة:
```bash
cp .env.example .env
```
ثم قم بتعديل المتغيرات في ملف `.env`

4. تشغيل قاعدة البيانات:
```bash
npx prisma migrate dev
```

5. تشغيل الخادم المحلي:
```bash
npm run dev
# أو
yarn dev
```

6. افتح المتصفح على العنوان:
```
http://localhost:3000
```

## المساهمة 🤝

نرحب بمساهماتكم! يرجى اتباع الخطوات التالية:

1. Fork المشروع
2. إنشاء فرع جديد (`git checkout -b feature/amazing-feature`)
3. Commit التغييرات (`git commit -m 'إضافة ميزة جديدة'`)
4. Push إلى الفرع (`git push origin feature/amazing-feature`)
5. فتح Pull Request

## الترخيص 📝

هذا المشروع مرخص تحت [MIT License](LICENSE)

## الدعم 💬

إذا واجهتك أي مشكلة أو لديك أي استفسار، يرجى فتح issue في هذا المستودع.
