
# CI/CD Final Project ⚙️

This project was created as part of the **"CI/CD Tools and Practices"** course in the IBM DevOps and Software Engineering Professional Certificate.

## 🚧 Objective
To implement a working **CI/CD pipeline** using industry-standard tools. The project automates the build, test, and deploy stages using GitHub Actions and Docker.

## 🧰 Tech Stack
- GitHub Actions (CI/CD workflow)
- Docker
- Python 3.9
- Makefile
- Bash scripting

## 🔁 Pipeline Overview
The pipeline performs:
- Code linting and style checks
- Unit testing
- Build and push of Docker images
- Deployment simulation

CI/CD logic is configured in `.github/workflows/ci.yml`.

## 🚀 Getting Started
```
git clone https://github.com/StivenHenao/ci-cd-final-project.git
cd ci-cd-final-project
```

# Setup environment
```
bash bin/setup.sh
```
## 📁 Project Layout
```
├── bin/
│   └── setup.sh
├── service/
├── .github/workflows/
│   └── ci.yml
├── Dockerfile
├── Makefile
```
## 📄 License
Apache 2.0

## Author
Skills Network
