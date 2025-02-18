# CallLog Checklist Updater

## Overview
This project automates the process of checking if phone numbers from a **checklist** exist in a **call log file**. It also retrieves the call duration for matched numbers. Instead of manually entering numbers into another website, this script automates the process, saving time and effort.

## Features
- Formats phone numbers to a standard format (e.g., `123-456-7890`).
- Compares phone numbers in the **checklist** with the **call log**.
- Marks if a checklist phone number was found in the call log.
- Retrieves and updates the **call duration** for matched entries.
- Outputs an updated checklist file with results.

## File Structure
- **CallLog.csv** – Contains call records with phone numbers and call details.
- **Checklist.xlsx** – Contains customer phone numbers to check against the call log.
- **Formatted_CallLog.csv** – (Generated) Call log file with formatted phone numbers.
- **Updated_Checklist.xlsx** – (Generated) The final checklist with matched results.

## Installation & Usage
### 1. Clone the repository:
```bash
git clone https://github.com/yourusername/CallLog_Checklist_Updater.git
cd CallLog_Checklist_Updater
