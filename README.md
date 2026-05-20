
📖 Overview

This is a Python Selenium automation framework project for DemoQA that demonstrates: 

- Web automation testing using Selenium WebDriver

- Test organization using PyTest

- Page Object Model (POM) structure

- Data-driven testing using Excel files

Automated sections:

Elements → Text Box

Forms → Practice Form

Widgets → Slider
---

📂 Project Structure
```bash
DemoQA-
│
├─ test_data/ 📄 Excel test data
│ └─ test_data.xlsx
│
├─ pages/ 🏷️ Page Object Models
│ ├─ elements_page.py # Text Box
│ ├─ forms_page.py # Form
│ └─ widgets_page.py # Slider
│
├─ test_cases/ 🧪 Test scripts
│ ├─ test_elements_page.py
│ ├─ test_forms_page.py
│ └─ test_widgets_page.py
│
├─ utilities/ ⚙️ Helper functions
│ └─ read_excel.py
│
├─ conftest.py 🔧 PyTest setup
└─ README.md 📝 Documentation
```
---
🛠️ Tools and Technologies

| Category | Tool / Technology | Purpose |

|----------|-------------------|----------|

| Programming Language | Python 3.x 🐍 | Core language for automation scripts |

| Automation Tool | Selenium WebDriver 🌐 | Browser automation for DemoQA |

| Testing Framework | PyTest ✅ | Test execution, parameterization, and reporting |

| Data Handling | OpenPyXL 📄 | Read and handle Excel test data |

| Browser | Google Chrome 🌎 | Target browser for automation tests |

| WebDriver | ChromeDriver 🛠️ | Bridge between Selenium and Chrome browser |

| IDE | PyCharm | Development environment |

| Version Control | Git & GitHub 🔗 | Source code management and hosting |

| Reporting | pytest-html 📊 | HTML reports for test execution |
---
📝 Test Data

Stored in test_data/test_data.xlsx

| full_name    | email            | current_address | permanent_address |

|---------------|------------------|-----------------|-------------------|

| Alice Tester | alice@test.com   | 123 Main St     | 456 Demo Ave      |

| Bob Example  | bob@example.com  | 789 Test Rd     | 101 QA Street     |
---
✏️ Elements

| full_name | email | current_address | permanent_address |
---
🗂️ Forms

| first_name | last_name | email | mobile |
---
🎚️ Slider

| offset |
---
▶️ How to Run the Project



1. Clone the repository

```bash
git clone https://github.com/ushaun01/demoqa-selenium-automation-project.git
```

2. Navigate to project folder

```bash
cd DemoQA-Selenium-Automation-Project
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Run test cases

```bash
pytest -v
```

5. Generate HTML report

```bash
pytest --html=Reports/report.html
```
---
📊 Test Execution Summary

| Test Module | Description | Status | Remarks|

|-------------|-------------|---------|----------| 

| 📝 Elements | Verifies the Text Box form functionality — enters user details and validates output | ✅ Passed | Successfully submits and displays entered data |

| 🗂️ Forms | Fills out and submits the DemoQA practice form using Excel-driven input | ✅ Passed | Form fields populated and submitted successfully |

| 🎚️ Widgets | Moves slider to given offset values and verifies slider value | ✅ Passed | Slider moved to target offset successfully |
---

🧾 Summary Report:

Total Test Cases Executed: 3

Passed: 3 ✅

Failed: 0 ❌

Skipped: 0 ⏭️

Overall Result: 🟢 All test cases passed successfull
---

✍️ Author

👩‍💻 Usha Nazare
---
 📌 Project Type
 
Practice Project
---
 👩‍💻 Profile
 
Python Selenium Automation Tester  

Mechanical Engineer Transitioned into QA Automation


