
# VTP-Mic
VTP-Mic: your Android phone as a wireless microphone for Voice Typer Pro
---

<div dir="rtl">

## VTP-Mic (برنامه‌ی اندروید): درباره‌ی هشدار گوگل هنگام نصب

وقتی VTP-Mic را روی گوشی نصب می‌کنید، ممکن است Google Play Protect بگوید «سازنده‌ی این برنامه را نمی‌شناسد». این پیام به این معنا نیست که در برنامه ویروس یا مشکل امنیتی پیدا شده است.

### چرا این پیام نشان داده می‌شود؟

گوگل این پیام را برای هر برنامه‌ای نشان می‌دهد که از Google Play نصب نشده و سازنده‌اش هنوز در سامانه‌ی تأیید سازندگان گوگل ثبت نشده است. VTP-Mic فعلاً مستقیم از همین صفحه منتشر می‌شود و گوگل هنوز سازنده‌اش را نمی‌شناسد. در نسخه‌های بعدی، با ثبت سازنده نزد گوگل یا انتشار در Google Play، این هشدار برطرف می‌شود.

### VTP-Mic با اطلاعات شما چه می‌کند؟

- **صدا فقط به کامپیوتر خود شما می‌رود.** میکروفون فقط وقتی روشن است که ضبط می‌کنید. صدا مستقیم، از راه وای‌فای یا بلوتوث، به همان کامپیوتری می‌رسد که با کد QR جفتش کرده‌اید و Voice Typer Pro روی آن اجرا می‌شود. VTP-Mic هیچ چیزی را برای ما یا هیچ سرور دیگری نمی‌فرستد.
- **همه‌چیز رمزگذاری‌شده است.** کلید رمز فقط داخل همان کد QR است و هرگز روی شبکه فرستاده نمی‌شود. کس دیگری روی همان شبکه نمی‌تواند صدای شما را بشنود.
- **بدون حساب کاربری، تبلیغ، ردیاب یا آمارگیری.** برنامه به هیچ سرور اینترنتی وصل نمی‌شود، حتی به سرور ما.
- **چیزی جز تنظیمات روی گوشی نمی‌ماند.** صدا روی گوشی ذخیره نمی‌شود. تنظیمات و کلید جفت‌شدن هم در پشتیبان‌گیری ابری گوشی نمی‌روند.
- **همیشه می‌بینید میکروفون روشن است یا نه.** تا وقتی برنامه روشن است، اعلانش دیده می‌شود. از اندروید ۱۲ به بعد، خود اندروید هم هنگام کار میکروفون نشانگر سبز نشان می‌دهد.

### هر اجازه برای چیست؟

| اجازه | دلیل |
|---|---|
| میکروفون | گرفتن صدای شما، فقط هنگام ضبط |
| دوربین | فقط اسکن کد QR هنگام جفت شدن با کامپیوتر |
| شبکه و وای‌فای | اندروید این اجازه را برای هر اتصال شبکه می‌خواهد، حتی اتصال مستقیم به کامپیوتر خودتان در خانه یا محل کار |
| بلوتوث | راه پشتیبان وقتی وای‌فای در دسترس نیست |
| اعلان و کار در پس‌زمینه | تا با صفحه‌ی خاموش هم کار کند و همیشه بدانید روشن است |
| استثنای بهینه‌سازی باتری | فقط اگر خودتان بخواهید، تا گوشی وسط دیکته برنامه را نبندد |

برنامه هیچ اجازه‌ای برای موقعیت مکانی، مخاطبان، پیامک یا فایل‌های شما نمی‌خواهد.

### نصب، قدم به قدم

1. فایل را فقط از بخش **Releases** همین صفحه دانلود کنید.
2. اگر Play Protect پیشنهاد داد برنامه برای بررسی فرستاده شود، آن را بپذیرید. بعد از بررسی، نصب ادامه پیدا می‌کند.
3. اگر پیام «سازنده‌ی ناشناس» آمد، «جزئیات بیشتر» و بعد «در هر صورت نصب شود» را بزنید.

### مطمئن شوید فایل اصل است

همه‌ی نسخه‌های VTP-Mic با یک کلید امضا می‌شوند. اندروید نسخه‌ی تازه را فقط وقتی روی نسخه‌ی قبلی نصب می‌کند که با همین کلید امضا شده باشد، پس نسخه‌ی تقلبی نمی‌تواند جای برنامه‌ی شما بنشیند. اثر انگشت گواهی امضا (SHA-256):

`cb4e81a9414e9c7642e75fc83bb07d5adab9f1f4d9313eefb7933ead86986ab1`

کاربران فنی می‌توانند آن را با `apksigner verify --print-certs` بررسی کنند.

سؤال یا مشکلی دارید؟ در بخش **Issues** همین صفحه بنویسید.

</div>

---

## VTP-Mic (Android app): about Google's warning during installation

When you install VTP-Mic, Google Play Protect may say it "doesn't recognize this app's developer". This does not mean a virus or a security problem was found in the app.

### Why does this warning appear?

Google shows it for every app that isn't installed from Google Play and whose developer isn't yet registered in Google's developer verification. VTP-Mic is currently published directly on this page, so Google doesn't know its developer yet. A future release will remove the warning, once the developer is registered with Google or the app is published on Google Play.

### What VTP-Mic does with your data

- **Your voice goes only to your own computer.** The microphone is on only while you record. The sound travels directly, over Wi-Fi or Bluetooth, to the computer you paired with a QR code, where Voice Typer Pro runs. VTP-Mic sends nothing to us or to any other server.
- **Everything is encrypted.** The key exists only inside that QR code and is never sent over the network. Nobody else on the same network can listen.
- **No account, no ads, no trackers, no analytics.** The app never connects to any internet server, not even ours.
- **Nothing but settings stays on the phone.** No audio is stored on the phone. The settings and the pairing key are also excluded from the phone's cloud backups.
- **You always know when the microphone is on.** The app's notification is visible whenever it runs. On Android 12 and later, Android itself also shows a green indicator while the microphone is in use.

### Why each permission

| Permission | Why |
|---|---|
| Microphone | To capture your voice, only while recording |
| Camera | Only to scan the QR code when pairing with your computer |
| Network and Wi-Fi | Android requires it for any network connection, even a direct one to your own computer at home or at work |
| Bluetooth | The backup path when Wi-Fi isn't available |
| Notifications and background work | So it keeps working with the screen off, and you always see that it's on |
| Battery optimization exception | Only if you choose it, so the phone doesn't close the app mid-dictation |

The app asks for no access to your location, contacts, messages or files.

### Installing, step by step

1. Download the file only from this page's **Releases** section.
2. If Play Protect offers to scan the app, accept. Once the scan finishes, the installation continues.
3. If the "unknown developer" warning appears, tap "More details", then "Install anyway".

### Make sure the file is genuine

Every version of VTP-Mic is signed with the same key. Android only installs an update over the existing app when it carries this same signature, so a fake copy can't replace yours. The signing certificate's SHA-256 fingerprint:

`cb4e81a9414e9c7642e75fc83bb07d5adab9f1f4d9313eefb7933ead86986ab1`

Technical users can check it with `apksigner verify --print-certs`.

Questions or problems? Open an issue in this page's **Issues** section.
