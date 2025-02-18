# Bank with Encryption Project

## 📌 Project Overview
This project is a **secure banking application** implementing **authentication, encryption, and user management**. It includes administrative controls, encrypted transactions, and secure user authentication.

## 🚀 Getting Started

### 📋 Prerequisites
Ensure you have the following installed:
- Python 3.x
- PostgreSQL or MySQL (for database management)
- Virtual environment (optional but recommended)

Install dependencies using:
```sh
pip install -r requirements.txt
```

### 🔧 Installation
Clone the repository:
```sh
git clone https://github.com/your_username/Bank-with-encryption.git
cd Bank-with-encryption
```

## 🏗 Project Structure
```
Bank-with-encryption/
│── entrypoint.py             # Application entry point
│── requirements.txt          # Required dependencies
│── config/                   # Configuration files for different environments
│   ├── dev.py
│   ├── prod.py
│   ├── testing.py
│── app/
│   ├── models.py             # Database schema
│   ├── auth/                 # Authentication logic
│   │   ├── routes.py
│   │   ├── forms.py
│   ├── admin/                # Admin panel
│   │   ├── routes.py
│   │   ├── forms.py
│   ├── public/               # Public-facing routes
│   ├── common/               # Shared utilities (encryption, mail services)
│── migrations/               # Database migration scripts
│── Memoria 1º parte.docx      # Project documentation (part 1)
│── Memoria 2º parte.docx      # Project documentation (part 2)
│── CHANGELOG.md              # Project change log
```

## 🎯 Usage

### Running the Application
To start the application in a development environment:
```sh
python entrypoint.py
```

### Running Database Migrations
```sh
alembic upgrade head
```

## ✅ Testing
Run tests using:
```sh
pytest app/tests/
```

## 🛠 Built With
- **Python 3**
- **Flask** - Web framework
- **SQLAlchemy** - ORM for database management
- **Alembic** - Database migration tool
- **PostgreSQL / MySQL** - Database backend
- **bcrypt** - Password hashing

## 🤝 Contributing
If you wish to contribute, feel free to fork the repository, make improvements, and submit a pull request.

---

