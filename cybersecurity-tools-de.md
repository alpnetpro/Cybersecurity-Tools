---
title: "Leitfaden für Cybersicherheitswerkzeuge"
author: "Alp Gokturk & ChatGPT ai"
version: "1"
date: "2026-09-28"
location: "Istanbul"
email: "alpnetpro@gmail.com"
github: "https://github.com/Alpnetpro"
folder: "Cybersecurity Tools"
language: "de"
---

<div dir="ltr">

# Leitfaden für Cybersicherheitswerkzeuge

Dieser Bericht wurde von Alp Gokturk mit Unterstützung der künstlichen Intelligenz ChatGPT erstellt.

**Alp Gokturk & ChatGPT ai**

**Version 1 | 28. September 2026 | 2026-09-28 | Istanbul**

Wenn Sie einen Fehler bemerken oder einen Vorschlag haben, schreiben Sie mir bitte eine E-Mail.

[alpnetpro@gmail.com](mailto:alpnetpro@gmail.com)

GitHub: [https://github.com/Alpnetpro](https://github.com/Alpnetpro)

Die neueste Version dieses Berichts steht auf meinem GitHub-Profil im Ordner Cybersecurity Tools zum Download bereit.

## Inhaltsverzeichnis

Die Seitenzahlen beziehen sich auf die deutsche PDF-Datei. Die Titel verweisen auf die entsprechenden Abschnitte dieser Markdown-Datei.

| Abschnitt | Seite |
|---|---:|
| [1. Domains, DNS und Registrierungsdaten](#s1) | 3 |
| [2. Digitale Zertifikate, TLS, WLAN und Gerätehersteller](#s2) | 5 |
| [3. IP-Inhaberschaft, Routing und Angriffsflächenmanagement](#s3) | 7 |
| [4. Referenzen zu Angriffstechniken und defensiven Analysen](#s4) | 9 |
| [5. Code, Open-Source-Projekte und APIs](#s5) | 11 |
| [6. Website-Informationen und Archivsuche](#s6) | 15 |
| [7. E-Mail-Adressen finden und prüfen](#s7) | 17 |
| [8. Bildersuche und Bildanalyse](#s8) | 20 |
| [9. Telefonnummern: Grenzen bei Genauigkeit und Abdeckung](#s9) | 22 |
| [10. Allgemeine Suchmaschinen](#s10) | 24 |

<a id="s1"></a>

## 1. Domains, DNS und Registrierungsdaten

### DomainIQ

Recherche zu Domains und IP-Adressen anhand gesammelter und historischer Daten.

[https://www.domainiq.com/](https://www.domainiq.com/)

### Who.is

Domainregistrierungsdaten über WHOIS und RDAP prüfen, einschließlich DNS und Nameservern.

[https://who.is/](https://who.is/)

### Whoisology

WHOIS-Archiv zur Untersuchung der Geschichte und Beziehungen von Domains; ältere Einträge bilden den aktuellen Stand möglicherweise nicht ab.

[https://whoisology.com/](https://whoisology.com/)

### WhoisXML API

WHOIS-, DNS-, Domain- und IP-APIs für Recherche und Automatisierung.

[https://www.whoisxmlapi.com/](https://www.whoisxmlapi.com/)

### SpyOnWeb

Mögliche Verbindungen zwischen Websites anhand gemeinsamer technischer Merkmale finden; diese belegen keine gemeinsame Eigentümerschaft.

[https://spyonweb.net/](https://spyonweb.net/)

### SynapsInt

Domains, IP-Adressen, ASNs, SSL-Daten und E-Mail-Adressen über eine Oberfläche suchen.

[https://synapsint.com/](https://synapsint.com/)

### C99 API

APIs für technische Abfragen und Hilfsfunktionen; Umfang und Kontingente hängen vom gewählten Dienst ab.

[https://api.c99.nl/](https://api.c99.nl/)

<a id="s2"></a>

## 2. Digitale Zertifikate, TLS, WLAN und Gerätehersteller

### crt.sh

Zertifikate nach Domain, Organisation oder Fingerabdruck suchen; nützlich für Recherchen zu Certificate Transparency.

[https://crt.sh/](https://crt.sh/)

### Cert Spotter

Für eine Domain ausgestellte Zertifikate überwachen und Sicherheits- oder Verfügbarkeitsprobleme erkennen.

[https://sslmate.com/certspotter/](https://sslmate.com/certspotter/)

### CipherSuite.info

Durchsuchbares Nachschlagewerk für TLS-Cipher-Suites und ihre Sicherheitseigenschaften.

[https://ciphersuite.info/](https://ciphersuite.info/)

### Certs.io

TLS-Zertifikate durchsuchen, um zugehörige Ressourcen einer Domain oder Organisation zu finden; Kontofunktionen wurden im Ausgangsbericht nicht getestet.

[https://certs.io/](https://certs.io/)

### WiGLE

Beobachtungen drahtloser Netzwerke sammeln und kartieren; keine Liste von Netzwerken, deren Nutzung erlaubt ist.

[https://wigle.net/](https://wigle.net/)

### WiFi Map

WLAN-Hotspots finden; vor allem für Internetzugang und Reisen, weniger für spezialisierte Sicherheitsanalysen.

[https://www.wifimap.io/](https://www.wifimap.io/)

### OpenWiFiMap

Open-Source-Kartenprojekt für gemeinschaftliche Funknetze wie Freifunk.

[https://openwifimap.net/](https://openwifimap.net/)

### MACVendors

Den registrierten Hersteller eines MAC-Adressbereichs anhand von IEEE-Daten ermitteln.

[https://macvendors.com/](https://macvendors.com/)

### MACAddress.io

Hersteller und Details zu MAC-Adressblöcken abfragen; mit einer API für Netzwerkskripte.

[https://macaddress.io/](https://macaddress.io/)

### MACLookup

Hersteller anhand einer MAC-Adresse oder OUI ermitteln; hilfreich bei ersten Geräteprüfungen.

[https://maclookup.app/](https://maclookup.app/)

### MACVendorLookup

MAC-Adressen mit registrierten Herstellerinformationen abgleichen.

[https://www.macvendorlookup.com/](https://www.macvendorlookup.com/)

<a id="s3"></a>

## 3. IP-Inhaberschaft, Routing und Angriffsflächenmanagement

### FullHunt

Internetexponierte Ressourcen einer Organisation für das Angriffsflächenmanagement erkennen und überwachen.

[https://fullhunt.io/](https://fullhunt.io/)

### RedHunt Labs

Externe Ressourcen und Sicherheitsrisiken durch kontinuierliche Überwachung erkennen.

[https://redhuntlabs.com/](https://redhuntlabs.com/)

### Deepinfo

Bedrohungsexposition verwalten und externe Ressourcen sowie Risiken untersuchen.

[https://www.deepinfo.com/](https://www.deepinfo.com/)

### IPinfo

IP-, Netzwerk- und ungefähre Standortdaten zur Anreicherung von Protokollen und zur Ermittlung von Netzbetreibern.

[https://ipinfo.io/](https://ipinfo.io/)

### ipdata

API für IP-Standorte und -Eigenschaften zur Analyse, Filterung und Automatisierung.

[https://ipdata.co/](https://ipdata.co/)

### NetworksDB

Beziehungen zwischen Unternehmen, IP-Adressbereichen, Domains und Netzwerkdaten untersuchen.

[https://networksdb.io/](https://networksdb.io/)

### BGP.tools

ASNs, IP-Präfixe und Routingbeziehungen prüfen; nützlich zum Lernen und zur Fehlerbehebung bei BGP.

[https://bgp.tools/](https://bgp.tools/)

### BigDataCloud

APIs für ungefähre IP-Geolokalisierung sowie geografische und netzwerkbezogene Daten.

[https://www.bigdatacloud.com/](https://www.bigdatacloud.com/)

### RADb

Internet-Routing-Registry zur Prüfung von Route-Objekten und registrierten Richtlinien.

[https://www.radb.net/](https://www.radb.net/)

### Cloudflare Radar

Übergreifende Trends bei Internetverkehr, Ausfällen, Angriffen und Technologien beobachten.

[https://radar.cloudflare.com/](https://radar.cloudflare.com/)

### Pentest-Tools

Penetrationstest- und Scanwerkzeuge zur Bewertung von Ressourcen im Rahmen einer Genehmigung.

[https://pentest-tools.com/](https://pentest-tools.com/)

<a id="s4"></a>

## 4. Referenzen zu Angriffstechniken und defensiven Analysen

Diese Quellen dienen überwiegend der Recherche und dem Lernen; sie sind keine allgemeinen Suchmaschinen.

### Hacking the Cloud

Enzyklopädie offensiver Sicherheitstechniken für Cloud-Umgebungen zum Verständnis von Konfigurationsrisiken.

[https://hackingthe.cloud/](https://hackingthe.cloud/)

### LOLDrivers

Informationen über verwundbare oder bösartige Windows-Treiber für Forschung und Erkennungsregeln.

[https://www.loldrivers.io/](https://www.loldrivers.io/)

### LOOBins

Missbrauchstechniken mit integrierten macOS-Werkzeugen für Verhaltensanalyse und Abwehr.

[https://loobins.io/](https://loobins.io/)

### WADComs

Referenz für Werkzeuge und Befehle zur Prüfung von Windows und Active Directory bei autorisierten Tests.

[https://wadcoms.github.io/](https://wadcoms.github.io/)

### Living Off the Pipeline

Dokumentation möglicher Missbrauchswege bei CI/CD-Werkzeugen für die Sicherheit von Entwicklungspipelines.

[https://boostsecurityio.github.io/lotp/](https://boostsecurityio.github.io/lotp/)

### LOLAPPS

Liste regulärer Anwendungen, deren Funktionen bei Angriffen missbraucht werden können.

[https://lolapps-project.github.io/](https://lolapps-project.github.io/)

### LOTHardware

Katalog angriffsbezogener Hardware, einschließlich USB- und HID-Werkzeugen.

[https://lothardware.com.tr/](https://lothardware.com.tr/)

### CVExploits

Exploit-Ressourcen zu CVEs finden; Ergebnisse müssen mit der tatsächlichen Version und den Bedingungen abgeglichen werden.

[https://cvexploits.io/](https://cvexploits.io/)

### Exploit Observer

Sammelt Informationen zu Schwachstellen und Exploits und bietet eine API; die Behauptung, der größte Anbieter zu sein, wurde im Ausgangsbericht nicht bestätigt.

[https://www.exploit.observer/](https://www.exploit.observer/)

### Coalition Exploit Scoring System

Bewertet die Wahrscheinlichkeit der Ausnutzung von Schwachstellen zur Unterstützung der Priorisierung.

[https://ess.coalitioninc.com/](https://ess.coalitioninc.com/)

<a id="s5"></a>

## 5. Code, Open-Source-Projekte und APIs

### GitHub Code Search

Code, Funktionen und Implementierungsbeispiele in zugänglichen Repositories suchen.

[https://github.com/search?type=code](https://github.com/search?type=code)

### GitLab

Projekte hosten und Code sowie Inhalte von Repositories durchsuchen; Funktionen hängen von Einstellungen und Tarif ab.

[https://gitlab.com/](https://gitlab.com/)

### grep.app

Text und Codeausschnitte in öffentlichen Repositories durchsuchen, um Anwendungsbeispiele für Funktionen zu finden.

[https://grep.app/](https://grep.app/)

### Sourcegraph

Code in Projekten und Repositories für Entwicklung und Softwareanalyse suchen und verstehen.

[https://sourcegraph.com/](https://sourcegraph.com/)

### Searchcode

Repository-Analyse und Codesuche mit APIs und MCP für Programmierassistenten.

[https://searchcode.com/](https://searchcode.com/)

### PublicWWW

Text im Quellcode von Webseiten suchen, um gemeinsame Technologien oder Codeausschnitte zu finden.

[https://publicwww.com/](https://publicwww.com/)

### NerdyData

Websites mit bestimmten Technologien anhand ihres Webcodes identifizieren.

[https://www.nerdydata.com/](https://www.nerdydata.com/)

### Veloria (früher WP Directory)

WordPress-Code zur Untersuchung von Plugins und Themes durchsuchen.

[https://veloria.dev/](https://veloria.dev/)

### GitHub Gist

Codeausschnitte, technische Notizen und kurze Skripte veröffentlichen und suchen.

[https://gist.github.com/](https://gist.github.com/)

### SourceForge

Projekte und Software hosten und entdecken; jedes Projekt sollte einzeln bewertet werden.

[https://sourceforge.net/](https://sourceforge.net/)

### Codeberg

Plattform für Zusammenarbeit und Git-Hosting bei Open-Source-Projekten.

[https://codeberg.org/](https://codeberg.org/)

### Launchpad

Entwicklungshosting, Fehlerberichte und Projektzusammenarbeit, insbesondere im Ubuntu-Ökosystem.

[https://launchpad.net/](https://launchpad.net/)

### SourceHut

Sammlung von Hosting- und Zusammenarbeitswerkzeugen für die Softwareentwicklung.

[https://sourcehut.org/](https://sourcehut.org/)

### Android Open Source

Offizielle Android-Code-Repositories zum Studium des Betriebssystems und seiner Komponenten.

[https://android.googlesource.com/](https://android.googlesource.com/)

### deps.dev

Informationen über Open-Source-Pakete und Abhängigkeiten zum Verständnis der Softwarelieferkette.

[https://deps.dev/](https://deps.dev/)

### ecosyste.ms

Daten und APIs zu Open-Source-Projekten, Paketen und Abhängigkeiten.

[https://ecosyste.ms/](https://ecosyste.ms/)

### Postman Explore

APIs und öffentliche Anfragesammlungen entdecken, um API-Nutzung und Automatisierung zu üben.

[https://www.postman.com/explore](https://www.postman.com/explore)

### Swagger

Werkzeuge zum Entwerfen, Dokumentieren und Testen von APIs.

[https://swagger.io/product/](https://swagger.io/product/)

### HotExamples

Codebeispiele zum Lernen; gefundene Beispiele sind nicht unbedingt sicher oder aktuell.

[https://hotexamples.com/](https://hotexamples.com/)

### Snipplr

Sammlung zum Teilen von Codeausschnitten; die Qualität der Beispiele muss geprüft werden.

[https://snipplr.com/](https://snipplr.com/)

### Google Code Archive

Historisches Archiv von Google-Code-Projekten; kein aktiver Hostingdienst für neue Projekte.

[https://code.google.com/archive/](https://code.google.com/archive/)

<a id="s6"></a>

## 6. Website-Informationen und Archivsuche

### Intelligence X

Domains, E-Mail-Adressen, IP-Adressen und andere Kennungen in Archiven und gesammelten Datensätzen suchen.

[https://intelx.io/](https://intelx.io/)

### Phonebook.cz

Zu einer Domain gehörende Domains, E-Mail-Adressen und URLs finden; laut Ausgangsbericht ist eine kostenpflichtige Lizenz erforderlich.

[https://phonebook.cz/](https://phonebook.cz/)

### Common Crawl Index

Den URL-Index von Common Crawl nach historischen Spuren im Web durchsuchen.

[https://index.commoncrawl.org/](https://index.commoncrawl.org/)

### BuiltWith

Website-Technologien wie Content-Management-Systeme und Analysewerkzeuge erkennen.

[https://builtwith.com/](https://builtwith.com/)

### Netcraft Site Report

Berichte über Technologie und Hosting-Infrastruktur einer Website.

[https://sitereport.netcraft.com/](https://sitereport.netcraft.com/)

### GrayhatWarfare - Buckets

Im Internet sichtbare Cloud-Speicherressourcen suchen.

[https://buckets.grayhatwarfare.com/](https://buckets.grayhatwarfare.com/)

### GrayhatWarfare - Shorteners

In URL-Sammlungen von Kurzlinkdiensten suchen.

[https://shorteners.grayhatwarfare.com/](https://shorteners.grayhatwarfare.com/)

### Similarweb

Website-Traffic und Wettbewerbsposition analysieren und schätzen; die Zahlen stammen nicht unbedingt direkt vom Websitebetreiber.

[https://www.similarweb.com/](https://www.similarweb.com/)

### HypeStat

Website-Statistiken und -Analysen, vor allem für Webrecherche und Marketing.

[https://hypestat.com/](https://hypestat.com/)

### StatsCrop

Öffentliche Berichte über Traffic, SEO und Website-Eigenschaften.

[https://www.statscrop.com/](https://www.statscrop.com/)

### ExpiredDomains

Abgelaufene oder zur Löschung vorgesehene Domains finden; Werkzeug für Domainhandel und -recherche.

[https://www.expireddomains.net/](https://www.expireddomains.net/)

<a id="s7"></a>

## 7. E-Mail-Adressen finden und prüfen

Diese Werkzeuge stellen keine beruflichen E-Mail-Konten bereit. Sie dienen der Kontaktsuche, der Zustellbarkeitsprüfung oder der Bewertung der E-Mail-Reputation.

### Hunter.io

Berufliche E-Mail-Adressen zu Unternehmen und Domains finden und prüfen.

[https://hunter.io/](https://hunter.io/)

### Reacher

Open-Source-Dienst und API zur E-Mail-Validierung für Entwickler.

[https://reacher.email/](https://reacher.email/)

### Email Hippo

E-Mail-Adressen validieren und ungültige Adressen sowie verdächtige Registrierungen reduzieren.

[https://www.emailhippo.com/](https://www.emailhippo.com/)

### Melissa

Qualität von Kontaktdaten einschließlich E-Mail- und Postadressen prüfen und verbessern.

[https://www.melissa.com/](https://www.melissa.com/)

### VoilaNorbert

Berufliche E-Mail-Adressen anhand von Personen- und Unternehmensinformationen finden und prüfen.

[https://www.voilanorbert.com/](https://www.voilanorbert.com/)

### FindEmails

E-Mail-Adressen suchen und validieren.

[https://www.findemails.com/](https://www.findemails.com/)

### EXPERTE Email Finder

Berufliche E-Mail-Adressen anhand eines Namens und einer Unternehmensdomain finden.

[https://www.experte.com/email-finder](https://www.experte.com/email-finder)

### Anymail Finder

Geschäftliche E-Mail-Adressen mit Prüfung der Zustellbarkeit finden.

[https://anymailfinder.com/](https://anymailfinder.com/)

### Tomba

Geschäftliche Kontaktdaten und E-Mail-Adressen suchen und anreichern.

[https://tomba.io/](https://tomba.io/)

### Snov.io

Kontaktdaten finden und prüfen sowie Vertriebskommunikation verwalten.

[https://snov.io/](https://snov.io/)

### EmailRep

Reputation und Risikoindikatoren einer E-Mail-Adresse zur Analyse verdächtiger E-Mails prüfen.

[https://emailrep.io/](https://emailrep.io/)

### MailboxValidator

E-Mail-Adressen über Weboberfläche und API validieren.

[https://www.mailboxvalidator.com/](https://www.mailboxvalidator.com/)

### ContactOut

Berufliche Kontaktdaten finden; vor allem ein Werkzeug für Personalbeschaffung und Vertrieb.

[https://contactout.com/](https://contactout.com/)

### Email-format

E-Mail-Adressmuster von Unternehmen prüfen, etwa name.surname@company.

[https://www.email-format.com/](https://www.email-format.com/)

### Emailable

Im Ausgangsbericht als aktuelles Weiterleitungsziel von Verify-email.org genannt; prüft E-Mail-Listen und Zustellbarkeit.

[https://emailable.com/](https://emailable.com/)

### Emailsearch.io

Geschäftliche Kontaktdaten nach Name, Unternehmen oder Domain suchen.

[https://emailsearch.io/](https://emailsearch.io/)

### EmailSherlock

Rückwärtssuche nach E-Mail-Adressen und zugehörigen Informationen; Ergebnisse sind Recherchehinweise, kein Identitätsnachweis.

[https://www.emailsherlock.com/](https://www.emailsherlock.com/)

<a id="s8"></a>

## 8. Bildersuche und Bildanalyse

### TinEye

Rückwärtsbildsuche, um veröffentlichte Kopien und andere Verwendungen desselben Fotos zu finden.

[https://tineye.com/](https://tineye.com/)

### Pixsy

Fotonutzung überwachen und bei der Verfolgung unerlaubter Nutzung helfen.

[https://www.pixsy.com/](https://www.pixsy.com/)

### Jimpl

Bildmetadaten und EXIF anzeigen, etwa Aufnahmezeit und Kamerainformationen.

[https://jimpl.com/](https://jimpl.com/)

### EXIFdata

EXIF anzeigen, bearbeiten und entfernen; im Ausgangsbericht wird die Verarbeitung im Browser erwähnt.

[https://www.exifdata.com/](https://www.exifdata.com/)

### PimEyes

Ähnliche Gesichtsbilder im Web suchen; visuelle Ähnlichkeit ist kein Identitätsnachweis.

[https://pimeyes.com/en](https://pimeyes.com/en)

### FaceCheck

Ähnliche Gesichtsfotos suchen; für einen eindeutigen Identitätsnachweis nicht ausreichend.

[https://facecheck.id/](https://facecheck.id/)

### Pictriev

Suche nach Gesichtsähnlichkeit, eher für Unterhaltung und Vergleiche als für verlässliche Identitätsanalysen.

[https://www.pictriev.com/](https://www.pictriev.com/)

### Same Energy

Bilder mit ähnlichem Stil und Erscheinungsbild finden; ein Werkzeug für visuelle Inspiration.

[https://same.energy/](https://same.energy/)

### Flickr

Fotos veröffentlichen und suchen; allgemeine Bildquelle statt spezialisiertem Sicherheitswerkzeug.

[https://www.flickr.com/](https://www.flickr.com/)

### Pixabay

Bibliothek für visuelle Inhalte ohne direkte Funktion als spezialisiertes Sicherheitswerkzeug.

[https://pixabay.com/](https://pixabay.com/)

<a id="s9"></a>

## 9. Telefonnummern: Grenzen bei Genauigkeit und Abdeckung

Diese Dienste garantieren weder die eindeutige Identifizierung jedes Rufnummerninhabers noch die Ermittlung des aktuellen Standorts einer Person.

### Tellows

Nutzerberichte und Bewertungen zu belästigenden oder verdächtigen Telefonnummern.

[https://www.tellows.com/](https://www.tellows.com/)

### Sync.me

Mögliche Anruferidentifizierung und Rufnummerninformationen anhand der Dienstdaten.

[https://sync.me/](https://sync.me/)

### NumLookup

Rufnummernrückwärtssuche in gesammelten Daten; die Qualität hängt von der Datenabdeckung ab.

[https://www.numlookup.com/](https://www.numlookup.com/)

### SpyDialer

US-Telefonnummern nachschlagen; kein weltweites Werkzeug zur Identifizierung jeder Nummer.

[https://spydialer.com/](https://spydialer.com/)

### National Cellular Directory

Verzeichnis für Telefonnummern und Kontaktdaten mit Schwerpunkt auf dem US-Markt.

[https://www.nationalcellulardirectory.com/](https://www.nationalcellulardirectory.com/)

### Phone Validator

Anschlusstypen wie Mobilfunk oder Festnetz und zugehörige Informationen prüfen.

[https://www.phonevalidator.com/](https://www.phonevalidator.com/)

### Free Carrier Lookup

Netzbetreiber und Anschlusstypen innerhalb der Abdeckung des Dienstes abfragen.

[https://www.freecarrierlookup.com/](https://www.freecarrierlookup.com/)

### ThisNumber

Wegweiser zu Telefonnummernquellen und Verzeichnissen in verschiedenen Ländern.

[https://www.thisnumber.com/](https://www.thisnumber.com/)

### ReversePhoneLookup

Informationen zu einer Rufnummer suchen; Ergebnisse sind kein amtlicher Nachweis der Anschlussinhaberschaft.

[https://www.reversephonelookup.com/](https://www.reversephonelookup.com/)

### ValidNumber

Rufnummernrückwärtssuche und mögliche Anruferinformationen.

[https://validnumber.com/](https://validnumber.com/)

### AnyWho

Personen- und Telefonnummernverzeichnis, hauptsächlich für die USA.

[https://www.anywho.com/](https://www.anywho.com/)

<a id="s10"></a>

## 10. Allgemeine Suchmaschinen

Dies sind keine spezialisierten Sicherheitswerkzeuge, sie helfen jedoch bei der Suche nach Dokumenten, Berichten und öffentlichen Informationen.

### Google

Allgemeine Web- und Bildersuche.

[https://www.google.com/](https://www.google.com/)

### Bing

Microsofts Suche nach Web- und Bildinhalten.

[https://www.bing.com/](https://www.bing.com/)

### Yahoo Search

Allgemeiner Suchdienst von Yahoo.

[https://search.yahoo.com/](https://search.yahoo.com/)

### Yandex

Web, Bilder und andere öffentliche Inhalte durchsuchen.

[https://yandex.com/](https://yandex.com/)

### Baidu

Suche mit starkem Schwerpunkt auf chinesischsprachigen Inhalten.

[https://www.baidu.com/](https://www.baidu.com/)

### You.com

Suchdienste und Web-APIs für KI-Anwendungen.

[https://you.com/](https://you.com/)

### SearXNG

Open-Source-Metasuchsoftware, die auf einem eigenen Server betrieben werden kann.

[https://docs.searxng.org/](https://docs.searxng.org/)

### DuckDuckGo

Allgemeine Suche mit Schwerpunkt auf Datenschutz.

[https://duckduckgo.com/](https://duckduckgo.com/)

### Swisscows

Suche mit Schwerpunkt auf Datenschutz und Inhaltsfilterung.

[https://swisscows.com/en](https://swisscows.com/en)

### Naver

Portal und allgemeiner Suchdienst mit Schwerpunkt auf koreanischsprachigen Inhalten.

[https://www.naver.com/](https://www.naver.com/)

### Brave Search

Allgemeine Suchmaschine von Brave.

[https://search.brave.com/](https://search.brave.com/)

### Yep

Allgemeine Suche für Nutzer und maschinelle Anwendungen.

[https://yep.com/](https://yep.com/)

### Gibiru

Suchdienst mit nach eigener Aussage besonderem Datenschutzfokus; diese Liste ist kein Datenschutzaudit.

[https://gibiru.com/](https://gibiru.com/)

### Kagi

Abonnementbasierte Suche mit Schwerpunkt auf einer werbefreien Nutzung.

[https://kagi.com/](https://kagi.com/)

</div>
