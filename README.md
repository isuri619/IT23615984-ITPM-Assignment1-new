# IT3040 – ITPM Assignment 1

## Transliteration Accuracy Testing (Option 1)

### 👤 Student Details

* Name: L.I.U.Peiris
* IT Number: IT23615984

---

## 📌 Project Overview

This project evaluates the accuracy of a chat-based Sinhala transliteration system available at:

👉 https://www.pixelssuite.com/chat-translator

The objective is to identify cases where the system fails to correctly convert Singlish (informal Sinhala typed using English letters) into Sinhala script.

---

## 🎯 Objectives

* Test the Chat Sinhala transliteration feature
* Identify incorrect conversions (negative test cases)
* Automate testing using Playwright
* Analyze system weaknesses based on results

---

## 🧪 Test Case Design

* Total Test Cases: **50**
* Type: **Negative Test Cases (Fail scenarios)**
* Coverage: All **24 Singlish input types**
* Minimum: At least **2 test cases per input type**

---

## ⚙️ Technologies Used

* Python 3.14
* Playwright
* OpenPyXL (Excel handling)

---

## 📂 Project Structure

```
test_automation_IT23615984/
│
├── test_automation.py
├── Assignment 1 - Test cases.xlsx
├── README.md
└── 
```

---

## 🚀 Setup Instructions

### 1. Install Python

Download and install Python 3.12+ 

### 2. Install Dependencies

Open Command Prompt and navigate to the project folder:

cd C:\Users\MSI\Downloads\test_automation_IT23615984

Run:

python -m pip install -U pip
python -m pip install playwright openpyxl
python -m playwright install

---

## ▶️ Running the Automation

Run the following command:

python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open

---

## 📊 Results

* The script automatically fills:

  * Actual Output
  * Status (Pass/Fail)

* After execution, the Excel file should be reviewed and validated.

---

## 📝 Additional Work

After automation:

* Added two columns in Excel:

  * Singlish input types covered
  * Evidence or rationale

* Filled them manually based on each test case

---

## ✅ Conclusion

This project demonstrates the effectiveness of automated testing in identifying weaknesses in transliteration systems and highlights areas where the system fails to correctly interpret informal Singlish inputs.
