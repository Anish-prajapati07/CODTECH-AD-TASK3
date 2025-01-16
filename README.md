# CODTECH-AD-TASK3
BUILD A TOOLKIT WITH MULTIPLE MODULES (E.G., PORT SCANNER, BRUTE-FORCER) FOR PENETRATION TESTING.

# PERSONAL DETAILS
Name:Anish Prajapati

Company:CODTECH IT SOLUTIONS

ID: CT08EDO

Domain:Cyber security and Ethical hacking

Duration:December 17th,2024 to january 17th,2025

Mentor:Neela Santhosh Kumar

# Overview of the project
•	This project is a Python-based modular penetration testing toolkit designed to assist ethical hackers, cybersecurity professionals, and developers in identifying vulnerabilities in network services and web applications.
•	It provides a simple interface for performing two essential security tests: Port Scanning and Brute Forcing.

# Modules in the Toolkit
****1. Port Scanner****
**•	Purpose:** Scans a target IP/hostname for open ports.

•	Features:
o	Uses multithreading for faster scanning.
o	Reports open ports to the user.

•	Workflow:
o	Takes a target IP/hostname and a list of ports as input.
o	Iterates through each port and checks if it is open by attempting a TCP connection.
•	Use Case: Useful for identifying which services are running on a target machine.


2. Brute-Forcer
•	Purpose: Attempts to crack HTTP Basic Authentication using a username and a password list.

•	Features:
o	Automates the brute-forcing process.
o	Reads passwords from a user-specified file.
o	Stops the attack as soon as valid credentials are found.

•	Workflow:
o	Takes a target URL, a username, and a password file as input.
o	Tries each password in the list and checks if the HTTP response indicates successful authentication.
• Use Case: Useful for testing the strength of passwords used in basic authentication.





