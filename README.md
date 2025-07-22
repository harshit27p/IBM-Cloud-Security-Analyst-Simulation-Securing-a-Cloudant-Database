# 🛡️ IBM Cloud Security Analyst Simulation: Securing a Cloudant Database

Welcome to the IBM Cloud Security Analyst Simulation repository!  
This project demonstrates the step-by-step simulation of securing an IBM Cloudant database using IBM Security and Compliance tools.

---

## 📘 Overview

This project simulates a real-world scenario where a **Cloud Security Analyst** creates a cloud-native database (IBM Cloudant), sets up object storage, configures compliance controls, and runs security checks. This process is essential to ensure the **confidentiality, integrity, and availability** of cloud-hosted services and data.

> 💡 No installation or live cloud deployment is required — this is a **simulation-based learning** project.

---

## 🎯 Objectives

By the end of this simulation, you will learn how to:

- ✅ Deploy an IBM Cloudant database
- ✅ Set up IBM Cloud Object Storage
- ✅ Create and manage control libraries using IBM Security and Compliance Center
- ✅ Run and evaluate security assessments on a cloud database
- ✅ Understand shared responsibility and cloud security principles

---

## 🛠️ Tools & Services Used

| Tool/Service                     | Purpose |
|----------------------------------|---------|
| IBM Cloudant                    | NoSQL database service |
| IBM Cloud Object Storage        | Storage for test result files |
| IBM Security and Compliance Center | Create controls, profiles, and scan reports |
| IAM (Identity & Access Management) | Secure authentication and role-based access control |
| TLS Encryption                  | Secure data in transit |
| Disk Encryption                 | Secure data at rest |

---

## 🧪 Simulation Workflow

### Step-by-Step Flow

1. **Create a Cloudant DB**  
   → Name: `usr-cldnt-database`  
   → Enable IAM authentication and disk encryption

2. **Set Up Cloud Object Storage**  
   → Create instance  
   → Create bucket (default configuration)

3. **Create Control Library**  
   → Name: `Cloudant Database Controls`  
   → Add assessments:
     - Encryption enabled
     - TLS 1.2 or higher for access

4. **Configure Compliance Scan**  
   → Attach control library to a profile  
   → Set default scope and schedule daily scans

5. **Review Results**  
   → Checkmarks ✅ indicate secure configuration  
   → Logs stored in object storage for audit

---

## 📂 Repository Structure

```bash
📁 ibm-cloud-security-simulation/
├── 📄 README.md
├── 📄 simulation-transcript.md   # Full step-by-step transcript (if exported)
├── 📄 secure-cloudant-checklist.md # Key security settings checklist
├── 📁 screenshots/               # Optional: Screenshots from simulation
└── 📁 docs/
    └── 📝 cloudant-security-report-summary.md

🔐 Security Concepts Reinforced

    IAM: Identity and role-based access control

    TLS: Encrypted communication channels

    Zero Trust: Trust no entity by default

    Least Privilege: Grant only necessary access

    Compliance-as-code: Use controls & scans to automate checks

📈 Benefits of the Simulation

    Learn real-world secure deployment patterns

    Understand how IBM Cloud tools help manage security posture

    Gain insights into cloud-native compliance practices

    Practice incident response readiness with test reports

🤝 Acknowledgements

    IBM Cloudant

    IBM Cloud Object Storage

    IBM Security and Compliance Center

    IBM SkillsBuild Platform
