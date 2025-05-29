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
