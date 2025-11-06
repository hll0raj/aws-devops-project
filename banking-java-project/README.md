# 💳 Java Banking System

A console-based Java application simulating a basic banking system with features like account creation, deposit, withdrawal, and balance inquiry. Now extended with Docker and Jenkins pipeline support to showcase DevOps skills.

---

## 📌 Features

- 🔐 User login and account creation
- 💰 Deposit and withdraw funds
- 📊 Check account balance
- 🧾 Transaction history
- ⚙️ Admin operations (optional)

---

## 🛠️ Technologies Used

- Java (OpenJDK 11)
- Maven (build tool)
- Docker (containerization)
- Jenkins (CI/CD pipeline)
- Git & GitHub

---

## 🐳 Docker Support

You can build and run this app using Docker:

```bash
mvn clean package
docker build -t java-banking-app .
docker run -p 8064:8064 java-banking-app
This project includes a Jenkinsfile to automate:

    ✅ Checkout source code

    ✅ Maven build

    ✅ Docker build and run

    You can set this up on a local Jenkins server or Jenkins on EC2.
Project structure
.
├── src/                     # Java source code
├── pom.xml                 # Maven config
├── Dockerfile              # Container definition
├── Jenkinsfile             # CI/CD pipeline
├── README.md               # Project documentation
└── ansible-playbook.yml    # (Optional) Infrastructure automation
Author

Rajnish kumar
AWS Certified Solutions Architect
