Lumen Repository

مخزن رسمی اپلیکیشن‌های قابل انتشار در Lumen Store

Lumen Repository یک ایندکس متمرکز برای شناسایی، بررسی و انتشار خودکار برنامه‌های متن‌باز در "Lumen Store" (https://github.com/deepcodecreate/lumenstore) است.

هدف این مخزن فراهم‌کردن بستری امن، شفاف و قابل اعتماد برای توسعه‌دهندگان و کاربران است؛ بستری که در آن دسترسی به برنامه‌ها، دریافت به‌روزرسانی‌ها و بررسی اصالت نسخه‌ها تا حد امکان به‌شکل خودکار انجام شود.

---

🇮🇷 فارسی

۱. قوانین استفاده و حقوق کاربران

استفاده از Lumen Repository و برنامه‌های منتشرشده از طریق آن به معنای پذیرش شرایط زیر است:

- استفاده از این مخزن برای اهداف قانونی، شخصی و تجاری مجاز است؛ مگر آنکه مجوز خود برنامه محدودیت دیگری تعیین کرده باشد.
- هرگونه استفاده با هدف آسیب‌رساندن به کاربران، سرقت اطلاعات، انتشار بدافزار، فریب کاربران یا سوءاستفاده از زیرساخت‌های مخزن ممنوع است.
- کاربران و توسعه‌دهندگان موظف‌اند حقوق مالکیت فکری، مجوزهای نرم‌افزاری و حقوق سایر اشخاص را رعایت کنند.
- هیچ‌کس مجاز نیست خود را مالک، مدیر یا نماینده رسمی Lumen Repository معرفی کند، مگر آنکه چنین اختیاری به‌صورت رسمی به او داده شده باشد.
- بازنشر، تغییر یا استفاده از محتوای این مخزن باید مطابق مجوزهای مربوط به هر بخش و قوانین مالکیت فکری انجام شود.
- انتشار یک برنامه در این مخزن به معنای تأیید کامل امنیت، کیفیت یا عملکرد آن توسط مدیران Lumen نیست.

۲. شرایط پذیرش برنامه‌ها

برای ثبت یک برنامه در Lumen Repository، رعایت تمام شرایط زیر الزامی است:

۲.۱. متن‌باز بودن

- برنامه باید متن‌باز باشد.
- سورس‌کد برنامه باید به‌صورت عمومی در GitHub منتشر شده باشد.
- مخزن سورس باید قابل دسترسی و بررسی باشد.
- انتشار نسخه‌های بسته و غیرقابل بررسی، بدون ارائه سورس متناظر، قابل پذیرش نیست.

۲.۲. فرایند ساخت و انتشار

- فایل‌های APK باید از طریق GitHub Actions پروژه ساخته و کامپایل شده باشند.
- فرایند ساخت باید تا حد امکان شفاف و قابل بررسی باشد.
- فایل‌های منتشرشده باید با سورس‌کد و نسخه اعلام‌شده مطابقت داشته باشند.

۲.۳. تصاویر و آیکون برنامه

هر پروژه باید تصاویر و آیکون موردنیاز خود را در مسیر زیر قرار دهد:

".github/assets"

حداقل موارد موردنیاز:

- آیکون برنامه با کیفیت مناسب.
- اسکرین‌شات‌های واقعی از محیط برنامه.

تصاویر باید متعلق به نسخه واقعی برنامه باشند و نباید با هدف گمراه‌کردن کاربران و نمایش قابلیت‌های غیرواقعی تهیه شده باشند.

۲.۴. مدیریت نسخه‌ها و تگ‌های انتشار

- تگ‌های Release باید به‌ترتیب و مطابق نسخه واقعی برنامه ایجاد شوند.
- شماره نسخه در تگ، فایل APK و اطلاعات داخلی برنامه باید هماهنگ باشد.
- برای هر تگ انتشار، وجود حداقل یک فایل APK با نسخه متناظر الزامی است.
- استفاده از تگ‌های نامنظم، تکراری یا ناسازگار با نسخه برنامه می‌تواند باعث اختلال در سیستم تشخیص و انتشار به‌روزرسانی‌ها شود.

۲.۵. توضیحات انتشار (Release Notes)

توضیحات هر نسخه در Lumen Store از README همان Release دریافت می‌شود.

بنابراین توصیه می‌شود برای هر انتشار، توضیحات کامل و دقیقی شامل موارد زیر ارائه کنید:

- معرفی تغییرات نسخه جدید.
- قابلیت‌های اضافه‌شده.
- مشکلات برطرف‌شده.
- تغییرات امنیتی.
- نکات مهم مربوط به نصب یا به‌روزرسانی.

توضیحات ناقص یا نامناسب مستقیماً بر کیفیت اطلاعات نمایش‌داده‌شده به کاربران تأثیر می‌گذارد.

۳. انتشار خودکار و مسئولیت توسعه‌دهندگان

پس از ثبت و پذیرش اولیه برنامه در ایندکس، فرایند انتشار نسخه‌های بعدی به‌صورت خودکار و بر اساس تگ‌های Release مخزن GitHub شما انجام خواهد شد.

از این مرحله به بعد:

- نسخه‌های جدید بر اساس تگ‌های انتشار شناسایی می‌شوند.
- اطلاعات انتشار از README همان Release دریافت می‌شود.
- فایل‌های APK توسط Lumen Store پردازش و برای انتشار انتخاب می‌شوند.

مسئولیت صحت اطلاعات نسخه‌ها، ترتیب تگ‌ها، سازگاری فایل‌های APK و جلوگیری از ایجاد اختلال در فرایند به‌روزرسانی بر عهده توسعه‌دهنده برنامه است.

در صورت ایجاد خطاهایی مانند تشخیص اشتباه نسخه، عدم شناسایی به‌روزرسانی یا انتشار نسخه ناسازگار به دلیل تگ‌گذاری نادرست، اصلاح مشکل بر عهده مالک مخزن برنامه خواهد بود.

۴. تشخیص معماری و فایل‌های APK

Lumen Store به‌صورت خودکار معماری سخت‌افزاری دستگاه کاربران را تشخیص داده و فایل APK مناسب را از میان فایل‌های انتشار انتخاب می‌کند.

در صورتی که برنامه شما از معماری‌های مختلف پشتیبانی می‌کند، پیشنهاد می‌شود فایل‌های APK جداگانه برای معماری‌های مورد پشتیبانی در بخش Assets هر Release قرار دهید.

برای مثال:

- "app-arm64-v8a.apk"
- "app-armeabi-v7a.apk"
- "app-x86_64.apk"
- "app-universal.apk"

نام‌گذاری صحیح فایل‌ها و ارائه نسخه‌های متناسب با معماری‌های مختلف به بهبود فرایند شناسایی و دریافت برنامه کمک می‌کند.

۵. حفظ امضای دیجیتال برنامه

تغییر کلید امضای برنامه (Signing Key) در نسخه‌های جدید به‌شدت ممنوع است، مگر در شرایط ضروری و با درنظرگرفتن سازوکار رسمی انتقال کلید.

برای جلوگیری از مشکلات کاربران:

- از یک کلید امضای ثابت برای تمام نسخه‌های برنامه استفاده کنید.
- فایل Keystore و اطلاعات امضای برنامه را به‌صورت امن نگهداری کنید.
- پیش از انتشار نسخه جدید، سازگاری امضای آن با نسخه‌های قبلی را بررسی کنید.

تغییر امضای برنامه ممکن است باعث شود کاربران نتوانند نسخه جدید را روی نسخه قبلی نصب کنند و مجبور به حذف برنامه و از دست دادن اطلاعات محلی خود شوند.

مسئولیت مشکلات ناشی از تغییر غیرضروری امضای برنامه بر عهده توسعه‌دهنده است.

۶. نحوه ثبت برنامه

در حال حاضر، ثبت برنامه‌ها به‌صورت دستی انجام می‌شود.

برای درخواست ثبت برنامه، به حساب شخصی زیر مراجعه کنید:

Telegram: "@lumenapps" (https://t.me/lumenapps)

درخواست ثبت باید شامل موارد زیر باشد:

- نام برنامه.
- لینک مخزن GitHub.
- توضیح کوتاه درباره عملکرد برنامه.
- لینک آخرین Release معتبر.

در آینده، با هدف ساده‌سازی فرایند ثبت و کاهش نیاز به بررسی دستی، ربات اختصاصی برای ثبت و مدیریت برنامه‌ها در نظر گرفته خواهد شد.

۷. بررسی امنیتی برنامه‌ها

امنیت کاربران یکی از اولویت‌های اصلی Lumen Repository است.

پیش از انتشار، مخزن سورس‌کد برنامه‌ها کلون شده و با استفاده از ابزارهای بررسی مبتنی بر هوش مصنوعی (AI) از نظر مشکلات امنیتی احتمالی مورد بررسی قرار می‌گیرد.

این بررسی با هدف شناسایی مواردی از جمله موارد زیر انجام می‌شود:

- کدهای مخرب و رفتارهای مشکوک.
- دسترسی‌های غیرضروری و پرخطر.
- نشت احتمالی اطلاعات کاربران.
- آسیب‌پذیری‌های امنیتی شناخته‌شده.
- رفتارهای فریبنده یا ناقض حریم خصوصی.

با این حال، هیچ فرایند بررسی خودکاری نمی‌تواند امنیت صددرصدی یک نرم‌افزار را تضمین کند.

پذیرش یک برنامه در Lumen Repository به معنای تضمین نبود آسیب‌پذیری یا تأیید امنیت کامل آن نیست. کاربران نیز باید هنگام نصب نرم‌افزارها مسئولانه تصمیم بگیرند.

۸. حق رد، تعلیق و حذف برنامه‌ها

مدیریت Lumen Repository این حق را برای خود محفوظ می‌دارد که در صورت مشاهده موارد زیر، از پذیرش، انتشار یا ادامه میزبانی یک برنامه جلوگیری کند:

- نقض قوانین این مخزن.
- وجود کد مخرب یا رفتارهای تهدیدکننده امنیت کاربران.
- نقض حریم خصوصی یا جمع‌آوری غیرمجاز اطلاعات.
- ارائه اطلاعات جعلی یا گمراه‌کننده.
- انتشار نسخه‌های دستکاری‌شده یا ناسازگار.
- سوءاستفاده از زیرساخت Lumen Store.
- نقض حقوق مالکیت فکری اشخاص دیگر.

در صورت بروز مشکل، ممکن است برنامه تا زمان رفع ایرادات از ایندکس حذف یا انتشار به‌روزرسانی‌های آن متوقف شود.

۹. مسئولیت‌ها و محدودیت ضمانت

Lumen Repository بستری برای معرفی و توزیع برنامه‌های متن‌باز است و مسئولیت اصلی توسعه، نگهداری، انتشار و پشتیبانی هر برنامه بر عهده توسعه‌دهنده آن قرار دارد.

مدیریت مخزن تلاش می‌کند از طریق بررسی‌های امنیتی و کنترل فرایند انتشار، محیط قابل اعتمادتری برای کاربران فراهم کند؛ با این حال، هیچ تضمین مطلقی درباره عملکرد بدون خطا، امنیت کامل یا سازگاری تمام برنامه‌ها ارائه نمی‌شود.

---

🇬🇧 English

1. Terms of Use and User Rights

By using Lumen Repository or downloading applications distributed through it, you agree to the following terms:

- The repository may be used for lawful personal and commercial purposes, subject to the applicable licenses of individual projects.
- Any attempt to harm users, steal information, distribute malware, deceive users, or abuse repository infrastructure is strictly prohibited.
- Developers and users must respect intellectual property rights, software licenses, and the rights of third parties.
- No individual may claim to be an official owner, administrator, or representative of Lumen Repository without explicit authorization.
- Redistribution, modification, and reuse of repository content must comply with the applicable licenses and intellectual property requirements.
- Inclusion in Lumen Repository does not constitute a guarantee or complete security endorsement by its administrators.

2. Application Submission Requirements

Applications must meet all of the following requirements to be considered for inclusion.

2.1. Open Source

- Applications must be open source.
- Their source code must be publicly available on GitHub.
- Source repositories must be accessible for inspection and review.
- Closed-source releases without corresponding reviewable source code will not be accepted.

2.2. Build and Release Process

- APK files must be compiled through the project's GitHub Actions workflows.
- The build process should be transparent and verifiable.
- Released binaries must correspond to the published source code and declared application version.

2.3. Application Assets

Each project must store its application assets in:

".github/assets"

Required assets include:

- A high-quality application icon.
- Real screenshots of the application's interface.

Images must accurately represent the actual application and must not mislead users about its features or functionality.

2.4. Versioning and Release Tags

- Release tags must follow a consistent and sequential versioning scheme.
- Tag versions, APK versions, and internal application version information must match.
- Every release tag must contain at least one APK with a matching version.
- Inconsistent, duplicated, or incorrectly formatted tags may interfere with automatic version detection and update delivery.

2.5. Release Notes

Lumen Store retrieves application descriptions from the README file attached to each GitHub Release.

Developers are strongly encouraged to provide complete release notes, including:

- New features.
- Improvements and changes.
- Bug fixes.
- Security updates.
- Important installation or upgrade instructions.

Incomplete release notes directly affect the quality of information presented to users.

3. Automatic Updates and Developer Responsibilities

After an application has been initially accepted and registered in the index, subsequent releases will be automatically processed and published through Lumen Store based on the GitHub Release tags of the application's repository.

The automated process includes:

- Detecting new releases.
- Retrieving release information from the corresponding README.
- Processing and selecting compatible APK files.

Developers are fully responsible for maintaining correct version information, consistent release tags, compatible APK files, and a reliable update process.

Issues caused by incorrect version detection, missing updates, or incompatible releases resulting from improper tagging must be resolved by the application maintainer.

4. Automatic Architecture Detection

Lumen Store automatically detects the user's device architecture and selects the appropriate APK from the available release assets.

If your application supports multiple architectures, providing separate APK files for each supported architecture is recommended.

For example:

- "app-arm64-v8a.apk"
- "app-armeabi-v7a.apk"
- "app-x86_64.apk"
- "app-universal.apk"

Proper APK naming and architecture-specific releases help improve compatibility and file selection.

5. Application Signing and Digital Signatures

Changing an application's signing key between releases is strongly prohibited unless absolutely necessary and handled through a proper signing-key migration process.

To prevent installation and update problems:

- Use the same signing key for all releases.
- Store your Keystore and signing credentials securely.
- Verify signature compatibility before publishing new versions.

Changing the signing key may prevent users from installing an update over their existing installation, potentially requiring them to uninstall the application and lose locally stored data.

Developers are responsible for problems resulting from unnecessary signing-key changes.

6. Application Submission

Currently, application submissions are handled manually.

To request inclusion in Lumen Repository, contact the following account:

Telegram: "@lumenapps" (https://t.me/lumenapps)

Please provide:

- Application name.
- GitHub repository URL.
- A brief description of the application.
- A link to the latest valid release.

An automated submission bot is planned for the future to simplify registration and reduce manual intervention.

7. Security Review

User security is one of the primary priorities of Lumen Repository.

Before publication, application source repositories are cloned and examined using AI-assisted security analysis tools.

The review aims to identify potential issues, including:

- Malicious code and suspicious behavior.
- Unnecessary or dangerous permissions.
- Potential user data exposure.
- Known security vulnerabilities.
- Deceptive behavior or privacy violations.

However, automated security analysis cannot guarantee that software is completely secure or free from vulnerabilities.

Acceptance into Lumen Repository does not constitute a guarantee of complete security. Users should always exercise caution when installing software.

8. Right to Reject, Suspend, or Remove Applications

The Lumen Repository administration reserves the right to reject, suspend, or remove applications in cases involving:

- Violations of repository policies.
- Malicious code or behavior that threatens user security.
- Privacy violations or unauthorized data collection.
- False or misleading information.
- Modified, tampered, or incompatible releases.
- Abuse of Lumen Store infrastructure.
- Violations of third-party intellectual property rights.

Applications may be temporarily removed from the index or have their updates suspended until identified issues are resolved.

9. Responsibilities and Disclaimer

Lumen Repository serves as an indexing and distribution platform for open-source applications. The primary responsibility for application development, maintenance, releases, and support remains with the respective developers.

The repository administration strives to provide a more reliable environment through security reviews and release validation. Nevertheless, no absolute guarantee is provided regarding uninterrupted operation, complete security, or compatibility across all devices.

---

Links

- Lumen Repository: https://github.com/deepcodecreate/lumenrepo
- Lumen Store: https://github.com/deepcodecreate/lumenstore
- Application Submission: https://t.me/lumenapps

---

Lumen Repository — Open Source, Transparency, and User Trust.