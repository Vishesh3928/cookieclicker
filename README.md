

# Cookie Clicker Automation Script

**Description:**

This script automates basic interactions with the online game Cookie Clicker, clicking the cookie and purchasing upgrades based on available cookies.

**Requirements:**

- Python 3.x
- Selenium library (`pip install selenium`)
- ChromeDriver for your browser version ([https://chromedriver.chromium.org/](https://chromedriver.chromium.org/))

**Instructions:**

1. Download and install ChromeDriver for your browser (Chrome, Firefox, etc.).
2. Place the `chromedriver.exe` file in the same directory as this script.
3. Make sure you have Python and Selenium installed.
4. Run the script: `python cookie_clicker_auto.py`


**Code breakdown:**

- Imports necessary libraries.
- Initializes ChromeDriver service and creates a browser instance.
- Navigates to the Cookie Clicker website.
- Waits for the language selection button and clicks it.
- Waits for the cookie element and clicks it repeatedly.
- Continuously checks for available cookie upgrades:
    - Extracts the price of each upgrade.
    - If enough cookies are available, clicks the upgrade and breaks the loop.


This mini project was only for learning purposes. 


