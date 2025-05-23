# Amazon Regression Framework 
This is a Selenium Test Automation Framework for performing regression testing on Amazon India website using:
- Selenium WebDriver
- TestNG
- Maven
- Page Object Model (POM)

## Project Structure
AmazonRegressionFramework/
├── src/
│   ├── main/
│   │   └── java/pages/          # Page classes
│   └── test/
│       └── java/tests/          # TestNG test classes
├── pom.xml                      # Maven dependencies and configuration
├── testng.xml                   # TestNG suite definition

## Setup Instructions
### 1. Clone the repo

```bash
git clone https://github.com/YOUR_USERNAME/AmazonRegressionFramework.git
cd AmazonRegressionFramework
```

### 2. Install Dependencies

Make sure you have:
- JDK 8 or above
- Maven installed (`mvn -v` to verify)

Then install dependencies:

```bash
mvn clean install
```

### 3. Update WebDriver Path

In `AmazonRegressionTests.java`, update:

java
System.setProperty("webdriver.chrome.driver", "path/to/chromedriver");

### 4. Run Tests
mvn test

##  Features

- Automated regression tests for login, search, add to cart, and checkout
- Page Object Model design pattern
- TestNG-based execution with parallel test configuration
- Easily extendable with new test cases and pages

This project is for educational/demo purposes.

