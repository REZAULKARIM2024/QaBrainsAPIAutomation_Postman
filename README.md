# QaBrainsAPIAutomation_Postman
API Test Automation Framework

A comprehensive API automation framework built using Postman to validate RESTful services of the QaBrains platform. This project demonstrates modern API testing practices, focusing on scalability, maintainability, and real-world validation scenarios.

🚀 Overview

QaBrainsAPIAutomation_Postman is designed to test and validate backend services of the QaBrains ecosystem. It covers essential API workflows such as authentication, CRUD operations, and response validation, ensuring reliability and consistency across services.

This framework simulates real-world API interactions and verifies request-response behavior, making it ideal for QA engineers aiming to strengthen API automation skills.

🛠️ Tech Stack
API Testing Tool: Postman
Automation: Postman Collection Runner
Scripting Language: JavaScript (Postman Scripts)
CI/CD Integration: Newman (CLI Runner)
Reporting (Optional): Newman HTML / Allure Reports
📁 Project Structure
QaBrainsAPIAutomation_Postman/
│
├── collections/        # Postman collection files (API requests)
├── environments/       # Environment variables (dev/test configs)
├── test-data/          # JSON data files for data-driven testing
├── reports/            # Generated test reports (optional)
└── README.md           # Project documentation
🎯 Test Coverage
🔐 Authentication APIs
Login / Token generation
Authorization validation
📦 CRUD Operations
Create, Read, Update, Delete endpoints
Status code and response validation
🔎 Response Validation
JSON schema validation
Key/value assertions
Data consistency checks
⚠️ Negative Testing
Invalid inputs
Unauthorized access
Error handling validation
🔄 End-to-End API Flows
Chained requests using variables
Dynamic data extraction and reuse
⚙️ Framework Highlights

✔️ Organized Postman Collections for modular testing
✔️ Environment-based configuration (Dev/Test)
✔️ Dynamic variables and chaining of requests
✔️ Pre-request & Test scripts for validation logic
✔️ Data-driven testing using JSON files
✔️ Newman CLI integration for automation
✔️ CI/CD ready framework

▶️ Running the Tests
Using Postman
Import the collection and environment files
Select the desired environment
Run using Collection Runner
Using Newman (CLI)

Install Newman:

npm install -g newman

Run tests:

newman run collections/QaBrains_API_Collection.json \
-e environments/QaBrains_Env.json
Generate HTML Report (Optional)
newman run collection.json -r html
📌 Prerequisites
Postman installed
Node.js (for Newman)
Basic knowledge of REST APIs
Access to QaBrains API endpoints
📈 Future Enhancements
Integrate advanced reporting (Allure / Extent-style reports)
Add CI/CD pipeline (GitHub Actions / Jenkins)
Implement advanced schema validation
Add environment-based test execution (multi-env support)
Integrate with cloud API testing tools
Enhance data-driven testing with external sources
🤝 Contribution

Contributions are welcome!
Feel free to fork the repository, create feature branches, and submit pull requests.

👨‍💻 Author

Rezaul Karim
Software QA Engineer | API & UI Automation | Manual Testing

📄 Summary

QaBrainsAPIAutomation_Postman is a practical, industry-oriented API automation project that showcases strong backend testing capabilities using Postman. It reflects best practices in API validation, automation scripting, and scalable test design—making it a valuable addition to any QA portfolio.
