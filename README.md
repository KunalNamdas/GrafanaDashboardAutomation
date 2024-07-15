# Grafana Dashboard Automation

This Python script automates logging into Grafana, navigating to a specific dashboard, and capturing a screenshot based on user-provided date ranges.

## Requirements

- Python 3.x
- Selenium WebDriver for Chrome
- Chrome Browser

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/kunalnamdas/GrafanaDashboardAutomation.git
   cd GrafanaDashboardAutomation
   ```
   
## Install dependencies:
 
 pip install selenium


## Download Chrome WebDriver from here and place it in your PATH.


# Usage

## 1. Modify the script:

- Replace "Your-Grafana-Login-url" with your Grafana login URL.
  
- Replace "Your-Grafana-Dashboard-Url" with your Grafana dashboard URL.

##  2. Run the script:

python GrafanaDashboardAutomation.py


## 3. Enter 'from' and 'to' dates when prompted in the format YYYY-MM-DD.

## 4. The script will log in, navigate to the specified Grafana dashboard with the date range, and capture a screenshot (screenshot.png).

# Notes

- Ensure you have Python installed along with necessary libraries (selenium).

- Adjust timeouts and paths as per your system configuration.

- This script is for educational purposes only.

