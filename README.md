# Automated Web Testing Suite

This project is a simple functional test automation framework for both web UI and API testing, built using Java, Selenium WebDriver, TestNG, and Postman.

---

## Tools & Technologies

- **Java** – Core programming language for test logic  
- **Selenium WebDriver** – Browser automation for UI testing  
- **TestNG** – Test execution and reporting  
- **Postman** – REST API test execution  
- **Maven** – Project and dependency management  
- **ChromeDriver** – Chrome interface for Selenium WebDriver  

---

## Features

### UI Test Coverage:
- Login functionality
- Product search
- Cart and checkout flow

### API Validation:
- Sample API tests using Postman collections

### Test Reporting:
- TestNG logs and assertion validation
- Screenshot evidence for UI test results

---

## 🖼️ Screenshots

| Test Scenario | Screenshot |
|---------------|------------|
| Terminal Test Results | `screenshots\Terminal.results.png` |
| Text File Results | `screenshots\Textfile.results.png` |

---

## Project Structure

```
QA_Automated_Testing_Suite/
├── postman/
│   └── SampleAPITests.postman_collection.json
├── screenshots/
│   ├── Terminal.results.png
│   └── Textfile.results.png
├── src/
│   ├── main/java/com/example/pages/
│   │   ├── LoginPage.java
│   │   ├── SearchPage.java
│   │   └── CheckoutPage.java
│   └── test/java/com/example/tests/
│       ├── LoginTest.java
│       ├── SearchTest.java
│       └── CheckoutTest.java
├── pom.xml
└── README.md
```

---

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/gabrielf159/QA_Automated_Testing_Suite.git
   cd QA_Automated_Testing_Suite
   ```

2. **Run tests using Maven:**
   ```bash
   mvn clean test
   ```

3. **Open TestNG reports** and view screenshots in the `/screenshots` folder.

---

## Author

**Gabriel Flores**

---

## Notes

- Ensure ChromeDriver version matches your installed Chrome browser.  
- Postman collection is located in `/postman`. You can import and run it directly in Postman.
