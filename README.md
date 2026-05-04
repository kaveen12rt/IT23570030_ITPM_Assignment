# IT23570030_ITPM_Assignment
ITPM

# Transliteration Accuracy Testing - IT23570030

This project is designed to evaluate the accuracy of a chat-style Singlish to Sinhala transliteration tool provided by Pixelssuite, using Playwright automation. The assessment identifies 50 failure scenarios (negative test cases) across all 24 Singlish input types specified in the assignment.

## Prerequisites
- Python 3.11 or 3.12 installed.
- Google Chrome browser.

## Installation Instructions
1. Open the Command Prompt (CMD) in the project folder.
2. Install the required Python libraries by running the following command:
   pip install playwright openpyxl
3. Install the Playwright browser drivers:
   python -m playwright install chromium

## Project Structure
- `IT23570030_test_automation.py`: The Python automation script using Playwright.
- `IT23570030_Test_Cases.xlsx`: The Excel file containing 50 negative test cases and automated results.
- `IT23570030_Git_Link.txt`: A text file containing the public GitHub repository link.
- `IT23570030_requirements.txt`:Text file containing required Python packages.

## How to Run the Tests
To run the automated transliteration tests, execute the following command in the terminal:

python IT23570030_test_automation.py --excel "IT23570030_Test_Cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 10000 --headless

## Results
- The script automatically fills the "Actual Output" and "Status" columns in the Excel file.
- All 50 scenarios in this project are "Negative Test Cases" designed to showcase system failures, thus the expected status for these cases is "FAIL".

# Student Information

Detail	Information
Student ID	IT23570030
Module	IT3040 - Information Technology Project Management
Assignment	Assignment 1 (Option 1)
Submission Date	May 2024
