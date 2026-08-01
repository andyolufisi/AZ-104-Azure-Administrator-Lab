# Azure Backup & Recovery

## 📌 Objective

The objective of this lab was to configure Azure Backup for a production virtual machine using Azure Recovery Services Vault. This ensures business continuity by protecting the virtual machine against accidental deletion, corruption, ransomware attacks, and infrastructure failures. The lab also demonstrates how Azure Backup creates recovery points that can be used to restore workloads with minimal downtime.

---

## 🏢 Business Scenario

As the Azure Administrator for a financial institution, protecting critical business systems is a key responsibility. The organization requires all production virtual machines to be backed up daily to prevent data loss caused by hardware failure, cyberattacks, accidental deletion, or application corruption.

In this lab, Azure Backup was configured to automatically protect the production virtual machine by creating scheduled recovery points inside an Azure Recovery Services Vault. This ensures that business services can be restored quickly in the event of a disaster while maintaining compliance with organizational backup policies.

---

## 🎯 Technologies Used

- Microsoft Azure
- Azure Recovery Services Vault
- Azure Backup
- Backup Policy
- Recovery Points
- Azure Virtual Machines
- Azure Storage
- Azure Monitor

---

## 🛠 Azure Resources Created

- Recovery Services Vault
- Backup Policy
- Protected Virtual Machine
- Recovery Point
- Backup Job

---

## 📋 Tasks Completed

- Created an Azure Recovery Services Vault.
- Configured Azure Backup for the production virtual machine.
- Associated the VM with the Recovery Services Vault.
- Applied the default backup policy.
- Started the initial backup operation.
- Verified backup job status.
- Confirmed that the VM is protected.
- Verified that Azure created a recovery point.
- Reviewed backup monitoring and job history.

---

## 🔄 Backup Workflow

```
Azure Virtual Machine
        │
        ▼
Backup Policy
        │
        ▼
Recovery Services Vault
        │
        ▼
Recovery Point
        │
        ▼
Restore Virtual Machine
```

---

## 🔒 Security & Business Benefits

Azure Backup provides several important business advantages:

- Automated scheduled backups
- Secure encrypted backup storage
- Protection against accidental deletion
- Recovery from ransomware incidents
- Business continuity
- Disaster recovery support
- Long-term data retention
- Centralized backup management

---

## 💡 Lessons Learned

During this lab, I learned how Azure Backup protects virtual machines by using Recovery Services Vault. I understood the relationship between backup policies, protected items, recovery points, and backup jobs. I also learned how Azure enables administrators to recover workloads after failures while reducing downtime and ensuring business continuity.

---

## 🚀 Skills Demonstrated

- Azure Backup Administration
- Recovery Services Vault Configuration
- Backup Policy Configuration
- Recovery Point Management
- Virtual Machine Protection
- Business Continuity Planning
- Disaster Recovery Fundamentals
- Azure Infrastructure Administration

---

## 📚 AZ-104 Exam Objectives Covered

- Configure Azure Backup
- Configure Recovery Services Vault
- Protect Azure Virtual Machines
- Configure Backup Policies
- Monitor Backup Jobs
- Restore Azure Resources
- Understand Business Continuity and Disaster Recovery (BCDR)

---

## ✅ Lab Outcome

Successfully deployed and configured Azure Backup for an Azure Virtual Machine using Recovery Services Vault. The virtual machine is protected through scheduled backups, recovery points are created automatically, and the environment is prepared for disaster recovery scenarios.

---

## 📷 Screenshots

- Recovery Services Vault
- Backup Configuration
- Backup Policy
- Backup Job
- Backup Completed
- Protected Items
- Recovery Point
- Backup Overview

---
