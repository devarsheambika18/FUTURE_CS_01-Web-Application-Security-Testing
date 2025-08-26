# FUTURE_CS_01-Web-Application-Security-Testing
Web application security testing report and PoC screenshots (SQL Injection, XSS, Authentication Flaws).
# Web Application Security Testing

## Overview
This repository contains the deliverables of a web application security assessment completed during my **Cybersecurity Internship at Future Intern**.  
The assessment focused on identifying and mitigating common web application vulnerabilities.

## Vulnerabilities Tested
1. **SQL Injection (SQLi)**  
   - Payload: `' OR 1=1--`  
   - Impact: Logged in without valid credentials; hidden data was exposed.

2. **Cross-Site Scripting (XSS)**  
   - Payload: `<script>alert('XSS')</script>`  
   - Impact: Script executed in victim's browser, confirming vulnerability.

3. **Authentication Flaw**  
   - Observation: Application revealed different responses for valid/invalid usernames, allowing enumeration.

## Tools Used
- OWASP ZAP  
- Burp Suite  
- SQLMap  

## Deliverables
- **Report:** [Web_Application_Security_Testing_Report.docx](Web_Application_Security_Testing_Report.docx)  
- **Proof-of-Concept Screenshots:** See `/screenshots` folder.  

## Key Takeaways
- Hands-on experience in identifying and documenting vulnerabilities.
- Understanding of secure coding practices and mitigation strategies.

---
