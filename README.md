# Automated Web Testing Suite

This project is an automated testing framework designed for web UI and API testing using:
- **Selenium WebDriver** for UI automation
- **Java** for core test logic
- **TestNG** for test management and reporting
- **Postman** for API validation

## Features
- UI Tests: Simulates login, search, and checkout functionality
- API Tests: Validates REST API endpoints via Postman collections
- Logging and reporting through TestNG

## Structure
```
src/
├── main/
│   └── java/
│       └── com/example/pages/
│           └── LoginPage.java, SearchPage.java, CheckoutPage.java
├── test/
│   └── java/
│       └── com/example/tests/
│           └── LoginTest.java, SearchTest.java, CheckoutTest.java
resources/
└── testdata/
postman/
└── SampleAPITests.postman_collection.json
```

## Setup
1. Clone the repository.
2. Import into IntelliJ or Eclipse.
3. Install dependencies (Selenium, TestNG).
4. Run TestNG suite from your IDE.

## Postman
Use the included `SampleAPITests.postman_collection.json` to run example REST API tests.

---
Created by Gabriel Flores.
