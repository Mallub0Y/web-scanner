# web-scaner
# 🔐 Basic Web Security Scanner

A simple Python-based security tool to identify common web vulnerabilities.

## 🚀 Features

* Checks for missing security headers
* Scans common open ports
* Detects common directories (admin, login, etc.)

## 🛠️ Installation

```bash
git clone https://github.com/yourusername/basic-security-scanner.git
cd basic-security-scanner
pip install -r requirements.txt
```

## ▶️ Usage

```bash
python scanner.py
```

Enter target URL when prompted.

## 📌 Example Output

```
[+] Checking Security Headers...
[MISSING] Content-Security-Policy

[+] Scanning Common Ports...
[OPEN] Port 80

[+] Checking Common Directories...
[FOUND] http://example.com/admin
```

## ⚠️ Disclaimer

This tool is for educational purposes only. Do not scan systems without permission.

## 🧠 Future Improvements

* Add XSS detection
* Add SQL injection testing
* Add threading for speed
* Export results to file
