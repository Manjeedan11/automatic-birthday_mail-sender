# Automatic Birthday Mail Sending

Automate the process of sending birthday emails to your contacts using Python.

## Overview

This project automates the process of sending birthday emails to contacts listed in an Excel spreadsheet. It reads the birthdays from the spreadsheet, checks if any of them match the current date, and sends birthday greetings via email to the respective contacts.

## Features

- Reads contact information from an Excel spreadsheet.
- Checks for birthdays matching the current date.
- Sends personalized birthday emails to contacts.
- Updates the "Last Sent" column in the spreadsheet to avoid duplicate emails.

## Requirements

- Python 3.x
- pandas
- smtplib (for email sending)
- openpyxl (for Excel file handling)

## Installation

1. Clone the repository:

```
git clone https://github.com/your-username/automatic-birthday-mail-sending.git
```

2. Navigate to the project directory:

```
cd automatic-birthday-mail-sending
```

3. Install the required dependencies:

```
pip install -r requirements.txt
```

## Usage

1. Place your contact information in an Excel spreadsheet (`Birthday.xlsx`) with the following columns:
   - Name
   - Email
   - Birthday
   - Last Sent (leave this column empty initially)

2. Run the `main.py` script:

```
python main.py
```

3. The script will check for birthdays matching the current date and send birthday emails to the respective contacts.

## Configuration

Before running the script, make sure to configure the following settings in `main.py`:

- Gmail ID and password for sending emails (`GMAIL_ID` and `GMAIL_PWD` variables).


