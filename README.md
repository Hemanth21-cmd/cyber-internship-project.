# cyber-internship-project.
Internship project: Password Strength Analyzer
Password Strength Analyzer with Custom Wordlist Generator
Overview
This tool checks how strong a password is and generates custom wordlists for ethical hacking practice. It uses a simple interface to analyze passwords and create wordlists based on inputs like name, date, or pet name.
Tools Used

Python
zxcvbn-python (for password strength analysis)
tkinter (for the graphical interface)

Installation

Install Python 3.8+ from python.org.
Install the required library:pip install zxcvbn-python



How to Use

Run the program:python password_analyzer.py


Enter a password to check its strength (score 0–4, with suggestions).
Enter a name, date (e.g., 2001), or pet name to generate a wordlist.
Save the wordlist as wordlist.txt.

Sample Output

wordlist.txt: Contains variations like “HEMANTH”, “HEMANTH2001”, “tom2001”, “hem@nth”.
Screenshot: Shows the program’s interface.

Project Report

See password_analyzer_report.pdf for details on the project’s purpose and steps.


