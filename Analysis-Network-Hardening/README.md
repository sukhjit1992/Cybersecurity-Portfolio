# Security Risk Assessment Report

## Project Overview

In this project, I performed a security risk assessment for a social media organization that recently experienced a data breach. The breach exposed customers' personal information, including names and addresses.

After reviewing the organization's network security, I identified four major vulnerabilities that could increase the risk of future attacks.

## Part 1: Identified Security Vulnerabilities

The following security weaknesses were identified:

1. **Password Sharing:** Employees share passwords, increasing the risk of unauthorized account access.
2. **Default Database Password:** The database administrator account still uses a default password, making it vulnerable to unauthorized access.
3. **Firewall Misconfiguration:** Firewalls do not have proper rules to filter incoming and outgoing network traffic.
4. **No Multi-Factor Authentication (MFA):** MFA is not enabled, leaving accounts more exposed if passwords are compromised.

## Part 2: Recommended Hardening Methods

I selected the following three security hardening methods to reduce these risks:

### 1. Password Policies and Multi-Factor Authentication (MFA)

Implement strong password policies requiring unique and sufficiently complex passwords. Enable MFA for administrative accounts to add another layer of security. Account lockout policies and rate limiting should also be used to reduce brute-force attacks.

### 2. Principle of Least Privilege

Users and administrators should only receive the access permissions required to perform their job responsibilities. This helps limit unauthorized access to sensitive information and reduces the potential impact of compromised accounts.

### 3. Firewall Maintenance

Review and update firewall configurations regularly. Implement appropriate rules to filter unauthorized incoming and outgoing traffic and help protect the organization's network from potential threats.

## Part 3: Conclusion

Based on my assessment, the organization has several security weaknesses that could lead to another data breach if left unaddressed.

Implementing strong password policies, MFA, least privilege access, and proper firewall maintenance will help reduce security risks and improve overall network protection.

Regular security reviews and updates should also be performed to maintain a stronger security posture and protect customers' personal information.

---

**Project Category:** Cybersecurity  
**Project Type:** Security Risk Assessment  
**Focus Areas:** Network Hardening, Access Control, Password Security, MFA, and Firewall Configuration
