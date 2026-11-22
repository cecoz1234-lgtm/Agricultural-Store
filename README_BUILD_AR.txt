مشروع Android لتطبيق المتجر الزراعي

هذا مشروع Android Studio وليس APK جاهزاً، لأن بيئة الإنشاء الحالية لا تحتوي Android SDK أو Gradle.

خطوات إنشاء APK:
1. تثبيت Android Studio على الكمبيوتر.
2. فتح هذا المجلد من Android Studio: AgriculturalStoreAndroid.
3. السماح بمزامنة Gradle وتنزيل SDK components عند الطلب.
4. من القائمة Build > Build Bundle(s) / APK(s) > Build APK(s).
5. ملف APK عادةً يظهر في app/build/outputs/apk/debug/app-debug.apk.

التطبيق:
- WebView يعرض واجهة المتجر المرفقة في assets/index.html.
- بيانات المنتجات محفوظة على جهاز المستخدم (LocalStorage).
- رابط WhatsApp يفتح رسالة الحجز إلى 07707024070.
- رمز إدارة المتجر داخل واجهة الويب: 1234 (غيّره قبل الاستخدام الحقيقي).

ملاحظات:
- الأسعار داخل التطبيق تجريبية.
- تحديث الأسعار في النسخة الحالية محلي على كل جهاز؛ ليس تحديثاً مركزياً بين جميع الزبائن. التحديث المركزي يحتاج قاعدة بيانات وخادم أو خدمة Firebase.
