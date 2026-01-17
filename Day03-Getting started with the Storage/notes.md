# Notes – AWS Storage Services

## 📦 Introduction to Storage

Storage in cloud computing refers to saving and accessing data over the internet.
AWS provides multiple storage services optimized for different workloads.

### Storage Types:
- Object Storage
- Block Storage
- File Storage

Each type is designed for specific use cases.

---

## 🪣 Introduction to Amazon S3

Amazon S3 (Simple Storage Service) is an **object storage service** used to store and retrieve any amount of data.

### Key Features:
- Highly durable (99.999999999%)
- Scalable
- Secure
- Cost-effective

### Common Use Cases:
- Backup and restore
- Static website hosting
- Media storage
- Data lakes

---

## 🛠 Using Amazon S3

- Data is stored as **objects** inside **buckets**
- Objects consist of:
  - Data
  - Metadata
  - Unique key
- Supports versioning, encryption, and lifecycle policies

---

## 🧰 Additional AWS Storage Services

- Amazon S3 Glacier – archival storage
- AWS Storage Gateway – hybrid storage
- AWS Backup – centralized backup service

---

## 💽 Block Storage at AWS – Amazon EBS

Amazon Elastic Block Store (EBS) provides **block-level storage** for EC2 instances.

### Key Characteristics:
- Attached to EC2 instances
- Persistent storage
- Low-latency performance

### Use Cases:
- Operating systems
- Databases
- Applications requiring fast disk access

---

## 📁 File Storage at AWS – Amazon EFS

Amazon Elastic File System (EFS) provides **file storage** for Linux-based workloads.

### Key Characteristics:
- Shared file system
- Scales automatically
- Accessible by multiple EC2 instances

### Use Cases:
- Content management systems
- Shared application data
- Web servers

---

## 🔍 Comparison Summary

| Service | Storage Type | Use Case |
|-------|-------------|---------|
| S3 | Object | Backup, media, static websites |
| EBS | Block | OS, databases |
| EFS | File | Shared file systems |

---

## 🧠 Key Takeaways

- Choose storage based on access pattern
- S3 is object storage, not a file system
- EBS is tied to EC2
- EFS allows shared access

