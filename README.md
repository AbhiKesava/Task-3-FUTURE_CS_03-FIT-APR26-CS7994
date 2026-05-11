# API Security Risk Analysis

## Project Overview

This project demonstrates a professional API Security Risk Analysis performed on publicly accessible demo APIs. The assessment focuses on identifying common API security weaknesses including authentication flaws, authorization issues, excessive data exposure, missing rate limiting, and weak input validation practices.

The project was conducted in a read-only and ethical manner using public APIs intended for testing and educational purposes.

---

# Objective

The objective of this project is to:

- Analyze public/demo APIs
- Identify common API security risks
- Assess authentication and authorization mechanisms
- Inspect headers and API responses
- Explain risks in business-friendly language
- Suggest remediation strategies aligned with modern SaaS security practices

---

# APIs Tested

## 1. JSONPlaceholder
A fake REST API commonly used for testing and prototyping.

Website:
https://jsonplaceholder.typicode.com

Tested Endpoints:
- /users
- /posts
- /comments

---

## 2. ReqRes API
A hosted REST API used for authentication and API workflow testing.

Website:
https://reqres.in

Tested Features:
- Login endpoint
- User retrieval
- Token responses

---

# Tools Used

| Tool | Purpose |
|------|----------|
| Postman | API request testing |
| Browser DevTools | Header and response inspection |
| GitHub | Project hosting |
| Google Docs / MS Word | Report documentation |
| PDF Export | Final report generation |

---

# Methodology

The following methodology was used during the assessment:

1. Review API documentation
2. Identify available endpoints
3. Test endpoints using Postman
4. Inspect request and response headers
5. Analyze authentication mechanisms
6. Inspect response data exposure
7. Evaluate rate-limiting behavior
8. Review input validation practices
9. Classify security risks
10. Document findings and recommendations

---

# Security Risks Identified

## 1. Missing Authentication
Some endpoints allowed unrestricted access to data without requiring authentication.

Severity: High

Potential Impact:
- Unauthorized access
- Data leakage
- Abuse of API resources

---

## 2. Excessive Data Exposure
Certain responses returned unnecessary information such as user emails and metadata.

Severity: Medium

Potential Impact:
- Privacy concerns
- Information disclosure
- Increased attack surface

---

## 3. Missing Rate Limiting
No visible throttling mechanisms were identified during testing.

Severity: Medium

Potential Impact:
- API abuse
- Brute-force attacks
- Denial of Service risks

---

## 4. Weak Input Validation
Input fields accepted unexpected characters and malformed data.

Severity: Medium

Potential Impact:
- Injection attacks
- Application instability
- Security bypass opportunities

---

# Risk Severity Classification

| Severity | Description |
|----------|-------------|
| High | Serious security issue requiring immediate attention |
| Medium | Moderate security weakness with business impact |
| Low | Minor issue or informational finding |

---

# Repository Structure

api-security-risk-analysis/

- README.md → Project documentation
- report/ → Final security report PDF
- screenshots/ → Evidence and testing screenshots
- postman_collection/ → Exported API request collection
- findings/ → Summary of identified risks

---

# Screenshots Included

The repository includes screenshots demonstrating:

- API requests and responses
- Header analysis
- Authentication testing
- Response inspection
- Evidence of identified risks

---

# Ethical Statement

This project was conducted using only public/demo APIs intended for educational and testing purposes.

No exploitation, denial-of-service activity, or unauthorized access attempts were performed.

All testing was limited to safe and read-only interactions.

---

# Learning Outcomes

This project demonstrates practical understanding of:

- API Security Fundamentals
- SaaS Security Risks
- Authentication & Authorization Analysis
- Security Documentation
- Risk Assessment
- AppSec Methodology
- Professional Security Reporting

---

# References

OWASP API Security Top 10
https://github.com/OWASP/API-Security

API Security Checklist
https://github.com/shieldfy/API-Security-Checklist

Public APIs Collection
https://github.com/public-apis/public-apis

---

# Conclusion

Modern SaaS applications rely heavily on APIs for communication between systems, applications, and services. Weak API security controls can expose organizations to sensitive data leakage, unauthorized access, and service abuse.

This project demonstrates how basic API security analysis can help identify common weaknesses and improve the overall security posture of modern applications.
