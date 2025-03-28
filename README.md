# Keylogger Project

## Overview
This project implements a keylogger in Python that captures user input and sends an email notification with the logged data. It utilizes the `pynput` library for keyboard event listening and `smtplib` for sending emails.

## Features
- Captures keystrokes and logs them to a file.
- Sends an email with the log file as an attachment when the Enter key is pressed.

## Requirements
- Python 3.x
- Libraries: `pynput`, `smtplib`, `email`

You can install the required libraries using pip:
```bash
pip install pynput
## Usage
Clone the repository:
bash

Copy
git clone https://github.com/tanyinso/Red-Team-CTF
cd Red-Team-CTF

Update the email configuration in the script:
Replace the sender and recipient email addresses.
For the sender email, open your Google account, enable 2-Factor Authentication, and create an app called 'keylogger'. A key will be generated which you will use in place of the email password.
Run the script:
bash

Copy
python keylogger.py
Code Overview
Below is the key logging functionality implemented in the script.

[key logging](path/to/your/image.png)

Key Capturing Process
The keylogger captures keystrokes and logs them into a file named log.txt. It handles various key events such as space, backspace, and enter.

Data Capturing Process Screenshot

Email Notification
Upon pressing the Enter key, an email is sent with the captured data as an attachment.

Email Captured Screenshot

Disclaimer
This project is intended for educational purposes only. Please ensure you have permission to monitor any system before deploying a keylogger.
