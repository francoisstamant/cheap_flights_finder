# cheap_flights_finder

# Description 

Code that scrapes flights from https://www.ca.kayak.com/flights for specified dates/destinations. If price found is deemed low enough for the user, an email alert with the site URL is sent to specified email address. Code can be run periodically using a task scheduler (Windows in my case). For a tutorial on how to do this: https://towardsdatascience.com/automate-your-python-scripts-with-task-scheduler-661d0a40b279

Way to buy cheap flights, avoid paying high prices.

flight_scraping.py file contains the entire code

To read about the code, go right here: https://towardsdatascience.com/how-to-find-cheap-flights-in-80-lines-of-code-ba4f492587db


# Prerequisites

1. Python 3 
2. Chrome driver installation: https://chromedriver.chromium.org/
3. Requirements.txt (pip install -r requirements.txt)
