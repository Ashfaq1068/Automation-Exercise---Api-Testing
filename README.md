🧪 AutomationExercise API Testing Project
📌 Overview

This project is designed to test and validate the public APIs provided by AutomationExercise
.
It demonstrates structured API testing practices, covering both positive and negative scenarios, along with response validation, edge cases, and error handling.

The repository is built as part of my personal learning and portfolio to showcase API test automation skills.

✅ Features

Covers core AutomationExercise API endpoints:

GET /api/productsList → Fetch all products

GET /api/brandsList → Fetch all brands

POST /api/searchProduct → Search products by keyword

POST /api/verifyLogin → Validate user login credentials

POST /api/createAccount → Create new user account

PUT /api/updateAccount → Update existing account details

DELETE /api/deleteAccount → Delete user account

GET /api/getUserDetailByEmail → Get user details by email

Tests include:

Status code verification (200, 400, 404, 405, etc.)

Response body validation (keys, types, values)

Positive & negative scenarios

Edge cases (missing parameters, invalid data)

Chained flows (Register → Login → Update → Delete)

⚙️ Tech Stack

(adjust if needed depending on your implementation)

Language: Python / Java / JavaScript (your choice)

Testing Framework: Pytest / JUnit / Mocha

HTTP Client: Requests / RestAssured / Axios

Reporting: Allure / HTML reports (optional)

CI/CD: GitHub Actions (optional)

📂 Project Structure
/
├── tests/
│   ├── test_products.py
│   ├── test_brands.py
│   ├── test_search.py
│   ├── test_user_account.py
│   └── ...
├── utils/
│   ├── api_client.py
│   ├── schemas/
│   └── helpers.py
├── config/
│   ├── config.yaml
│   └── env.json
├── reports/
│   └── test-report.html
├── requirements.txt
├── README.md
└── .gitignore

🚀 How to Run

Clone the repository:

git clone <your-repo-url>
cd automationexercise-api-testing


Install dependencies:

pip install -r requirements.txt
# or npm install / mvn clean install depending on stack


Run the tests:

pytest -v
# or npm test / mvn test


Generate reports (if enabled):

allure serve reports/

📈 Future Enhancements

Add more negative & boundary test cases

Integrate reporting dashboards (Allure, HTML)

Configure CI/CD pipeline for automated runs

Implement data-driven testing

Explore performance testing of APIs

🙌 Credits

APIs provided by AutomationExercise

This project is for educational and portfolio purposes
