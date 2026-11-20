
# Vendor Web Application Risk Assessment

> Third-party and application risk: security assessment of a vendor-hosted financial application handling PII.

![Third-party and application risk](https://img.shields.io/badge/Focus-Third--party%20and%20application%20risk-0f766e) ![NIST SP 800-63B](https://img.shields.io/badge/Framework-NIST%20SP%20800--63B-2b6cb0)

| | |
| --- | --- |
| **Focus area** | Third-party and application risk |
| **Frameworks and standards** | NIST SP 800-63B |

## Objective

Determine whether a vendor-hosted financial application handling sensitive PII met an acceptable security standard, and define what the vendor had to fix before the organization could rely on it.

## Execution

- I assessed the application's data handling, transport security, credential storage and session management against NIST SP 800-63B.
- I identified high-risk findings: unencrypted traffic and outdated cryptography for credential protection.
- I rated each finding by severity and by the sensitivity of the PII exposed.
- I specified remediation: enforce TLS, move password storage to Argon2id or bcrypt, vault credentials and harden sessions.
- I translated technical findings into risk statements a business owner could act on.

## Business outcomes

- Produced findings with remediation requirements the vendor could be held to contractually.
- Delivered a clear vendor decision to the business owner, with mandatory fixes tied to contract terms so sensitive PII would not be entrusted to a vendor that failed baseline encryption and credential-protection standards.

## Skills demonstrated

- Application and vendor risk assessment
- Cryptography and credential-storage review
- Finding severity rating
- Business-ready risk communication



## Deliverables

**Risk Assessment Report**


<img width="794" height="912" alt="Risk assess 1" src="https://github.com/user-attachments/assets/2694b65e-2302-4922-97c8-4d58648f55f9" />

<img width="796" height="882" alt="Risk assess 2" src="https://github.com/user-attachments/assets/2e0c1ff2-f32e-4c64-affa-ecdaefe3c4d4" />

<img width="796" height="914" alt="Risk assess 3" src="https://github.com/user-attachments/assets/4c5e0beb-9342-409e-9f77-946f018ff4a0" />

<img width="798" height="904" alt="Risk assess 4" src="https://github.com/user-attachments/assets/f8b0a99a-5b10-43f9-8a54-af677e75ec02" />



*All materials are sanitized and contain no confidential or client data.*
