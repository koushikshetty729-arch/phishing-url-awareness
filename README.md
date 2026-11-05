# EWB Phishing URL Awareness Checker

## 1. Project Overview
The Phishing URL Awareness Checker is a beginner-friendly Python project that checks URL text for selected warning signs. It helps users learn about suspicious URL patterns.

The program does not open URLs or visit websites.

## 2. Project Objectives
- Identify common warning signs in URL text.
- Improve awareness of phishing risks.
- Practise Python functions, conditions, loops, and regular expressions.
- Explain why a URL warning does not automatically prove a website is malicious.

## 3. Features
The checker looks for:
- The @ symbol in a URL.
- URLs longer than 100 characters.
- An IP-address-shaped hostname.
- Five or more hostname segments.
- A hostname containing the xn-- punycode marker.
- The HTTP scheme.

## 4. Requirements
- Python 3.10 or later.
- Visual Studio Code or another Python editor.
- No additional Python packages are required.

## 5. How to Run
1. Open the project folder in VS Code.
2. Open the integrated terminal.
3. Run: python phishing_checker.py
4. Enter a sample URL when prompted.
5. Read the warnings.
6. Type q to exit.

## 6. Testing
The program was run using sample URL text.

Record the actual results for these five test cases:
1. https://www.example.com/login
2. http://192.0.2.10/account
3. http://example.com@sample.invalid/login
4. https://a.b.c.d.e.example.invalid/path
5. https://xn--example.invalid/

Add the observed result and pass/fail status for each test after completing all five tests. Do not claim a test passed unless you observed its result.

## 7. Limitations
- This is a basic awareness tool, not a complete phishing detector.
- It does not check website reputation or website content.
- A suspicious pattern does not prove a URL is malicious.
- A URL with no listed warning signs is not guaranteed to be safe.
- HTTPS alone does not prove that a website is trustworthy.

## 8. Ethical Use
Use fictional or approved sample URLs for learning. Do not enter passwords, OTPs, or other confidential information. The program checks text only and does not visit the entered URL.

## 9. Future Improvements
- Add more URL warning-sign checks.
- Improve URL format validation.
- Add clearer risk summaries.
- Create more test cases.

## 10. Author
Name: Koushik N.
Project: EWB Phishing URL Awareness Checker
Course/Batch: Add your official course or batch name.