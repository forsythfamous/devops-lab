# DevOps Lab

A simple Node.js application containerized with Docker and automated using Makefile commands.

This repository serves as a hands-on DevOps learning project demonstrating:

- Docker containerization
- Makefile automation
- Git version control
- Application deployment workflows

---

## Project Structure

devops-lab/
├── app.js
├── Dockerfile
├── Makefile
└── README.md
```

---

## Technologies Used

- Node.js
- Docker
- Make
- Git
- GitHub
- Linux

---

## Prerequisites

Before running this project, ensure you have:

- Docker installed
- Git installed
- Make installed

Verify installations:

```bash
docker --version
git --version
make --version
```

---

## Build the Docker Image

```bash
docker build -t devops-lab .
```
Expected output:

```text
Successfully tagged devops-hello:latest
```
---

## Run the Application

```bash
docker run --rm devops-hello
```

Expected output:

```text
Hello, DevOps!
```

---

## Makefile Automation

Build the image:

```bash
make build
```

Run the container:

```bash
make run
```

Clean up resources:

```bash
make clean
```

> Available commands may vary depending on your Makefile configuration.

---

## Git Workflow Demonstrated

Stage changes:
- git add .

Commit changes:
- git commit -m "feat: bump to v2"

View commit history:
- git log --oneline

Example:
- ae24406 feat: bump to v2
- 3af1a33 Initial commit

---

## Learning Objectives

This project was created to practice:

- Writing Dockerfiles
- Building container images
- Running containers
- Automating repetitive tasks with Makefiles
- Managing source code with Git and GitHub

---

## Future Improvements

Planned enhancements include:

- Add GitHub Actions CI/CD pipeline
- Automated testing
- Docker Hub integration
- Azure Container Apps deployment
- Infrastructure as Code (IaC)
- Application monitoring and logging
- Security scanning

---

## Author

**Forsyth Famous**

GitHub: https://github.com/forsythfamous

---

## License

This project is intended for educational and demonstration purposes.
