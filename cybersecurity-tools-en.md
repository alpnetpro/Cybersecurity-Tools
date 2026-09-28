---
title: "Cybersecurity Tools Guide"
author: "Alp Gokturk & ChatGPT ai"
version: "1"
date: "2026-09-28"
location: "Istanbul"
email: "alpnetpro@gmail.com"
github: "https://github.com/Alpnetpro"
folder: "Cybersecurity Tools"
language: "en"
---

<div dir="ltr">

# Cybersecurity Tools Guide

This report is the work of Alp Gokturk, prepared with the capabilities of ChatGPT artificial intelligence.

**Alp Gokturk & ChatGPT ai**

**Version 1 | 28 September 2026 | 2026-09-28 | Istanbul**

If you notice an error or have a suggestion, please email me.

[alpnetpro@gmail.com](mailto:alpnetpro@gmail.com)

GitHub: [https://github.com/Alpnetpro](https://github.com/Alpnetpro)

The latest version of this report is available to download from my GitHub, in the Cybersecurity Tools folder.

## Contents

Page numbers refer to the English PDF. Section titles link to the corresponding sections in this Markdown file.

| Section | Page |
|---|---:|
| [1. Domains, DNS and registration data](#s1) | 3 |
| [2. Digital certificates, TLS, Wi-Fi and device manufacturers](#s2) | 5 |
| [3. IP ownership, routing and attack surface management](#s3) | 7 |
| [4. Attack technique references and defensive study](#s4) | 9 |
| [5. Code, open-source projects and APIs](#s5) | 11 |
| [6. Website information and archival search](#s6) | 15 |
| [7. Finding and checking email addresses](#s7) | 17 |
| [8. Image search and analysis](#s8) | 20 |
| [9. Phone numbers: accuracy and coverage limitations](#s9) | 22 |
| [10. General search engines](#s10) | 24 |

<a id="s1"></a>

## 1. Domains, DNS and registration data

### DomainIQ

Research domains and IP addresses using collected and historical data.

[https://www.domainiq.com/](https://www.domainiq.com/)

### Who.is

Check domain registration data through WHOIS and RDAP, including DNS and name servers.

[https://who.is/](https://who.is/)

### Whoisology

An archive of WHOIS data for investigating domain history and relationships; older records may not reflect the current situation.

[https://whoisology.com/](https://whoisology.com/)

### WhoisXML API

WHOIS, DNS, domain and IP APIs for research and automation.

[https://www.whoisxmlapi.com/](https://www.whoisxmlapi.com/)

### SpyOnWeb

Find possible connections between websites through shared technical attributes; a shared attribute does not prove common ownership.

[https://spyonweb.net/](https://spyonweb.net/)

### SynapsInt

Search domains, IP addresses, ASNs, SSL data and email addresses in one interface.

[https://synapsint.com/](https://synapsint.com/)

### C99 API

APIs for technical lookups and utilities; features and quotas depend on the chosen service.

[https://api.c99.nl/](https://api.c99.nl/)

<a id="s2"></a>

## 2. Digital certificates, TLS, Wi-Fi and device manufacturers

### crt.sh

Search certificates by domain, organization or fingerprint; useful for Certificate Transparency research.

[https://crt.sh/](https://crt.sh/)

### Cert Spotter

Monitor certificates issued for a domain and identify certificate security or availability problems.

[https://sslmate.com/certspotter/](https://sslmate.com/certspotter/)

### CipherSuite.info

A searchable reference for TLS cipher suites and their security properties.

[https://ciphersuite.info/](https://ciphersuite.info/)

### Certs.io

Search TLS certificates to discover assets related to a domain or organization; account functionality was not tested in the source report.

[https://certs.io/](https://certs.io/)

### WiGLE

Collect and map observations of wireless networks; this is not a list of networks that you are authorized to join.

[https://wigle.net/](https://wigle.net/)

### WiFi Map

Find Wi-Fi hotspots; mainly useful for connectivity and travel rather than specialist security analysis.

[https://www.wifimap.io/](https://www.wifimap.io/)

### OpenWiFiMap

An open-source mapping project for community wireless networks such as Freifunk.

[https://openwifimap.net/](https://openwifimap.net/)

### MACVendors

Identify the registered manufacturer of a MAC address range using IEEE data.

[https://macvendors.com/](https://macvendors.com/)

### MACAddress.io

Look up manufacturers and MAC block details, with an API suitable for network scripts.

[https://macaddress.io/](https://macaddress.io/)

### MACLookup

Look up a manufacturer using a MAC address or OUI; useful for initial device checks.

[https://maclookup.app/](https://maclookup.app/)

### MACVendorLookup

Match MAC addresses to registered manufacturer information.

[https://www.macvendorlookup.com/](https://www.macvendorlookup.com/)

<a id="s3"></a>

## 3. IP ownership, routing and attack surface management

### FullHunt

Discover and monitor an organization's internet-facing assets for attack surface management.

[https://fullhunt.io/](https://fullhunt.io/)

### RedHunt Labs

Identify external assets and security risks through continuous monitoring.

[https://redhuntlabs.com/](https://redhuntlabs.com/)

### Deepinfo

Manage threat exposure and assess external assets and risks.

[https://www.deepinfo.com/](https://www.deepinfo.com/)

### IPinfo

IP, network and approximate location data for log enrichment and identifying network providers.

[https://ipinfo.io/](https://ipinfo.io/)

### ipdata

An API for IP location and attributes, supporting analysis, filtering and automation.

[https://ipdata.co/](https://ipdata.co/)

### NetworksDB

Investigate relationships between companies, IP ranges, domains and network data.

[https://networksdb.io/](https://networksdb.io/)

### BGP.tools

Inspect ASNs, IP prefixes and routing relationships; useful for learning and troubleshooting BGP.

[https://bgp.tools/](https://bgp.tools/)

### BigDataCloud

APIs for approximate IP geolocation and geographic and network data.

[https://www.bigdatacloud.com/](https://www.bigdatacloud.com/)

### RADb

An internet routing registry for examining route objects and registered policies.

[https://www.radb.net/](https://www.radb.net/)

### Cloudflare Radar

Observe large-scale trends in internet traffic, outages, attacks and technologies.

[https://radar.cloudflare.com/](https://radar.cloudflare.com/)

### Pentest-Tools

Penetration testing and scanning tools for assessing assets covered by authorization.

[https://pentest-tools.com/](https://pentest-tools.com/)

<a id="s4"></a>

## 4. Attack technique references and defensive study

These are mainly research and learning references, not general-purpose search engines.

### Hacking the Cloud

An encyclopedia of offensive cloud security techniques for understanding configuration risks.

[https://hackingthe.cloud/](https://hackingthe.cloud/)

### LOLDrivers

Information about vulnerable or malicious Windows drivers for research and detection rule development.

[https://www.loldrivers.io/](https://www.loldrivers.io/)

### LOOBins

Misuse techniques involving built-in macOS tools, for behavioral analysis and defense.

[https://loobins.io/](https://loobins.io/)

### WADComs

A reference for Windows and Active Directory assessment tools and commands in authorized tests.

[https://wadcoms.github.io/](https://wadcoms.github.io/)

### Living Off the Pipeline

Documentation of possible misuse of CI/CD tools, supporting development pipeline security.

[https://boostsecurityio.github.io/lotp/](https://boostsecurityio.github.io/lotp/)

### LOLAPPS

A list of ordinary applications whose capabilities may be misused in attacks.

[https://lolapps-project.github.io/](https://lolapps-project.github.io/)

### LOTHardware

A catalog of attack-related hardware, including USB and HID tools.

[https://lothardware.com.tr/](https://lothardware.com.tr/)

### CVExploits

Find exploit resources associated with CVEs; results must be matched to the actual version and conditions.

[https://cvexploits.io/](https://cvexploits.io/)

### Exploit Observer

Aggregates vulnerability and exploit information and provides an API; the source report did not verify the claim that it is the largest.

[https://www.exploit.observer/](https://www.exploit.observer/)

### Coalition Exploit Scoring System

Scores the probability of vulnerability exploitation to support prioritization.

[https://ess.coalitioninc.com/](https://ess.coalitioninc.com/)

<a id="s5"></a>

## 5. Code, open-source projects and APIs

### GitHub Code Search

Search code, functions and implementation examples in accessible repositories.

[https://github.com/search?type=code](https://github.com/search?type=code)

### GitLab

Host projects and search repository code and content; features depend on settings and the plan.

[https://gitlab.com/](https://gitlab.com/)

### grep.app

Search text and code snippets in public repositories to find examples of function usage.

[https://grep.app/](https://grep.app/)

### Sourcegraph

Search and understand code across projects and repositories for development and software analysis.

[https://sourcegraph.com/](https://sourcegraph.com/)

### Searchcode

Repository analysis and code search, with APIs and MCP for programming assistants.

[https://searchcode.com/](https://searchcode.com/)

### PublicWWW

Search text within web page source code to find shared technologies or code snippets.

[https://publicwww.com/](https://publicwww.com/)

### NerdyData

Identify websites that use specific technologies by examining their web code.

[https://www.nerdydata.com/](https://www.nerdydata.com/)

### Veloria (formerly WP Directory)

Search WordPress code for research into plugins and themes.

[https://veloria.dev/](https://veloria.dev/)

### GitHub Gist

Publish and search code snippets, technical notes and short scripts.

[https://gist.github.com/](https://gist.github.com/)

### SourceForge

Host and discover projects and software; each project should be evaluated separately.

[https://sourceforge.net/](https://sourceforge.net/)

### Codeberg

A collaboration and Git hosting platform for open-source projects.

[https://codeberg.org/](https://codeberg.org/)

### Launchpad

Development hosting, bug reporting and project collaboration, especially in the Ubuntu ecosystem.

[https://launchpad.net/](https://launchpad.net/)

### SourceHut

A suite of software development hosting and collaboration tools.

[https://sourcehut.org/](https://sourcehut.org/)

### Android Open Source

Official Android code repositories for studying the operating system and its components.

[https://android.googlesource.com/](https://android.googlesource.com/)

### deps.dev

Information about open-source packages and dependencies for understanding the software supply chain.

[https://deps.dev/](https://deps.dev/)

### ecosyste.ms

Data and APIs covering open-source projects, packages and dependencies.

[https://ecosyste.ms/](https://ecosyste.ms/)

### Postman Explore

Discover APIs and public request collections for practicing API usage and automation.

[https://www.postman.com/explore](https://www.postman.com/explore)

### Swagger

Tools for designing, documenting and testing APIs.

[https://swagger.io/product/](https://swagger.io/product/)

### HotExamples

Code examples for study; an example you find is not necessarily secure or up to date.

[https://hotexamples.com/](https://hotexamples.com/)

### Snipplr

A code snippet sharing repository; examples require a quality review.

[https://snipplr.com/](https://snipplr.com/)

### Google Code Archive

A historical archive of Google Code projects, not an active hosting service for new projects.

[https://code.google.com/archive/](https://code.google.com/archive/)

<a id="s6"></a>

## 6. Website information and archival search

### Intelligence X

Search domains, email addresses, IP addresses and other identifiers in archives and collected datasets.

[https://intelx.io/](https://intelx.io/)

### Phonebook.cz

Find domains, email addresses and URLs related to a domain; the source report states that a paid license is required.

[https://phonebook.cz/](https://phonebook.cz/)

### Common Crawl Index

Search the Common Crawl URL index to investigate historical traces on the web.

[https://index.commoncrawl.org/](https://index.commoncrawl.org/)

### BuiltWith

Identify website technologies, such as content management systems and analytics tools.

[https://builtwith.com/](https://builtwith.com/)

### Netcraft Site Report

Reports on a website's technology and hosting infrastructure.

[https://sitereport.netcraft.com/](https://sitereport.netcraft.com/)

### GrayhatWarfare - Buckets

Search cloud storage resources visible on the internet.

[https://buckets.grayhatwarfare.com/](https://buckets.grayhatwarfare.com/)

### GrayhatWarfare - Shorteners

Search URLs collected from link shortening services.

[https://shorteners.grayhatwarfare.com/](https://shorteners.grayhatwarfare.com/)

### Similarweb

Analyze and estimate website traffic and competitive position; figures are not necessarily direct data from the site owner.

[https://www.similarweb.com/](https://www.similarweb.com/)

### HypeStat

Website statistics and analysis, mainly for web research and marketing.

[https://hypestat.com/](https://hypestat.com/)

### StatsCrop

Public reports about traffic, SEO and website characteristics.

[https://www.statscrop.com/](https://www.statscrop.com/)

### ExpiredDomains

Find expired domains or domains pending deletion; a tool for domain trading and research.

[https://www.expireddomains.net/](https://www.expireddomains.net/)

<a id="s7"></a>

## 7. Finding and checking email addresses

These tools do not provide professional email accounts. They find contact information, check deliverability or assess email reputation.

### Hunter.io

Find and verify professional email addresses associated with companies and domains.

[https://hunter.io/](https://hunter.io/)

### Reacher

An open-source email validation service and API for developers.

[https://reacher.email/](https://reacher.email/)

### Email Hippo

Validate email addresses and reduce invalid addresses and suspicious sign-ups.

[https://www.emailhippo.com/](https://www.emailhippo.com/)

### Melissa

Validate and improve contact data quality, including email and postal addresses.

[https://www.melissa.com/](https://www.melissa.com/)

### VoilaNorbert

Find and verify work email addresses using information about a person and their company.

[https://www.voilanorbert.com/](https://www.voilanorbert.com/)

### FindEmails

Search and validate email addresses.

[https://www.findemails.com/](https://www.findemails.com/)

### EXPERTE Email Finder

Find professional email addresses using a name and company domain.

[https://www.experte.com/email-finder](https://www.experte.com/email-finder)

### Anymail Finder

Find business email addresses with a deliverability checking process.

[https://anymailfinder.com/](https://anymailfinder.com/)

### Tomba

Search and enrich business contact information and email addresses.

[https://tomba.io/](https://tomba.io/)

### Snov.io

Find and verify contact information and manage sales communications.

[https://snov.io/](https://snov.io/)

### EmailRep

Check an email address's reputation and risk indicators for suspicious email analysis.

[https://emailrep.io/](https://emailrep.io/)

### MailboxValidator

Validate email addresses through a web interface and API.

[https://www.mailboxvalidator.com/](https://www.mailboxvalidator.com/)

### ContactOut

Find professional contact information; mainly a recruitment and sales tool.

[https://contactout.com/](https://contactout.com/)

### Email-format

Check companies' email naming patterns, such as name.surname@company.

[https://www.email-format.com/](https://www.email-format.com/)

### Emailable

Identified in the source report as the current destination of Verify-email.org; checks email lists and deliverability.

[https://emailable.com/](https://emailable.com/)

### Emailsearch.io

Search business contact information by name, company or domain.

[https://emailsearch.io/](https://emailsearch.io/)

### EmailSherlock

Reverse email lookup and related information; results are research leads, not proof of identity.

[https://www.emailsherlock.com/](https://www.emailsherlock.com/)

<a id="s8"></a>

## 8. Image search and analysis

### TinEye

Reverse image search to find published copies and other uses of the same photograph.

[https://tineye.com/](https://tineye.com/)

### Pixsy

Monitor photo usage and help pursue unauthorized use.

[https://www.pixsy.com/](https://www.pixsy.com/)

### Jimpl

Display image metadata and EXIF, such as capture time and camera information.

[https://jimpl.com/](https://jimpl.com/)

### EXIFdata

View, edit and remove EXIF; the source report mentions in-browser processing.

[https://www.exifdata.com/](https://www.exifdata.com/)

### PimEyes

Search the web for similar facial images; visual similarity is not proof of identity.

[https://pimeyes.com/en](https://pimeyes.com/en)

### FaceCheck

Search for similar facial photographs; insufficient for conclusive identity verification.

[https://facecheck.id/](https://facecheck.id/)

### Pictriev

Facial similarity search, mainly for entertainment and comparison rather than reliable identity analysis.

[https://www.pictriev.com/](https://www.pictriev.com/)

### Same Energy

Find images with a similar style and appearance; a visual inspiration tool.

[https://same.energy/](https://same.energy/)

### Flickr

Publish and search photographs; a general image source rather than a specialist security tool.

[https://www.flickr.com/](https://www.flickr.com/)

### Pixabay

A visual content library with no direct role as a specialist security tool.

[https://pixabay.com/](https://pixabay.com/)

<a id="s9"></a>

## 9. Phone numbers: accuracy and coverage limitations

These services do not guarantee identification of every number’s owner or a person’s live location.

### Tellows

User reports and ratings for nuisance or suspicious phone numbers.

[https://www.tellows.com/](https://www.tellows.com/)

### Sync.me

Possible caller identification and phone number details based on the service's data.

[https://sync.me/](https://sync.me/)

### NumLookup

Reverse phone lookup in collected data; quality depends on data coverage.

[https://www.numlookup.com/](https://www.numlookup.com/)

### SpyDialer

Look up US phone numbers; not a global tool for identifying every number.

[https://spydialer.com/](https://spydialer.com/)

### National Cellular Directory

A phone number and contact directory focused on the US market.

[https://www.nationalcellulardirectory.com/](https://www.nationalcellulardirectory.com/)

### Phone Validator

Check line types, such as mobile or landline, and related information.

[https://www.phonevalidator.com/](https://www.phonevalidator.com/)

### Free Carrier Lookup

Look up carriers and line types within the service's coverage.

[https://www.freecarrierlookup.com/](https://www.freecarrierlookup.com/)

### ThisNumber

A guide to phone number resources and directories in different countries.

[https://www.thisnumber.com/](https://www.thisnumber.com/)

### ReversePhoneLookup

Search information associated with a number; results are not official evidence of line ownership.

[https://www.reversephonelookup.com/](https://www.reversephonelookup.com/)

### ValidNumber

Reverse phone lookup and possible caller information.

[https://validnumber.com/](https://validnumber.com/)

### AnyWho

A directory of people and phone numbers, mainly for the United States.

[https://www.anywho.com/](https://www.anywho.com/)

<a id="s10"></a>

## 10. General search engines

These are not specialist security tools, but they help find documents, reports and public information.

### Google

General web and image search.

[https://www.google.com/](https://www.google.com/)

### Bing

Microsoft's web and visual content search.

[https://www.bing.com/](https://www.bing.com/)

### Yahoo Search

Yahoo's general search service.

[https://search.yahoo.com/](https://search.yahoo.com/)

### Yandex

Search the web, images and other public content.

[https://yandex.com/](https://yandex.com/)

### Baidu

Search with a strong focus on Chinese-language content.

[https://www.baidu.com/](https://www.baidu.com/)

### You.com

Search services and web APIs for artificial intelligence applications.

[https://you.com/](https://you.com/)

### SearXNG

Open-source metasearch software that can be hosted on your own server.

[https://docs.searxng.org/](https://docs.searxng.org/)

### DuckDuckGo

General search with a focus on privacy.

[https://duckduckgo.com/](https://duckduckgo.com/)

### Swisscows

Search emphasizing privacy and content filtering.

[https://swisscows.com/en](https://swisscows.com/en)

### Naver

A portal and general search service focused on Korean-language content.

[https://www.naver.com/](https://www.naver.com/)

### Brave Search

Brave's general search engine.

[https://search.brave.com/](https://search.brave.com/)

### Yep

General search for users and machine applications.

[https://yep.com/](https://yep.com/)

### Gibiru

A search service claiming a privacy focus; this list is not a privacy audit.

[https://gibiru.com/](https://gibiru.com/)

### Kagi

Subscription search focused on an ad-free experience.

[https://kagi.com/](https://kagi.com/)

</div>
