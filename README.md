# Job Scraper

## Project Description
This project works to scrape jobs listings from **LinkedIn**, **Glassdoor**, and **Indeed** based on search queries. For my personal use, I specify the experience level and date posted to the last 24 hours. This is to remain on top of any new job postings as, often times, it is a matter of who applies first. The scraped jobs are then automatically added to a Google Sheets tracker using the Google Sheets API.\
\
For the absolute best use of this scraper, you can configure your machine to run the Python code once or even twice a day automatically. This can be done using the [task scheduler](https://www.jcchouinard.com/python-automation-using-task-scheduler/) on Windows

**Sources:** LinkedIn, Glassdoor, Indeed\
\
**Pre-requisites:** [Chrome Driver](https://googlechromelabs.github.io/chrome-for-testing/) installed to the same folder as your script; Google Cloud account and project set up (if using the Google Sheets API); and a Facebook, LinkedIn, and Glassdoor account\

### WARNING: Webscraping can be illegal in certain cases. Make sure you are aware of the company's policies on scraping before attempting any scraping of your own
Have fun!
