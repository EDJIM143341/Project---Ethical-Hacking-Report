# Final Project - Ethical Hacking Report
_**Client :**_ **Lazada Group**

_**Date :**_ **May, 11 2024**

_**Prepared By :**_ **Buquid, Ed Jim C. and Bondoy, Monica G.**

_**Executive Summary :**_ This report presents the technical findings of the ethical hacking assessment
conducted for Lazada. The assessment aimed to identify vulnerabilities within the
organization's network infrastructure, applications, and systems. Through various testing methodologies,
including penetration testing and vulnerability scanning, critical and high-risk issues were discovered.
This report provides detailed descriptions of these findings, along with actionable recommendations for
remediation.

_**Vulnerability Summary :**_
1.  #### Network Infrastructure ####

* **Crital :** Remote Code Execution vulnerability (CVE-2024-1234) in the Apache Struts framework (version 2.3.34) running on Lazada’s main server, potentially allowing an attacker to execute arbitrary code remotely.
* **High :**  Misconfigured firewall rules on Lazada’s payment processing server permitting unrestricted access from external IP ranges to sensitive internal services such as SSH and RDP.

2.  #### Web Applications : ####
* **Critical :** SQL Injection vulnerability in the login form of Lazada, potentially enabling an attacker to extract sensitive data from the database.
* **High :** Cross-Site Scripting (XSS) vulnerability in Lazada, allowing attackers to execute malicious scripts in users’ browsers.

* **Critical :**  Insecure Direct Object References (IDOR) vulnerability in the user profile section of Lazada, potentially allowing an attacker to manipulate references to access unauthorized data.
* **High :** Cross-Site Request Forgery (CSRF) vulnerability in Lazada, potentially enabling an attacker to trick a victim into performing actions they did not intend to.



