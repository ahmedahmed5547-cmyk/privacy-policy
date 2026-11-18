# Privacy Policy — VEXO Player: IPTV and Video player (`com.pureplayer.video`) | سياسة الخصوصية
**Last Updated / آخر تحديث:** November 18, 2026  
**Developer / المطور:** Ahmed M Moumen  
**Contact Email / البريد الإلكتروني للتواصل:** [AHMEDAHMED5547@GMAIL.COM](mailto:ahmedahmed5547@gmail.com)

---

## 1. Overview | نظرة عامة
**VEXO Player — IPTV and Video player** (`com.pureplayer.video`) is a local media and playlist player for Android. We respect your privacy and operate on a strict **100% local-first privacy model**. We do not collect, store on external servers, sell, or share any personal or sensitive user data.

تطبيق **VEXO Player — IPTV and Video player** (`com.pureplayer.video`) هو مشغل وسائط وقوائم تشغيل محلي لنظام أندرويد. نحن نحترم خصوصيتك ونعمل وفق نموذج خصوصية محلي صارم بنسبة **100% داخل الجهاز فقط**. نحن لا نجمع أو نخزن على خوادم خارجية أو نبيع أو نشارك أي بيانات شخصية أو حساسة للمستخدمين.

## 2. Permissions Used & Purpose | الأذونات المستخدمة والغرض منها
- **`READ_MEDIA_VIDEO` / `READ_MEDIA_VISUAL_USER_SELECTED` / `READ_EXTERNAL_STORAGE` (maxSdkVersion 32):** Required as core functionality to index, organize, and play video files and folders stored locally on the user's device. Media file lists never leave the device. (مطلوبة كوظيفة أساسية لفهرسة وتنظيم وتشغيل ملفات ومجلدات الفيديو المخزنة محلياً على جهاز المستخدم، ولا تغادر قوائم الملفات الجهاز أبداً).
- **`USE_BIOMETRIC` / `USE_FINGERPRINT`:** Used strictly on-device via `AndroidKeyStore` to authenticate access to user-locked folders in the Private Vault. Biometric data is handled exclusively by the Android OS hardware and is never accessed, transmitted, or stored by the app. (تُستخدم حصرياً داخل الجهاز عبر `AndroidKeyStore` للمصادقة عند فتح المجلدات المقفلة في الخزنة الخاصة، وتُعالج البصمة عبر عتاد نظام أندرويد فقط ولا يصل إليها التطبيق أو يخزنها أو يرسلها).
- **`INTERNET` & `ACCESS_NETWORK_STATE`:** Used only when the user explicitly streams a user-provided network URL/playlist or searches for subtitles from public subtitle APIs. (تُستخدم فقط عندما يقوم المستخدم بنفسه بتشغيل رابط بث شبكي أو قائمة تشغيل يضيفها يدوياً، أو عند البحث عن ملفات الترجمة عبر واجهات الترجمة العامة).

## 3. Data Storage, Encryption & Backup Exclusion | تخزين البيانات والتشفير واستثناء النسخ السحابي
- **Private Vault PIN (رمز PIN للخزنة الخاصة):** Hashed locally using `PBKDF2WithHmacSHA256` with `>= 100,000` iterations and a 16-byte random cryptographic salt. (يُشفر محلياً بتقنية `PBKDF2WithHmacSHA256` مع أكثر من `100,000` تكرار وملح تشفير عشوائي بحجم 16 بايت).
- **Playlist Credentials (بيانات اعتماد قوائم التشغيل):** Encrypted locally using `AES-256-GCM` backed by hardware `AndroidKeyStore` (`pure_player_iptv_cred_aes_v1`). (تُشفر محلياً بمعيار `AES-256-GCM` المدعوم بعتاد `AndroidKeyStore`).
- **Cloud Backup Exclusion (استثناء النسخ الاحتياطي السحابي):** All sensitive databases, caches, and preferences are explicitly excluded from Google Cloud Auto-Backup and device-to-device transfer in `backup_rules.xml` and `data_extraction_rules.xml`. (جميع قواعد البيانات والتفضيلات الحساسة مستثناة صراحةً من النسخ الاحتياطي السحابي التلقائي لجوجل ومن النقل بين الأجهزة).

## 4. Content Disclaimer | إخلاء مسؤولية المحتوى
VEXO Player (IPTV and Video player) does not provide, host, bundle, or distribute any media content or playlists. Users are solely responsible for the local videos or playlists they choose to play.

لا يوفر تطبيق VEXO Player (IPTV and Video player) ولا يستضيف أو يدمج أو يوزع أي محتوى وسائط أو قنوات أو قوائم تشغيل. المستخدم وحده هو المسؤول عن ملفات الفيديو المحلية أو قوائم التشغيل التي يختار تشغيلها.

## 5. Contact Us | تواصل معنا
If you have any questions or inquiries regarding this Privacy Policy or data protection practices, please contact the developer directly at:  
في حال وجود أي استفسارات بخصوص سياسة الخصوصية أو حماية البيانات، يرجى التواصل مع المطور مباشرةً عبر البريد الإلكتروني:  
**Email:** [AHMEDAHMED5547@GMAIL.COM](mailto:ahmedahmed5547@gmail.com)
