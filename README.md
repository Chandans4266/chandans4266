# 👋 Hi, I'm Chandan Kumar

## 🚀 QA Automation Tester | Software Testing | Web Automation

Welcome to my GitHub profile! 👋

I'm a **QA Automation Tester** passionate about software quality, test automation, and building maintainable automation frameworks.

I have experience in **Web Application Testing, Functional Testing, Regression Testing, UI Testing, and Test Automation**. I enjoy learning new automation technologies and applying them through practical projects.

Currently, I'm strengthening my skills in **Playwright with JavaScript**, while continuing to build my knowledge of API automation and modern automation frameworks.

---

# 👨‍💻 About Me

* 🔍 QA Automation Tester with experience in Web Application Testing
* 🧪 Interested in building reliable and maintainable automation frameworks
* 🌐 Experienced in UI and functional testing
* 🎭 Currently working with Playwright and JavaScript
* ☕ Working with Java and Selenium WebDriver
* 📋 Experience with TestNG and Page Object Model
* 🐞 Experience with defect tracking and test management tools
* 📚 Continuously learning modern QA automation technologies
* 🚀 Interested in improving test coverage and reducing repetitive manual testing

---

# 🛠️ Technical Skills

## 💻 Programming Languages

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge\&logo=openjdk\&logoColor=white)

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge\&logo=javascript\&logoColor=black)

---

## 🧪 Automation Testing

![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge\&logo=selenium\&logoColor=white)

![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge\&logo=playwright\&logoColor=white)

### Selenium

* Selenium WebDriver
* Browser automation
* Web element identification
* Locators
* Waits
* Actions
* Page Object Model
* TestNG integration
* Screenshots
* Reusable automation components

### Playwright

* Playwright Test
* Page Object Model
* Locators
* Assertions
* Browser automation
* Cross-browser testing
* File uploads
* Test execution
* Test reports
* Debugging
* Reusable page classes

---

# 🧰 Testing Frameworks

### TestNG

* Test annotations
* Assertions
* Test suites
* TestNG XML
* Test execution
* Data-driven testing
* Test organization

---

# 🌐 API Testing

![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge\&logo=postman\&logoColor=white)

Currently learning and improving my knowledge of:

* API testing
* REST APIs
* HTTP methods
* GET
* POST
* PUT
* PATCH
* DELETE
* Status codes
* Request parameters
* Headers
* JSON response validation
* Postman
* REST Assured

---

# 📋 Testing Skills

I have experience and interest in different areas of software testing:

* ✅ Functional Testing
* ✅ Regression Testing
* ✅ Smoke Testing
* ✅ Sanity Testing
* ✅ UI Testing
* ✅ Web Application Testing
* ✅ Cross-Browser Testing
* ✅ Integration Testing
* ✅ Test Case Design
* ✅ Test Execution
* ✅ Defect Reporting
* ✅ Bug Verification
* ✅ Retesting
* ✅ Exploratory Testing

---

# 🏗️ Automation Framework Concepts

I'm interested in designing automation frameworks that are:

* Maintainable
* Reusable
* Scalable
* Easy to understand
* Easy to debug

### Concepts I work with

```text
Page Object Model
       ↓
Reusable Page Classes
       ↓
Test Classes
       ↓
Test Data
       ↓
Assertions
       ↓
Reports
```

---

# 📂 Featured Automation Projects

## 🎭 Playwright Automation Framework

**Technology:** JavaScript + Playwright

This project focuses on building a reusable Playwright automation framework.

### Features

* Page Object Model
* Login automation
* Reusable locators
* Test assertions
* Cross-browser testing
* File upload automation
* Test reports
* Debugging
* Test organization

### Example structure

```text
Playwright_Framework
│
├── pages
│   └── LoginPage.js
│
├── tests
│   └── login.spec.js
│
├── test-data
│
├── playwright.config.js
│
├── package.json
│
└── README.md
```

---

# 🔐 Example Playwright POM

```javascript
import { test } from '@playwright/test';
import { LoginPage } from '../pages/LoginPage';

test('Login Test', async ({ page }) => {

    await page.goto(
        'https://opensource-demo.orangehrmlive.com/web/index.php/auth/login'
    );

    const loginPage = new LoginPage(page);

    await loginPage.login('Admin', 'admin123');

});
```

### Page Object

```javascript
export class LoginPage {

    constructor(page) {

        this.page = page;

        this.username = page.getByPlaceholder('Username');

        this.password = page.getByPlaceholder('Password');

        this.loginButton =
            page.getByRole('button', { name: 'Login' });
    }

    async login(username, password) {

        await this.username.fill(username);

        await this.password.fill(password);

        await this.loginButton.click();
    }
}
```

---

# ☕ Selenium Automation

I also work with Java and Selenium WebDriver.

### Areas of practice

```text
Java
  ↓
Selenium WebDriver
  ↓
Page Object Model
  ↓
TestNG
  ↓
Assertions
  ↓
Reports
```

---

# 🐞 Defect Management

I have experience working with defect and test management tools.

### Tools

* Jira
* Zephyr Scale
* Confluence

### Defect lifecycle

```text
New
 ↓
Assigned
 ↓
In Progress
 ↓
Fixed
 ↓
Retest
 ↓
Verified
 ↓
Closed
```

---

# 🔄 Typical Automation Workflow

My approach to automation generally follows:

```text
Requirement Analysis
        ↓
Test Scenario Identification
        ↓
Test Case Creation
        ↓
Automation Feasibility
        ↓
Framework / POM
        ↓
Script Development
        ↓
Execution
        ↓
Failure Analysis
        ↓
Defect Reporting
        ↓
Fix Verification
        ↓
Regression Testing
```

---

# 📚 Currently Learning

I'm continuously improving my automation skills.

### 🎭 Playwright

* Advanced locators
* Fixtures
* Hooks
* Parameterization
* Page Object Model
* API testing with Playwright
* Parallel execution
* Reports
* CI/CD integration

### 🌐 API Automation

* Postman
* REST Assured
* JSON validation
* API automation framework

### 🥒 BDD

* Cucumber
* Feature files
* Gherkin
* Step definitions

### ⚙️ CI/CD

* Git
* GitHub
* GitHub Actions
* Continuous testing

---

# 🧠 JavaScript Practice

I regularly practice JavaScript fundamentals required for automation.

### Topics

* Variables
* Data types
* Arrays
* Strings
* Loops
* Functions
* Objects
* Array methods
* `map()`
* `filter()`
* `reduce()`
* `includes()`
* `indexOf()`
* `push()`
* Promises
* Async/Await

Example:

```javascript
let arr = [2, 3, 4, 5, 6, 7, 8, 2, 3, 4];

let unique = [];

for (let i = 0; i < arr.length; i++) {

    if (!unique.includes(arr[i])) {
        unique.push(arr[i]);
    }
}

console.log(unique);
```

---

# 🔧 Tools & Technologies

| Category        | Tools                   |
| --------------- | ----------------------- |
| Programming     | Java, JavaScript        |
| UI Automation   | Selenium, Playwright    |
| Test Framework  | TestNG, Playwright Test |
| API Testing     | Postman, REST Assured   |
| Test Management | Zephyr Scale            |
| Defect Tracking | Jira                    |
| Documentation   | Confluence              |
| Version Control | Git, GitHub             |
| IDE             | Visual Studio Code      |
| Browsers        | Chrome, Firefox, Edge   |
| Methodology     | Agile / Scrum           |

---

# 📊 Testing Approach

I focus on creating automation that provides:

### 🔹 Reliability

Tests should produce consistent and meaningful results.

### 🔹 Maintainability

Using reusable components and Page Object Model to reduce duplication.

### 🔹 Readability

Writing test scripts that are easy for other team members to understand.

### 🔹 Reusability

Common actions should be written once and reused across multiple tests.

### 🔹 Debuggability

Test failures should provide enough information to identify the problem quickly.

---

# 🎯 Career Goal

My goal is to grow as a **QA Automation Engineer / SDET** by developing strong skills in:

```text
Java
  +
Selenium
  +
JavaScript
  +
Playwright
  +
API Automation
  +
CI/CD
  +
Automation Framework Design
```

I aim to contribute to projects where quality engineering, automation, and continuous improvement are important parts of the development process.

---

# 📈 My Learning Journey

```text
Manual Testing
      ↓
Web Application Testing
      ↓
Java
      ↓
Selenium
      ↓
TestNG
      ↓
Page Object Model
      ↓
JavaScript
      ↓
Playwright
      ↓
API Testing
      ↓
CI/CD
      ↓
Advanced Automation
```

---

# 🤝 Let's Connect

I'm always interested in connecting with other QA professionals, automation engineers, and developers.

### 💼 LinkedIn

[Connect with me on LinkedIn](https://www.linkedin.com/)

### 📧 Email

**[your-email@example.com](mailto:your-email@example.com)**

---

# ⭐ Thanks for Visiting!

Thanks for visiting my GitHub profile.

Feel free to explore my repositories and automation projects.

If you find something useful, ⭐ a repository and follow my learning journey!

---

### 🚀 Keep Learning • Keep Testing • Keep Automating

> **Quality is everyone's responsibility.**

