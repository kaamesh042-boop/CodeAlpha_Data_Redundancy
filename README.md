# 🛡️ DataGuard Cloud – Redundancy Removal System

> An intelligent cloud infrastructure monitoring and redundancy detection system that identifies duplicate and near-duplicate cloud resource records using hash-based fingerprinting and similarity analysis.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge\&logo=html5\&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge\&logo=css3\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge\&logo=javascript\&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

## 📖 Overview

DataGuard Cloud is a modern web application designed to improve cloud data integrity by detecting redundant infrastructure records before they are stored. The system performs real-time validation using hash fingerprinting and similarity scoring, helping organizations reduce duplicate entries, maintain cleaner datasets, and improve storage efficiency.

The application features a responsive analytics dashboard, real-time validation engine, audit logging system, and an intuitive user interface for managing cloud resource records.

---

## ✨ Features

* 🔍 Real-time duplicate detection
* ⚡ Hash-based fingerprint generation
* 📊 Similarity scoring algorithm
* 🧠 Near-duplicate identification
* 📈 Interactive analytics dashboard
* 📋 Cloud resource management
* 📝 Audit logging system
* 📉 Database statistics visualization
* 🚀 Responsive modern UI
* 🎯 Record validation before insertion
* 🗑️ Bulk duplicate removal
* 📍 Service and region monitoring
* 💾 In-memory cloud resource database
* 🎨 Professional dashboard interface

---

## 🏗️ System Workflow

1. User submits a cloud resource record.
2. A unique hash fingerprint is generated.
3. The system compares the record against existing entries.
4. Similarity scores are calculated using weighted attributes.
5. The record is classified as:

   * ✅ Unique
   * ⚠ Near Duplicate
   * ❌ Exact Duplicate
   * 🔵 False Positive
6. The dashboard updates analytics and logs automatically.

---

## 🧠 Duplicate Detection Logic

The redundancy engine evaluates multiple cloud resource attributes, including:

* Instance ID
* Region
* Service Type
* CPU Usage
* Memory Usage
* Storage Capacity
* Instance Status

The system combines:

* Hash Matching
* Weighted Similarity Analysis
* Field Comparison
* Threshold-Based Classification

to determine whether a record should be accepted or rejected.

---

## 📊 Dashboard Modules

### Analytics Dashboard

* Average CPU Usage
* Average Memory Usage
* Active Services
* Region Distribution
* Validation Statistics
* Instance Status Overview

### Record Submission

Users can:

* Add new cloud resource records
* Generate random test data
* Test duplicate scenarios
* Preview generated hashes
* Validate records instantly

### Database Viewer

* Search cloud resources
* View stored records
* Delete entries
* Monitor cloud instances

### Audit Log

Tracks every validation event including:

* Unique records
* Exact duplicates
* Near duplicates
* False positives
* Cleanup operations

---

## 🛠️ Technologies Used

| Technology       | Purpose                 |
| ---------------- | ----------------------- |
| HTML5            | Structure               |
| CSS3             | Styling & Responsive UI |
| JavaScript (ES6) | Application Logic       |
| Google Fonts     | Typography              |
| CSS Animations   | User Experience         |

---

## 📂 Project Structure

```
DataGuard-Cloud/
│
├── dataguard.html
├── README.md
└── assets/
```

---

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/kaamesh042-boop/DataGuard-Cloud.git
```

### Open the Project

Simply open:

```
dataguard.html
```

in your preferred web browser.

No installation or additional dependencies are required.

---

## 🎯 Use Cases

* Cloud Infrastructure Monitoring
* Resource Inventory Management
* Duplicate Record Prevention
* Cloud Database Validation
* Educational Demonstrations
* Data Quality Management
* Cloud Operations Dashboard

---

## 📸 Application Highlights

* Modern dashboard interface
* Live analytics
* Real-time validation
* Duplicate detection engine
* Audit trail management
* Interactive database viewer

---

## 🔮 Future Enhancements

* Database integration (MySQL / PostgreSQL)
* User authentication
* Role-based access control
* REST API support
* Machine Learning duplicate prediction
* Cloud provider integration (AWS, Azure, GCP)
* Export reports (PDF / Excel)
* Email notifications
* Dark mode
* Multi-user collaboration

---

## 🤝 Contributing

Contributions are welcome!

If you'd like to improve this project:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push your branch
5. Open a Pull Request

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Kaamesh**

If you found this project helpful, consider giving it a ⭐ on GitHub to support future development.

---

## 🌟 Project Goal

**DataGuard Cloud** demonstrates how intelligent redundancy detection and similarity analysis can improve cloud data quality, reduce storage waste, and maintain accurate infrastructure records through efficient validation techniques.
