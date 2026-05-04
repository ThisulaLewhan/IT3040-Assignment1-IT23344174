# IT3040 – ITPM Assignment 1
## Option 1 – Transliteration Accuracy Testing

https://github.com/ThisulaLewhan/IT3040-Assignment1-IT23344174.git

This project contains Playwright automation scripts and test cases used to evaluate the Sinhala transliteration accuracy of the following website:

https://www.pixelssuite.com/chat-translator

## Requirements

- Python 3.11 or 3.12
- Playwright
- Google Chrome

## Install Dependencies

```bash
pip install -U pip
pip install playwright openpyxl
playwright install
```

## Run Automation

```bash
python test_automation.py --excel "test_automation/Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
```

## Repository Contents

- Playwright automation scripts
- Excel test cases
- Configuration files

## Student Information

Module: IT3040 – ITPM  
Assignment: Assignment 1 – Option 1