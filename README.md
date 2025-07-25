# McDonald's Pie Day 2024 Automation Script

## Overview

This Python script automates the process of inputting the digits of Pi into the McDonald's Pie Day 2024 game. It uses the Selenium library to control a web browser, simulating user interaction to enter the digits of Pi and complete the game.

## Features

- **Automated Input**: Automatically inputs the digits of Pi into the game interface.
- **Web Control**: Uses Selenium to navigate and interact with the website.
- **Customizable**: Easily modify the email and name fields for user input.

## Status
Note: The McDonald's Pie Day 2024 website is no longer active. This script is provided for educational purposes and may not function as intended.

## Requirements

- Python 3.x
- Selenium library
- Chrome WebDriver

## Installation

1. Download the project

2. Install the required packages:
   pip install selenium

3. Make sure to download the Chrome WebDriver that matches your Chrome version from [here](https://sites.google.com/chromium.org/driver/).

## Usage

1. Open the script and modify the email and name fields with your information:
   driver.find_element(By.ID, "input-email").send_keys("your_email@example.com")
   driver.find_element(By.ID, "input-name").send_keys("Your Name")

2. Run the script:
   python <file_name>.py

3. The script will automatically navigate to the McDonald's Pie Day 2024 website, input the digits of Pi, and complete the game.

## Important Notes

- Ensure that the Chrome WebDriver is compatible with your installed version of Chrome.
- The script is designed to work with the specific layout and class names of the web page. If the website changes, the script may need to be updated accordingly.
