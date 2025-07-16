# PENETRATION-TESTING-TOOKLIT
COMPANY: CODETECH IT SOLUTIONS

NAME: ANISHA PRAVIN

INTERN ID: CITSOD165

DOMAIN: CYBERSECURITY

DURATION: 4 WEEKS

MENTOR: NEELA SANTHOSH

DESCRIPTION
# Penetration Testing Toolkit 

 SECTION: Project Name and Purpose
 This tells what the project is and why it’s useful:

It’s a toolkit built using Python.

It helps in ethical hacking.

It finds vulnerabilities in websites and networks.

SECTION: Files Explained
Here, we explain what each Python file does:

 1. penetration_toolkit.py
It’s the main menu.

When you run it, you’ll see options like:


1. Web Vulnerability Scanner
2. Port Scanner
3. Subdomain Finder
4. Login Bruteforce
You select a number and the related scanner runs.

 2. web_scanner.py
Checks if a website is vulnerable to:

XSS (Cross-Site Scripting) – used to inject malicious scripts

SQL Injection – used to bypass login or get data from database

Exposed Admin Pages – checks if URLs like /admin or /login are publicly accessible

 3. port_scanner.py
Scans a server (IP or domain) to find open ports

Example: It may detect port 80 (used for websites) or port 22 (used for SSH)

 4. subdomain_finder.py
Tries to find hidden subdomains like:

admin.example.com

mail.example.com

These can sometimes reveal admin panels or email servers.
 5. login_bruteforce.py
Tries to guess a password for a login form.

Uses a small list of common passwords like:

admin

123456

password

letmein

SECTION: How to Run the Toolkit

##  How to Run the Toolkit
This part shows you how to set up and run the tool.

Steps:

Make sure Python is installed.

Install required libraries:


pip install requests beautifulsoup4
Run the toolkit:

nginx
python penetration_toolkit.py
It opens the menu, and you can pick the scanner you want.

 SECTION: Safety Warning

##  Important Notes:
 This reminds you:

Only test your own systems or websites.

Unauthorized scanning can be illegal.

The toolkit is for learning and ethical use only.

 SECTION: Example Use
shell
Copy
Edit
##  Example Usage
This helps users understand:

What happens when they choose each menu option.

For example:

Option 1 → Web scanner runs

Option 2 → Port scanner runs

and so on…
output
<img width="575" height="247" alt="Image" src="https://github.com/user-attachments/assets/c75a2c96-b421-437c-8282-21b47f5c4814" />



















---


