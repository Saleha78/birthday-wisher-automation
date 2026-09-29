🎂 Birthday Wisher Automation

A Python automation project that automatically sends personalized birthday wishes via email based on birthdays stored in a CSV file.

The project uses Python, SMTP, CSV, environment variables, and GitHub Actions to automate the process without needing to run the program manually.

✨ Features
🎂 Checks birthdays from a CSV file
💌 Sends personalized birthday emails automatically
📧 Uses SMTP for email delivery
🔐 Keeps email credentials secure using environment variables
⚙️ Runs automatically using GitHub Actions
🗓️ Can be scheduled to run daily
🛠️ Technologies Used
Python
SMTP
CSV
datetime
GitHub Actions
Environment Variables
📂 Project Structure
birthday-wisher-automation/
│
├── main.py
├── birthdays.csv
├── letter_templates/
│   ├── letter_1.txt
│   ├── letter_2.txt
│   └── letter_3.txt
│
└── .github/
    └── workflows/
        └── scheduled.yml
⚙️ How It Works
The program reads the birthday information from birthdays.csv.
It checks whether anyone has a birthday today.
If a birthday matches, it selects a random letter template.
The person's name is added to the message.
The birthday wish is sent through email using SMTP.
GitHub Actions runs the program automatically according to the scheduled workflow.
🔐 Security

Email credentials are not stored directly in the code.

Sensitive information is stored using GitHub Secrets / environment variables, helping keep account credentials private.

🚀 Automation

The project uses GitHub Actions to run automatically on a schedule.

This means the birthday checker can run in the background without manually opening and running the Python program every day.

📌 Purpose

This project was built to practice:

Python automation
Working with CSV files
Email automation with SMTP
Environment variables
GitHub Actions and scheduled workflows

Made with 🐍 Python & ❤️
