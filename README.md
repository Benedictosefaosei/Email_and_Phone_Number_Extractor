# 📧🔢 Email and Phone Number Extractor

A simple yet powerful **Python script** that automatically extracts **email addresses** and **phone numbers** from any copied text — using **regular expressions (regex)** and the **clipboard**.

---

## 🚀 Features

- ✅ Extracts all **valid email addresses** and **US-style phone numbers** from any text.
- 📋 Automatically **reads from your clipboard** and **copies extracted results back**.
- 🧠 Uses **regular expressions (regex)** for accurate pattern matching.
- ⚡ Runs instantly — just copy your text and execute the script!

---

## 🧩 How It Works

1. The script takes the **text currently stored in your clipboard** (via `pyperclip`).
2. It scans the text using two regex patterns:
   - One for **phone numbers**
   - One for **email addresses**
3. All matches are collected and copied back to your clipboard.
4. The script also prints the results to your terminal.

---

## 🛠️ Requirements

Make sure you have **Python 3.x** installed.  
You also need the `pyperclip` module for clipboard operations.

Install it via pip:

```bash
pip install pyperclip


📜 Usage

Copy any text containing email addresses or phone numbers.

Run the script in your terminal:

python extractor.py


The script will:

Search for all emails and phone numbers

Print them in your terminal

Copy them back to your clipboard for easy pasting

🧠 Example
Input (copied text):
Hello John, you can reach me at john.doe@gmail.com or (415) 555-1234.
Alternatively, contact support@company.org or 212-777-4567.

Output (in terminal and clipboard):
Copied to clipboard
415-555-1234
212-777-4567
john.doe@gmail.com
support@company.org

🧩 Code Structure
# 1. Import libraries
import pyperclip, re

# 2. Define regex patterns for phones and emails
# 3. Extract text from clipboard
# 4. Find all matches
# 5. Copy results back to clipboard

⚠️ Notes

This script is intended for educational and personal productivity use.

It currently supports standard US phone number formats (e.g., 415-555-1234, (415) 555-1234, 415.555.1234).

You can modify the regex patterns to support international numbers or custom formats.

🧑‍💻 Author

Benedict Osei Sefa
Benedictosefaosei@gmail.com
```
