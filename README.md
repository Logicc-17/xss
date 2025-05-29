# Web Vulnerability Scanner

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)

A Python-based web vulnerability scanner that automatically checks websites for common security vulnerabilities.

## Features

- **Website Crawling**: Discovers all accessible pages within a target domain
- **XSS Testing**: Detects Cross-Site Scripting vulnerabilities in web forms
- **SQL Injection**: Identifies potential SQL injection points
- **Directory Listing Check**: Finds directories with enabled directory listing
- **Config File Exposure**: Detects exposed configuration files
- **Information Disclosure**: Checks for server information leaks

## Requirements

- Python 3.8+
- Required packages:
  ```bash
  pip install requests beautifulsoup4
Installation

    Clone the repository:
    bash

git clone https://github.com/Logicc-17/vulnerability-scanner.git
cd vulnerability-scanner

Install dependencies:
bash

    pip install -r requirements.txt

Usage

Run the scanner:
bash

python scanner.py

You will be prompted to enter the target URL:

Enter target URL (include http:// or https://): http://example.com

Scan Types
Vulnerability	Description
XSS	Tests for Cross-Site Scripting
SQL Injection	Checks for SQLi vulnerabilities
Directory Listing	Finds open directories
Config Files	Detects exposed configuration files
Server Information	Checks for info disclosure
Configuration Options

Edit these in the code:
python

self.max_links = 50        # Max pages to scan
self.rate_limit_delay = 1  # Seconds between requests
self.timeout = 10          # Request timeout in seconds

Sample Output

[+] Starting scan for http://example.com
[*] Crawling: http://example.com
[+] Testing for XSS vulnerabilities
[*] Found 3 forms on http://example.com/contact
[!] XSS Vulnerability found in http://example.com/contact
[+] Scan completed in 45.23 seconds

[+] Scan Summary:
Total pages scanned: 12
Total vulnerabilities found: 3

Important Notes

⚠️ Legal Disclaimer:

    Use only on authorized systems

    Obtain permission before scanning

    For educational purposes only

License

MIT License - See LICENSE file for details
