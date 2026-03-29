# rust-rest-api-1

> Rust REST API 1: Blazing-fast REST API with Axum, SQLx, JWT, and PostgreSQL

## ✨ Features
- JWT authentication with access + refresh tokens
- Role-based access control (admin/user)
- Full CRUD with pagination, search, and filtering
- Premium responsive UI with dark/light mode
- Real-time validation and error handling
- Docker Compose for one-command startup
- Comprehensive README with API documentation
- Database migrations with Alembic/Flyway

## 🧰 Tech Stack
Rust, Axum, SQLite, Rusqlite

## 🏗️ Architecture
Three-tier architecture: Rust, Axum backend, native frontend, PostgreSQL database. Containerized with Docker.

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/rust-rest-api-1
cd rust-rest-api-1

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
