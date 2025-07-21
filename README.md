# 📌 Cypress End-to-End Automation Framework with Page Object Model (POM)

## 🚀 Overview
This project is a **self-built Cypress automation framework** designed using the **Page Object Model (POM)** approach. It focuses on writing **clean, maintainable, and modular test scripts** using **fixtures**, **beforeEach() hooks**, and **custom Cypress commands**. Ideal for rapid UI testing, API interception, and integration with **CI/CD pipelines** for modern web applications.

---

## ⚙️ Tech Stack
- **Language:** JavaScript (ES6+)
- **Test Framework:** Cypress v12+
- **Design Pattern:** Page Object Model (POM)
- **Assertions:** Chai, Mocha
- **Test Data Management:** Fixtures (JSON files)
- **CI/CD Compatible:** Jenkins/GitHub Actions ready
- **Reporting:** Mochawesome / Allure (optional)

---

## ✅ Key Features
- ✅ **Page Object Model (POM)** for easy maintenance and scalability
- ✅ **Fixtures** for dynamic test data management
- ✅ **beforeEach() hooks** for proper pre-condition setup
- ✅ **Reusable custom commands** for common actions (`cypress/support/commands.js`)
- ✅ **Headless and GUI execution**
- ✅ **Parallel Execution Ready** with Cypress Dashboard (optional)
- ✅ **CI/CD Pipeline Compatible**

---

## 📁 Project Folder Structure
```
cypress/
 ├── fixtures/                 # Test data (userData.json, credentials.json)
 ├── integration/              # Test cases
 │    ├── login.spec.js
 │    └── dashboard.spec.js
 ├── pages/                    # POM files
 │    ├── LoginPage.js
 │    └── DashboardPage.js
 ├── support/
 │    ├── commands.js          # Custom Cypress commands
 │    └── index.js
 └── plugins/
      └── index.js
cypress.json                    # Cypress configuration
package.json                    # NPM project setup
```

---

## 🟣 How to Run

### 🖥️ Install dependencies
```
npm install
```

### ▶️ Run tests in headed mode (Cypress GUI)
```
npx cypress open
```

### 🚀 Run tests in headless mode
```
npx cypress run
```

---

## 📝 Reporting (Optional)
- Install and configure **Mochawesome** for beautiful HTML reports:
```
npm install --save-dev mochawesome mochawesome-merge mochawesome-report-generator
```

---

## 💡 What I Learned
- Mastered **POM architecture** in Cypress
- Learned advanced **fixture data management**
- Implemented **beforeEach() hooks** for reusable setup flows
- Enhanced understanding of **custom command creation**
- Practiced **writing clean, maintainable test suites** suitable for real-world projects

---

## 📌 Why This Project?
This project demonstrates my practical knowledge of **real-time Cypress automation frameworks**. It showcases my ability to design **modular, scalable, and CI/CD-friendly test solutions**, ready for remote QA/SDET roles.

---

## 📎 Repository Link
📂 [GitHub Repository](https://github.com/princu2701/PROJECT_CYPRESS-01)

