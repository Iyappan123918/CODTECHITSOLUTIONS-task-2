*Name : IYAPPAN.R
Company : CODTECH IT SOLUTIONS ID : CT08DS9526
Domain : CYBERSECURITY AND ETHICAL HACKING
Duration: September to October 2024
Mentor : Muzammil *

CODE-TECH-TASK-2
Overview of the Simple Vulnerability Scanning Tool Purpose: The tool is designed to perform basic vulnerability assessments on a specified network or website by checking for common security vulnerabilities. It helps identify open ports, outdated software versions, and basic misconfigurations.

OUTPUT Screenshot:
![Screenshot (5)](https://github.com/user-attachments/assets/1d8507f7-253c-4f2a-86b9-6add4e098139)


Key Features

Open Port Scanning: 1.Utilizes the nmap library to scan the first 1024 ports of a target (IP address or domain). 2.Identifies which ports are open, which could indicate potential entry points for unauthorized access.

Software Version Checking: 1.Checks for outdated software installed on the system. 2.Compares installed versions against known latest versions (can be expanded with additional software).

Misconfiguration Detection: 1.Makes an HTTP request to the target to check for basic misconfigurations by analyzing the HTTP response status code. 2.Alerts the user if the server responds with an unexpected status code (e.g., anything other than 200).

Technologies Used 1.Python: The primary programming language for implementing the tool. 2.Libraries:nmap: For network port scanning. 2.1.requests: To make HTTP requests and check server responses. 2.2.psutil (optional): For system-level information (not explicitly used in the current version but can be useful for expanding functionality).

Usage 1.The user runs the script and inputs the target IP address or domain. 2.The tool performs the scans and outputs the results directly to the console, detailing open ports, outdated software, and any misconfigurations detected.

Considerations Educational Purpose: 1.The tool is designed for educational use and should not be used against any system without explicit permission. Scalability: 2.The tool is simple and can be extended with additional features, such as more comprehensive vulnerability checks, logging capabilities, or integration with external databases for version comparisons.

Future Enhancements 1.Expand the software version checking with a broader database. 2.Implement more comprehensive misconfiguration checks (e.g., SSL/TLS configuration, directory listings). 3.Add logging and reporting features for better output management. 4.Include command-line arguments for more flexible usage.

This project serves as a foundational step in understanding network security and vulnerability assessments, making it suitable for educational environments or initial explorations into cybersecurity.
