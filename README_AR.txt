تطبيق مواقيت القاهرة — مشروع Android Studio

المشروع يحول واجهة مواقيت القاهرة إلى تطبيق أندرويد مستقل يعمل داخل WebView.

طريقة إخراج APK:
1) ثبّت Android Studio على الكمبيوتر.
2) فك ضغط MawaqitCairo-Android-Project.zip.
3) من Android Studio اختر Open ثم اختر مجلد MawaqitCairo.
4) انتظر اكتمال Gradle Sync وتنزيل Android SDK Platform 35 عند الطلب.
5) من القائمة Build اختر Build Bundle(s) / APK(s) ثم Build APK(s).
6) ستجد ملف APK داخل app/build/outputs/apk/debug/.

المتطلبات:
- Android Studio حديث.
- JDK 17 أو أحدث (Android Studio يوفر JBR عادةً).
- اتصال إنترنت أول مرة لمزامنة Gradle وجلب مواقيت الصلاة.

ملاحظات:
- الساعة والتاريخ يعتمدان على توقيت الجهاز مع عرض المنطقة الزمنية Africa/Cairo.
- مواقيت الصلاة تُجلب من AlAdhan API بطريقة الحساب 5 (Egyptian General Authority of Survey).
- يلزم اتصال الإنترنت لتحديث المواقيت. الساعة والتاريخ المحليان يعملان دون اتصال.
- هذه نسخة أولى؛ لا تحتوي بعد على تنبيهات الأذان أو إشعارات الصلاة.
