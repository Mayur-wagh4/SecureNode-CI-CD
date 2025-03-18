# SecureNode-CI-CD

## Overview
SecureNode-CI-CD is a **Node.js application** integrated with a **CI/CD pipeline** using **Jenkins, Docker, and GitHub Actions**. This project ensures automated builds, testing, and deployment in a **secure and scalable environment**.

## Features
- **Automated CI/CD pipeline** with Jenkins & GitHub Actions
- **Dockerized application** for consistent deployments
- **Security scanning** with OWASP ZAP & Trivy
- **Real-time monitoring** with Prometheus & Grafana

## Tech Stack
- **Node.js & Express.js** → Backend framework
- **Jenkins & GitHub Actions** → CI/CD automation
- **Docker & Docker Compose** → Containerization
- **Prometheus & Grafana** → Monitoring & visualization
- **SonarQube & Trivy** → Security & code quality analysis

## Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Mayur-wagh4/SecureNode-CI-CD.git
cd SecureNode-CI-CD
```

### 2️⃣ Install Node.js & Dependencies
```bash
sudo apt update && sudo apt install -y nodejs npm
type node -v  # Verify installation
npm install
```

### 3️⃣ Run the Application
```bash
node app.js
```

## Running with Docker Compose
For containerized deployment:
```bash
docker-compose up -d
```

## CI/CD Pipeline Setup

### **Jenkins Setup**
- Install Jenkins & required plugins (`Git`, `Docker Pipeline`, `NodeJS`)
- Configure `Jenkinsfile` in the repository
- Run pipeline to test, build, and deploy the application

### **GitHub Actions (CI/CD Alternative)**
- Modify `.github/workflows/pipeline.yml` to configure builds
- Push code to trigger automated deployments

## Usage
- **Access Application** → [http://localhost:3000](http://localhost:3000)
- **Check Logs** → `docker logs <container_name>`
- **Restart Service** → `docker restart <container_name>`

## Contributing
We welcome contributions! Feel free to **submit a pull request** or **open an issue** to improve the project.

## License
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

