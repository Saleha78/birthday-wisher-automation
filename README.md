# 🎂 Birthday Wisher Automation

A Python automation project that automatically sends personalized birthday wishes via email based on birthdays stored in a CSV file.

The project uses Python, SMTP, CSV, environment variables, and GitHub Actions to automate the process without needing to run the program manually.

## ✨ Features

* 🎂 Checks birthdays from a CSV file
* 💌 Sends personalized birthday emails automatically
* 📧 Uses SMTP for email delivery
* 🔐 Keeps email credentials secure using environment variables
* ⚙️ Runs automatically using GitHub Actions
* 🗓️ Supports scheduled daily execution

## 🛠️ Technologies Used

* Python
* SMTP
* CSV
* datetime
* GitHub Actions
* Environment Variables

## ⚙️ How It Works

1. The program reads birthday information from the CSV file.
2. It checks whether anyone has a birthday today.
3. If a birthday matches, it selects a random letter template.
4. The person's name is added to the message.
5. The birthday wish is sent through email using SMTP.
6. GitHub Actions runs the program automatically according to the scheduled workflow.

## 🔐 Security

Email credentials are not stored directly in the source code.

Sensitive information is stored using GitHub Secrets and environment variables to help keep account credentials private.

## 🚀 Automation

GitHub Actions is used to run the birthday checker automatically on a schedule.

This allows the program to check birthdays and send wishes without manually running the Python script every day.

## 📌 Project Purpose

This project was built to practice:

* Python automation
* CSV file handling
* Email automation with SMTP
* Environment variables
* GitHub Actions
* Scheduled workflows

## 💡 What I Learned

Through this project, I practiced connecting a Python script with GitHub Actions to create a simple automated workflow that can run independently on a schedule.

---

Made with 🐍 Python & ❤️

