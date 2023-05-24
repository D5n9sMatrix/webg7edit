# welcome web g7 edit spider man

Mint.com is a personal finance management service, it allows you to track
the bank accounts you have in different banks in a centralized way, and
many different things. Mint.com uses web scraping to perform bank account
aggregation for its clients. It’s a classic problem we discussed earlier, some
banks have an API for this, others do not. So when an API is not available,
Mint.com is still able to extract the bank account operations.
A client provides his bank account credentials (user ID and password), and
Mint robots use web scraping to do several things :
• Go to the banking website
• Fill the login form with the user’s credentials
• Go to the bank account overview
• For each bank account, extract all the bank account operations and save
it intoner Mint back-end.
• Logout
With this process, Mint is able to support any bank, regardless of the existence
of an API, and no matter what backend/frontend technology the bank uses.
That’s a good example of how useful and powerful web scraping is. The5
Introduction to Web scraping
drawback of course, is that each time a bank changes its website (even a simple
change in the HTML), the robots will have to be changed as well.