<p align="center">
  <img src="https://www.reddit.com/r/WatchDogs_Legion/comments/1ms0ro3/my_browser_had_a_ubisoft_ad_today/" alt="Mazen Turky — Offensive Security" width="100%" style="border-radius:8px"/>
</p>

<h1 align="center">
  <img alt="typing" src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=34&color=00ff99&center=true&lines=Hi,+I%27m+Mazen+Turky+%F0%9F%91%8B;EWPT+%7C+CyberTalents+%7C+Penetration+Tester;I+Find+Vulnerabilities+%26+Help+Fix+Them+%F0%9F%94%A5" />
</h1>

<p align="center">
  <a href="mailto:turkymazen13@gmail.com"><img src="https://img.shields.io/badge/Email-turkymazen13%40gmail.com-e84855?style=for-the-badge&logo=gmail" alt="email" /></a>
  <a href="https://www.linkedin.com/in/mazen-abdellatief/"><img src="https://img.shields.io/badge/LinkedIn-Mazen%20Abdellatief-0A66C2?style=for-the-badge&logo=linkedin" alt="linkedin" /></a>
  <a href="https://certs.ine.com/042fdd2d-4746-4eb7-a50c-5103d9e70607#acc.29MDil3q"><img src="https://img.shields.io/badge/eWPT-INE-181717?style=for-the-badge" alt="eWPT" /></a>
  <a href="https://cybertalents.com/certifications/9a8099ed-c91c-47aa-8a9c-5cde72865d40"><img src="https://img.shields.io/badge/CyberTalents-Web-ffdd00?style=for-the-badge" alt="cybertalents-web" /></a>
  <a href="https://cybertalents.com/certifications/9f496854-fbb4-4c58-a1cb-6075df2bef76"><img src="https://img.shields.io/badge/CyberTalents-Mobile-ffdd00?style=for-the-badge" alt="cybertalents-mobile" /></a>
  <a href="https://github.com/MazenTurky7"><img src="https://img.shields.io/badge/GitHub-MazenTurky7-8b949e?style=for-the-badge&logo=github" alt="github" /></a>
</p>

---

## 🔥 TL;DR — Who I am
**EWPT-certified Cybersecurity Engineer** · Offensive security & pentesting specialist. I find and validate web/mobile vulnerabilities (SQLi, XSS, CSRF, IDOR, SSRF), simulate AD attack paths, and deliver **actionable remediation** that dev teams can implement the next day.

---

## 🧰 Quick Tech Stack
`Burp Suite` • `MobSF` • `Frida` • `Nmap` • `Metasploit` • `OWASP ZAP` • `Python` • `Bash` • `PowerShell` • `Kali` • `MITRE ATT&CK`

---

## 💎 Bug Bounty & Vulnerability Highlights
> Honest, verifiable work — focused on impact.

- 🥇 **Verified HackerOne reports:** **PLACEHOLDER_BOUNTY_COUNT** — e.g. `1` (Valid CSRF)  
  - Report (example): **CSRF → session action hijack** — PoC & remediation delivered.  
  - Verification: `PLACEHOLDER_HACKERONE_PROFILE_OR_REPORT_URL`
- 🔍 **Common impact:** broken state changes, session weaknesses, missing CSRF tokens, insecure headers.  
- 📝 **Deliverables I provide:** Executive summary, technical PoC, remediation checklist, prioritized risk matrix.

> _To display a verified badge: replace `PLACEHOLDER_HACKERONE_PROFILE_OR_REPORT_URL` with your actual HackerOne profile/report link._

---

## 🧩 Featured Projects (concise + demonstrative)

### 🔧 Offensive Security Toolkit — `PenTest-toolkit`
`git clone https://github.com/MazenTurky7/PenTest-toolkit && ./pentool --help`

**What it does:** modular recon, subdomain enumeration, S3 checks, API fuzzing, Burp templates.  
**Quick demo (recon + API fuzz):**
```bash
# Recon + simple API fuzz example
./pentool enum --target example.com --subs --s3check --output findings.json
python3 tools/fuzz_api.py --target https://api.example.com --wordlist wordlists/common-params.txt
````

### 🐞 HackerOne — CSRF (Validated)

* Valid CSRF discovered on production; vendor acknowledged & fixed. PoC and remediation delivered (CSRF tokens, SameSite flags, header hardening).

---

## 📌 Sample PoC (safe, non-exploitative)

> Minimal example demonstrating a CSRF POST PoC concept (non-destructive, educational):

```html
<!-- CSRF PoC — demo only, DO NOT run against targets without permission -->
<html>
  <body onload="document.forms[0].submit()">
    <form action="https://victim.example.com/profile/change-email" method="POST">
      <input type="hidden" name="email" value="attacker@example.com"/>
    </form>
  </body>
</html>
```

---

## 📈 Visual Widgets & Proof (replace placeholders)

<p align="center">
  <!-- Replace with real badge counts or remove if you prefer -->
  <img src="https://img.shields.io/badge/Verified%20Reports-PLACEHOLDER_BOUNTY_COUNT-orange?style=flat-square" alt="bounty-count" />
  <img src="https://img.shields.io/badge/Labs-50%2B-blue?style=flat-square" alt="labs" />
  <img src="https://img.shields.io/badge/Experience-ITI%20Scholarship-green?style=flat-square" alt="iti" />
</p>

---

## 🧠 What I bring to a pentest

* **Manual-first approach**: scanners are second—manual logic & chained requests find the interesting bugs.
* **Real-world chain building**: session pivot → SSRF → internal API → RCE (validated in lab).
* **Readable deliverables**: concise exec summary + technical appendix + remediation steps.

---

## 🎯 Current Focus

* Advanced session pivot chains and stateful exploitation (Auth bypass + CSRF/SSRF combos).
* Mobile runtime tampering & API fuzzing (Frida + MobSF).
* Automating PoC capture for repeatable reporting.

---

## ⚡ Personality / Fun

* Motto: **Hack ethically. Ship fixes. Repeat.**
* Background music: Mounir & Adele
* Coffee: Turkish espresso — strong

---

## 📬 Collaborate

**Email:** [turkymazen13@gmail.com](mailto:turkymazen13@gmail.com)
**Phone:** +20 1063444558
**LinkedIn:** [https://www.linkedin.com/in/mazen-abdellatief](https://www.linkedin.com/in/mazen-abdellatief)


---

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=16&color=00ff99&center=true&lines=If+you+like+my+work,+star+my+repos+⭐;+Want+to+hire+or+collaborate,+reach+out+via+email+📧" />
</p>

<!-- End -->

```
