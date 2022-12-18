### [Bunk] Riot Games Account Generator w/ Captcha Support ###


A script that automates the process of creating a League of Legends account through the official website.

**Reason**

*This script was created to automate the process of creating Riot Games /  League of Legends accounts, which can be a tedious task when done manually.*

**Features**

Automates the process of filling out the sign up form and submitting it on the official website
Generates random information for the account, including email, password, username, and date of birth
Uses undetected_chromedriver and anycaptcha to bypass CAPTCHA challenges
Provides error handling for various exceptions that may occur during the process

**Requirements**

[Named link](https://chrome.google.com/webstore/detail/nopecha-captcha-solver/dknlfmjaanfblgfdfebhijalfmhmjjjo "Captcha Extension")

- Python 3.7 or higher
- Selenium
- undetected_chromedriver

**Installation**

- Clone or download the repository to your local machine
- Install the required packages by running pip install -r requirements.txt

**Usage**

- Edit the options in the script to customize the Chrome options, such as window size and extensions
- Run the script by using python main.py
- The script will open a Chrome window and navigate to the sign up page. It will then generate random account information and fill out the form. If a CAPTCHA challenge is encountered, it will be automatically solved using anycaptcha.
Once the form is submitted, the script will print a message indicating that the account creation was successful.

**Contributing**
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

*License*
This project is licensed under the MIT License - see the LICENSE file for details.
