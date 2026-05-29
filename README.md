# DMT-CyberFang - Ultimate Security Tool

## جهاز أمن سيبراني محمول | Portable Cybersecurity Device

---

## 📋 عن الجهاز | About

DMT-CyberFang هو جهاز أمن سيبراني محمول يجمع بين مدير كلمات المرور وأداة اختراق أخلاقي في جهاز واحد. يعمل على معالج ESP32 مع شاشة LCD وزر تحكم واحد.

DMT-CyberFang is a portable cybersecurity device that combines a password manager and an ethical hacking tool in one device. It runs on ESP32 with LCD screen and single button control.

---

## 🔧 المكونات | Hardware

| المكون | Component |
|--------|-----------|
| ESP32 | Microcontroller |
| LCD 16x2 I2C | Display |
| Boot Button (GPIO 0) | Control |
| LED (GPIO 2) | Status |

**توصيلات LCD | LCD Wiring:** VCC→3.3V, GND→GND, SDA→GPIO21, SCL→GPIO22

---

## 🔐 Dr Password - مدير كلمات المرور

- حفظ 50 تطبيق + 50 موقع
- تشفير XOR وحفظ في Preferences
- صفحة ويب عربية - Dark Mode - متجاوبة
- إضافة، تعديل، حذف، بحث، تصفية، مفضلة
- تحليل قوة كلمة المرور (Strong/Medium/Weak)
- Hotspot: Dr Password / Mouad09.7

---

## 🐱‍💻 Dr Hacker - أداة اختراق أخلاقي

- مسح 80 شبكة WiFi
- ترتيب حسب قوة الإشارة (++++ إلى +)
- Evil Twin Attack + صفحة دخول مزيفة
- Deauth Attack (فصل الأجهزة)
- حفظ 50 كلمة مسروقة مع الوقت والتاريخ

---

## 🎮 نظام الأزرار | Button System

| الوقت | المؤشر | الإجراء |
|-------|--------|---------|
| 1s | SEL:2s | تنقل |
| 2s | ENT:2s | دخول / مسح / Evil Twin |
| 3s | VIEW:3s | عرض كلمة المرور / Deauth |
| 5s | BACK:5s | رجوع للرئيسية |
| 7s | HOT:7s | تشغيل Hotspot |
| 10s | STOP:10s | إيقاف كل شيء |
| 15s | RESTART | إعادة تشغيل |

---

## 📺 شاشة LCD | LCD Display

| الحالة | السطر الأول | السطر الثاني |
|--------|-------------|---------------|
| ترحيب | Welcome Dr Mouad | Press Boot |
| قائمة رئيسية | Dr Mouad | >1-Dr Password |
| تطبيقات | Apps: | > Instagram S |
| مواقع | Websites: | > Gmail S |
| Hotspot | Hotspot: | Hold 7s to ON |
| مسح | Scanning WiFi... | SCAN:12s |
| شبكات | Networks: 5 | 1:MyWiFi +++ |
| Evil Twin | EVIL TWIN | Target: MyWiFi |
| Deauth | DEAUTH ATTACK | Target: MyWiFi |
| سرقة | PASSWORD STOLEN! | الكلمة |

---

## 📊 قوة الإشارة | Signal Strength

| الرمز | القوة | dBm |
|-------|-------|-----|
| ++++ | قوية جداً | > -50 |
| +++ | قوية | -50 to -70 |
| ++ | متوسطة | -70 to -80 |
| + | ضعيفة | < -80 |

---

## 🔌 صفحات الويب | Web Pages

**Hotspot:** http://192.168.4.1

- صفحة عربية RTL
- Dark Mode
- جداول تفاعلية
- أزرار: عرض، تعديل، حذف، مفضلة
- بحث وتصفية
- إضافة جديدة
- توليد كلمة مرور

---

## 📦 البيانات الافتراضية | Default Data

**تطبيقات | Apps:**
- Instagram / mouad_insta / Insta@2024Secure
- TikTok / mouad_tiktok / TikTok#456Strong
- Snapchat / mouad_snap / Snap@789Best
- Telegram / mouad_tg / Telegram@2024

**مواقع | Websites:**
- Gmail / mouad@gmail.com / Gmail@2024Secure
- Facebook / mouad_fb / FB#456Strong
- Twitter / mouad_tw / X@789Best
- GitHub / mouad_gh / GitHub@2024Code

---

## 📜 الترخيص | License

**Educational and Ethical Use License - EEUL v1.0**

- ✅ للاستخدام التعليمي والأكاديمي فقط
- ✅ لمشاريع التخرج الجامعية
- ❌ يمنع بيع الجهاز أو الكود
- ❌ يمنع الاستخدام التجاري
- ❌ يمنع اختراق شبكات الآخرين دون إذن

**لا يمكن بيع هذا الجهاز تحت أي ظرف من الظروف.**

This device CANNOT be sold under any circumstances.

---

## 👨‍💻 المطور | Developer

Dr Mouad Security Labs

**Contact:** drmouad@cyberfang.com

---

## ⚠️ تنبيه | Warning

هذا الجهاز للأغراض التعليمية والأخلاقية فقط. المستخدم مسؤول وحده عن أي استخدام غير قانوني.

This device is for educational and ethical purposes only. User is solely responsible for any illegal use.

---

**DMT-CyberFang - Learn responsibly, test ethically, protect everyone.**

**تعلم بمسؤولية، اختبر بأخلاقية، حماية للجميع.**

---
