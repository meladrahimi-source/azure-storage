# azure-storage & cloud services

☁️ Azure Cloud Fundamentals  
«Practical hands-on experience with Azure Infrastructure and Storage Services using the Azure Portal.»

---

## 📖 Project Overview

This repository documents my Azure Cloud learning journey and practical exercises completed in Microsoft Azure. The project focuses on understanding, deploying, and configuring core Azure Services, spanning web hosting, databases, networking, and dedicated storage solutions.

The project highlights the following core components:
* 🌐 Web App (App Services)
* 🗄️ Azure Database for MySQL & Free SQL
* 🔒 Virtual Network (VNet)
* 📦 Blob Storage
* 📂 Azure Files
* 📥 Queue Storage
* 📊 Table Storage

---

## 🎯 Learning Objectives

* Create and configure an Azure Account and manage core profiles.
* Deploy and manage scalable web applications via Azure Web App.
* Provision and connect managed relational databases (MySQL & Free SQL).
* Design secure environments using Azure Virtual Network (VNet).
* Work with Blob Containers and perform structured/unstructured file uploads.
* Create and manage production-ready Azure File Shares.
* Understand asynchronous communication using Azure Queue Storage concepts.
* Explore NoSQL fast-retrieval mechanisms via Table Storage.
* Compare various Azure architecture services and analyze their real-world use cases.

---

## 🏗️ Azure Infrastructure Architecture

```text
Azure Account ──┬── Web App (App Hosting)
                ├── Virtual Network (VNet Security)
                ├── Databases (MySQL / Free SQL)
                └── Storage Account ──┬── Blob Containers ──> Unstructured Files
                                      ├── File Shares ──> Shared Folders
                                      ├── Queues ──> Application Messages
                                      └── Tables ──> NoSQL Data

## Detailed Services & Practical Exercises
### 1. Account & Profile* **Purpose:** Identity and subscription access management within the Azure Portal.* **Practical Exercise:** Setup and verified resource groups for centralized cloud asset governance.* **Screenshot:**![Azure Profile](./screenshots/profile.png)
### 2. Web App (App Services)* **Purpose:** Hosting web applications with built-in infrastructure scaling and high availability.* **Practical Exercise:** Created and deployed an enterprise-ready app service slot.* **Screenshot:**![Azure Web App](./screenshots/webapp.png)
### 3. Azure Database for MySQL* **Purpose:** Managed community MySQL database instance for scalable application backend architectures.* **Practical Exercise:** Provisioned the database server and configured secure firewall access rules.* **Screenshot:**![Azure MySQL](./screenshots/mysql.png)
### 4. Free SQL Database* **Purpose:** Cloud-native relational database used for testing queries and cost-efficient application prototyping.* **Practical Exercise:** Built database schemas and executed cloud-based T-SQL commands.* **Screenshot:**![Azure Free SQL](./screenshots/freesql.png)
### 5. Virtual Network (VNet)* **Purpose:** Providing isolated network environments to route and secure traffic natively between components.* **Practical Exercise:** Configured subnets and network topology routes to isolate internal cloud workloads.* **Screenshot:**![Azure VNet](./screenshots/vnet.png)
### 6. Blob Storage* **Purpose:** Storing massive volumes of unstructured binary and object data.* **Data types handled:** Images, Documents, PDFs, Videos, and System Backups.* **Practical Exercise:** Initialized object storage containers and managed file lifecycle policies.* **Screenshot:**![Azure Blob Storage](./screenshots/blobstorage.png)
### 7. Azure Files* **Purpose:** Fully managed cloud-based file shares accessible simultaneously via SMB or NFS protocols.* **Practical Exercise:** Mounted a shared file directory system simulated for distributed cloud components.* **Screenshot:**![Azure Files](./screenshots/azurefile.png)
### 8. Queue Storage* **Purpose:** Decoupling application tiers by storing large quantities of processing messages reliably.* **Practical Exercise:** Created messaging queues to handle microservices communication asynchronously.* **Screenshot:**![Azure Queue](./screenshots/queue.png)
### 9. Table Storage* **Purpose:** A fast NoSQL key-value store optimized for massive semi-structured non-relational datasets.* **Practical Exercise:** Populated entities and partitions to verify immediate record indexing.* **Screenshot:**![Azure Table](./screenshots/table.png)
--- ️ *If you find this comprehensive Azure ecosystem showcase helpful, feel free to give this repository a star!*
