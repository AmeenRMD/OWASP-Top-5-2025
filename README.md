# OWASP Top 5 Web Application Security Risks (2025)

A security research and analysis project focused on the **OWASP Top 5 Web Application Security Risks (2025)**.  
This repository demonstrates practical understanding of how modern web vulnerabilities occur, how attackers exploit them, and how developers and security teams can detect and mitigate them in real-world systems.

The project emphasizes **application security fundamentals**, **real breach analysis**, and **defender-oriented thinking**, making it suitable for a cybersecurity portfolio.

---

## Project Overview

The OWASP Top Risks highlight the most common and impactful security failures affecting web applications and APIs.  
This project analyzes each risk with:

- Clear explanation of the vulnerability
- Common causes and failure patterns
- Attacker detection and exploitation techniques
- Developer and tester detection strategies
- Real-world breach case studies
- Security impact and lessons learned

## Downloads

- Full report (PDF): `OWASP Top 5 (2025).pdf)`
- Presentation (PDF): `OWASP Top 5.pdf`

For best viewing experience, download the PDF. GitHub preview may not render all visuals correctly.

---

## Covered Security Risks

### Broken Access Control
Failures that allow users to act outside intended permissions.

- Insecure Direct Object References (IDOR)
- Privilege escalation
- Missing or inconsistent server-side authorization
- API and URL manipulation

**Real-world case:** Optus Data Breach (2022)

---

### Security Misconfiguration
Incorrect or insecure system, framework, cloud, or server configurations.

- Default credentials and unused services
- Exposed cloud storage and overly permissive IAM roles
- Verbose error messages and debug modes in production

**Real-world case:** Capital One Cloud Misconfiguration (2019)

---

### Software Supply Chain Failures
Security weaknesses introduced through third-party components and build pipelines.

- Vulnerable or unmaintained dependencies
- Compromised CI/CD pipelines
- Dependency poisoning and typosquatting attacks

**Real-world case:** SolarWinds Orion Attack (2020)

---

### Cryptographic Failures
Weak, missing, or incorrectly implemented cryptographic protections.

- Use of deprecated algorithms
- Poor key management practices
- Missing TLS or insecure encryption modes
- Crypto downgrade and validation failures

**Real-world case:** WhatsApp Encryption Downgrade Flaw (2023)

---

### Injection
Untrusted input interpreted as code or commands by the application.

- SQL and NoSQL injection
- OS command injection
- LDAP, ORM, and template injection
- Unsafe dynamic query construction

**Real-world case:** British Airways Breach (2018)

---

## Attacker vs Defender Perspective

Each vulnerability is analyzed from two viewpoints:

### Attacker Perspective
- How vulnerabilities are discovered
- Common exploitation techniques
- Indicators of insecure implementations
- Typical developer mistakes abused in attacks

### Defender Perspective
- Secure coding and configuration practices
- Server-side enforcement strategies
- Testing and validation approaches
- Preventive controls and design considerations

---

## Security Concepts Demonstrated

- OWASP Top Risks methodology
- Secure Software Development Lifecycle (SSDLC)
- Application and API security fundamentals
- Cloud and configuration security
- Dependency and supply chain risk awareness
- Cryptographic best practices
- Security testing concepts (SAST, DAST, IAST)

This is a research and analysis project; no automated exploitation or scanning was performed.

---

## Why This Project Matters

Most large-scale breaches originate from:
- Broken authorization logic
- Misconfigurations
- Weak cryptography
- Unsafe dependency usage
- Unvalidated input handling

This project focuses on understanding **why these failures happen**, not just listing them, reflecting real-world application security challenges.

---

## Author

**Ameen ul Islam**  
**MES College, Marampally**

---

## References

- OWASP Official Documentation
- OWASP Risk and CVE Data Contributions
- Public breach disclosures and security advisories
