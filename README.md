Automated Port Scanning with Custom Report Output

Overview
This Python-based tool automates the process of network port scanning using Masscan and Nmap, and generates structured reports in CSV and HTML formats. It helps IT professionals and students discover open ports, detect services, and create audit-ready reports efficiently.

Features
- Command-line input for IP addresses or ranges
- Fast scanning with Masscan
- In-depth service scanning with Nmap
- Report generation (CSV, HTML)
- Logging of scan activity

Installation

Install system tools and Python libraries:

```bash
brew install masscan nmap
pip3 install python-nmap pandas beautifulsoup4
