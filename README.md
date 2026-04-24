# web-application-security-assessment

This repository contains a security assessment report conducted as part of an internship project on a real-world web application.

---

## Project Overview

The objective of this assessment was to evaluate the security posture of a web-based application prior to production deployment.

The testing focused on identifying common vulnerabilities in both application logic and system configuration.

---

## Scope of Testing

* File upload validation
* Authentication mechanisms
* DNS configuration
* Infrastructure exposure

---

## Tools Used

* Burp Suite (Community Edition)
* Nessus Vulnerability Scanner
* Kali Linux
* OpenSSL CLI
* Google Chrome DevTools – Network traffic inspection 

---

## Key Findings

The assessment identified several critical vulnerabilities, including:

**Unrestricted File Upload (Critical)**
  Allows malicious files to be uploaded and potentially executed on the server.

**DNS Misconfiguration (Medium)**
  Exposes the system to cache poisoning and denial-of-service risks.

**No Rate Limiting (Medium)**
  Enables brute-force attacks on authentication endpoints.

---

## Full Report

You can view the complete security assessment here:
 [Download Report](./report.pdf)

---

## Disclaimer

All sensitive information has been removed or anonymized to maintain confidentiality.
This report is intended for portfolio and educational purposes only.

---

## Author

Security enthusiast with experience in web application testing using tools like Burp Suite and Nessus.

