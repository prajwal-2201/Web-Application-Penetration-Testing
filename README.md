# 🔐 Web Application Penetration Testing  
## (OWASP Top 10 Based)

> **An end-to-end web application penetration testing project conducted in a controlled lab environment, focusing on identifying and exploiting real-world OWASP Top 10 vulnerabilities.**

---

## 👤 Author
**Prajwal V**  
**Branch:** Computer Science and Engineering (CSE)  
**College:** PES University  

---

## 📌 Project Overview

This project demonstrates a **practical web application penetration test** performed on a deliberately vulnerable application (**DVWA**) using **OWASP Top 10 methodology**.

The goal of this project is to:
- Understand how real web attacks work  
- Identify common security flaws in web applications  
- Safely exploit vulnerabilities to prove impact  
- Document findings in a **professional penetration testing report**

This project also **builds upon network reconnaissance skills** from a previous project, where exposed services were identified before testing the application layer.

---

## 🧠 Methodology Used

- OWASP Top 10 Web Application Security Risks  
- Manual testing approach  
- Controlled local lab environment (no real websites tested)  

> ⚠️ **Ethical Note:**  
> All testing was conducted strictly for educational purposes on a deliberately vulnerable application.

---

## 🧪 Test Environment

| Component | Details |
|--------|--------|
| OS | Kali Linux (Virtual Machine) |
| Web Server | Apache |
| Database | MariaDB (MySQL) |
| Application | DVWA |
| Security Level | LOW |

---

## 🛠️ Tools & Technologies

- Kali Linux  
- Damn Vulnerable Web Application (DVWA)  
- Apache Web Server  
- MariaDB  
- PHP  
- Firefox Browser  

---

## 🚨 Vulnerabilities Identified

The assessment focused on **high-impact and commonly exploited OWASP Top 10 vulnerabilities**:

### ✅ 1. SQL Injection
- Database queries manipulated using crafted input  
- Resulted in unauthorized access to multiple user records  

### ✅ 2. Reflected Cross-Site Scripting (XSS)
- Injected JavaScript executed in the victim’s browser  
- Demonstrated client-side code execution  

### ✅ 3. Broken Authentication
- Weak/default credentials allowed unauthorized login  
- No rate limiting or lockout mechanisms  

### ✅ 4. Security Misconfiguration
- PHP configuration details publicly exposed  
- Enabled system fingerprinting and information disclosure  

### ✅ 5. Vulnerable & Outdated Components
- Web server version disclosed (`Apache/2.4.66`)  
- Enables attackers to search for known CVEs  

### ✅ 6. Cross-Site Request Forgery (CSRF)
- Sensitive actions performed without CSRF token validation  
- Allowed unauthorized password changes  

---

## 📊 Risk Summary

| Severity | Vulnerabilities |
|-------|----------------|
| **High** | SQL Injection, Broken Authentication |
| **Medium** | XSS, Security Misconfiguration |
| **Low** | Version Disclosure |

---

## 📄 Deliverable

📌 **Full Penetration Testing Report (PDF)**  
- Detailed findings  
- Proof of concept  
- Impact analysis  
- Remediation recommendations  

> The report follows **professional security reporting standards**, similar to real-world penetration testing deliverables.

---

## 🔒 Disclaimer

> This project was conducted strictly for **educational and learning purposes** in a **controlled local environment** using a deliberately vulnerable application.  
> No unauthorized systems or real-world applications were tested.

---

## 🚀 Future Enhancements

- Testing higher DVWA security levels (Medium / High)  
- Mapping findings to CVEs  
- Integrating Burp Suite for advanced request interception  
- Automating vulnerability reporting  

---

## 🏁 Why This Project Matters

This project demonstrates:
- Practical understanding of **web application attack surfaces**
- Hands-on experience with **OWASP Top 10**
- Ethical penetration testing mindset
- Ability to document and communicate security findings clearly  

---

### ⭐ If you’re reviewing this project
Feel free to explore the **PDF report** for complete technical details.
