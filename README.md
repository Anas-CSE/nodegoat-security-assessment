# NodeGoat Security Assessment

A 3-week cybersecurity internship project focused on security assessment and hardening of the OWASP NodeGoat application.

## Project Overview
- **Week 1** — Vulnerability Assessment
- **Week 2** — Security Implementation
- **Week 3** — Penetration Testing & Logging

## Setup Instructions
```bash
sudo docker-compose up -d
```
Open browser: http://localhost:4000

## Week 1 — Vulnerabilities Found
- XSS — Profile, Contributions, Allocations, Research pages
- Improper Input Validation — All pages
- OWASP ZAP Scan — 21 alerts found

## Week 2 — Security Fixes Applied
- Input Sanitization — validator.escape()
- Removed eval() — replaced with parseInt()
- Password Hashing — bcrypt
- JWT Authentication — jsonwebtoken
- HTTP Headers — Helmet.js

## Week 3 — Advanced Security
- Nmap penetration testing — only port 4000 open
- Winston logging — Console + File transport
- Security checklist created

## Author
Anas-CSE — github.com/Anas-CSE
