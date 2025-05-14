```markdown
# OrangeHRM Automation Testing with Cypress (POM)

This project demonstrates automation testing on the OrangeHRM demo site using **Cypress** applying **Page Object Model (POM)** structure.

---

## 🚀 Tech Stack
- Cypress (E2E Testing Framework)
- JavaScript (ES6)
- Page Object Model (POM) structure

---

## 🌐 Tested Website
- [OrangeHRM Demo](https://opensource-demo.orangehrmlive.com/)

---

## 🗂 Project Structure

```

cypress/
├── e2e/
│   └── login_test.cy.js     # Login testing using POM
├── support/
│   ├── pages/
│   │   └── LoginPage.js         # Login Page Object Model (POM)

````

---

## ⚙ Installation Steps

1. Clone the repository:
```bash
git clone https://github.com/elfathin777/Cypress-POM.git
````

2. Install dependencies:

```bash
npm install
```

3. Run Cypress in interactive mode:

```bash
npx cypress open
```


---

## ✅ Test Cases Covered

| TC ID      | Description                            | Expectation          |
| ---------- | -------------------------------------- | -------------------- |
| TC.Log.001 | Login with valid username and password | Dashboard visible    |
| TC.Log.002 | Invalid username and invalid password  | Invalid credentials  |
| TC.Log.003 | Invalid username and valid password    | Invalid credentials  |
| TC.Log.004 | Valid username and invalid password    | Invalid credentials  |
| TC.Log.005 | Lowercase username and valid password  | Invalid credentials  |
| TC.Log.006 | Valid username and uppercase password  | Invalid credentials  |
| TC.Log.007 | Empty username and password fields     | Required error shown |
| TC.Log.008 | Empty username and valid password      | Required error shown |
| TC.Log.009 | Valid username and empty password      | Required error shown |

---

## 📸 Auto Screenshot on Failure

Screenshots will automatically be taken:

* After each test.
* On test failure.

You can find the screenshots in:

```
cypress/screenshots/
```

---

## 💡 Best Practices Used

* Clean POM structure.
* Centralized page interaction logic.
* Custom error checking & screenshots.
* Modular and maintainable approach.

---

## ✨ Author

* Haruna Elfathin
