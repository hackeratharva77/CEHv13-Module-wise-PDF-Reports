# 🌐 Web Application Hacking

## 📌 Introduction
**Web Application Hacking** involves exploiting vulnerabilities in web applications to gain unauthorized access, manipulate data, or disrupt services.  
Since most organizations rely heavily on web-based applications, attackers often target them to steal sensitive information, inject malicious scripts, or bypass authentication.

---

## 🎯 Objectives
- Understand the structure and components of web applications.  
- Identify vulnerabilities such as **XSS, SQLi, CSRF, File Upload flaws, Broken Authentication**.  
- Learn exploitation techniques for gaining unauthorized access.  
- Assess the impact of attacks and recommend countermeasures.  
- Strengthen web applications against cyber threats.  

---

## 📂 Methodology
1. **Information Gathering** – Identify web technologies, subdomains, frameworks.  
2. **Mapping** – Analyze input fields, parameters, and hidden endpoints.  
3. **Vulnerability Detection** – Check for misconfigurations, injections, and insecure code.  
4. **Exploitation** – Execute payloads to gain access or exfiltrate data.  
5. **Post-Exploitation** – Escalate privileges, maintain access, or pivot.  
6. **Reporting** – Document vulnerabilities and mitigation strategies.  

---

## 🧰 Common Tools
- **Burp Suite** – Proxy interception and vulnerability analysis.  
- **OWASP ZAP** – Web application scanner.  
- **Nikto** – Web server scanning.  
- **Acunetix** – Automated web vulnerability scanning.  
- **Nmap NSE** – Script-based scanning for web flaws.  
- **SQLMap** – Automated SQL injection exploitation.  
- **Dirbuster/Gobuster** – Directory and file brute-forcing.  

---


## 🛡️ Defensive Countermeasures

Input validation and sanitization.

Use prepared statements (to prevent SQLi).

Implement Content Security Policy (CSP).

Enforce secure authentication and session management.

Keep web servers, frameworks, and plugins up to date.

Perform regular penetration testing.

---

## ⚠️ Disclaimer

This repository is for educational purposes only.
Do not attempt these attacks on unauthorized systems. Always work in a controlled lab environment with permission.

---

###  📄 README for **SQL Injection**  

---

# 💉 SQL Injection (SQLi)
---
## 📌 Introduction
**SQL Injection** is one of the most dangerous web vulnerabilities where attackers inject malicious SQL queries into input fields.  
It allows attackers to manipulate backend databases, extract sensitive data, bypass authentication, and even gain full system control.

---

## 🎯 Objectives
- Understand the working of SQL injection attacks.  
- Detect input fields and parameters vulnerable to SQLi.  
- Exploit SQL injection to extract database information.  
- Learn automated exploitation with tools like SQLMap.  
- Apply remediation strategies to secure applications.  

---

## 📂 Types of SQL Injection
1. **In-Band SQLi**
   - Classic SQL injection using same communication channel.  
   - Examples: Union-based, Error-based.  

2. **Blind SQLi**
   - Database doesn’t show errors; attackers infer results.  
   - Examples: Boolean-based, Time-based.  

3. **Out-of-Band SQLi**
   - Data retrieved using different channel (DNS, HTTP requests).  

---

## 🧰 Common Tools
- **SQLMap** – Automated SQLi exploitation.  
- **Burp Suite** – Manual SQLi payload injection.  
- **Havij** – Automated SQL injection tool.  
- **NoSQLMap** – Exploitation of NoSQL injection.  
- **Nmap NSE Scripts** – SQL injection checks.  


---

## 🛡️ Defensive Countermeasures

Use prepared statements (parameterized queries).

Implement stored procedures securely.

Enforce least privilege for database accounts.

Use Web Application Firewalls (WAFs).

Regular security testing with DAST & SAST tools.

---

## ⚠️ Disclaimer

This repository is created for educational purposes only.
Perform SQLi testing only on authorized systems within scope. Unauthorized attacks are illegal.
