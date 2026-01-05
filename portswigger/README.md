# PortSwigger Web Security Academy – Progress Tracker

**Owner:** Marino  
**Purpose:** Demonstrate hands-on web application security knowledge to support  
CMMC / NIST 800-171 auditing and technical control validation.

This directory contains structured writeups for completed PortSwigger labs.
Each lab includes:
- Vulnerability summary
- Exploitation overview
- Evidence
- Mitigation guidance (auditor-relevant)

---

## 📊 Overall Progress

| Category | Completed | Total | Status |
|--------|----------|-------|--------|
| SQL Injection | 8 | TBD | ⬜ In Progress |
| Authentication | 0 | 12 | ⬜ In Progress |
| Access Control | 0 | TBD | ⬜ In Progress |
| XSS | 0 | TBD | ⬜ In Progress |
| Other | 0 | TBD | ⬜ In Progress |

_Last updated:_ YYYY-MM-DD

---

## 🗂 Lab Index

### SQL Injection
- [ ] Lab 01 – Basic SQL Injection  
- [ ] Lab 02 – Blind SQL Injection  
- [ ] Lab 03 – SQL Injection UNION attack  

📁 Folder: `portswigger/sql-injection/`

---

### Authentication
- [ ] Lab 01 – Username enumeration  
- [ ] Lab 02 – Password reset flaw  

📁 Folder: `portswigger/authentication/`

---

### Access Control
- [ ] Lab 01 – Insecure Direct Object Reference (IDOR)  
- [ ] Lab 02 – Method-based access control bypass  

📁 Folder: `portswigger/access-control/`

---

### Cross-Site Scripting (XSS)
- [ ] Lab 01 – Reflected XSS  
- [ ] Lab 02 – Stored XSS  

📁 Folder: `portswigger/xss/`

---

## 🧠 Auditor-Relevant Takeaways

> This section highlights patterns and control-relevant observations
> discovered while completing labs.

- Common access control failures map directly to **NIST 800-171 AC controls**
- Authentication weaknesses frequently indicate:
  - poor MFA enforcement
  - lack of account lockout policies
- Many vulnerabilities persist despite “policy compliance”

(Updated periodically as patterns emerge.)

---

## 📝 Notes on Methodology

- Labs are completed manually (no auto-solvers)
- Focus is on **root cause analysis**, not exploit novelty
- Writeups emphasize:
  - what failed
  - why it failed
  - how an auditor would verify remediation

---

## 🔄 Update Log

| Date | Summary |
|----|--------|
| YYYY-MM-DD | Repository initialized |
| YYYY-MM-DD | Completed first SQL Injection labs |
