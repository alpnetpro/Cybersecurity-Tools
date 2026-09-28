---
title: "راهنمای ابزارهای سایبرسکیوریتی"
author: "Alp Gokturk & ChatGPT ai"
version: "1"
date: "2026-09-28"
location: "Istanbul"
email: "alpnetpro@gmail.com"
github: "https://github.com/Alpnetpro"
folder: "Cybersecurity Tools"
language: "fa"
---

<div dir="rtl">

# راهنمای ابزارهای سایبرسکیوریتی

این گزارش کاری از آلپ گوکتورک است که با بهره‌گیری از توانمندی هوش مصنوعی ChatGPT تهیه شده است.

**Alp Gokturk & ChatGPT ai**

**نسخهٔ ۱ | ۶ مهر ۱۴۰۵ | 2026-09-28 | استانبول**

اگر اشکالی دیدید یا پیشنهادی دارید، لطفاً ایمیل بزنید.

[alpnetpro@gmail.com](mailto:alpnetpro@gmail.com)

GitHub: [https://github.com/Alpnetpro](https://github.com/Alpnetpro)

آخرین نسخهٔ این گزارش از گیت‌هاب من، در پوشهٔ Cybersecurity Tools قابل دانلود است.

## فهرست مطالب

شمارهٔ صفحات مربوط به فایل PDF هم‌زبان است. عنوان‌ها به بخش‌های همین فایل Markdown پیوند دارند.

| عنوان | صفحه |
|---|---:|
| [۱. دامنه، DNS و اطلاعات ثبت](#s1) | 3 |
| [۲. گواهی دیجیتال، TLS، Wi-Fi و سازندهٔ دستگاه](#s2) | 5 |
| [۳. مالکیت IP، مسیریابی و مدیریت سطح حمله](#s3) | 7 |
| [۴. منابع تکنیک‌های حمله و مطالعهٔ دفاعی](#s4) | 9 |
| [۵. کد، پروژه‌های متن‌باز و API](#s5) | 11 |
| [۶. اطلاعات وب‌سایت و جست‌وجوی آرشیوی](#s6) | 15 |
| [۷. یافتن یا بررسی ایمیل](#s7) | 17 |
| [۸. جست‌وجو و بررسی تصویر](#s8) | 20 |
| [۹. شماره تلفن؛ محدودیت دقت و پوشش](#s9) | 22 |
| [۱۰. موتورهای عمومی جست‌وجو](#s10) | 24 |

<a id="s1"></a>

## ۱. دامنه، DNS و اطلاعات ثبت

### DomainIQ

تحقیق دربارهٔ دامنه و IP با استفاده از داده‌های گردآوری‌شده و تاریخی.

[https://www.domainiq.com/](https://www.domainiq.com/)

### Who.is

بررسی اطلاعات ثبت دامنه با WHOIS و RDAP، همراه با DNS و نام‌سرورها.

[https://who.is/](https://who.is/)

### Whoisology

آرشیو اطلاعات WHOIS برای بررسی تاریخچه و ارتباط دامنه‌ها؛ داده‌های قدیمی لزوماً وضعیت فعلی نیستند.

[https://whoisology.com/](https://whoisology.com/)

### WhoisXML API

مجموعهٔ APIهای WHOIS، DNS، دامنه و IP برای تحقیق و اتوماسیون.

[https://www.whoisxmlapi.com/](https://www.whoisxmlapi.com/)

### SpyOnWeb

یافتن ارتباط احتمالی سایت‌ها از ویژگی‌های فنی مشترک؛ اشتراک ویژگی اثبات مالکیت مشترک نیست.

[https://spyonweb.net/](https://spyonweb.net/)

### SynapsInt

جست‌وجوی دامنه، IP، ASN، SSL و ایمیل در یک رابط.

[https://synapsint.com/](https://synapsint.com/)

### C99 API

مجموعهٔ APIهای استعلام و ابزارهای فنی؛ امکانات و سهمیه به سرویس انتخابی وابسته است.

[https://api.c99.nl/](https://api.c99.nl/)

<a id="s2"></a>

## ۲. گواهی دیجیتال، TLS، Wi-Fi و سازندهٔ دستگاه

### crt.sh

جست‌وجوی گواهی با دامنه، سازمان یا اثرانگشت؛ مناسب تحقیق Certificate Transparency.

[https://crt.sh/](https://crt.sh/)

### Cert Spotter

پایش گواهی‌های صادرشده برای دامنه و شناسایی مشکلات امنیتی یا دسترس‌پذیری گواهی.

[https://sslmate.com/certspotter/](https://sslmate.com/certspotter/)

### CipherSuite.info

مرجع قابل جست‌وجوی مجموعه‌رمزهای TLS و جزئیات امنیتی آن‌ها.

[https://ciphersuite.info/](https://ciphersuite.info/)

### Certs.io

جست‌وجوی گواهی‌های TLS برای یافتن دارایی‌های مرتبط با دامنه و سازمان؛ عملکرد حساب در متن مبنا آزمایش نشده است.

[https://certs.io/](https://certs.io/)

### WiGLE

گردآوری و نقشه‌برداری مشاهدات شبکه‌های بی‌سیم؛ فهرست شبکه‌های مجاز برای اتصال عمومی نیست.

[https://wigle.net/](https://wigle.net/)

### WiFi Map

یافتن نقاط اتصال Wi-Fi؛ کاربرد بیشتر در اتصال و سفر تا تحلیل تخصصی امنیت.

[https://www.wifimap.io/](https://www.wifimap.io/)

### OpenWiFiMap

پروژهٔ متن‌باز نقشهٔ شبکه‌های بی‌سیم اجتماعی، مانند شبکه‌های Freifunk.

[https://openwifimap.net/](https://openwifimap.net/)

### MACVendors

یافتن سازندهٔ ثبت‌شدهٔ محدودهٔ MAC با داده‌های IEEE.

[https://macvendors.com/](https://macvendors.com/)

### MACAddress.io

استعلام سازنده و مشخصات بلوک MAC، با API مناسب اسکریپت‌های شبکه.

[https://macaddress.io/](https://macaddress.io/)

### MACLookup

جست‌وجوی سازنده از روی MAC یا OUI؛ مناسب بررسی اولیهٔ تجهیزات.

[https://maclookup.app/](https://maclookup.app/)

### MACVendorLookup

تطبیق MAC با اطلاعات سازندهٔ ثبت‌شده.

[https://www.macvendorlookup.com/](https://www.macvendorlookup.com/)

<a id="s3"></a>

## ۳. مالکیت IP، مسیریابی و مدیریت سطح حمله

### FullHunt

کشف و پایش دارایی‌های اینترنتی سازمان برای مدیریت سطح حمله.

[https://fullhunt.io/](https://fullhunt.io/)

### RedHunt Labs

شناسایی دارایی‌های بیرونی و ریسک‌های امنیتی با پایش مستمر.

[https://redhuntlabs.com/](https://redhuntlabs.com/)

### Deepinfo

مدیریت مواجهه با تهدید و بررسی دارایی‌ها و ریسک‌های بیرونی.

[https://www.deepinfo.com/](https://www.deepinfo.com/)

### IPinfo

اطلاعات IP، شبکه و موقعیت تقریبی؛ برای غنی‌سازی لاگ و شناخت ارائه‌دهندهٔ شبکه.

[https://ipinfo.io/](https://ipinfo.io/)

### ipdata

API اطلاعات موقعیت و ویژگی‌های IP برای تحلیل، فیلتر و اتوماسیون.

[https://ipdata.co/](https://ipdata.co/)

### NetworksDB

بررسی ارتباط شرکت‌ها با محدوده‌های IP، دامنه و اطلاعات شبکه.

[https://networksdb.io/](https://networksdb.io/)

### BGP.tools

بررسی ASN، پیشوندهای IP و روابط مسیریابی؛ مفید برای یادگیری و عیب‌یابی BGP.

[https://bgp.tools/](https://bgp.tools/)

### BigDataCloud

APIهای موقعیت تقریبی IP و داده‌های جغرافیایی و شبکه‌ای.

[https://www.bigdatacloud.com/](https://www.bigdatacloud.com/)

### RADb

پایگاه ثبت اطلاعات مسیریابی اینترنت؛ بررسی اشیای Route و سیاست‌های ثبت‌شده.

[https://www.radb.net/](https://www.radb.net/)

### Cloudflare Radar

مشاهدهٔ روند ترافیک، اختلال‌ها، حملات و فناوری‌های اینترنت در مقیاس کلان.

[https://radar.cloudflare.com/](https://radar.cloudflare.com/)

### Pentest-Tools

مجموعهٔ ابزارهای تست نفوذ و اسکن برای ارزیابی دارایی‌های تحت مجوز.

[https://pentest-tools.com/](https://pentest-tools.com/)

<a id="s4"></a>

## ۴. منابع تکنیک‌های حمله و مطالعهٔ دفاعی

این موارد عمدتاً مرجع تحقیق و آموزش هستند، نه موتور جست‌وجوی عمومی.

### Hacking the Cloud

دانشنامهٔ تکنیک‌های امنیت تهاجمی در محیط‌های ابری؛ مفید برای شناخت ریسک پیکربندی‌ها.

[https://hackingthe.cloud/](https://hackingthe.cloud/)

### LOLDrivers

اطلاعات درایورهای آسیب‌پذیر یا مخرب ویندوز؛ برای تحقیق و ساخت قواعد تشخیص.

[https://www.loldrivers.io/](https://www.loldrivers.io/)

### LOOBins

روش‌های سوءاستفاده از ابزارهای داخلی macOS؛ برای تحلیل رفتار و دفاع.

[https://loobins.io/](https://loobins.io/)

### WADComs

مرجع ابزارها و فرمان‌های ارزیابی Windows و Active Directory در آزمایش‌های مجاز.

[https://wadcoms.github.io/](https://wadcoms.github.io/)

### Living Off the Pipeline

مستندسازی سوءاستفادهٔ احتمالی از ابزارهای CI/CD؛ مناسب امنیت زنجیرهٔ توسعه.

[https://boostsecurityio.github.io/lotp/](https://boostsecurityio.github.io/lotp/)

### LOLAPPS

فهرست برنامه‌های عادی که قابلیت‌هایشان ممکن است در حملات سوءاستفاده شود.

[https://lolapps-project.github.io/](https://lolapps-project.github.io/)

### LOTHardware

کاتالوگ سخت‌افزارهای مرتبط با حملات، از جمله ابزارهای USB و HID.

[https://lothardware.com.tr/](https://lothardware.com.tr/)

### CVExploits

جست‌وجوی منابع اکسپلویت مرتبط با CVE؛ نتیجه باید با نسخه و شرایط واقعی تطبیق داده شود.

[https://cvexploits.io/](https://cvexploits.io/)

### Exploit Observer

گردآوری اطلاعات آسیب‌پذیری و اکسپلویت و ارائهٔ API؛ ادعای «بزرگ‌ترین» در متن مبنا تأیید نشده است.

[https://www.exploit.observer/](https://www.exploit.observer/)

### Coalition Exploit Scoring System

امتیازدهی احتمال بهره‌برداری از آسیب‌پذیری برای کمک به اولویت‌بندی.

[https://ess.coalitioninc.com/](https://ess.coalitioninc.com/)

<a id="s5"></a>

## ۵. کد، پروژه‌های متن‌باز و API

### GitHub Code Search

جست‌وجوی کد، توابع و نمونه‌های پیاده‌سازی در مخازن قابل دسترسی.

[https://github.com/search?type=code](https://github.com/search?type=code)

### GitLab

میزبانی پروژه و جست‌وجوی کد و محتوای مخزن؛ امکانات به تنظیمات و پلن وابسته است.

[https://gitlab.com/](https://gitlab.com/)

### grep.app

جست‌وجوی عبارت و قطعه‌کد در مخازن عمومی؛ مناسب یافتن نمونهٔ استفاده از توابع.

[https://grep.app/](https://grep.app/)

### Sourcegraph

جست‌وجو و فهم کد در پروژه‌ها و مخازن برای توسعه و تحلیل نرم‌افزار.

[https://sourcegraph.com/](https://sourcegraph.com/)

### Searchcode

تحلیل مخزن و جست‌وجوی کد، با API و MCP برای دستیارهای برنامه‌نویسی.

[https://searchcode.com/](https://searchcode.com/)

### PublicWWW

جست‌وجوی عبارت در کد صفحات وب؛ یافتن فناوری یا قطعه‌کد مشترک.

[https://publicwww.com/](https://publicwww.com/)

### NerdyData

شناسایی سایت‌های استفاده‌کننده از فناوری‌های مشخص با بررسی کد وب.

[https://www.nerdydata.com/](https://www.nerdydata.com/)

### Veloria (WP Directory سابق)

جست‌وجوی کد وردپرس برای تحقیق دربارهٔ افزونه‌ها و قالب‌ها.

[https://veloria.dev/](https://veloria.dev/)

### GitHub Gist

انتشار و جست‌وجوی قطعه‌کد، یادداشت فنی و اسکریپت‌های کوتاه.

[https://gist.github.com/](https://gist.github.com/)

### SourceForge

میزبانی و کشف پروژه‌ها و نرم‌افزارها؛ هر پروژه باید جداگانه ارزیابی شود.

[https://sourceforge.net/](https://sourceforge.net/)

### Codeberg

بستر همکاری و میزبانی Git برای پروژه‌های متن‌باز.

[https://codeberg.org/](https://codeberg.org/)

### Launchpad

میزبانی توسعه، گزارش اشکال و همکاری روی پروژه‌ها، به‌ویژه در اکوسیستم Ubuntu.

[https://launchpad.net/](https://launchpad.net/)

### SourceHut

مجموعهٔ ابزارهای میزبانی و همکاری توسعهٔ نرم‌افزار.

[https://sourcehut.org/](https://sourcehut.org/)

### Android Open Source

مخازن رسمی کد Android؛ برای مطالعهٔ پیاده‌سازی سیستم‌عامل و اجزای آن.

[https://android.googlesource.com/](https://android.googlesource.com/)

### deps.dev

اطلاعات بسته‌های متن‌باز و وابستگی‌های آن‌ها؛ شناخت زنجیرهٔ تأمین نرم‌افزار.

[https://deps.dev/](https://deps.dev/)

### ecosyste.ms

داده‌ها و APIهای پروژه‌ها، بسته‌ها و وابستگی‌های متن‌باز.

[https://ecosyste.ms/](https://ecosyste.ms/)

### Postman Explore

کشف APIها و مجموعه‌درخواست‌های عمومی؛ تمرین API و اتوماسیون.

[https://www.postman.com/explore](https://www.postman.com/explore)

### Swagger

ابزارهای طراحی، مستندسازی و آزمون API.

[https://swagger.io/product/](https://swagger.io/product/)

### HotExamples

نمونه‌های کد برای مطالعه؛ نمونهٔ پیدا‌شده لزوماً امن یا به‌روز نیست.

[https://hotexamples.com/](https://hotexamples.com/)

### Snipplr

مخزن اشتراک قطعه‌کد؛ نمونه‌ها نیازمند بررسی کیفیت هستند.

[https://snipplr.com/](https://snipplr.com/)

### Google Code Archive

آرشیو تاریخی پروژه‌های Google Code؛ سرویس فعال میزبانی پروژهٔ جدید نیست.

[https://code.google.com/archive/](https://code.google.com/archive/)

<a id="s6"></a>

## ۶. اطلاعات وب‌سایت و جست‌وجوی آرشیوی

### Intelligence X

جست‌وجوی دامنه، ایمیل، IP و سایر شناسه‌ها در مجموعه‌های آرشیوی و داده‌های گردآوری‌شده.

[https://intelx.io/](https://intelx.io/)

### Phonebook.cz

یافتن دامنه، ایمیل و URL مرتبط با یک دامنه؛ متن مبنا نیاز به مجوز پولی را ذکر می‌کند.

[https://phonebook.cz/](https://phonebook.cz/)

### Common Crawl Index

جست‌وجو در نمایهٔ URLهای آرشیو Common Crawl برای بررسی آثار قدیمی وب.

[https://index.commoncrawl.org/](https://index.commoncrawl.org/)

### BuiltWith

شناسایی فناوری‌های وب‌سایت، مانند سیستم مدیریت محتوا و ابزارهای تحلیلی.

[https://builtwith.com/](https://builtwith.com/)

### Netcraft Site Report

گزارش دربارهٔ فناوری و زیرساخت میزبانی وب‌سایت.

[https://sitereport.netcraft.com/](https://sitereport.netcraft.com/)

### GrayhatWarfare - Buckets

جست‌وجوی منابع ذخیره‌سازی ابری نمایان در اینترنت.

[https://buckets.grayhatwarfare.com/](https://buckets.grayhatwarfare.com/)

### GrayhatWarfare - Shorteners

جست‌وجوی URLهای گردآوری‌شده از سرویس‌های کوتاه‌کنندهٔ لینک.

[https://shorteners.grayhatwarfare.com/](https://shorteners.grayhatwarfare.com/)

### Similarweb

تحلیل و برآورد ترافیک و جایگاه رقابتی سایت‌ها؛ آمار لزوماً دادهٔ مستقیم مالک سایت نیست.

[https://www.similarweb.com/](https://www.similarweb.com/)

### HypeStat

آمار و تحلیل وب‌سایت؛ بیشتر برای تحقیق وب و بازاریابی.

[https://hypestat.com/](https://hypestat.com/)

### StatsCrop

گزارش‌های عمومی دربارهٔ ترافیک، SEO و ویژگی‌های سایت.

[https://www.statscrop.com/](https://www.statscrop.com/)

### ExpiredDomains

یافتن دامنه‌های منقضی یا در حال حذف؛ ابزار تجارت و تحقیق دامنه.

[https://www.expireddomains.net/](https://www.expireddomains.net/)

<a id="s7"></a>

## ۷. یافتن یا بررسی ایمیل

این ابزارها سرویس ساخت ایمیل حرفه‌ای نیستند؛ برای یافتن اطلاعات تماس، بررسی قابلیت تحویل یا ارزیابی اعتبار ایمیل استفاده می‌شوند.

### Hunter.io

یافتن و بررسی ایمیل‌های حرفه‌ای مرتبط با شرکت‌ها و دامنه‌ها.

[https://hunter.io/](https://hunter.io/)

### Reacher

سرویس و API متن‌باز اعتبارسنجی ایمیل برای توسعه‌دهندگان.

[https://reacher.email/](https://reacher.email/)

### Email Hippo

اعتبارسنجی ایمیل و کاهش آدرس‌های نامعتبر و ثبت‌نام‌های مشکوک.

[https://www.emailhippo.com/](https://www.emailhippo.com/)

### Melissa

بررسی و بهبود کیفیت داده‌های تماس، شامل ایمیل و آدرس.

[https://www.melissa.com/](https://www.melissa.com/)

### VoilaNorbert

یافتن و تأیید ایمیل کاری بر اساس اطلاعات فرد و شرکت.

[https://www.voilanorbert.com/](https://www.voilanorbert.com/)

### FindEmails

جست‌وجو و اعتبارسنجی آدرس‌های ایمیل.

[https://www.findemails.com/](https://www.findemails.com/)

### EXPERTE Email Finder

یافتن ایمیل حرفه‌ای با اطلاعات نام و دامنهٔ شرکت.

[https://www.experte.com/email-finder](https://www.experte.com/email-finder)

### Anymail Finder

یافتن ایمیل تجاری با فرایند بررسی قابلیت تحویل.

[https://anymailfinder.com/](https://anymailfinder.com/)

### Tomba

جست‌وجو و غنی‌سازی اطلاعات تماس و ایمیل‌های تجاری.

[https://tomba.io/](https://tomba.io/)

### Snov.io

یافتن و بررسی اطلاعات تماس و مدیریت ارتباطات فروش.

[https://snov.io/](https://snov.io/)

### EmailRep

بررسی اعتبار و نشانه‌های ریسک آدرس ایمیل؛ برای تحلیل ایمیل مشکوک.

[https://emailrep.io/](https://emailrep.io/)

### MailboxValidator

بررسی اعتبار ایمیل با رابط وب و API.

[https://www.mailboxvalidator.com/](https://www.mailboxvalidator.com/)

### ContactOut

یافتن اطلاعات تماس حرفه‌ای؛ بیشتر ابزار استخدام و فروش.

[https://contactout.com/](https://contactout.com/)

### Email-format

بررسی الگوی ساخت ایمیل در شرکت‌ها، مانند name.surname@company.

[https://www.email-format.com/](https://www.email-format.com/)

### Emailable

مقصد فعلی Verify-email.org در متن مبنا؛ بررسی فهرست ایمیل و قابلیت تحویل.

[https://emailable.com/](https://emailable.com/)

### Emailsearch.io

جست‌وجوی اطلاعات تماس تجاری بر اساس نام، شرکت یا دامنه.

[https://emailsearch.io/](https://emailsearch.io/)

### EmailSherlock

جست‌وجوی معکوس ایمیل و اطلاعات مرتبط؛ نتیجه سرنخ تحقیق است، نه اثبات هویت.

[https://www.emailsherlock.com/](https://www.emailsherlock.com/)

<a id="s8"></a>

## ۸. جست‌وجو و بررسی تصویر

### TinEye

جست‌وجوی معکوس تصویر برای یافتن نسخه‌های منتشرشده و استفاده‌های دیگر از همان عکس.

[https://tineye.com/](https://tineye.com/)

### Pixsy

پایش استفاده از عکس‌ها و کمک به پیگیری استفادهٔ بدون مجوز.

[https://www.pixsy.com/](https://www.pixsy.com/)

### Jimpl

نمایش فراداده و EXIF تصویر؛ مانند زمان ثبت و اطلاعات دوربین.

[https://jimpl.com/](https://jimpl.com/)

### EXIFdata

مشاهده، ویرایش و حذف EXIF؛ متن مبنا پردازش در مرورگر را ذکر می‌کند.

[https://www.exifdata.com/](https://www.exifdata.com/)

### PimEyes

جست‌وجوی تصاویر چهرهٔ مشابه در وب؛ شباهت تصویری اثبات هویت نیست.

[https://pimeyes.com/en](https://pimeyes.com/en)

### FaceCheck

جست‌وجوی عکس‌های چهرهٔ مشابه؛ برای تأیید قطعی هویت کافی نیست.

[https://facecheck.id/](https://facecheck.id/)

### Pictriev

جست‌وجوی شباهت چهره؛ بیشتر سرگرمی و مقایسه تا تحلیل معتبر هویت.

[https://www.pictriev.com/](https://www.pictriev.com/)

### Same Energy

جست‌وجوی تصاویر دارای سبک و ظاهر مشابه؛ ابزار الهام بصری.

[https://same.energy/](https://same.energy/)

### Flickr

انتشار و جست‌وجوی عکس؛ منبع عمومی تصویر، نه ابزار تخصصی امنیت.

[https://www.flickr.com/](https://www.flickr.com/)

### Pixabay

کتابخانهٔ محتوای تصویری؛ جایگاه مستقیمی در ابزارهای تخصصی امنیت ندارد.

[https://pixabay.com/](https://pixabay.com/)

<a id="s9"></a>

## ۹. شماره تلفن؛ محدودیت دقت و پوشش

این سرویس‌ها شناسایی قطعی مالک هر شماره یا موقعیت زندهٔ شخص را تضمین نمی‌کنند.

### Tellows

گزارش‌های کاربران و امتیازدهی شماره‌های مزاحم یا مشکوک.

[https://www.tellows.com/](https://www.tellows.com/)

### Sync.me

شناسایی احتمالی تماس‌گیرنده و اطلاعات شماره از داده‌های سرویس.

[https://sync.me/](https://sync.me/)

### NumLookup

جست‌وجوی معکوس شماره در داده‌های گردآوری‌شده؛ کیفیت وابسته به پوشش داده.

[https://www.numlookup.com/](https://www.numlookup.com/)

### SpyDialer

جست‌وجوی شماره‌های آمریکا؛ ابزار جهانی شناسایی همهٔ شماره‌ها نیست.

[https://spydialer.com/](https://spydialer.com/)

### National Cellular Directory

دایرکتوری شماره و اطلاعات تماس با تمرکز بر بازار آمریکا.

[https://www.nationalcellulardirectory.com/](https://www.nationalcellulardirectory.com/)

### Phone Validator

بررسی نوع خط، مانند موبایل یا تلفن ثابت، و اطلاعات مرتبط.

[https://www.phonevalidator.com/](https://www.phonevalidator.com/)

### Free Carrier Lookup

استعلام اپراتور و نوع خط در محدودهٔ پوشش سرویس.

[https://www.freecarrierlookup.com/](https://www.freecarrierlookup.com/)

### ThisNumber

راهنمای منابع و دایرکتوری‌های شماره تلفن در کشورهای مختلف.

[https://www.thisnumber.com/](https://www.thisnumber.com/)

### ReversePhoneLookup

جست‌وجوی اطلاعات مرتبط با شماره؛ نتایج سند رسمی مالکیت خط نیست.

[https://www.reversephonelookup.com/](https://www.reversephonelookup.com/)

### ValidNumber

جست‌وجوی معکوس شماره و اطلاعات احتمالی تماس‌گیرنده.

[https://validnumber.com/](https://validnumber.com/)

### AnyWho

دایرکتوری اشخاص و شماره‌ها، عمدتاً برای آمریکا.

[https://www.anywho.com/](https://www.anywho.com/)

<a id="s10"></a>

## ۱۰. موتورهای عمومی جست‌وجو

این‌ها ابزار تخصصی امنیت نیستند، اما برای یافتن اسناد، گزارش‌ها و اطلاعات عمومی کاربرد دارند.

### Google

جست‌وجوی عمومی وب و تصاویر.

[https://www.google.com/](https://www.google.com/)

### Bing

جست‌وجوی وب و محتوای تصویری مایکروسافت.

[https://www.bing.com/](https://www.bing.com/)

### Yahoo Search

سرویس جست‌وجوی عمومی Yahoo.

[https://search.yahoo.com/](https://search.yahoo.com/)

### Yandex

جست‌وجوی وب، تصویر و سایر محتوای عمومی.

[https://yandex.com/](https://yandex.com/)

### Baidu

جست‌وجو با تمرکز قوی بر محتوای چینی.

[https://www.baidu.com/](https://www.baidu.com/)

### You.com

خدمات جست‌وجو و APIهای وب برای کاربردهای هوش مصنوعی.

[https://you.com/](https://you.com/)

### SearXNG

نرم‌افزار متن‌باز فراجست‌وجو؛ قابل میزبانی روی سرور خود.

[https://docs.searxng.org/](https://docs.searxng.org/)

### DuckDuckGo

جست‌وجوی عمومی با تمرکز بر حریم خصوصی.

[https://duckduckgo.com/](https://duckduckgo.com/)

### Swisscows

جست‌وجو با تأکید بر حریم خصوصی و فیلتر محتوا.

[https://swisscows.com/en](https://swisscows.com/en)

### Naver

درگاه و جست‌وجوی عمومی با تمرکز بر محتوای کره‌ای.

[https://www.naver.com/](https://www.naver.com/)

### Brave Search

موتور جست‌وجوی عمومی Brave.

[https://search.brave.com/](https://search.brave.com/)

### Yep

جست‌وجوی عمومی برای کاربران و کاربردهای ماشینی.

[https://yep.com/](https://yep.com/)

### Gibiru

جست‌وجو با ادعای تمرکز بر حریم خصوصی؛ این فهرست ممیزی حریم خصوصی آن نیست.

[https://gibiru.com/](https://gibiru.com/)

### Kagi

جست‌وجوی اشتراکی با تمرکز بر تجربهٔ بدون تبلیغات.

[https://kagi.com/](https://kagi.com/)

</div>
