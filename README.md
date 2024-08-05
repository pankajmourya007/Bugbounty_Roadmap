# Bug Bounty Roadmap

Welcome to the Bug Bounty Roadmap repository! This repository contains a comprehensive guide for bug bounty hunters, organized into various categories with detailed `.md` files.

## Table of Contents

- [Reconnaissance](#reconnaissance)
  - [Passive Recon](#passive-recon)
    - [Google Dorking](Reconnaissance/Passive_Recon/Google_Dorking.md)
    - [WHOIS Lookups](Reconnaissance/Passive_Recon/WHOIS_Lookups.md)
    - [Subdomain Enumeration](Reconnaissance/Passive_Recon/Subdomain_Enumeration.md)
    - [OSINT Tools](Reconnaissance/Passive_Recon/OSINT_Tools.md)
  - [Active Recon](#active-recon)
    - [Port Scanning](Reconnaissance/Active_Recon/Port_Scanning.md)
    - [Service Enumeration](Reconnaissance/Active_Recon/Service_Enumeration.md)
    - [Banner Grabbing](Reconnaissance/Active_Recon/Banner_Grabbing.md)
    - [Directory Bruteforcing](Reconnaissance/Active_Recon/Directory_Bruteforcing.md)
- [Web Application Testing](#web-application-testing)
  - [OWASP Top 10](#owasp-top-10)
    - [Injection](Web_Application_Testing/OWASP_Top_10/Injection.md)
    - [Broken Authentication](Web_Application_Testing/OWASP_Top_10/Broken_Authentication.md)
    - [Sensitive Data Exposure](Web_Application_Testing/OWASP_Top_10/Sensitive_Data_Exposure.md)
    - [XML External Entities](Web_Application_Testing/OWASP_Top_10/XML_External_Entities.md)
    - [Broken Access Control](Web_Application_Testing/OWASP_Top_10/Broken_Access_Control.md)
    - [Cross-Site Scripting](Web_Application_Testing/OWASP_Top_10/Cross_Site_Scripting.md)
    - [Security Misconfiguration](Web_Application_Testing/OWASP_Top_10/Security_Misconfiguration.md)
    - [Insecure Deserialization](Web_Application_Testing/OWASP_Top_10/Insecure_Deserialization.md)
    - [Using Components with Known Vulnerabilities](Web_Application_Testing/OWASP_Top_10/Using_Components_with_Known_Vulnerabilities.md)
    - [Insufficient Logging & Monitoring](Web_Application_Testing/OWASP_Top_10/Insufficient_Logging_and_Monitoring.md)
  - [SQL Injection](#sql-injection)
    - [Overview](Web_Application_Testing/SQL_Injection/Overview.md)
    - [Union Based](Web_Application_Testing/SQL_Injection/Union_Based.md)
    - [Error Based](Web_Application_Testing/SQL_Injection/Error_Based.md)
    - [Blind SQLi](Web_Application_Testing/SQL_Injection/Blind_SQLi.md)
  - [Cross-Site Scripting](#cross-site-scripting)
    - [Overview](Web_Application_Testing/Cross_Site_Scripting/Overview.md)
    - [Stored XSS](Web_Application_Testing/Cross_Site_Scripting/Stored_XSS.md)
    - [Reflected XSS](Web_Application_Testing/Cross_Site_Scripting/Reflected_XSS.md)
    - [DOM-Based XSS](Web_Application_Testing/Cross_Site_Scripting/DOM_Based_XSS.md)
  - [Remote Code Execution](Web_Application_Testing/Remote_Code_Execution.md)
  - [File Inclusion](#file-inclusion)
    - [LFI](Web_Application_Testing/File_Inclusion/LFI.md)
    - [RFI](Web_Application_Testing/File_Inclusion/RFI.md)
  - [Business Logic Flaws](Web_Application_Testing/Business_Logic_Flaws.md)
  - [IDOR](Web_Application_Testing/IDOR.md)
  - [API Security](Web_Application_Testing/API_Security.md)
- [Mobile Application Testing](#mobile-application-testing)
  - [Android Testing](#android-testing)
    - [Static Analysis](Mobile_Application_Testing/Android_Testing/Static_Analysis.md)
    - [Dynamic Analysis](Mobile_Application_Testing/Android_Testing/Dynamic_Analysis.md)
    - [Reverse Engineering](Mobile_Application_Testing/Android_Testing/Reverse_Engineering.md)
    - [Common Vulnerabilities](Mobile_Application_Testing/Android_Testing/Common_Vulnerabilities.md)
  - [iOS Testing](#ios-testing)
    - [Static Analysis](Mobile_Application_Testing/iOS_Testing/Static_Analysis.md)
    - [Dynamic Analysis](Mobile_Application_Testing/iOS_Testing/Dynamic_Analysis.md)
    - [Reverse Engineering](Mobile_Application_Testing/iOS_Testing/Reverse_Engineering.md)
    - [Common Vulnerabilities](Mobile_Application_Testing/iOS_Testing/Common_Vulnerabilities.md)
- [Network Security Testing](#network-security-testing)
  - [Network Scanning](Network_Security_Testing/Network_Scanning.md)
  - [Vulnerability Scanning](Network_Security_Testing/Vulnerability_Scanning.md)
  - [Exploitation](Network_Security_Testing/Exploitation.md)
  - [Post Exploitation](Network_Security_Testing/Post_Exploitation.md)
- [Cloud Security Testing](#cloud-security-testing)
  - [AWS Security](Cloud_Security_Testing/AWS_Security.md)
  - [Azure Security](Cloud_Security_Testing/Azure_Security.md)
  - [GCP Security](Cloud_Security_Testing/GCP_Security.md)
  - [Common Vulnerabilities](Cloud_Security_Testing/Common_Vulnerabilities.md)
- [Tools and Techniques](#tools-and-techniques)
  - [Burp Suite](Tools_and_Techniques/Burp_Suite/Configuration.md)
  - [Nmap](Tools_and_Techniques/Nmap.md)
  - [Metasploit](Tools_and_Techniques/Metasploit.md)
  - [Nikto](Tools_and_Techniques/Nikto.md)
  - [Gobuster](Tools_and_Techniques/Gobuster.md)
  - [Sublist3r](Tools_and_Techniques/Sublist3r.md)
  - [ReconNG](Tools_and_Techniques/ReconNG.md)
  - [Other Tools](Tools_and_Techniques/Other_Tools.md)
- [Report Writing](#report-writing)
  - [Report Template](Report_Writing/Report_Template.md)
  - [Impact Assessment](Report_Writing/Impact_Assessment.md)
  - [Proof of Concept](Report_Writing/Proof_of_Concept.md)
  - [Remediation Advice](Report_Writing/Remediation_Advice.md)
  - [Sample Reports](Report_Writing/Sample_Reports.md)
- [Learning Resources](#learning-resources)
  - [Books](Learning_Resources/Books.md)
  - [Blogs](Learning_Resources/Blogs.md)
  - [Courses](Learning_Resources/Courses.md)
  - [Conferences](Learning_Resources/Conferences.md)
  - [CTF Platforms](Learning_Resources/CTF_Platforms.md)

## Contributing

Contributions are welcome! Please see the [CONTRIBUTING.md](CONTRIBUTING.md) file for more information.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
