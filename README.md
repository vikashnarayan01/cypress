# Cypress Test Automation Project  

## 📌 Overview  
This project uses [Cypress](https://www.cypress.io/) for end-to-end (E2E) testing of web applications. 
It provides fast, reliable, and easy-to-write tests with built-in capabilities for UI and API testing.  

## 🛠️ Tech Stack  
- **Test Framework:** Cypress  
- **Language:** JavaScript
- **Assertions:**  Mocha  
- **CI/CD Support:** GitHub Actions, Jenkins

## 🚀 Setup Instructions  

### 1️⃣ Prerequisites  
Ensure you have the following installed:  
- [Node.js](https://nodejs.org/) (LTS recommended)  
- npm (comes with Node.js) or yarn  

### 2️⃣ Install Dependencies  
npm install

### Run Cypress UI Test Runner
npx cypress open
npx cypress run
npx cypress run --browser chrome

### Debugging Tips
Use cy.pause() to stop test execution at a specific step.

Use cy.screenshot() for capturing snapshots.

Run tests with DEBUG=cypress:* npx cypress open for detailed logs.

