## URL Safety Checker

##  Project Overview
The URL Safety Checker is a web-based application that analyzes a given URL and determines whether it is Safe, Suspicious, or Dangerous. It helps users avoid phishing and malicious websites by checking common risk indicators.

---

##  Problem Statement
With the rapid increase in phishing attacks and fraudulent websites, users often click unsafe links unknowingly. There is a need for a simple tool that can quickly analyze and classify URLs based on risk factors.

---

##  Solution
This project uses a rule-based detection system to evaluate URLs based on:
- URL length
- Presence of IP address
- Special characters (e.g., @, -)
- HTTPS protocol usage

A risk score is calculated and the URL is classified accordingly.

---

## Technologies Used
- HTML
- CSS
- Python
- Flask
- Regular Expressions (Regex)
- Git & GitHub

---

##  Project Structure
URL-Safety-Checker/
│
├── app.py
├── config.py
├── requirements.txt
│
├── models/
│   └── url_checker.py
│
├── templates/
│   └── index.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   └── images/
│
└── docs/
