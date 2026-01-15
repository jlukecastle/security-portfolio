# IAM Hardening Lab ***IN PROGRESS***

This lab focuses on designing and implementing a **secure, least-privilege IAM model** in Amazon Web Services (AWS).

The objective is to demonstrate a security-engineer mindset by:
- Securing the AWS account baseline
- Reducing standing privilege
- Preventing common IAM misconfigurations and privilege-escalation paths
- Using roles instead of long-lived credentials
- Validating controls through testing and analysis

---

## Objectives

By completing this lab, I aimed to:

- Secure the AWS root account and eliminate unsafe defaults
- Implement least-privilege access for human users
- Use IAM roles for administrative and service access
- Enforce MFA and reduce credential-based risk
- Identify and mitigate IAM privilege-escalation paths
- Document decisions and tradeoffs clearly

---

## Threat Model

This lab is designed to mitigate common IAM-related threats, including:

- Compromise of long-lived credentials
- Excessive permissions granted to users
- Privilege escalation through IAM misconfiguration
- Unauthorized access due to lack of MFA
- Lack of visibility into identity-related actions
