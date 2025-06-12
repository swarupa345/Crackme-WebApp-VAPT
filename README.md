# Crackme-WebApp-VAPT
Vulnerability Assessment of Crackme WebApp – SQLi &amp; XSS findings
# 🔐 Crackme WebApp – Web Application Vulnerability Assessment

**Project Duration**: Mar 2025 – May 2025  
**Target URL**: [http://3.20.15.221:1001/oszmegjaij/app](http://3.20.15.221:1001/oszmegjaij/app)

## ✅ Summary
Performed a complete Web Application Penetration Test (WAPT) of Crackme WebApp hosted online.

## 🔍 Key Vulnerabilities Identified
- **SQL Injection**: Bypassed login authentication via payload `' OR '1'='1'--`
- **Reflected XSS**: Detected in input parameters; allowed JavaScript execution with payload `<script>alert(1)</script>`

## 🛠️ Tools Used
- **Burp Suite**, **curl**, **WhatWeb**, **httpx**

## 📄 Report
- Detailed PDF report includes: PoC, impact analysis, screenshots, OWASP Top 10 mapping, and remediation

📎 [View Full Report](./Crackme-VAPT-Report.pdf)

## 📸 Screenshots
*(Optional)* Included for PoC illustration



