# OWASP-Top-10-by-Ayush-Gaur
This a descriptive (Theoretical ) guide for OWASP top 10 techniques  

# **OWASP Top 10 Report**  
**By Ayush Gaur**  

## **Introduction**  
The OWASP Top 10 is a guide that highlights critical vulnerabilities in web applications. It provides tutorials to help understand, exploit, and secure web applications against potential threats.  

---

## **Top 10 Vulnerabilities**  

### **1. Injection**  
- **Description**: Attackers exploit untrusted inputs to inject commands or queries into a system.  
- **Examples**:  
  - **SQL Injection**: Manipulates SQL queries to access, modify, or delete database data.  
  - **Command Injection**: Executes system commands via untrusted inputs.  
- **Prevention**:  
  - Sanitize inputs and use parameterized queries.  

---

### **2. Broken Authentication**  
- **Description**: Exploits weak authentication mechanisms to gain unauthorized access.  
- **Prevention**:  
  - Enforce strong passwords.  
  - Implement MFA (Multi-Factor Authentication).  
  - Use automated lockout after repeated failed attempts.  

---

### **3. Sensitive Data Exposure**  
- **Description**: Sensitive information is leaked through weak encryption or insecure data transfer methods.  
- **Prevention**:  
  - Use strong encryption algorithms.  
  - Enforce HTTPS for secure data transmission.  

---

### **4. XML External Entities (XXE)**  
- **Description**: Malicious XML data exploits vulnerable XML parsers, causing attacks like DoS or SSRF.  
- **Prevention**:  
  - Use secure XML parsers and disable external entity processing.  

---

### **5. Broken Access Control**  
- **Description**: Users access unauthorized functionality or data.  
- **Prevention**:  
  - Implement Role-Based Access Control (RBAC).  
  - Enforce access checks on the server side.  

---

### **6. Security Misconfiguration**  
- **Description**: Poorly configured security settings expose systems to attacks.  
- **Examples**:  
  - Weak passwords, open S3 buckets, unnecessary features enabled.  
- **Prevention**:  
  - Regularly review and secure configurations.  

---

### **7. Cross-Site Scripting (XSS)**  
- **Description**: Malicious scripts injected into web applications execute on users’ browsers.  
- **Types**:  
  - Stored, Reflected, DOM-Based XSS.  
- **Prevention**:  
  - Sanitize and validate inputs/outputs.  
  - Use trusted libraries and APIs.  

---

### **8. Insecure Deserialization**  
- **Description**: Exploits deserialization of untrusted data, enabling DoS or Remote Code Execution.  
- **Prevention**:  
  - Avoid deserializing untrusted data.  
  - Validate inputs and outputs.  

---

### **9. Components with Known Vulnerabilities**  
- **Description**: Outdated or vulnerable components are exploited by attackers.  
- **Prevention**:  
  - Regularly update dependencies and components.  
  - Monitor for known vulnerabilities (e.g., using exploit-db).  

---

### **10. Insufficient Logging and Monitoring**  
- **Description**: Lack of proper logging makes detecting and tracing attacks difficult.  
- **Prevention**:  
  - Log critical events (e.g., HTTP status codes, timestamps, IPs).  
  - Implement monitoring systems to detect anomalies.  

---

## **Conclusion**  
The OWASP Top 10 outlines critical security risks to help developers build secure web applications. While it highlights the most common vulnerabilities, OWASP encompasses much more and is an invaluable resource for staying ahead of threats.

---

## **References**  
1)	 OWASP  Top 10 2020 (tryhackme.com)
Link: https://tryhackme.com/r/room/owasptop10

2)	OWASP Testing Guide 4.0
Link: https://owasp.org/www-project-web-security-testing-guide/

3)	OWASP Web Security Testing Guide (WSTG)
Link: https://owasp.org/www-project-web-security-testing-guide/

4)OWASP Cheat Sheet Series
Link: https://cheatsheetseries.owasp.org/
  
