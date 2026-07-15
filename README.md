<div align="center">

# ☁️ Cloud Print Queue System

### Secure • Scalable • Cloud-Native Print Management

A cloud-enabled **Print Queue Management System** built with **FastAPI**, **Azure SQL Database**, and **SQLAlchemy**, designed to streamline print job management through a secure, scalable, and centralized architecture.

---

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-0.115+-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Azure](https://img.shields.io/badge/Microsoft-Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Azure SQL](https://img.shields.io/badge/Azure-SQL-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-ORM-D71F00?style=for-the-badge)
![MIT License](https://img.shields.io/badge/License-MIT-success?style=for-the-badge)

</div>

---

# 🚀 Overview

Cloud Print Queue System is a cloud-native web application that centralizes document printing by allowing users to securely upload documents, manage print jobs,make payments and monitor queue status through a high-performance REST API.

Built using **FastAPI** and **SQLAlchemy**, the system integrates with **Azure SQL Database** to provide reliable cloud-based data management while maintaining a modular and scalable backend architecture.

---

# ✨ Key Features

### 📄 Print Queue Management

- Upload documents for printing
- Create and manage print jobs
- Monitor print queue status
- View print history
- Centralized job processing

### ☁️ Cloud Infrastructure

- Azure SQL Database integration
- Cloud-hosted backend services
- Secure database connectivity
- Scalable cloud architecture

### ⚡ RESTful API

- High-performance FastAPI backend
- Interactive Swagger documentation
- ReDoc API documentation
- Clean API architecture

### 🔒 Security

- Environment-based configuration
- Secure credential management
- Database connection isolation
- Production-ready configuration

---

# 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| Python | Backend Development |
| FastAPI | REST API Framework |
| SQLAlchemy | ORM |
| Azure SQL Database | Cloud Database |
| Uvicorn | ASGI Server |
| HTML • CSS • JavaScript | Frontend |
| Azure App Service | Cloud Deployment |

---

# 🏗 Architecture

```text
                Client
                   │
                   ▼
          FastAPI REST API
                   │
        ┌──────────┴──────────┐
        │                     │
        ▼                     ▼
 Document Upload        Print Queue
        │                     │
        └──────────┬──────────┘
                   ▼
             SQLAlchemy ORM
                   │
                   ▼
         Azure SQL Database
```

---

# 📂 Project Structure

```text
CloudPrintSystem/
│
├── app/
│   ├── routes/
│   ├── models/
│   ├── database/
│   ├── services/
│   └── utils/
│
├── static/
├── templates/
├── migrations/
├── .github/
├── requirements.txt
├── .env.example
├── main.py
└── README.md
```

---

# ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/KaustubhDeshmane/CloudPrintSystem.git
cd CloudPrintSystem
```

### Create Virtual Environment

```bash
python -m venv venv
```

**Windows**

```bash
venv\Scripts\activate
```

**Linux / macOS**

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Configure Environment Variables

Create a `.env` file using `.env.example`.

```env
DB_SERVER=
DB_NAME=
DB_USERNAME=
DB_PASSWORD=
```

### Run the Application

```bash
uvicorn main:app --reload
```

Server runs on:

```text
http://127.0.0.1:8000
```

---

# 📖 API Documentation

FastAPI automatically generates interactive documentation.

### Swagger UI

```text
http://127.0.0.1:8000/docs
```

### ReDoc

```text
http://127.0.0.1:8000/redoc
```

---

# ☁️ Azure Services

The application is designed to integrate seamlessly with Microsoft Azure.

- Azure SQL Database
- Azure App Service
- Azure Storage (Optional)
- Azure Resource Groups

---

# 🎯 Project Highlights

- Cloud-native backend architecture
- Secure database connectivity
- Modular FastAPI project structure
- ORM-powered database operations
- RESTful API design
- Environment-based configuration
- Azure cloud integration
- Scalable deployment workflow

---

# 📚 Learning Outcomes

This project demonstrates practical experience with:

- Cloud Computing using Microsoft Azure
- Backend API Development
- SQLAlchemy ORM
- Database Design
- FastAPI Framework
- Azure SQL Integration
- Environment Configuration
- Production Deployment

---

# 🚀 Future Improvements

- User Authentication & Authorization
- File Storage using Azure Blob Storage
- Print Job Prioritization
- Real-time Queue Updates
- Email Notifications
- Dashboard Analytics
- Docker Containerization
- CI/CD Pipeline Integration

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new feature branch

```bash
git checkout -b feature/your-feature
```

3. Commit your changes

```bash
git commit -m "Add your feature"
```

4. Push your branch

```bash
git push origin feature/your-feature
```

5. Open a Pull Request

---

# 📜 License

This project is licensed under the **MIT License**.

---

# 👨‍💻 Author

**Kaustubh Deshmane**

Passionate about building scalable cloud applications, backend systems, and modern software solutions.

---

# 📬 Contact

Feel free to reach out for collaboration, feedback, or project discussions.

**GitHub:** @KaustubhDeshmane

---

<div align="center">

### ⭐ If you found this project useful, consider giving it a star!

**Built with ❤️ by Kaustubh Deshmane**

</div>
