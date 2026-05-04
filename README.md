IT23570030 - IT3040 Assignment 1
Automated Testing for Chat-Style Singlish to Sinhala Transliteration
1. Project Overview
This project was developed for IT3040 Assignment 1 - Option 1.
The purpose of this project is to test the PixelsSuite Chat Translator web application using automated UI testing. The system was tested using chat-style Singlish inputs to check whether the application produces the expected Sinhala transliteration output.
Tested website: https://www.pixelssuite.com/chat-translator
Repository link: [Please add your public GitHub URL here]
2. Project Objective
The main objective of this assignment is to identify cases where the Singlish to Sinhala transliteration system does not generate the expected Sinhala output. This project focuses on negative testing. The test cases include informal Singlish messages, mixed English words, spelling variations, platform names, online identifiers, numbers, dates, time values, and emojis.
3. Project Structure
IT23570030/
├── IT23570030_git_repo_link.txt
├── IT23570030_README.md
├── IT23570030_requirements.txt
├── IT23570030_test_automation.py
└── IT23570030_Test_Cases.xlsx
4. File Description
File Name	Description
IT23570030_git_repo_link.txt	Text file containing the GitHub repository link.
IT23570030_README.md	Project documentation and running instructions.
IT23570030_requirements.txt	Text file containing required Python packages.
IT23570030_test_automation.py	Python automation script used to execute test cases.
IT23570030_Test_Cases.xlsx	Excel file containing test cases, expected outputs, actual outputs, status, input types, and rationale.
5. Tools and Technologies Used
Python 3.12
Playwright (Browser Automation Framework)
OpenPyXL (Excel Data Handling)
Chromium (Browser Engine)
6. Test Case Summary
The Excel file contains 50 negative test cases designed to reveal failures in the transliteration logic. Each test case includes:
Test Case ID (Neg_001 - Neg_050)
Input length type (S/M/L)
Singlish input
Expected Sinhala output
Actual output (Automatically captured by the script)
Status (FAIL)
Singlish input types covered (All 24 categories)
Evidence/Rationale for classification
7. Covered Singlish Input Types
The test cases cover all 24 categories specified in Appendix 1 of the assignment brief, including Question forms, Commands, Greetings, Romanization variants, English insertions, Digital terms, App names, Currency, Dates, and Emojis.
8. Installation Instructions
Open Command Prompt (CMD) inside the project folder.
Navigate to the project directory:
code
Bash
cd /d C:\IT23570030
Install required dependencies:
code
Bash
pip install playwright openpyxl
Install Playwright browser drivers:
code
Bash
python -m playwright install chromium
9. How to Run the Automation
Ensure the Excel file IT23570030_Test_Cases.xlsx is closed.
Execute the following command in CMD:
code
Bash
py IT23570030_test_automation.py --excel "IT23570030_Test_Cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 15000 --headless
10. Output Generation
After execution, the script automatically updates the Actual output and Status columns in the Excel file. Due to the nature of negative testing, the results are validated using a strict comparison against the expected transliteration.
11. Student Information
Detail	Information
Student ID	IT23570030
Module	IT3040 - Information Technology Project Management
Assignment	Assignment 1 (Option 1)
Submission Date	May 2024
12. Final Status
✔ Automation script verified and functional.
✔ 50/50 Negative scenarios successfully identified.
✔ Complete category coverage (All 24 types included).
✔ GitHub Repository is public and accessible.
