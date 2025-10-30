Here we scrape a quote and details of the author from this site http//quotes.toscrape.com using the Python framework called BeautifulSoup.
Here, we develop a guessing game using different data structures and algorithms.
The user will be given 4 chances to guess the author of a famous quote. In every chance, the user will be provided with a hint which can be the author's birth date, the first name's first letter, the second name's first letter, etc. 
On successfully guessing the author, a message is printed, and if the user fails to guess the answer even after all 4 chances, then again a message is printed along with the answer.

Approach:
Import module
-requests help us grab the page, when the response is received it is stored in the form of a string
-bs4 library is used to create beasutifulSoup object.
-csv library helps reading and writing CSV files using python
-sleep function from time module helps add delay in the execution of the program.
-choice function from random module returns a random element.
Create a list to store values scraped
Scrape the details from this link: http//quotes.toscrape.com
Extract data
Game logic
-Return random items from the dictionary created
-Set number of guesses
-Write message for success and failure
-Keep giving hints until either number of chances reach zero or the user gets it right
