---
title: "Siber Güvenlik Araçları Rehberi"
author: "Alp Gokturk & ChatGPT ai"
version: "1"
date: "2026-09-28"
location: "Istanbul"
email: "alpnetpro@gmail.com"
github: "https://github.com/Alpnetpro"
folder: "Cybersecurity Tools"
language: "tr"
---

<div dir="ltr">

# Siber Güvenlik Araçları Rehberi

Bu rapor, ChatGPT yapay zekâsının yeteneklerinden yararlanılarak Alp Gokturk tarafından hazırlanmıştır.

**Alp Gokturk & ChatGPT ai**

**Sürüm 1 | 28 Eylül 2026 | 2026-09-28 | İstanbul**

Bir hata fark ederseniz veya öneriniz varsa lütfen bana e-posta gönderin.

[alpnetpro@gmail.com](mailto:alpnetpro@gmail.com)

GitHub: [https://github.com/Alpnetpro](https://github.com/Alpnetpro)

Bu raporun en güncel sürümünü GitHub hesabımdaki Cybersecurity Tools klasöründen indirebilirsiniz.

## İçindekiler

Sayfa numaraları Türkçe PDF dosyasına aittir. Başlıklar bu Markdown dosyasındaki ilgili bölümlere bağlantı verir.

| Başlık | Sayfa |
|---|---:|
| [1. Alan adları, DNS ve kayıt bilgileri](#s1) | 3 |
| [2. Dijital sertifikalar, TLS, Wi-Fi ve cihaz üreticileri](#s2) | 5 |
| [3. IP sahipliği, yönlendirme ve saldırı yüzeyi yönetimi](#s3) | 7 |
| [4. Saldırı teknikleri kaynakları ve savunma çalışmaları](#s4) | 9 |
| [5. Kod, açık kaynaklı projeler ve API’ler](#s5) | 11 |
| [6. Web sitesi bilgileri ve arşiv araması](#s6) | 15 |
| [7. E-posta adresi bulma ve kontrol etme](#s7) | 17 |
| [8. Görsel arama ve inceleme](#s8) | 20 |
| [9. Telefon numaraları: doğruluk ve kapsam sınırlamaları](#s9) | 22 |
| [10. Genel arama motorları](#s10) | 24 |

<a id="s1"></a>

## 1. Alan adları, DNS ve kayıt bilgileri

### DomainIQ

Toplanan ve geçmişe ait verilerle alan adlarını ve IP adreslerini araştırma.

[https://www.domainiq.com/](https://www.domainiq.com/)

### Who.is

WHOIS ve RDAP ile alan adı kayıt bilgilerini, DNS kayıtlarını ve ad sunucularını inceleme.

[https://who.is/](https://who.is/)

### Whoisology

Alan adı geçmişini ve ilişkilerini incelemek için WHOIS arşivi; eski kayıtlar güncel durumu yansıtmayabilir.

[https://whoisology.com/](https://whoisology.com/)

### WhoisXML API

Araştırma ve otomasyon için WHOIS, DNS, alan adı ve IP API’leri.

[https://www.whoisxmlapi.com/](https://www.whoisxmlapi.com/)

### SpyOnWeb

Ortak teknik özelliklerden siteler arasında olası bağlantılar bulma; ortak özellik, aynı sahibin kanıtı değildir.

[https://spyonweb.net/](https://spyonweb.net/)

### SynapsInt

Alan adı, IP, ASN, SSL ve e-posta bilgilerini tek arayüzde arama.

[https://synapsint.com/](https://synapsint.com/)

### C99 API

Teknik sorgular ve yardımcı araçlar için API’ler; özellikler ve kotalar seçilen hizmete bağlıdır.

[https://api.c99.nl/](https://api.c99.nl/)

<a id="s2"></a>

## 2. Dijital sertifikalar, TLS, Wi-Fi ve cihaz üreticileri

### crt.sh

Alan adı, kuruluş veya parmak iziyle sertifika arama; Certificate Transparency araştırmaları için yararlıdır.

[https://crt.sh/](https://crt.sh/)

### Cert Spotter

Bir alan adı için düzenlenen sertifikaları izleme; sertifika güvenliği veya erişilebilirliği sorunlarını belirleme.

[https://sslmate.com/certspotter/](https://sslmate.com/certspotter/)

### CipherSuite.info

TLS şifre takımları ve güvenlik özellikleri için aranabilir başvuru kaynağı.

[https://ciphersuite.info/](https://ciphersuite.info/)

### Certs.io

Alan adı veya kuruluşla ilişkili varlıkları bulmak için TLS sertifikalarını arama; kaynak raporda hesap işlevleri test edilmemiştir.

[https://certs.io/](https://certs.io/)

### WiGLE

Kablosuz ağ gözlemlerini toplama ve haritalama; bağlanma izniniz olan ağların listesi değildir.

[https://wigle.net/](https://wigle.net/)

### WiFi Map

Wi-Fi erişim noktalarını bulma; uzman güvenlik analizinden çok bağlantı ve seyahat amaçlıdır.

[https://www.wifimap.io/](https://www.wifimap.io/)

### OpenWiFiMap

Freifunk gibi topluluk kablosuz ağları için açık kaynaklı haritalama projesi.

[https://openwifimap.net/](https://openwifimap.net/)

### MACVendors

IEEE verileriyle MAC adresi aralığının kayıtlı üreticisini bulma.

[https://macvendors.com/](https://macvendors.com/)

### MACAddress.io

Ağ betikleri için uygun API ile üretici ve MAC adres bloğu bilgilerini sorgulama.

[https://macaddress.io/](https://macaddress.io/)

### MACLookup

MAC adresi veya OUI ile üretici arama; cihazların ilk incelemesi için yararlıdır.

[https://maclookup.app/](https://maclookup.app/)

### MACVendorLookup

MAC adreslerini kayıtlı üretici bilgileriyle eşleştirme.

[https://www.macvendorlookup.com/](https://www.macvendorlookup.com/)

<a id="s3"></a>

## 3. IP sahipliği, yönlendirme ve saldırı yüzeyi yönetimi

### FullHunt

Saldırı yüzeyi yönetimi için kuruluşun internete açık varlıklarını keşfetme ve izleme.

[https://fullhunt.io/](https://fullhunt.io/)

### RedHunt Labs

Sürekli izleme ile dış varlıkları ve güvenlik risklerini belirleme.

[https://redhuntlabs.com/](https://redhuntlabs.com/)

### Deepinfo

Tehditlere maruz kalma durumunu yönetme; dış varlıkları ve riskleri inceleme.

[https://www.deepinfo.com/](https://www.deepinfo.com/)

### IPinfo

Log zenginleştirme ve ağ sağlayıcısını tanıma için IP, ağ ve yaklaşık konum bilgileri.

[https://ipinfo.io/](https://ipinfo.io/)

### ipdata

Analiz, filtreleme ve otomasyon için IP konumu ve özellikleri API’si.

[https://ipdata.co/](https://ipdata.co/)

### NetworksDB

Şirketlerle IP aralıkları, alan adları ve ağ bilgileri arasındaki ilişkileri inceleme.

[https://networksdb.io/](https://networksdb.io/)

### BGP.tools

ASN, IP önekleri ve yönlendirme ilişkilerini inceleme; BGP öğrenme ve sorun giderme için yararlıdır.

[https://bgp.tools/](https://bgp.tools/)

### BigDataCloud

Yaklaşık IP konumu, coğrafi veriler ve ağ verileri için API’ler.

[https://www.bigdatacloud.com/](https://www.bigdatacloud.com/)

### RADb

Route nesnelerini ve kayıtlı politikaları incelemek için internet yönlendirme kayıt veritabanı.

[https://www.radb.net/](https://www.radb.net/)

### Cloudflare Radar

İnternet trafiği, kesintiler, saldırılar ve teknolojilerdeki geniş ölçekli eğilimleri izleme.

[https://radar.cloudflare.com/](https://radar.cloudflare.com/)

### Pentest-Tools

Yetki kapsamındaki varlıkları değerlendirmek için sızma testi ve tarama araçları.

[https://pentest-tools.com/](https://pentest-tools.com/)

<a id="s4"></a>

## 4. Saldırı teknikleri kaynakları ve savunma çalışmaları

Bunlar çoğunlukla araştırma ve eğitim kaynaklarıdır; genel amaçlı arama motorları değildir.

### Hacking the Cloud

Yapılandırma risklerini anlamaya yönelik, bulutta saldırı odaklı güvenlik teknikleri ansiklopedisi.

[https://hackingthe.cloud/](https://hackingthe.cloud/)

### LOLDrivers

Araştırma ve tespit kuralı geliştirme için güvenlik açığı içeren veya zararlı Windows sürücüleri hakkında bilgiler.

[https://www.loldrivers.io/](https://www.loldrivers.io/)

### LOOBins

Davranış analizi ve savunma için macOS’un yerleşik araçlarının kötüye kullanım yöntemleri.

[https://loobins.io/](https://loobins.io/)

### WADComs

Yetkili testlerde Windows ve Active Directory değerlendirme araçları ve komutları için başvuru kaynağı.

[https://wadcoms.github.io/](https://wadcoms.github.io/)

### Living Off the Pipeline

Geliştirme hattı güvenliği için CI/CD araçlarının olası kötüye kullanımını belgeleyen kaynak.

[https://boostsecurityio.github.io/lotp/](https://boostsecurityio.github.io/lotp/)

### LOLAPPS

Yetenekleri saldırılarda kötüye kullanılabilecek normal uygulamaların listesi.

[https://lolapps-project.github.io/](https://lolapps-project.github.io/)

### LOTHardware

USB ve HID araçları dahil, saldırılarla ilişkili donanım kataloğu.

[https://lothardware.com.tr/](https://lothardware.com.tr/)

### CVExploits

CVE’lerle ilişkili istismar kaynaklarını bulma; sonuçlar gerçek sürüm ve koşullarla karşılaştırılmalıdır.

[https://cvexploits.io/](https://cvexploits.io/)

### Exploit Observer

Güvenlik açığı ve istismar bilgilerini toplar, API sunar; kaynak raporda «en büyük» olduğu iddiası doğrulanmamıştır.

[https://www.exploit.observer/](https://www.exploit.observer/)

### Coalition Exploit Scoring System

Önceliklendirmeye yardımcı olmak için güvenlik açıklarının istismar edilme olasılığını puanlama.

[https://ess.coalitioninc.com/](https://ess.coalitioninc.com/)

<a id="s5"></a>

## 5. Kod, açık kaynaklı projeler ve API’ler

### GitHub Code Search

Erişilebilir depolarda kod, işlev ve uygulama örnekleri arama.

[https://github.com/search?type=code](https://github.com/search?type=code)

### GitLab

Proje barındırma, depo kodu ve içeriğinde arama; özellikler ayarlara ve plana bağlıdır.

[https://gitlab.com/](https://gitlab.com/)

### grep.app

İşlev kullanım örnekleri bulmak için herkese açık depolarda metin ve kod parçaları arama.

[https://grep.app/](https://grep.app/)

### Sourcegraph

Geliştirme ve yazılım analizi için proje ve depolarda kod arama ve anlama.

[https://sourcegraph.com/](https://sourcegraph.com/)

### Searchcode

Programlama asistanları için API ve MCP ile depo analizi ve kod arama.

[https://searchcode.com/](https://searchcode.com/)

### PublicWWW

Ortak teknolojileri veya kod parçalarını bulmak için web sayfası kaynak kodunda metin arama.

[https://publicwww.com/](https://publicwww.com/)

### NerdyData

Web kodunu inceleyerek belirli teknolojileri kullanan siteleri saptama.

[https://www.nerdydata.com/](https://www.nerdydata.com/)

### Veloria (eski adıyla WP Directory)

Eklenti ve tema araştırmaları için WordPress kodunda arama.

[https://veloria.dev/](https://veloria.dev/)

### GitHub Gist

Kod parçaları, teknik notlar ve kısa betikler yayımlama ve arama.

[https://gist.github.com/](https://gist.github.com/)

### SourceForge

Proje ve yazılım barındırma ve keşfetme; her proje ayrı değerlendirilmelidir.

[https://sourceforge.net/](https://sourceforge.net/)

### Codeberg

Açık kaynaklı projeler için iş birliği ve Git barındırma platformu.

[https://codeberg.org/](https://codeberg.org/)

### Launchpad

Özellikle Ubuntu ekosisteminde geliştirme barındırma, hata bildirimi ve proje iş birliği.

[https://launchpad.net/](https://launchpad.net/)

### SourceHut

Yazılım geliştirme için barındırma ve iş birliği araçları paketi.

[https://sourcehut.org/](https://sourcehut.org/)

### Android Open Source

İşletim sistemini ve bileşenlerini incelemek için resmi Android kod depoları.

[https://android.googlesource.com/](https://android.googlesource.com/)

### deps.dev

Yazılım tedarik zincirini anlamak için açık kaynak paketler ve bağımlılıkları hakkında bilgiler.

[https://deps.dev/](https://deps.dev/)

### ecosyste.ms

Açık kaynaklı projeler, paketler ve bağımlılıklar hakkında veriler ve API’ler.

[https://ecosyste.ms/](https://ecosyste.ms/)

### Postman Explore

API kullanımı ve otomasyon pratiği için API’leri ve herkese açık istek koleksiyonlarını keşfetme.

[https://www.postman.com/explore](https://www.postman.com/explore)

### Swagger

API tasarımı, dokümantasyonu ve testi için araçlar.

[https://swagger.io/product/](https://swagger.io/product/)

### HotExamples

İnceleme için kod örnekleri; bulunan örnek güvenli veya güncel olmayabilir.

[https://hotexamples.com/](https://hotexamples.com/)

### Snipplr

Kod parçalarının paylaşıldığı depo; örneklerin kalitesi incelenmelidir.

[https://snipplr.com/](https://snipplr.com/)

### Google Code Archive

Google Code projelerinin geçmiş arşivi; yeni projeler için aktif barındırma hizmeti değildir.

[https://code.google.com/archive/](https://code.google.com/archive/)

<a id="s6"></a>

## 6. Web sitesi bilgileri ve arşiv araması

### Intelligence X

Arşivlerde ve toplanmış veri kümelerinde alan adı, e-posta, IP ve diğer tanımlayıcıları arama.

[https://intelx.io/](https://intelx.io/)

### Phonebook.cz

Bir alan adıyla ilişkili alan adlarını, e-postaları ve URL’leri bulma; kaynak raporda ücretli lisans gerektiği belirtilir.

[https://phonebook.cz/](https://phonebook.cz/)

### Common Crawl Index

Web’deki geçmiş izleri incelemek için Common Crawl URL dizininde arama.

[https://index.commoncrawl.org/](https://index.commoncrawl.org/)

### BuiltWith

İçerik yönetim sistemleri ve analiz araçları gibi web sitesi teknolojilerini belirleme.

[https://builtwith.com/](https://builtwith.com/)

### Netcraft Site Report

Web sitesinin teknolojisi ve barındırma altyapısı hakkında raporlar.

[https://sitereport.netcraft.com/](https://sitereport.netcraft.com/)

### GrayhatWarfare - Buckets

İnternette görünür bulut depolama kaynaklarını arama.

[https://buckets.grayhatwarfare.com/](https://buckets.grayhatwarfare.com/)

### GrayhatWarfare - Shorteners

Bağlantı kısaltma hizmetlerinden toplanan URL’lerde arama.

[https://shorteners.grayhatwarfare.com/](https://shorteners.grayhatwarfare.com/)

### Similarweb

Web trafiğini ve rekabet konumunu analiz ve tahmin etme; rakamlar site sahibinden doğrudan alınmış veriler olmayabilir.

[https://www.similarweb.com/](https://www.similarweb.com/)

### HypeStat

Başlıca web araştırması ve pazarlama için web sitesi istatistikleri ve analizi.

[https://hypestat.com/](https://hypestat.com/)

### StatsCrop

Trafik, SEO ve site özellikleri hakkında herkese açık raporlar.

[https://www.statscrop.com/](https://www.statscrop.com/)

### ExpiredDomains

Süresi dolmuş veya silinmek üzere olan alan adlarını bulma; alan adı ticareti ve araştırması aracı.

[https://www.expireddomains.net/](https://www.expireddomains.net/)

<a id="s7"></a>

## 7. E-posta adresi bulma ve kontrol etme

Bu araçlar profesyonel e-posta hesabı oluşturmaz. İletişim bilgisi bulma, teslim edilebilirliği kontrol etme veya e-posta itibarını değerlendirme amacıyla kullanılır.

### Hunter.io

Şirket ve alan adlarıyla ilişkili profesyonel e-posta adreslerini bulma ve doğrulama.

[https://hunter.io/](https://hunter.io/)

### Reacher

Geliştiriciler için açık kaynaklı e-posta doğrulama hizmeti ve API.

[https://reacher.email/](https://reacher.email/)

### Email Hippo

E-posta adreslerini doğrulama; geçersiz adresleri ve şüpheli kayıtları azaltma.

[https://www.emailhippo.com/](https://www.emailhippo.com/)

### Melissa

E-posta ve posta adresleri dahil iletişim verilerinin kalitesini kontrol etme ve iyileştirme.

[https://www.melissa.com/](https://www.melissa.com/)

### VoilaNorbert

Kişi ve şirket bilgileriyle iş e-posta adreslerini bulma ve doğrulama.

[https://www.voilanorbert.com/](https://www.voilanorbert.com/)

### FindEmails

E-posta adreslerini arama ve doğrulama.

[https://www.findemails.com/](https://www.findemails.com/)

### EXPERTE Email Finder

Ad ve şirket alan adıyla profesyonel e-posta adreslerini bulma.

[https://www.experte.com/email-finder](https://www.experte.com/email-finder)

### Anymail Finder

Teslim edilebilirlik kontrolüyle iş e-posta adreslerini bulma.

[https://anymailfinder.com/](https://anymailfinder.com/)

### Tomba

İş iletişim bilgilerini ve e-posta adreslerini arama ve zenginleştirme.

[https://tomba.io/](https://tomba.io/)

### Snov.io

İletişim bilgilerini bulma ve doğrulama; satış iletişimini yönetme.

[https://snov.io/](https://snov.io/)

### EmailRep

Şüpheli e-posta analizi için adresin itibarını ve risk göstergelerini inceleme.

[https://emailrep.io/](https://emailrep.io/)

### MailboxValidator

Web arayüzü ve API ile e-posta adreslerini doğrulama.

[https://www.mailboxvalidator.com/](https://www.mailboxvalidator.com/)

### ContactOut

Profesyonel iletişim bilgilerini bulma; ağırlıklı olarak işe alım ve satış aracı.

[https://contactout.com/](https://contactout.com/)

### Email-format

Şirketlerin name.surname@company gibi e-posta adresi oluşturma biçimlerini inceleme.

[https://www.email-format.com/](https://www.email-format.com/)

### Emailable

Kaynak raporda Verify-email.org’un yönlendirildiği güncel hizmet olarak belirtilir; e-posta listelerini ve teslim edilebilirliği kontrol eder.

[https://emailable.com/](https://emailable.com/)

### Emailsearch.io

Ad, şirket veya alan adıyla iş iletişim bilgilerini arama.

[https://emailsearch.io/](https://emailsearch.io/)

### EmailSherlock

Tersine e-posta araması ve ilişkili bilgiler; sonuçlar araştırma ipucudur, kimlik kanıtı değildir.

[https://www.emailsherlock.com/](https://www.emailsherlock.com/)

<a id="s8"></a>

## 8. Görsel arama ve inceleme

### TinEye

Aynı fotoğrafın yayımlanmış kopyalarını ve diğer kullanımlarını bulmak için tersine görsel arama.

[https://tineye.com/](https://tineye.com/)

### Pixsy

Fotoğraf kullanımını izleme ve izinsiz kullanımı takip etmeye yardımcı olma.

[https://www.pixsy.com/](https://www.pixsy.com/)

### Jimpl

Çekim zamanı ve kamera bilgileri gibi görsel üst verilerini ve EXIF’i gösterme.

[https://jimpl.com/](https://jimpl.com/)

### EXIFdata

EXIF görüntüleme, düzenleme ve silme; kaynak raporda işlemenin tarayıcıda yapıldığı belirtilir.

[https://www.exifdata.com/](https://www.exifdata.com/)

### PimEyes

Web’de benzer yüz görsellerini arama; görsel benzerlik kimlik kanıtı değildir.

[https://pimeyes.com/en](https://pimeyes.com/en)

### FaceCheck

Benzer yüz fotoğraflarını arama; kesin kimlik doğrulaması için yeterli değildir.

[https://facecheck.id/](https://facecheck.id/)

### Pictriev

Yüz benzerliği araması; güvenilir kimlik analizinden çok eğlence ve karşılaştırma amaçlıdır.

[https://www.pictriev.com/](https://www.pictriev.com/)

### Same Energy

Benzer stil ve görünüme sahip görselleri bulma; görsel ilham aracı.

[https://same.energy/](https://same.energy/)

### Flickr

Fotoğraf yayımlama ve arama; uzman güvenlik aracı değil, genel görsel kaynağıdır.

[https://www.flickr.com/](https://www.flickr.com/)

### Pixabay

Uzman güvenlik araçları arasında doğrudan yeri olmayan görsel içerik kütüphanesi.

[https://pixabay.com/](https://pixabay.com/)

<a id="s9"></a>

## 9. Telefon numaraları: doğruluk ve kapsam sınırlamaları

Bu hizmetler her numaranın sahibini kesin olarak belirlemeyi veya bir kişinin anlık konumunu göstermeyi garanti etmez.

### Tellows

Rahatsız edici veya şüpheli telefon numaraları hakkında kullanıcı bildirimleri ve puanları.

[https://www.tellows.com/](https://www.tellows.com/)

### Sync.me

Hizmet verilerinden olası arayan kimliği ve numara bilgileri.

[https://sync.me/](https://sync.me/)

### NumLookup

Toplanmış verilerde tersine numara araması; kalite veri kapsamına bağlıdır.

[https://www.numlookup.com/](https://www.numlookup.com/)

### SpyDialer

ABD telefon numaralarını arama; her numarayı tanımlayan küresel bir araç değildir.

[https://spydialer.com/](https://spydialer.com/)

### National Cellular Directory

ABD pazarına odaklanan telefon numarası ve iletişim rehberi.

[https://www.nationalcellulardirectory.com/](https://www.nationalcellulardirectory.com/)

### Phone Validator

Mobil veya sabit hat gibi hat türlerini ve ilişkili bilgileri kontrol etme.

[https://www.phonevalidator.com/](https://www.phonevalidator.com/)

### Free Carrier Lookup

Hizmetin kapsadığı alanlarda operatör ve hat türünü sorgulama.

[https://www.freecarrierlookup.com/](https://www.freecarrierlookup.com/)

### ThisNumber

Farklı ülkelerdeki telefon numarası kaynakları ve rehberleri için kılavuz.

[https://www.thisnumber.com/](https://www.thisnumber.com/)

### ReversePhoneLookup

Numarayla ilişkili bilgileri arama; sonuçlar hattın sahibini gösteren resmi belge değildir.

[https://www.reversephonelookup.com/](https://www.reversephonelookup.com/)

### ValidNumber

Tersine telefon numarası araması ve olası arayan bilgileri.

[https://validnumber.com/](https://validnumber.com/)

### AnyWho

Ağırlıklı olarak ABD için kişi ve telefon numarası rehberi.

[https://www.anywho.com/](https://www.anywho.com/)

<a id="s10"></a>

## 10. Genel arama motorları

Bunlar uzman güvenlik araçları değildir; ancak belge, rapor ve herkese açık bilgi bulmak için yararlıdır.

### Google

Genel web ve görsel arama.

[https://www.google.com/](https://www.google.com/)

### Bing

Microsoft’un web ve görsel içerik araması.

[https://www.bing.com/](https://www.bing.com/)

### Yahoo Search

Yahoo’nun genel arama hizmeti.

[https://search.yahoo.com/](https://search.yahoo.com/)

### Yandex

Web, görsel ve diğer herkese açık içeriklerde arama.

[https://yandex.com/](https://yandex.com/)

### Baidu

Çince içeriğe güçlü biçimde odaklanan arama.

[https://www.baidu.com/](https://www.baidu.com/)

### You.com

Yapay zekâ uygulamaları için arama hizmetleri ve web API’leri.

[https://you.com/](https://you.com/)

### SearXNG

Kendi sunucunuzda barındırabileceğiniz açık kaynaklı meta arama yazılımı.

[https://docs.searxng.org/](https://docs.searxng.org/)

### DuckDuckGo

Gizliliğe odaklanan genel arama.

[https://duckduckgo.com/](https://duckduckgo.com/)

### Swisscows

Gizlilik ve içerik filtrelemeyi öne çıkaran arama.

[https://swisscows.com/en](https://swisscows.com/en)

### Naver

Korece içeriğe odaklanan portal ve genel arama hizmeti.

[https://www.naver.com/](https://www.naver.com/)

### Brave Search

Brave’in genel arama motoru.

[https://search.brave.com/](https://search.brave.com/)

### Yep

Kullanıcılar ve makine uygulamaları için genel arama.

[https://yep.com/](https://yep.com/)

### Gibiru

Gizliliğe odaklandığını belirten arama hizmeti; bu liste bir gizlilik denetimi değildir.

[https://gibiru.com/](https://gibiru.com/)

### Kagi

Reklamsız deneyime odaklanan abonelikli arama hizmeti.

[https://kagi.com/](https://kagi.com/)

</div>
