Craiglist Checker
=================
Send a text when there's a new "For Sale" post for a given keyword or phrase.

The script sends an SMS message to a given phone number using GMail's SMTP protocol, so you'll need to add your GMail username and password to the config file.

An SMS message will only be sent if a new post appears (based on the full URL).

Setup
-----
Install the required libraries via pip:
    pip install -r requirements.txt

Usage
-----
    python craigslist-checker.py <search-term> <phone-number>

It's useful to setup a cronjob that will run the script every N minutes.