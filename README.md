# Task 11 – Phishing Attack Simulation & Detection

## Objective
The objective of this task is to understand phishing attacks, simulate a phishing campaign in a controlled lab environment using Kali Linux, identify phishing indicators, and learn prevention techniques to improve social engineering awareness.

---

## Tools Used
- Kali Linux
- GoPhish (Phishing Simulation Framework)
- MailHog (Local SMTP Testing Server)
- Firefox Browser

---

## Task Execution Steps

### 1. Understand Phishing Attacks
Phishing is a social engineering attack where attackers impersonate trusted entities to steal sensitive information such as usernames and passwords. This task focuses on understanding how phishing works and how it can be detected and prevented.

---

### 2. Create Fake Email Template
A phishing email template was created using GoPhish with urgent language to simulate a real-world phishing scenario. The email contained a verification link that redirected users to a fake landing page.

**Difficulty Faced:**
- Initial internet and DNS configuration issues in Kali Linux prevented cloning GoPhish from GitHub.
- Network troubleshooting was required to restore connectivity.

---

### 3. Setup Landing Page
A fake account verification landing page was created to demonstrate how attackers collect user credentials. The landing page was configured to capture submitted data for simulation purposes.

**Difficulty Faced:**
- Basic HTML understanding was required to create the login form.
- Correctly linking the landing page with the email template.

---

### 4. Send Test Phishing Email
To ensure safety, MailHog was used as a local SMTP server to send test phishing emails without delivering them to real users.

**Difficulty Faced:**
- MailHog was not available via the `apt` package manager in Kali Linux.
- Manual installation of the MailHog binary was required.

---

### 5. Track Responses
GoPhish campaign dashboard was used to track user interactions such as:
- Email opened
- Link clicked
- Data submitted

These metrics helped analyze the effectiveness of the phishing simulation.

---

### 6. Identify Red Flags
The following phishing indicators were identified:
- Urgent or threatening language
- Suspicious sender address
- Fake or misleading links
- Requests for sensitive information
- Poor grammar or formatting

---

### 7. Learn Prevention Methods
Prevention techniques learned during this task include:
- User awareness and training
- Email filtering and spam detection
- Multi-factor authentication (MFA)
- URL inspection
- Zero-trust security approach

---

### 8. Document Simulation
The complete phishing simulation was documented with screenshots, step-by-step methodology, results, detection techniques, and prevention strategies. All findings were prepared for GitHub submission.

