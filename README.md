<div align="center">

```
██████╗  ██████╗ ██████╗ ████████╗ ███████╗██╗    ██╗██╗ ██████╗  ██████╗ ███████╗██████╗
██╔=═██╗██╔═══██╗██╔══██╗╚══██╔══╝██╔════╝██║    ██║██║██╔════╝ ██╔════╝ ██╔════╝██╔══██╗
██████╔╝██║   ██║██████╔╝   ██║   ███████╗██║ █╗ ██║██║██║  ███╗██║  ███╗█████╗  ██████╔╝
██╔═══╝ ██║   ██║██╔══██╗   ██║   ╚════██║██║███╗██║██║██║   ██║██║   ██║██╔══╝  ██╔══██╗
██║     ╚██████╔╝██║  ██║   ██║   ███████║╚███╔███╔╝██║╚██████╔╝╚██████╔╝███████╗██║  ██║
╚═╝      ╚═════╝ ╚═╝  ╚═╝   ╚═╝   ╚══════╝ ╚══╝╚══╝ ╚═╝ ╚═════╝  ╚═════╝ ╚══════╝╚═╝  ╚═╝
```

### 🕵️ Web Security Academy — Lab Tracker

*Pwning labs. Taking notes. Breaking things responsibly.*

---

![Solved](https://img.shields.io/badge/Labs%20Solved-82-informational?style=for-the-badge&logo=target&logoColor=white&color=0A84FF)
![Updated](https://img.shields.io/badge/Last%20Updated-2026--08--09-informational?style=for-the-badge&logo=clockify&logoColor=white&color=F59E0B)
![Level](https://img.shields.io/badge/Level-NEWBIE-informational?style=for-the-badge&logo=hackthebox&logoColor=white&color=22C55E)
![Progress](https://img.shields.io/badge/Overall%20Progress-9.1%25-informational?style=for-the-badge&logo=progress&logoColor=white&color=8B5CF6)
![Tool](https://img.shields.io/badge/Tool-Burp%20Suite-informational?style=for-the-badge&logo=burpsuite&logoColor=white&color=FF6633)

</div>

---

## 📖 About

This file tracks my progress through [PortSwigger Web Security Academy](https://portswigger.net/web-security) labs. I focus on web app pentesting, documenting key labs as full writeups (linked below) and logging all solves here for reference.

> Full writeups are reserved for first-time techniques, complex exploits, or custom tooling. See `platforms/portswigger/` for details.

---



## 📊 Progress Dashboard

<div align="center">

| Tier | Solved | Total | Progress |
|:----:|:------:|:-----:|:--------:|
| 🟢 **Apprentice** | `32` | `61` | ![37%](https://img.shields.io/badge/-37.7%25-22C55E?style=flat-square) |
| 🟡 **Practitioner** | `46` | `174` | ![17%](https://img.shields.io/badge/-17.8%25-F59E0B?style=flat-square) |
| 🔴 **Expert** | `3` | `39` | ![5%](https://img.shields.io/badge/-5%25-EF4444?style=flat-square) |
| ⚡ **Total** | `82` | `274` | ![20.4%](https://img.shields.io/badge/-20.4%25-0A84FF?style=flat-square) |

</div>



## 🗂️ Categories Covered

| Category | Solved | Total | Status |
|----------|:------:|:-----:|--------|
| 🔐 Authentication vulnerabilities | `14` | `14` | ![Done](https://img.shields.io/badge/COMPLETE-22C55E?style=flat-square) |
| 💉 SQL injection | `11` | `18` | ![In progress](https://img.shields.io/badge/IN%20PROGRESS-F59E0B?style=flat-square) |
| 🚪 Access control | `13` | `13` | ![Done](https://img.shields.io/badge/COMPLETE-22C55E?style=flat-square) |
| 📜 Cross-site scripting | `30` | `30` | ![Done](https://img.shields.io/badge/COMPLETE-22C55E?style=flat-square) |
| 📂Path traversal | `6` | `6` | ![Done](https://img.shields.io/badge/COMPLETE-22C55E?style=flat-square) |
| 💻OS command injection | `5` | `5` | ![Done](https://img.shields.io/badge/COMPLETE-22C55E?style=flat-square) |
| 🔌 WebSockets | `0` | `3` | ![Not started](https://img.shields.io/badge/NOT%20STARTED-6B7280?style=flat-square) |
| 📤File upload vulnerabilities | `5` | `7` | ![In progress](https://img.shields.io/badge/IN%20PROGRESS-F59E0B?style=flat-square) |
| Web LLM attacks | `5` | `6` |![In progress](https://img.shields.io/badge/IN%20PROGRESS-F59E0B?style=flat-square) |
| NoSQL injection | `2` | `4` | ![In progress](https://img.shields.io/badge/IN%20PROGRESS-F59E0B?style=flat-square) |
| API testing | `1 ` | `5 ` | ![Done](https://img.shields.io/badge/COMPLETE-22C55E?style=flat-square) |
| Web LLM attacks | `1` | `8` | ![In progress](https://img.shields.io/badge/IN%20PROGRESS-F59E0B?style=flat-square) |
| Server-side request forgery (SSRF) | `3` | `7` | ![In progress](https://img.shields.io/badge/IN%20PROGRESS-F59E0B?style=flat-square) |
| GraphQL API vulnerabilities | `5` | `5` | ![Done](https://img.shields.io/badge/COMPLETE-22C55E?style=flat-square) |
---

## 🗺️ How to Read

| Column | Description |
|--------|-------------|
| `No` | Sequential lab number |
| `Date` | When solved `YYYY-MM-DD` |
| `Topic` | Vulnerability category |
| `Lab Title` | Exact name from PortSwigger |
| `Difficulty` | `APPRENTICE` · `PRACTITIONER` · `EXPERT` |
| `Writeup` | Link to full writeup or `N/A` for quick solves |

---

## 🧪 Solved Labs

> 📌 **25 labs solved** · Sorted chronologically · Pending slots reserved below

| No | Date | Topic | Lab Title | Difficulty | Writeup |
|----|------|-------|-----------|:----------:|:-------:|
| `01` | 2026-06-17 | 💉 SQL Injection | SQL injection vulnerability in WHERE clause allowing retrieval of hidden data | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `02` | 2026-06-17 | 💉 SQL Injection | SQL injection vulnerability allowing login bypass | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `03` | 2026-06-17 | 💉 SQL Injection | SQL injection attack, querying the database type and version on Oracle | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `04` | 2026-06-17 | 💉 SQL Injection | SQL injection attack, querying the database type and version on MySQL and Microsoft | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `05` | 2026-06-17 | 💉 SQL Injection | SQL injection attack, listing the database contents on non-Oracle databases | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `06` | 2026-06-17 | 💉 SQL Injection | SQL injection attack, listing the database contents on Oracle | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `07` | 2026-06-17 | 💉 SQL Injection | SQL injection UNION attack, determining the number of columns returned by the query | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `08` | 2026-06-17 | 💉 SQL Injection | SQL injection UNION attack, finding a column containing text | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `09` | 2026-06-17 | 💉 SQL Injection | SQL injection UNION attack, retrieving data from other tables | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `10` | 2026-06-17 | 💉 SQL Injection | SQL injection UNION attack, retrieving multiple values in a single column | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `11` | 2026-06-17 | 💉 SQL Injection | Blind SQL injection with conditional responses | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `12` | 2026-06-22 | 🔐 Authentication | Username enumeration via different responses | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `13` | 2026-06-22 | 🔐 Authentication | 2FA simple bypass | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `14` | 2026-06-23 | 🔐 Authentication | Password reset broken logic | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `15` | 2026-06-23 | 🔐 Authentication | Username enumeration via subtly different responses | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `16` | 2026-06-23 | 🔐 Authentication | Username enumeration via response timing | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `17` | 2026-06-24 | 🔐 Authentication | Broken brute-force protection, IP block | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `18` | 2026-06-24 | 🔐 Authentication | Username enumeration via account lock | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `19` | 2026-06-25 | 🔐 Authentication | 2FA broken logic | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `20` | 2026-06-25 | 🔐 Authentication | Brute-forcing a stay-logged-in cookie | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `21` | 2026-06-25 | 🔐 Authentication | Offline password cracking | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `22` | 2026-06-26 | 🔐 Authentication | Broken brute-force protection, multiple credentials per request | ![](https://img.shields.io/badge/EXPERT-EF4444?style=flat-square) | — |
| `23` | 2026-06-27 | 🔐 Authentication | Password reset poisoning via middleware | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `24` | 2026-06-27 | 🔐 Authentication | Password brute-force via password change | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `25` | 2026-06-28 | 🔐 Authentication | 2FA bypass using a brute-force attack | ![](https://img.shields.io/badge/EXPERT-EF4444?style=flat-square) | — |
| `26` | 2026-06-29 |  Cross-site scripting | Reflected XSS into HTML context with nothing encoded | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `27` | 2026-06-29 |  Cross-site scripting | Stored XSS into HTML context with nothing encoded | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `28` | 2026-06-29 | Path traversal | File path traversal, simple case | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `29` | 2026-06-30 | Cross-site scripting | DOM XSS in document.write sink using source location.search | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `30` | 2026-06-30 | Cross-site scripting | DOM XSS in innerHTML sink using source location.search | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `31` | 2026-06-30 | Path traversal | File path traversal, traversal sequences blocked with absolute path bypass | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `32` | 2026-06-30 | Path traversal | File path traversal, traversal sequences stripped non-recursively | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `33` | 2026-07-01 | Cross-site scripting | DOM XSS in jQuery anchor href attribute sink using location.search source | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `34` | 2026-07-01 | Cross-site scripting | DOM XSS in jQuery selector sink using a hashchange event | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `35` | 2026-07-02 | Cross-site scripting | Reflected XSS into attribute with angle brackets HTML-encoded | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `36` | 2026-07-02 | Path traversal | File path traversal, traversal sequences stripped with superfluous URL-decode | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `37` | 2026-07-02 | Path traversal | File path traversal, validation of start of path | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `38` | 2026-07-03 | Path traversal | File path traversal, validation of file extension with null byte bypass | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `39` | 2026-07-03 | OS command injection | OS command injection, simple case | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `40` | 2026-07-04 | OS command injection | Blind OS command injection with time delays | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `41` | 2026-07-04 | OS command injection | Blind OS command injection with output redirection | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `42` | 2026-07-05 | OS command injection | Blind OS command injection with out-of-band interaction | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `43` | 2026-07-05 | OS command injection | Blind OS command injection with out-of-band data exfiltration | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `44` | 2026-07-06 | Access control vulnerabilities | Unprotected admin functionality | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `45` | 2026-06-07 | Access control vulnerabilities | Unprotected admin functionality with unpredictable URL | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `46` | 2026-06-07 | Access control vulnerabilities | User role controlled by request parameter | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `47` | 2026-06-08 | Access control vulnerabilities | User role can be modified in user profile | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `48` | 2026-06-08 | Access control vulnerabilities | User ID controlled by request parameter  | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `49` | 2026-06-08 | Access control vulnerabilities | User ID controlled by request parameter, with unpredictable user IDs | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `50` | 2026-06-09 | Access control vulnerabilities | User ID controlled by request parameter with data leakage in redirect | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `51` | 2026-06-09 | Access control vulnerabilities | User ID controlled by request parameter with password disclosure | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) |  |
| `52` | 2026-06-09 | Access control vulnerabilities | Insecure direct object references | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `53` | 2026-06-10 | Access control vulnerabilities | URL-based access control can be circumvented | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `54` | 2026-06-11 | Access control vulnerabilities | Method-based access control can be circumvented | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `55` | 2026-06-11 | Access control vulnerabilities | Multi-step process with no access control on one step  | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `56` | 2026-07-12 | Access control vulnerabilities | Referer-based access control  | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `57` | 2026-07-13 | File upload vulnerabilities | Remote code execution via web shell upload | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `58` | 2026-07-14 | File upload vulnerabilities | Web shell upload via Content-Type restriction bypass | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `59` | 2026-07-15 | File upload vulnerabilities | Web shell upload via path traversal | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `60` | 2026-07-15 | File upload vulnerabilities | Web shell upload via obfuscated file extension | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `61` | 2026-07-16 | File upload vulnerabilities | Remote code execution via polyglot web shell upload | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `62` | 2026-07-20 | Race conditions | Limit overrun race conditions | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `63` | 2026-07-21 | Race conditions | Bypassing rate limits via race conditions | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `64` | 2026-06-21 | Race conditions | Multi-endpoint race conditions | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `65` | 2026-06-22 | Race conditions | Single-endpoint race conditions |![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | — |
| `66` | 2026-06-23 | Race conditions | Exploiting time-sensitive vulnerabilities | ![](https://img.shields.io/badge/PRACTITIONER-F59E0B?style=flat-square) | [📄 Writeup](writeups/items/Exploiting-time-sensitive-vulnerabilities.md) |
| `67` | 2026-06-24 | NoSQL injection | Detecting NoSQL injection | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `68` | 2026-06-25 | NoSQL injection | Exploiting NoSQL operator injection to bypass authentication | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `69` | 2026-06-25 | API testing | Exploiting an API endpoint using documentation | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `70` | 2026-06-26 | Web LLM attacks | Exploiting LLM APIs with excessive agency | ![](https://img.shields.io/badge/APPRENTICE-22C55E?style=flat-square) | — |
| `71` | 2026-07-27 | Server-side request forgery (SSRF) | Basic SSRF against the local server | — |  |
| `72` | 2026-07-28 | Server-side request forgery (SSRF) | Basic SSRF against another back-end system | — | — |
| `73` | 2026-08-03 | Server-side request forgery (SSRF) | Blind SSRF with out-of-band detection | — | — |
| `74` | 2026-08-03 | API testing | Exploiting server-side parameter pollution in a query string | — | — |
| `75` | 2026-08-04 | API testing | Finding and exploiting an unused API endpoint | — | — |
| `76` | 2026-08-05 | API testing | Exploiting a mass assignment vulnerability | — | — |
| `77` | 2026-08-06 | API testing | Exploiting server-side parameter pollution in a REST URL | — | — |
| `78` | 2026-08-06 | GraphQL API vulnerabilities | Accessing private GraphQL posts | — | — |
| `79` | 2026-08-07 | GraphQL API vulnerabilities | Accidental exposure of private GraphQL fields | — | — |
| `80` | 2026-08-08 | GraphQL API vulnerabilities | Finding a hidden GraphQL endpoint | — | — |
| `81` | 2026-08-08 | GraphQL API vulnerabilities | Bypassing GraphQL brute force protections | — | — |
| `82` | 2026-08-09 | GraphQL API vulnerabilities | Performing CSRF exploits over GraphQL | — | — |
| `83` | 2026-08-10 | Cross-site scripting | Stored XSS into anchor href attribute with double quotes HTML-encoded | — | — |
| `84` | 2026-08-10 | Cross-site scripting | Reflected XSS into a JavaScript string with angle brackets HTML encoded | — | — |
| `85` | 2026-08-10 | Cross-site scripting | DOM XSS in document.write sink using source location.search inside a select element | — | — |
| `86` | 2026-08-10 | Cross-site scripting | DOM XSS in AngularJS expression with angle brackets and double quotes HTML-encoded | — | — |
| `87` | 2026-08-10 | Cross-site scripting | Reflected DOM XSS | — | — |
| `88` | 2026-08-10 | Cross-site scripting | Stored DOM XSS | — | — |
| `89` | 2026-08-11 | Cross-site scripting | Reflected XSS into HTML context with most tags and attributes blocked | — | — |
| `90` | 2026-08-11 | Cross-site scripting | Reflected XSS into HTML context with all tags blocked except custom ones | — | — |
| `91` | 2026-08-12 | Cross-site scripting | Reflected XSS with some SVG markup allowed | — | — |
| `92` | 2026-08-12 | Cross-site scripting | Reflected XSS in canonical link tag | — | — |
| `93` | 2026-08-12 | Cross-site scripting | Reflected XSS into a JavaScript string with single quote and backslash escaped | — | — |
| `94` | 2026-08-12 | Cross-site scripting | Reflected XSS into a JavaScript string with angle brackets and double quotes HTML-encoded and single quotes escaped | — | — |
| `95` | 2026-08-13 | Cross-site scripting | Stored XSS into onclick event with angle brackets and double quotes HTML-encoded and single quotes and backslash escaped | — | — |
| `96` | 2026-08-14 | Cross-site scripting | Reflected XSS into a template literal with angle brackets, single, double quotes, backslash and backticks Unicode-escaped | — | — |
| `97` | 2026-08-14 | Cross-site scripting | Exploiting cross-site scripting to steal cookies | — | — |
| `98` | 2026-08-14 | Cross-site scripting | Exploiting cross-site scripting to capture passwords | — | — |
| `99` | 2026-08-14 | Cross-site scripting | Exploiting XSS to bypass CSRF defenses | — | — |
| `100` | 2026-08-14 | Cross-site scripting | Reflected XSS with AngularJS sandbox escape without strings | — | — |
| `101` | 2026-08-14 | Cross-site scripting | Reflected XSS with AngularJS sandbox escape and CSP | — | — |
| `102` | 2026-08-14 | Cross-site scripting | Reflected XSS with event handlers and href attributes blocked | — | — |
| `103` | 2026-08-14 | Cross-site scripting | Reflected XSS in a JavaScript URL with some characters blocked | — | — |
| `104` | 2026-08-15 | Cross-site scripting | Reflected XSS protected by very strict CSP, with dangling markup attack | — | — |
| `105` | 2026-08-15 | Cross-site scripting | Reflected XSS protected by CSP, with CSP bypass | — | — |
| `106` | 2026-08-16 | Cross-origin resource sharing (CORS) | CORS vulnerability with basic origin reflection | — | — |
| `107` | 2026-08-16 | Cross-origin resource sharing (CORS) | CORS vulnerability with trusted null origin | — | — |
| `108` | 2026-08-16 | Cross-origin resource sharing (CORS) | CORS vulnerability with trusted insecure protocols | — | — |
| `109` | 2026-08-00 | — | *Pending...* | — | — |
| `110` | 2026-08-00 | — | *Pending...* | — | — |
| `111` | 2026-08-00 | — | *Pending...* | — | — |
| `112` | 2026-08-00 | — | *Pending...* | — | — |
| `113` | 2026-08-00 | — | *Pending...* | — | — |
| `114` | 2026-08-00 | — | *Pending...* | — | — |
| `115` | 2026-08-00 | — | *Pending...* | — | — |
| `116` | 2026-08-00 | — | *Pending...* | — | — |
| `117` | 2026-08-00 | — | *Pending...* | — | — |



---

<div align="center">

*Keep hacking. Stay curious. Never stop learning.* 🔓

[![PortSwigger](https://img.shields.io/badge/PortSwigger-Web%20Security%20Academy-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white)](https://portswigger.net/web-security)

</div>
