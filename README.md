# AWS SOC 2 Compliance Checklist ✅

This project provides a real-world, screenshot-backed compliance checklist for aligning AWS services with **SOC 2** Trust Services Criteria. The checklist highlights foundational GRC principles such as access control, encryption, monitoring, and network security using actual AWS console configurations.

---

## 🔍 Overview

Ideal for:
- Cloud engineers conducting internal audits
- GRC professionals preparing for SOC 2 reviews
- Students building real-world cloud security portfolios

---

## 📂 Files Included

| File | Description |
|------|-------------|
| `AWS_SOC2_Compliance_Checklist.xlsx` | Main checklist with control mappings, compliance status, and notes |
| `summary-report.md` | Executive-level summary with screenshots and findings |
| `mapping-table.pdf` | Mapping between AWS services and SOC 2 principles |
| `screenshots/` | Folder of actual AWS screenshots documenting each control |

---

## ✅ Screenshot Summary

| Area | Screenshot Filename | Summary |
|------|----------------------|---------|
| IAM Password Policy | `iam-password-policy.png` | Shows enforced complexity and rotation requirements |
| IAM MFA Setup | `mfa-device-selection-authenticator-app.png` | Shows selection of authenticator app for MFA |
| S3 Public Access | `s3-block-public-access.png` | Confirms all public access to S3 is blocked |
| S3 Encryption | `s3-default-encryption.png` | Shows default encryption (SSE-S3) is enabled |
| CloudTrail Logging | `cloudtrail-management-events.png` | Logs read/write management API calls |
| CloudTrail Multi-Region | `cloudtrail-multi-region-review.png` | Confirms logging is enabled across all AWS regions |
| EC2 Security Group | `ec2-security-group-inbound.png` | Displays network access rules for EC2 traffic |
| GuardDuty | `guardduty-findings-empty.png` | GuardDuty enabled for threat detection |

---

## 🧠 How to Use

1. Clone the repo or download the zipped folder.
2. Review checklist and validate your own AWS account.
3. Replace screenshots with your own if doing an internal audit.
4. Use the markdown files as documentation during GRC reviews or interviews.

---

## 🛠️ Created By

[Your Name] – GRC / Cloud Security  
Old Dominion University · Cybersecurity & AI Governance Focus  
[LinkedIn URL]  
