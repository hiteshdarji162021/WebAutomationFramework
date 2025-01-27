# Web Automation Framework

This repository contains a **Web Automation Framework** built with **Selenium**, **Java**, **TestNG**, **Selenium Grid**, and **Docker**. It is designed for efficient and scalable automated testing of web applications.

---

## ✨ Key Features

- ✅ Cross-browser testing with Selenium WebDriver.
- ✅ Parallel test execution using Selenium Grid.
- ✅ Dockerized setup for easy environment management.
- ✅ Modular design with Page Object Model (POM).
- ✅ Configurable through property files.

---

## 📋 Prerequisites

1. **Java JDK** (8 or higher)  
2. **Maven** (for dependencies)  
3. **Docker** (for Selenium Grid setup)

---

## 🚀 How to Use

### 1️⃣ Clone the Repository
bash
git clone https://github.com/your-repo-name.git
cd your-repo-name

### 2️⃣ Start Selenium Grid with Docker
bash
Copy
Edit
docker-compose up

### 3️⃣ Configure Test Settings
Update the config.properties file for:

Browser type
Selenium Grid URL
Test data paths

### 4️⃣ Run Tests
Execute tests using Maven:

bash
Copy
Edit
mvn test

### 📊 Reports
After execution, detailed reports are available in the test-output folder.

### 🗂️ Folder Structure
The project structure is as follows:

src/ ├── main/ │ ├── base/ # Base classes │ ├── pages/ # Page Object Models (POM) │ └── utils/ # Utility functions ├── test/ │ ├── tests/ # Test cases │ └── data/ # Test data ├── docker-compose.yml # Selenium Grid Docker setup ├── config.properties # Configuration file └── README.md # Project documentation

### 💬 Contact
For queries or issues, feel free to create an issue or reach out to:
📧 Email: your-email@example.com

Enjoy using the framework! 🚀

