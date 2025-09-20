📌 Overview

This task focused on identifying security weaknesses in a web application, mapped to the OWASP Top 10 (2021).
The main vulnerabilities tested were SQL Injection, Replay and Impersonation, User Enumeration, Insecure Token Design, Insecure Direct Object Reference (IDOR), and Business Logic Exploitation.

🛠️ Tools Used

Kali Linux 🐉

Burp Suite 🕷️

OWASP Juice Shop (test application) 🍹

🔎 Vulnerabilities Found

SQL Injection – Malicious queries can be injected to extract or manipulate database data.

Replay and Impersonation – Captured requests or tokens can be reused to impersonate valid users.

User Enumeration – Error messages or responses reveal if a user account exists.

Insecure Token Design – Weakly generated or predictable tokens allow session hijacking.

Business Logic Exploitation (Payback Functionality) – Flawed workflows let attackers abuse intended functionality for gain.

Insecure Direct Object Reference (IDOR / Broken Access Control) – Attackers can access or modify resources by manipulating IDs in requests.

📑 Summary

The assessment revealed multiple critical vulnerabilities that exist due to weak input validation, broken access controls, insecure session handling, and flawed business logic.
If exploited, these issues could lead to data leakage, account compromise, or financial fraud.
Implementing the recommended mitigations and aligning with OWASP best practices will significantly improve the application’s security.
