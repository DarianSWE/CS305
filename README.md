Overview
This project focuses on identifying and mitigating security vulnerabilities in Artemis Financial’s internal software. The assessment aimed to enhance security while maintaining functionality, ensuring compliance with industry standards.

Client & Security Concerns
Client: Artemis Financial – a wealth management firm handling sensitive financial transactions.
Issue: Potential security vulnerabilities in their software, including risks of unauthorized access, data breaches, and weak authentication.

Security Assessment & Mitigation
Conducted static & dynamic security testing to identify vulnerabilities (SQL injection, XSS, weak authentication).
Implemented multi-factor authentication (MFA) and data encryption to strengthen security layers.
Applied secure coding practices, including input validation and principle of least privilege (PoLP).
Challenges & Solutions
Challenge: Identifying vulnerabilities in third-party dependencies.
Solution: Used OWASP Dependency-Check and automated security scans to flag and update outdated libraries.
Tools & Best Practices
Penetration Testing: Burp Suite, OWASP ZAP
Code Analysis: SonarQube, GitHub Dependabot
Secure Coding: Input sanitization, secure password hashing (bcrypt), encrypted database storage
Validation & Testing
Performed regression testing to ensure refactored code maintained functionality.
Re-ran security scans post-refactoring to check for new vulnerabilities.
Conducted peer code reviews to validate security improvements.
Key Takeaways for Future Work
This project highlights the importance of proactive security assessments and secure coding in financial software. The methodology and tools used here will be valuable in future security-focused development tasks.

