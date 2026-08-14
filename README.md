# FUTURE_CS_01 — Vulnerability Assessment Report for a Live Website

## Task Overview
Task 1 of the Future Interns Cyber Security Internship. This project involves
conducting a vulnerability assessment on a live website, identifying security
risks, classifying them by severity, and providing clear remediation guidance.

## Website Tested
demo.testfire.net (Altoro Mutual) — a legally scannable demo banking
application published by HCL Technologies for security testing practice.

## Scope & Ethics
This assessment was strictly read-only and passive:
- Public-facing pages only
- Passive scanning (Nmap service detection, OWASP ZAP Passive Scan)
- Header and configuration analysis
- No login bypass, exploitation, brute force, or DoS activity was performed

## Objective
- Identify common web vulnerabilities
- Classify risk as Low / Medium / High
- Explain issues in simple, business-friendly language
- Provide clear remediation steps

## Tools Used
- Nmap – port & service scanning
- OWASP ZAP (Passive Scan) – vulnerability detection
- Browser DevTools – manual inspection
- Canva – report design

## Repository Structure

FUTURE_CS_01/
- README.md
- scan-results/
  * nmap service detection.txt
  * nmap targeted scripts.txt
  * zap scan report.html
- report/
  * Vulnerability Assessment Report.pdf
- screenshots/
  * 1.1 nmap scan.png
  * 1.2 nmap scan.png
  * 2 zap alerts overview.png
  * 3 anti-CSRF findings.png
  * 4 content security policy findings.png
  * 5 clickjacking finding.png
  * 6 information disclousre suspicious comment.png


## Findings Summary
11 total findings — 4 Medium, 4 Low, 3 Informational. Full details, risk
ratings, plain-language explanations, and fixes are in the PDF report.

## Deliverable
A professionally designed Vulnerability Assessment Report (PDF) covering
findings, risk ratings, and fixes.

## Author
Yuvraj Singh — Certified Ethical Hacker (CEH v13)
LinkedIn: https://linkedin.com/in/yuvraj-singh-997a45372
