# 🐛 Bug Bounty Writeups

A collection of real-world security findings discovered during bug bounty hunting and independent research.

This repository focuses on **practical vulnerabilities with real impact**, not low-signal or automated scan results.

---

## 📌 What You’ll Find Here

* Clear, structured vulnerability reports
* Real attack scenarios and impact analysis
* Reproducible steps and technical breakdowns
* Focus on authentication, access control, and logic flaws

---

## 🗂️ Writeups

### 🔐 Session Cookie Persistence (Authentication Bypass)

* **Severity:** High
* **Category:** Broken Authentication
* **Impact:** Account Takeover

➡️ [View Writeup](./writeups/session-cookie-persistence.md)

---

### ⚙️ Server Misconfiguration

* **Severity:** Medium
* **Category:** Information Disclosure
* **Impact:** Reconnaissance / Attack Surface Exposure

➡️ [View Writeup](./writeups/server-misconfiguration.md)

---

## 🧠 Methodology

My testing approach prioritizes **depth over volume**:

* Manual testing over blind automation
* Reconnaissance-driven analysis
* Authentication & session handling flaws
* Business logic vulnerabilities
* Chaining low-impact issues into real exploits

---

## 🛠️ Tools

* Burp Suite
* Nmap
* Nuclei
* ffuf
* Browser DevTools

---

## 🎯 Focus Areas

* Broken authentication
* Session management flaws
* IDOR / access control issues
* Business logic vulnerabilities
* Misconfigurations (only when impactful)

---

## ⚠️ Responsible Disclosure

* All findings are responsibly disclosed
* Sensitive details are redacted
* No real user data is exposed
* Content is for educational purposes only

---

## 👨‍💻 About Me

**Yoonus K Y**
Bug bounty researcher | Cybersecurity enthusiast

* 🌐 Portfolio: https://yoonas18.github.io/portfolio
* 💼 LinkedIn: https://linkedin.com/in/yoonusky
* 🐛 Bugcrowd: https://bugcrowd.com/Yoonas18
* 💻 GitHub: https://github.com/Yoonas18

---

## ⚡ Final Note

Most bug bounty reports fail because they lack real impact.

This repository focuses on vulnerabilities that:

* Break real security assumptions
* Can be exploited in practice
* Demonstrate meaningful risk

---
