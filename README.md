# Test Automation UI Project

## Setup Instructions

1. Install Python

2. Install required packages:

```
pip install playwright openpyxl
```

3. Install Playwright browsers:

```
python -m playwright install
```

---

## Run the Script

```
python image_preview_test.py --url "https://www.pixelssuite.com/convert-to-png" --slow-mo-ms 2000
```

---

## Description

This project tests the image preview functionality of the Pixelssuite website using Playwright.
It uploads a PNG image and checks whether it is displayed correctly in the preview section.

---

## Files

* image_preview_test.py → Automation script
* execution_results.csv → Test results
* README.md → Instructions

---
