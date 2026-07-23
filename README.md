<p align="center">
  <img src="plagiarism_checker_app/public/assets/images/logo-icon.svg" alt="Plagiarism Checker System" width="140" />
</p>

<h1 align="center">Plagiarism Checker System</h1>

<p align="center">
  A plagiarism detection system built with Flask and Docker, using embedding comparison and Milvus vector search to process and compare text-based documents.
</p>

## ✨ Features

- **Document processing** — uploads and processes text-based documents
- **Plagiarism detection** — detects similarities through embedding comparison
- **Vector search** — uses Milvus for efficient similarity searches
- **Admin and user interfaces** — provides separate interfaces for administrators and general users
- **Containerized setup** — runs the complete system with Docker Compose
- **Database management tools** — includes phpMyAdmin and Milvus management interfaces

## 🧰 Tech Stack

Flask · Laravel · MySQL · Milvus · Docker · Docker Compose · phpMyAdmin · Attu

## Prerequisites

- [Docker](https://docs.docker.com/get-docker/)
- Docker Compose

## Quick Start

```bash
# 1. Clone the repository
git clone https://github.com/your-repo/plagiarism_checker_system.git
cd plagiarism_checker_system

# 2. Build and start the application
docker compose up -d --build
```

The command builds and starts all required services.

## Included Services

| Service | Purpose |
| --- | --- |
| **Flask backend** | Processes requests and plagiarism detection operations |
| **Laravel frontend** | Provides the admin and user interfaces |
| **MySQL** | Stores application data |
| **Milvus** | Stores embeddings and performs vector similarity searches |
| **phpMyAdmin** | Provides a web interface for MySQL management |
| **Attu** | Provides a web interface for Milvus management |

## Accessing the Application

| Interface | URL | Description |
| --- | --- | --- |
| **Admin Panel** | [http://localhost:8000/admin/login](http://localhost:8000/admin/login) | Admin login interface |
| **User Login** | [http://localhost:8000/user/login](http://localhost:8000/user/login) | General user login |
| **phpMyAdmin** | [http://localhost:8383](http://localhost:8383) | MySQL database management |
| **Attu Console** | [http://localhost:3000](http://localhost:3000) | Milvus vector database web UI |
| **Milvus Console** | [http://localhost:9091/webui/](http://localhost:9091/webui/) | Milvus vector database web UI |

### Admin Account

| Role | Email | Password |
| --- | --- | --- |
| Admin | `admin@gmail.com` | `123123` |

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.
