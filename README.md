<p align="center">
  <img src="https://img.shields.io/badge/Microsoft-Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white">
  <img src="https://img.shields.io/badge/Security-Key%20Vault-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/AZ--500-Aligned-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Secrets%20Management-blue?style=for-the-badge">
</p>

<h1 align="center">Azure Key Vault – Secrets Management & Hardening Lab</h1>

<p align="center">
  Enterprise-style hands-on Microsoft Azure Key Vault lab demonstrating secure secret lifecycle management, 
  soft-delete protection, purge protection, and security hardening best practices.<br><br>
  AZ-500 aligned | Built by Amal Basnayake — Cybersecurity Engineer
</p>

<p align="center">
  <a href="https://github.com/AmalUBasnayake/Azure-Key-Vault-Secrets-Lab/stargazers">
    <img src="https://img.shields.io/github/stars/AmalUBasnayake/Azure-Key-Vault-Secrets-Lab?style=social">
  </a>
  <a href="https://www.linkedin.com/in/amal-udayanga-basnayake">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin&logoColor=white">
  </a>
  <a href="https://github.com/AmalUBasnayake">
    <img src="https://img.shields.io/badge/GitHub-Portfolio-black?style=flat&logo=github&logoColor=white">
  </a>
</p>

---

## 🎯 Lab Objective

This lab demonstrates how to securely manage application secrets using Azure Key Vault.

✔ Create and securely store a secret  
✔ Enable soft-delete with 90-day retention  
✔ Enable purge protection (mandatory recovery enforcement)  
✔ Review secret versions and metadata  
✔ Validate deployment and resource integrity  

---

## 🏗️ Architecture Overview

<p align="center">
  <img src="screenshots/architecture-overview.png" width="850" alt="Azure Key Vault Lab Architecture Diagram">
</p>

### Architecture Flow:

1. Administrator deploys **Azure Key Vault**
2. Secret (`MySecretPassword`) is stored securely
3. Soft-delete retention policy (90 days) is enforced
4. Purge protection prevents accidental permanent deletion
5. Azure RBAC & access policies control access

This architecture follows secure cloud design principles aligned with AZ-500 exam objectives.

---

## 📸 Screenshots Gallery

<table>
  <tr>
    <td align="center">
      <strong>1️⃣ Secrets List – MySecretPassword Created</strong><br>
      <img src="screenshots/1-secrets-list-created.png" width="420" alt="Secret successfully created">
    </td>
    <td align="center">
      <strong>2️⃣ Deployment Overview</strong><br>
      <img src="screenshots/2-deployment-in-progress.png" width="420" alt="Key Vault deployment status">
    </td>
  </tr>
  <tr>
    <td align="center">
      <strong>3️⃣ Secret Version & Properties</strong><br>
      <img src="screenshots/3-secret-version-details.png" width="420" alt="Secret version history">
    </td>
    <td align="center">
      <strong>4️⃣ Soft-Delete & Purge Protection Enabled</strong><br>
      <img src="screenshots/4-soft-delete-purge-protection.png" width="420" alt="Soft-delete 90 days enabled">
    </td>
  </tr>
  <tr>
    <td align="center" colspan="2">
      <strong>5️⃣ Key Vault Resource List</strong><br>
      <img src="screenshots/5-key-vaults-list.png" width="800" alt="Vault listed in subscription">
    </td>
  </tr>
</table>

---

## 🚀 Implementation Steps (Technical Summary)

1️⃣ Created new Key Vault  
   - Name: **Amal-Secure-Vault-01**  
   - Resource Group: **AZ500-KeyVault-RG**  
   - Region: **East US**

2️⃣ Generated Secret  
   - Secret Name: **MySecretPassword**
   - Successfully stored and verified

3️⃣ Enabled Security Controls  
   - Soft-delete: **Enabled (90 days retention)**
   - Purge protection: **Enabled**

4️⃣ Verified:
   - Secret versioning
   - Deployment status
   - Vault availability
   - No deleted vault instances

---

## 🧠 Key Security Takeaways

🔐 Soft-delete prevents accidental secret loss  
🛡 Purge protection enforces mandatory retention  
🔄 Secret versioning enables rollback & audit trails  
🎯 Centralized secrets management reduces attack surface  
📘 Critical knowledge area for AZ-500 certification  

---

## 🔗 References

- Azure Key Vault Secrets Overview  
- Soft-delete & Purge Protection Documentation  
- AZ-500 Certification Guide  

---

<p align="center">
  <strong>If this lab helped your AZ-500 preparation, consider giving it a ⭐</strong><br>
  Fork, clone, or raise issues — contributions welcome!
</p>

<p align="center">
  Built with dedication by <a href="https://www.linkedin.com/in/amal-udayanga-basnayake">Amal Basnayake</a><br>
  Cybersecurity Engineer | Cloud Security | Azure Security Enthusiast
</p>
