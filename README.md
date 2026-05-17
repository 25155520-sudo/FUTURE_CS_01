Vulnerability Assessment Report

The security assessment was conducted on a locally hosted instance of OWASP Juice Shop.
Target URL
http://localhost:3000
OWASP Juice Shop is an intentionally vulnerable web application designed for cybersecurity learning and security testing practice,run and host the website locally using docker desktop

Scope of Assessment
The assessment focused only on passive and ethical security analysis.

In Scope:
Public-facing web application analysis
Passive scanning and crawling
Security header inspection
Cookie configuration analysis
Basic port and service enumeration
Information disclosure checks
Out of Scope:
Exploitation attempts
Login bypass
Brute-force attacks
Denial-of-Service (DoS)
Malware execution
Any destructive or harmful activity

All testing was performed in a safe local environment for educational purposes only.

Tools Used
1. Nmap
Used for:
Open port detection
Service exposure analysis
Basic network reconnaissance
Key Finding
Port 3000 exposed for web application access

2. OWASP ZAP
Used for:
Passive vulnerability scanning
Website crawling and endpoint discovery
Detection of exposed files and information disclosure issues
Key Findings
Sensitive files exposed
Backup files publicly accessible
Information disclosure through file structure

3. Firefox Developer Edition
Used for:
Inspecting HTTP response headers
Analyzing cookie security settings
Reviewing browser-side security protections
Key Findings
Missing Content Security Policy (CSP)
Missing HSTS
Insecure cookie configuration
Partial implementation of security headers

Risk Classification
The identified vulnerabilities were categorized as:
High Risk
Medium Risk
Low Risk
based on their potential business and security impact.

Ethics Statement
This project followed ethical cybersecurity practices:
Passive testing only
No exploitation performed
No harmful actions executed
Educational and research purposes only
