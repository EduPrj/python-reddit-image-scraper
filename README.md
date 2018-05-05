# python-reddit-image-scraper
Python 3 implementation of an image scraper utilizing the Reddit API and the Python Reddit API Wrapper (PRAW). Requires a Reddit Client ID and Client Secret to use.

###subr-image-scraper.py
Scrapes top imgur.com and i.redd.it images from a subreddit specified in the script. 

###To do
Make python-reddit-image-scraper more generic by scraping from an arbitrary list of subreddits provided in a different file.

Improve management of scraped images by creating a directory named scraped-images in the current working directory, and a new sub-directory within scraped-images for each subreddit.  

Reduce redundancy by only scraping unvisited subreddit submissions.
