# 🐳 WordPress Deployment with Docker Compose

A containerized setup for running **WordPress**, **MySQL**, and **phpMyAdmin** locally using Docker Compose.

---

## 🛠️ Tech Stack & Services

This setup orchestrates three separate containers:
* **WordPress**: The primary CMS application container running on port `8000`.
* **MySQL**: Database container configured with persistent storage.
* **phpMyAdmin**: Web-based database management tool running on port `8080`.

---

## 🚀 Getting Started

### Prerequisites
* [Docker](https://www.docker.com/) installed on your machine.
* [Docker Compose](https://docs.docker.com/compose/) installed.

### Installation & Run

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/mostafaAli-17/Docker-Compose.git](https://github.com/mostafaAli-17/Docker-Compose.git)
   cd Docker-Compose
2. ###Start the containers
  docker compose up -d
3.Access the applications:
​🌐 WordPress Site: http://localhost:8000
​🗄️ phpMyAdmin Console: http://localhost:8080
