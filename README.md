 Automated Web Testing Suite

This is a simple automated testing framework built for UI and API validation using modern QA tools and practices. It demonstrates proficiency in test automation with Selenium WebDriver and TestNG, and includes REST API testing via Postman collections.

---

Tools & Technologies

- **Java** – Core test logic and framework
- **Selenium WebDriver** – UI automation for web applications
- **TestNG** – Test management and reporting
- **Postman** – REST API testing with collections
- **Maven** – Build and dependency management
- **ChromeDriver** – WebDriver interface for Google Chrome

---

 Features

- **UI Tests**
  - Login functionality
  - Product search validation
  - Shopping cart and checkout process
- **API Tests**
  - Sample REST endpoint validation using Postman
- **Robust Reporting**
  - TestNG logs and assertions
  - Screenshot capture for test result evidence

---

Test Case(s)

| Test Case       | Screenshot |
|-----------------|------------|
| Login Test      | 
| Search Test     |
| Checkout Test   |
| All 3 (above)   | (from terminal) (screenshots/Terminal.results.png)  |
                  | (from TextFile) (screenshots/Textfile.results.png)  |


---

Project Structure

QA_Automated_Testing_Suite/
├── postman/
│ └── SampleAPITests.postman_collection.json
├── screenshots/
│ ├── Terminal.results.png
│ ├── Textfile.results.png
├── src/
│ ├── main/java/com/example/pages/
│ │ ├── LoginPage.java
│ │ ├── SearchPage.java
│ │ └── CheckoutPage.java
│ └── test/java/com/example/tests/
│ ├── LoginTest.java
│ ├── SearchTest.java
│ └── CheckoutTest.java
├── pom.xml
└── README.md

Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/QA_Automated_Testing_Suite.git
   
Set up the ChromeDriver path if necessary.

Run tests using:

mvn clean test

Import SampleAPITests.postman_collection.json into Postman and execute the API suite.

Author
Gabriel Flores
