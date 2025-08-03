# Playwright
🧪 Playwright Automation with Python
This project uses Playwright with Python to perform fast, reliable, and cross-browser end-to-end testing for modern web applications.

🚀 Features
Cross-browser automation (Chromium, Firefox, WebKit)

Headless & headed mode execution

Fast execution with auto-wait and smart assertions

Page Object Model (POM) support for maintainability

Supports screenshots, tracing, and video recording for debugging

Easy integration with CI/CD pipelines

🛠️ Technology Stack
Language: Python 3.7+

Framework: Playwright for Python

Test Runner: Pytest

Reporting: Playwright HTML reports / Allure (optional)

📁 Project Structure
bash
Copy
Edit
project-root/
├── tests/               # Test cases
├── pages/               # Page Object classes
├── utils/               # Helper functions or configs
├── playwright.config.py # Configuration file
├── requirements.txt     # Python dependencies
└── README.md            # Project description
⚙️ Installation
bash
Copy
Edit
pip install -r requirements.txt
playwright install
▶️ Running Tests
bash
Copy
Edit
pytest tests/
For headed mode:

bash
Copy
Edit
pytest tests/ --headed
To generate Playwright HTML report:

bash
Copy
Edit
pytest tests/ --html=report.html
📷 Additional Capabilities
playwright codegen: Record test scripts via UI

context.tracing.start(): Capture trace logs

page.screenshot(): Capture screenshots at any step

