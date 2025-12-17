# Azure Fundamentals (AZ-900) – Azure Storage Services

This repository documents my learning from **Microsoft Azure Fundamentals (AZ-900)**, focusing on **Azure Storage Services**.

The content covers core storage concepts, service comparisons, redundancy models, and data migration options in Azure.

---

## 📌 Topics Covered

### 🔹 Azure Storage Services
- **Azure Blob Storage**
  - Object storage for unstructured data
  - Use cases: images, videos, backups, logs
- **Azure File Storage**
  - Fully managed file shares in the cloud
  - Lift-and-shift scenarios
- **Azure Queue Storage**
  - Message storage for decoupling applications
- **Azure Table Storage**
  - NoSQL key-value storage

---

### 🔹 Storage Tiers
- **Hot Tier**
  - Frequently accessed data
  - Low access cost, higher storage cost
- **Cool Tier**
  - Infrequently accessed data
  - Lower storage cost, higher access cost
- **Archive Tier**
  - Rarely accessed data
  - Lowest storage cost, highest retrieval latency

---

### 🔹 Redundancy Options
- **LRS (Locally Redundant Storage)**
  - Data replicated within a single datacenter
- **ZRS (Zone-Redundant Storage)**
  - Replication across availability zones
- **GRS (Geo-Redundant Storage)**
  - Replication to a secondary region
- **GZRS (Geo-Zone-Redundant Storage)**
  - Combines zone and geo redundancy

---

### 🔹 Storage Account Options
- **General-purpose v2 (GPv2)**
  - Recommended default option
  - Supports all storage services
- **Blob Storage Accounts**
  - Optimized for blob workloads

---

### 🔹 Moving Files to Azure
- **AzCopy**
  - Command-line tool for fast data transfer
- **Azure Storage Explorer**
  - GUI-based storage management
- **Azure File Sync**
  - Sync on-premises file servers with Azure

---

### 🔹 Migration Options
- **Azure Migrate**
  - Central hub for assessing and migrating workloads
- **Azure Data Box**
  - Physical device for large-scale data transfer
- **Online vs Offline Migration**
  - Based on data size and network constraints

---

## 🎯 Learning Outcome

After completing this module, I can:
- Compare Azure storage services and their use cases
- Choose appropriate storage tiers based on access patterns
- Understand Azure data redundancy models
- Identify tools for data movement and migration
- Select suitable storage account types

---

## 📚 Source
- **Microsoft Learn – AZ-900: Microsoft Azure Fundamentals**
- Domain: Describe Azure Storage Services

---

## 🚀 Next Steps
- Hands-on labs using Azure Blob Storage
- Practice storage redundancy scenarios
- Prepare for AZ-900 certification exam

---

> This repository is part of my ongoing cloud learning journey and will be expanded with practical examples and diagrams.
