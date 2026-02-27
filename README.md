# Afrishop - E-Commerce Platform

A comprehensive single-vendor e-commerce platform built with Vue.js (Frontend), Python Django (Backend), and PostgreSQL (Database).

## 🎯 Project Overview

Afrishop is an enterprise-grade e-commerce solution designed for African merchants to sell products online with advanced features including:

- 📦 Product Management & Inventory
- 🛒 Shopping Cart & Checkout
- 💳 Multiple Payment Gateway Integration
- 📊 Analytics & Reporting
- 👤 User Management & Authentication
- 📝 Order Management
- 📧 Email Notifications
- 🔐 Security & SSL
- 📱 Responsive Design
- 🌍 Multi-language Support

## 📁 Project Structure

```
afrishop/
├── frontend/              # Vue.js Frontend Application
├── backend/               # Django REST API
├── docs/                  # Documentation
├── docker/                # Docker Configuration
└── README.md
```

## 🛠 Technology Stack

- **Frontend**: Vue.js 3, Vuex, Vue Router, Axios
- **Backend**: Python 3.9+, Django 4.0+, Django REST Framework
- **Database**: PostgreSQL 13+
- **Authentication**: JWT (JSON Web Tokens)
- **Payment**: Stripe, PayPal, Flutterwave
- **Email**: SendGrid, SMTP
- **Hosting**: Docker, AWS/DigitalOcean
- **Analytics**: Google Analytics, Custom Dashboard

## 🚀 Quick Start

### Prerequisites
- Node.js 16+
- Python 3.9+
- PostgreSQL 13+
- Docker & Docker Compose (optional)

### Installation

#### Backend Setup
```bash
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

#### Frontend Setup
```bash
cd frontend
npm install
npm run serve
```

## 📚 Documentation

See [docs/](./docs/) directory for detailed documentation.

## 📝 License

MIT License

## 👤 Author

Joshua K. Paka