# Analysis of network hardening
# **Scenario**

**Review the following scenario. Then complete the step-by-step instructions.**

You are a security analyst working for a social media organization. The organization recently experienced a major data breach, which compromised the safety of their customers’ personal information, such as names and addresses. Your organization wants to implement strong network hardening practices that can be performed consistently to prevent attacks and breaches in the future. 

After inspecting the organization’s network, you discover four major vulnerabilities. The four vulnerabilities are as follows:

The organization’s employees' share passwords.

The admin password for the database is set to the default.

The firewalls do not have rules in place to filter traffic coming in and out of the network.

Multifactor authentication (MFA) is not used. 

If no action is taken to address these vulnerabilities, the organization is at risk of experiencing another data breach or other attacks in the future. 

In this activity, you will write a security risk assessment to analyze the incident and explain what methods can be used to further secure the network.

# **Security risk assessment report** 

# Network Hardening: Security Risk Assessment Report

## Overview
This report outlines critical vulnerabilities discovered following a major data breach at our organization and proposes essential network hardening techniques to prevent future incidents.

---

## Part 1: Recommended Network Hardening Methods

To address the identified vulnerabilities and improve our network security posture, we recommend the following four hardening measures:

### 1. Password Policy Enforcement (NIST Guidelines)
Implement password policies aligned with the latest NIST SP 800-63B recommendations:

- Eliminate frequent forced password changes (unless compromise is suspected).
- Require passwords to be salted and hashed at creation.
- Avoid complexity rules that encourage insecure workarounds.
- Block commonly used or previously breached passwords.

### 2. Role-Based Network Access Privileges
Adopt the principle of least privilege using Role-Based Access Control (RBAC):

- Assign permissions based on user roles and responsibilities.
- Restrict access to critical systems (e.g., databases) to authorized users only.
- Monitor and audit access logs regularly to detect anomalies.

### 3. Mandatory Multifactor Authentication (MFA)
Implement MFA across the organization, especially for privileged accounts:

- Use a combination of factors:
  - **Something you know**: Password or PIN.
  - **Something you have**: OTP via mobile app or hardware token.
  - **Something you are**: Biometric data (e.g., fingerprint, facial recognition).
- Require MFA at all remote access points and critical systems.

### 4. Firewall Rule Configuration and Port Filtering
Strengthen perimeter security by configuring firewall rules and filtering ports:

- Block unused or insecure ports (e.g., Telnet, SMBv1).
- Only allow necessary services and ports.
- Monitor and log traffic for abnormal behavior or threats.

---

## Part 2: Justification for Recommendations

Each of the proposed methods addresses one or more of the vulnerabilities discovered during the network review:

- **Password Policies:** Help defend against brute-force and credential stuffing attacks by ensuring passwords are not easily guessable or reused.
- **Access Privileges:** Minimize the risk of insider threats and unauthorized access to sensitive systems.
- **Multifactor Authentication:** Prevent unauthorized access even when login credentials are compromised.
- **Firewall Rules & Port Filtering:** Limit the attack surface and control traffic flow, reducing exposure to external threats.

---

## Conclusion

By adopting these hardening strategies, the organization can substantially enhance its cybersecurity defenses and reduce the likelihood of future data breaches.

It is critical that these measures be applied organization-wide and supported with security awareness training to ensure compliance and long-term protection.

---


