Phishing Website Detector 
Overview
This project detects phishing websites using simple Python-based rules.

How it Works
The program checks:
- HTTPS usage
- Suspicious keywords (login, verify, bank)
- Special characters (@, -)
- Number of dots in the URL

Based on these, it classifies a website as:
- Safe
- Phishing

Tech Used
- Python

Example
Input:
http://verify-bank-login.secure-user.ru

Output:
Phishing Website Detected

Future Improvements
- Add Machine Learning model
- Improve detection accuracy
- Build web interface
