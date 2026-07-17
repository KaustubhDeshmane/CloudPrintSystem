<div align="center">

# ☁️ Cloud Print Queue System

### Cloud-Native Print Management Platform

A secure and scalable **cloud-based print queue management system** that enables users to upload documents, configure print settings, make secure online payments via **PhonePe**, and track print jobs in real time. Administrators can efficiently manage print queues, documents, payments, and job statuses through a centralized dashboard.

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge\&logo=fastapi\&logoColor=white)
![Azure](https://img.shields.io/badge/Microsoft%20Azure-0078D4?style=for-the-badge\&logo=microsoftazure\&logoColor=white)
![Azure SQL](https://img.shields.io/badge/Azure%20SQL-CC2927?style=for-the-badge\&logo=microsoftsqlserver\&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge)
![PhonePe](https://img.shields.io/badge/PhonePe-Payment-5F259F?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-success?style=for-the-badge)

</div>

---

# 📖 Overview

Cloud Print Queue System modernizes the traditional printing workflow by combining **FastAPI**, **Microsoft Azure**, and **PhonePe Payment Gateway** into a unified cloud platform. Users can upload documents, customize print settings, pay securely online, and monitor their print requests, while administrators manage the complete printing lifecycle from a centralized dashboard.

---

# ✨ Features

### 👤 User

* 📄 Upload PDF/documents
* 🖨️ Configure print settings
* 📑 Paper size, orientation & duplex options
* 🎨 Color / Black & White printing
* 🔢 Multiple copies & page selection
* 💰 Automatic cost estimation
* 💳 Secure PhonePe payments
* 📊 Queue tracking
* 🧾 Download payment receipts
* 📜 Print history

### 👨‍💼 Admin

* Dashboard overview
* Queue management
* Print job monitoring
* Payment verification
* Customer management
* Search & filters
* Analytics & reporting

### ☁️ Cloud

* Azure App Service
* Azure SQL Database
* Azure Blob Storage
* Secure environment variables
* Scalable cloud deployment

---

# 🏗️ Architecture

```text
                    User Portal
                         │
                         ▼
            Upload & Configure Print Job
                         │
                         ▼
                 FastAPI REST Backend
        ┌────────────┬─────────────┬────────────┐
        ▼            ▼             ▼
 Azure Blob      PhonePe       SQLAlchemy
   Storage       Payment            ORM
        │            │              │
        └────────────┼──────────────┘
                     ▼
            Azure SQL Database
                     │
                     ▼
          Queue Management Engine
                     │
                     ▼
              Admin Dashboard
```

---

# 🛠️ Tech Stack

| Category | Technologies                          |
| -------- | ------------------------------------- |
| Backend  | Python, FastAPI, SQLAlchemy, Uvicorn  |
| Frontend | HTML, CSS, JavaScript                 |
| Database | Azure SQL Database                    |
| Cloud    | Azure App Service, Azure Blob Storage |
| Payment  | PhonePe Payment Gateway               |

---

# 📂 Project Structure

```text
CloudPrintQueueSystem/
│
├── app/
│   ├── routes/
│   ├── models/
│   ├── services/
│   ├── database/
│   └── utils/
│
├── static/
├── templates/
├── requirements.txt
├── .env.example
├── main.py
└── README.md
```

---

# ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/KaustubhDeshmane/CloudPrintQueueSystem.git
cd CloudPrintQueueSystem
```

### Create Virtual Environment

```bash
python -m venv venv
```

**Windows**

```bash
venv\Scripts\activate
```

**Linux/macOS**

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Configure Environment Variables

```env
DB_SERVER=
DB_NAME=
DB_USERNAME=
DB_PASSWORD=

AZURE_STORAGE_CONNECTION_STRING=
AZURE_STORAGE_CONTAINER=

PHONEPE_MERCHANT_ID=
PHONEPE_SALT_KEY=
```

### Run the Server

```bash
uvicorn main:app --reload
```

---

# 📚 API Documentation

| Documentation | URL                           |
| ------------- | ----------------------------- |
| Swagger UI    | `http://localhost:8000/docs`  |
| ReDoc         | `http://localhost:8000/redoc` |

---

# ☁️ Azure Services

* Azure App Service
* Azure SQL Database
* Azure Blob Storage
* Azure Resource Group

---

# 🔒 Security

* Environment-based configuration
* Secure Azure SQL connections
* Azure Blob Storage
* Input validation with FastAPI
* SQLAlchemy ORM protection
* PhonePe payment verification
* Production-ready configuration

---

# 🚀 Highlights

* Cloud-native architecture
* Modular FastAPI backend
* RESTful API design
* Azure cloud integration
* Secure online payments
* Scalable storage
* Interactive Swagger documentation
* Responsive user interface

---

# 🎯 Future Improvements

* JWT Authentication
* Docker support
* CI/CD pipeline
* Email notifications
* Real-time queue updates
* Multi-printer support
* Azure Key Vault integration
* Admin analytics dashboard

---

# 🤝 Contributing

Contributions are welcome!

```bash
# Fork the repository
git checkout -b feature/your-feature

git commit -m "Add new feature"

git push origin feature/your-feature
```

Then open a Pull Request.

---

# 📄 License

This project is licensed under the **MIT License**.

---

# 👨‍💻 Author

**Kaustubh Deshmane**

Passionate about building scalable cloud applications, backend systems, and modern software solutions.

---

# 📬 Contact

For feedback, suggestions, or collaboration:

* **GitHub:** **@KaustubhDeshmane**

---

<div align="center">

### ⭐ If you found this project helpful, consider giving it a star!

**Built with ❤️ by Kaustubh Deshmane**

</div>
