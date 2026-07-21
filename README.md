# 🚀 AI Synthetic Enterprise Data Generator

[![GitHub stars](https://img.shields.io/github/stars/vishakha2121/synthetic-data-ai-generator)](https://github.com/vishakha2121/synthetic-data-ai-generator/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/vishakha2121/synthetic-data-ai-generator)](https://github.com/vishakha2121/synthetic-data-ai-generator/network)
[![GitHub issues](https://img.shields.io/github/issues/vishakha2121/synthetic-data-ai-generator)](https://github.com/vishakha2121/synthetic-data-ai-generator/issues)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)

> An intelligent AI-powered synthetic data generator that creates realistic enterprise datasets while preserving privacy. Perfect for ML training, software testing, and development purposes.

---

## 📋 Table of Contents
- [🌟 Features](#-features)
- [📸 Screenshots](#-screenshots)
- [🛠️ Tech Stack](#️-tech-stack)
- [📁 Project Structure](#-project-structure)
- [🚀 Quick Start](#-quick-start)
- [📦 Installation](#-installation)
- [⚙️ Configuration](#️-configuration)
- [🔧 Usage](#-usage)
- [📊 Data Generation](#-data-generation)
- [🔐 Privacy Features](#-privacy-features)
- [🤖 AI Integration](#-ai-integration)
- [📈 Analytics Dashboard](#-analytics-dashboard)
- [🧪 Testing](#-testing)
- [📝 API Documentation](#-api-documentation)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [📞 Contact](#-contact)

---

## 🌟 Features

### 🔐 Privacy-Preserving
- **Differential Privacy** - Add controlled noise to protect individual records
- **Data Anonymization** - Remove or mask personally identifiable information
- **K-Anonymity** - Ensure each record is indistinguishable from at least k-1 others
- **GDPR Compliance** - Built-in compliance checking for data protection regulations
- **Privacy Score** - Real-time privacy metrics for generated datasets

### 🤖 AI-Powered Generation
- **Gemini AI Integration** - Smart data enhancement and validation
- **Natural Language Schema** - Generate schemas from text descriptions
- **Intelligent Suggestions** - AI-powered field recommendations
- **Pattern Recognition** - Detect and replicate data patterns
- **Data Validation** - Automatic data quality checks

### 📊 Data Types Supported
- **Personal Data** - Names, emails, phone numbers, addresses
- **Business Data** - Companies, departments, job titles
- **Financial Data** - Transactions, invoices, payment methods
- **Customer Data** - Profiles, preferences, behavior patterns
- **Product Data** - SKUs, descriptions, pricing, inventory
- **Time Series** - Dates, timestamps, sequential data
- **Geo Data** - Coordinates, cities, countries, regions
- **Custom Fields** - Any custom data type you need

### 🎨 Modern UI/UX
- **Beautiful Dashboard** - Real-time statistics and analytics
- **Drag-and-Drop** - Visual schema builder
- **Dark/Light Theme** - Toggle between themes
- **Responsive Design** - Works on all devices
- **Real-time Preview** - See data as it's generated
- **Export Options** - CSV, JSON, Excel, Parquet
- **Generation History** - Track all generations
- **Progress Tracking** - Real-time generation progress

### 📦 Export Formats
- CSV (Comma Separated Values)
- JSON (JavaScript Object Notation)
- Excel (XLSX)
- Parquet (Columnar Storage)
- SQL (Insert statements)

---

## 📸 Screenshots

### Dashboard View



---

## 🛠️ Tech Stack

### **Backend**
| Technology | Version | Purpose |
|------------|---------|---------|
| Python | 3.9+ | Core language |
| FastAPI | 0.104.1 | Web framework |
| SQLAlchemy | 2.0.23 | ORM |
| SQLite | 3.x | Database |
| Faker | 20.1.0 | Data generation |
| Pandas | 2.0.3 | Data manipulation |
| NumPy | 1.24.3 | Numerical computing |
| SciPy | 1.11.4 | Scientific computing |
| Cryptography | 41.0.7 | Security |
| Gemini AI | 0.3.0 | AI integration |

### **Frontend**
| Technology | Version | Purpose |
|------------|---------|---------|
| React | 18.2.0 | UI framework |
| Vite | 4.5.0 | Build tool |
| Tailwind CSS | 3.3.6 | Styling |
| Material-UI | 5.14.19 | Component library |
| React Router | 6.20.0 | Routing |
| React Query | 3.39.3 | State management |
| Recharts | 2.10.3 | Charts |
| Axios | 1.6.2 | HTTP client |
| React Hook Form | 7.48.2 | Form handling |

### **DevOps & Tools**
- Git & GitHub
- Docker (optional)
- VS Code
- Postman
- ESLint
- Prettier

---

## 📁 Project Structure



---

## 🚀 Quick Start

### **Prerequisites**
- Python 3.9 or higher
- Node.js 18 or higher
- npm or yarn
- Git
- Gemini API Key (for AI features)

### **Step 1: Clone Repository**
```bash
git clone https://github.com/vishakha2121/synthetic-data-ai-generator.git
cd synthetic-data-ai-generator

# Navigate to backend
cd backend

# Create virtual environment
python -m venv venv

# Activate virtual environment
# For Windows:
venv\Scripts\activate
# For Mac/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Set up environment variables
cp .env.example .env
# Edit .env and add your GEMINI_API_KEY

# Initialize database
python -m app.main

# Navigate to frontend (open new terminal)
cd frontend

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env

# Start development server
npm run dev