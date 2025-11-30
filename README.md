# AccuKnox-user-management-tests

Automation: Playwright (Python) + Page Object Model

## What is included
- Playwright POM-based tests for OrangeHRM User Management flows (Add/Search/Edit/Delete)
- Two Problem-2 scripts:
  - `system_health_monitor.py` (System Health Monitoring)
  - `app_health_checker.py` (Application Health Checker)
- Test case document (Markdown) with steps you can paste into Excel/Google Sheets.

## Playwright & Python
- Playwright version used: 1.49+ (compatible)
- Python 3.8+

## Setup
1. Clone the repo
```bash
git clone https://github.com/venomshetty08-oss/AccuKnox-user-management-tests.git
cd AccuKnox-user-management-tests
```

2. Create and activate a virtual environment

```bash
python -m venv venv
# Windows
venv\Scripts\activate
# Mac/Linux
source venv/bin/activate
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Install Playwright browsers

```bash
playwright install
```

## Run the Playwright test

```bash
pytest -q
```

## Problem 2 scripts

- System Health Monitor

```bash
python problem2/system_health_monitor.py
```

- App Health Checker

```bash
python problem2/app_health_checker.py --url https://opensource-demo.orangehrmlive.com/
```

## How to push to GitHub

```bash
git init
git add .
git commit -m "Initial commit: AccuKnox user management tests"
git branch -M main
git remote add origin https://github.com/venomshetty08-oss/AccuKnox-user-management-tests.git
git push -u origin main
```

