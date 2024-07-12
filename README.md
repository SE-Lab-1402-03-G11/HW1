<div dir="rtl">

# گزارش کار

این فایل شامل گزارش مربوط به اولین آزمایش درس آزمایشگاه نرم‌افزار است. اعضای گروه یازدهم علی رحمی‌زاد، بهزاد نبوی، و مهدی قائم‌پناه هستند که از میان آن‌ها علی رحمی‌زاد به عنوان سرگروه این آزمایش انتخاب شد.

### پیش از شروع کار

پیش از آن که خود فرایند انجام دادن کار آغاز شود، اعضای گروه به مطالعه‌ی منابع معرفی‌شده برای انجام دادن این آزمایش پرداختند. یعنی ویدئوی آشنایی با گیت را مشاهده کردند، و به کمک لینک‌های ارائه‌شده نحوه‌ی صحیح نام‌گذاری Branch و Commit را یاد گرفتند، با Kanban Board گیتهاب آشنا شدند، و ...

### تقسیم وظایف

در ابتدا برای تقسیم وظایف میان اعضای گروه یک جلسه تشکیل شد. علی رحمی‌زاد به عنوان سرگروه و Product Owner این آزمایش انتخاب شد و وظیفه‌ی مدیریت Kanban Board به او سپرده شد.

برای آن که فرایند توسعه آغاز شود، تعدادی از مواردی که باید انجام می‌شدند در Kanban Board تعریف شدند. این موارد در ابتدا بسیار ناقص بودند و به مرور زمان و پس از آن که کار کمی پیش رفت کامل‌تر شدند. اضافه کردن موارد جدید به Backlog از وظایف علی رحمی‌زاد به عنوان PO بود و تمامی اعضای گروه حواسشان به رعایت کردن این مورد بود.

### موضوع پروژه

همچنین اعضای گروه تصمیم گرفتند برای این تمرین یک باغ وحش مجازی را به کمک تصاویر گوناگون پیاده‌سازی کنند. تصمیم گرفته شد که این صفحه‌ی Static فقط به کمک یک فایل html تولید شود.

### دستورات Git

به کمک برگه‌ی تقلبی که ارائه شده‌بود اعضای گروه با دستورات مختلف Git آشنا شدند و از آن‌ها استفاده کردند. همان‌طور که از لاگ مخزن گیتهاب مشخص است، اعضای گروه از دستورات متعددی برای انجام کارهای مربوط به راه‌اندازی، اضافه کردن فایل‌ها به مخزن، مدیریت شاخه‌ها، مشاهده و مقایسه‌ی تعارضات (conflicts)، و حتی بازگرداندن کامیت‌ها استفاده کردند.

### gitignore

از یک فایل gitignore استفاده کردیم تا موارد DS_Store که توسط سیستم عامل MacOS تولید می‌شدند در فعالیت داخل نشوند.

### شاخه‌ها

برای آن که موارد گوناگون پیاده‌سازی شوند، از شاخه‌های مختلفی استفاده کردیم و فعالیت‌ها را از شاخه‌ی main جدا کردیم. مثلا برای آن که تصاویر و توضیحات مربوط به پرندگان را آماده کنیم، یک شاخه‌ی جدا ساختیم. در ساختن شاخه‌ها قواعد نام‌گذاری آن‌ها را هم مورد توجه قرار دادیم.

### تعارضات

سه بار به شکل‌های گوناگون تعارضاتی که ممکن است در یک پروژه پیش بیایند را شبیه‌سازی کردیم که در ادامه می‌توانید مستندات مربوط به آن‌ها را مشاهده کنید:

- تعارض اول:
    - ![تعارض اول - تصویر اول](https://github.com/SE-Lab-1402-03-G11/HW1/blob/main/screenshots/conflict1_1.png)
    - ![تعارض اول - تصویر دوم](https://github.com/SE-Lab-1402-03-G11/HW1/blob/main/screenshots/conflict1_2.png)
- تعارض دوم:
    - ![تعارض دوم - تصویر اول](https://github.com/SE-Lab-1402-03-G11/HW1/blob/main/screenshots/conflict2_1.png)
    - ![تعارض دوم - تصویر دوم](https://github.com/SE-Lab-1402-03-G11/HW1/blob/main/screenshots/conflict2_2.png)
- تعارض سوم:
    - ![تعارض سوم - تصویر اول](https://github.com/SE-Lab-1402-03-G11/HW1/blob/main/screenshots/conflict3_1.png)
    - ![تعارض سوم - تصویر دوم](https://github.com/SE-Lab-1402-03-G11/HW1/blob/main/screenshots/conflict3_2.png)

### محافظت از شاخه‌ی main

همان‌طور که از ما خواسته شده‌بود تنظیمات مخزن را طوری تغییر دادیم که امکان ادغام دیگر شاخه‌ها با این شاخه به جز از طریق pull request وجود نداشته باشد.

### ادغام صحیح

هرگاه نیاز شد شاخه‌ها را با یکدیگر ادغام کنیم، این کار را به درستی و به کمک pull request انجام دادیم.

### استقرار

با استفاده از deploy.yaml کار استقرار را انجام دادیم. هم‌اکنون این صفحه از طریق [این آدرس](https://se-lab-1402-03-g11.github.io/HW1/template.html) در دسترس است.

### موارد استفاده از هوش مصنوعی

برای آن که محتویات سایت را آماده کنیم از هوش مصنوعی chatGPT استفاده کردیم. همچنین قالب فایل html که از اهداف این آزمایش نبود هم توسط همین هوش مصنوعی برایمان آماده شد.

### پاسخ به سوالات

- **سوال اول:**

برای آن که Git بتواند نسخه‌های گوناگون را کنترل کند، لازم است تغییراتی که در کدها انجام می‌شود را ردیابی کند. اطلاعاتی که Git برای ردیابی کردن این تغییرات نیاز دارد، در پوشه‌ای به نام .git نگه‌داری می‌شود. از آن‌جا که این پوشه مخصوص پوشه‌هایی است که از Git برای مدیریت نسخه‌ها استفاده می‌کنند، پس از دستور git init ساخته می‌شود.

- **سوال دوم:**

در عبارت atomic commit منظور از عبارت atomic آن است که فرض می‌شود همه‌ی تغییراتی که در این کامیت انجام شده‌اند، هم‌زمان رخ داده‌اند و به عنوان یک واحد تغییر در مخزن اعمال شده‌اند. اگر کامیت‌ها این شرط را داشته باشند می‌توان در صورت وقوع هرگونه مشکلی دقیقا یک گام یک گام کد را بع عقب برگرداند و همچنین می‌توان وضعیت مخزن را در هر لحظه به شکل دقیق و مجزا مشاهده کرد. نقش این عبارت در عبارت atomic pull request هم دقیقا همین است.

- **سوال سوم:**

    - fetch: موارد جدید را از مخزن اصلی دانلود می‌کند و بدون آن که آن‌ها را ادغام کند، به مخزن محلی می‌ریزد.
    - pull: موارد جدید را از مخزن اصلی دانلود می‌کند و با شاخه‌ی فعلی مخزن محلی ادغام می‌کند.
    - merge: یک شاخه‌ی دیگر را با شاخه‌ی فعلی ادغام می‌کند.
    - rebase: یک زنجیره از کامیت‌های متوالی را از شاخه‌ی فعلی به یک جای دیگر می‌برد و آن‌ها را با همین ترتیب اجرا می‌کند.
    - cherry-pick: تغییرات یک کامیت خاص را روی شاخه‌ی فعلی اعمال می‌کند.
    
- **سوال چهارم:**

    - reset: اشاره‌گر HEAD را به به یک کامیت دیگر منتقل می‌کند
    - revert: با ایجاد کردن یک commit جدید تغییرات انجام‌شده توسط یک کامیت خاص را با حفظ تاریخچه برمی‌گرداند.
    - restore: فایل های درخت کار را از index یا یک commit خاص بازیابی می‌کند؛ بدون آن که تاریخچه را تغییر دهد.
    - switch:شاخه‌ها را تغییر می‌دهد یا فایل‌های درختیکار را بازیابی می‌کند.
    - checkout: یک دستور چند منظوره است که برای تغییر شاخه‌ها، بازیابی فایل‌ها، و یا بررسی کردن commit یا مسیرهای خاص استفاده می‌شود.

- **سوال پنجم:**

stage یک منطقه میانی است که در آن تغییرات یک کامیت قبل از آن که وارد مخزن شوند، آماده می‌شوند. وقتی از دستور git add استفاده می کنید، تغییرات برای انجام شدن آماده می‌شوند. Index تغییراتی را که قرار است در کامیت بعدی اعمال کنید، پیگیری می‌کند.

دستور git stash برای ذخیره موقت تغییراتی که در Index ایجاد کرده‌اید، استفاده می‌شود و به شما امکان می‌دهد بدون آن که این تغییرات اعمال شوند، به یک حالت کاری بدون تغییر منتقل شوید. اگر در میانه‌ی انجام یک کار باشید و سپس لازم شود به سراغ یک کار دیگر بروید از این دستور استفاده می‌کنید تا تغییرات کار اولی یک جا نگه داشته شوند ولی فعلا اعمال نشوند.

- **سوال ششم:**

یک اسنپ‌شات به وضعیت کلی یک پروژه در یک لحظه‌ی خاص از زمان اشاره می‌کند. وقتی که یک چیزی را کامیت می‌کنید، Git یک اسنپ‌شات جدید، که شامل تمامی فایل‌های پروژه می‌شود، ایجاد می‌کند. این اسنپ‌شات وضعیت دقیق هر فایل را در آن زمان ثبت می کند. در واقع آن چه که تفاوت میان دو اسنپ‌شات متوالی را نشان می‌دهد یک کامیت است که تغییرات در آن اعلام شده‌اند.

- **سوال هفتم:**

یک مخزن محلی در کامپیوتر محلی شما قرار دارد. این مخزن محلی یک محیط کاری برای توسعه‌دهندگان است. این محیط به توسعه‌دهندگان اجازه می‌دهد تا تغییراتی در پروژه ایجاد کنند، ویژگی‌های جدید را بیازمایند، و تغییرات را قبل از به اشتراک گذاشتن بررسی کنند.

یک مخزن ریموت بر روی یک سرور میزبانی می شود؛معمولا در پلتفرمی مانند GitHub، GitLab، Bitbucket یا یک سرور خصوصی. این به عنوان یک مکان مرکزی عمل می کند که در آن چندین توسعه‌دهنده می‌توانند در یک پروژه همکاری کنند. هدف اصلی یک مخزن از راه دور آسان کردن همکاری و اشتراک گذاری بین چندین توسعه‌دهنده است. این محیط به عنوان یک مکان متمرکز عمل می‌کند که در آن توسعه‌دهندگان می‌توانند تغییرات خود را اعمال کنند، کد را با دیگران به اشتراک بگذارند، و کار خود را با اعضای تیم همگام کنند.

برای از دست نرفتن اطلاعات ضروری است که به طور مرتب از مخزن محلی خود نسخه پشتیبان تهیه کنید. یک مخزن ریموت به عنوان یک پشتیبان و افزونگی برای کد پروژه شما عمل می‌کند تا اگر دستگاه شما با خرابی سخت‌افزاری یا دیگر مشکلات  مواجه شود، کل پروژه از دست نرود.