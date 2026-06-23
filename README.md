# ☁️ Cloud Print Queue System

A cloud-enabled print queue management system built with **FastAPI**, **Azure SQL Database**, and **SQLAlchemy**. The application allows users to upload documents, manage print jobs, and maintain a centralized print queue through a scalable cloud-based architecture.

---

## 🚀 Features

### 📄 Print Job Management

* Upload documents for printing
* Create and manage print jobs
* Track print queue status
* View job history

### ☁️ Cloud Integration

* Azure SQL Database integration
* Cloud-hosted backend services
* Centralized data management
* Scalable deployment architecture

### 🔐 Secure Configuration

* Environment variable based configuration
* Secure database connectivity
* Isolated application settings

### ⚡ REST API

* FastAPI-powered backend
* Lightweight and high-performance API
* Easy integration with frontend applications
* Interactive API documentation

---

## 🛠️ Technology Stack

| Technology          | Purpose                   |
| ------------------- | ------------------------- |
| Python              | Backend Development       |
| FastAPI             | REST API Framework        |
| SQLAlchemy          | ORM & Database Operations |
| Azure SQL Database  | Cloud Database            |
| Uvicorn             | ASGI Server               |
| HTML/CSS/JavaScript | Frontend Interface        |
| Azure               | Cloud Platform            |

---

## 📂 Project Structure

```text
CloudPrintSystem
│
├── app/
├── static/
├── templates/
├── migrations/
├── .github/
├── requirements.txt
├── .env.example
├── README.md
└── main.py
```

---

## ⚙️ Installation

### Prerequisites

* Python 3.10+
* Azure SQL Database
* Git

### Clone Repository

```bash
git clone https://github.com/KaustubhDeshmane/CloudPrintSystem.git
cd CloudPrintSystem
```

### Create Virtual Environment

```bash
python -m venv venv
```

#### Windows

```bash
venv\Scripts\activate
```

#### Linux / macOS

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Configure Environment Variables

Create a `.env` file using `.env.example` as a reference.

```env
DB_SERVER=your_server
DB_NAME=your_database
DB_USERNAME=your_username
DB_PASSWORD=your_password
```

### Run Application

```bash
uvicorn main:app --reload
```

Application will be available at:

```text
http://127.0.0.1:8000
```

---

## 📖 API Documentation

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

## ☁️ Azure Deployment

This project is designed to be deployed on Azure services and integrates with:

* Azure SQL Database
* Azure App Service
* Azure Storage (optional)
* Azure Resource Groups

---

## 🎯 Learning Outcomes

This project demonstrates:

* Cloud Application Development
* Database Design & Integration
* REST API Development
* Environment Configuration Management
* Azure Cloud Services
* ORM using SQLAlchemy
* Full-Stack Application Architecture

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Kaustubh Deshmane**

---

### ⭐ If you found this project useful, consider giving it a star!

*Code. Create. Innovate.*
