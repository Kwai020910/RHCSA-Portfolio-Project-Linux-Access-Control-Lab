# 🔐 RHCSA Portfolio Project – Enterprise Linux Access Control & Security Hardening Lab

A hands-on, real-world RHCSA-aligned project demonstrating **Linux access control, permissions hardening, and least-privilege security design** in an enterprise multi-department environment.

This lab simulates how Linux administrators secure shared servers used by multiple business units (Engineering, Finance, Support) while allowing collaboration **without data leakage**.

---

## 🎯 Objectives

By completing this lab, you will demonstrate practical skills in:

- User & group management  
- Linux ownership and permissions (`chmod`, `chown`, `chgrp`)  
- ACLs (`setfacl`, `getfacl`) for fine-grained access control  
- Special permissions: **SGID** and **Sticky Bit**  
- Applying the **least-privilege security model**  
- Verifying access control configurations (RHCSA-style validation)

---

## 🏢 Scenario (Real-World)

You are a Linux administrator at **AquilaTech Solutions**.  
A shared Linux server hosts sensitive data for multiple departments:

- 🛠 Engineering  
- 💰 Finance  
- 🎧 Support  

Your task is to design and implement secure access controls that:
- Protect sensitive data  
- Enable collaboration  
- Prevent unauthorized access and accidental deletion  

---

## 🧪 Lab Environment

### Directory Structure

```text
/srv/aquilatech/
├── engineering/
├── finance/
├── support/
├── shared/
└── dropbox/


