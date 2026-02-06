🌐 Web Scraper using Python
A simple Python project that demonstrates web scraping using the requests and BeautifulSoup libraries. The script extracts quotes, authors, and links from a scrape-friendly website and saves the data into a CSV file.
📌 Project Description
This project connects to a public demo website designed for learning web scraping. It fetches HTML content, parses it, extracts useful information, and stores the results in a structured CSV file.
The scraper is built with error handling and follows ethical scraping practices.
🚀 Features
Fetch HTML content using requests
Parse HTML using BeautifulSoup
Identify and extract HTML tags and attributes
Extract quotes, authors, and links
Handle missing elements safely
Save extracted data to a CSV file
Follow ethical web scraping practices
🛠️ Technologies Used
Python 3
Requests
BeautifulSoup4
CSV module
📂 Project Structure
web_scraper.py   # Main Python script
quotes.csv       # Output file with scraped data
README.md        # Project documentation
⚙️ Installation
Install the required libraries:
pip install requests beautifulsoup4
▶️ How to Run
Run the Python script:
python web_scraper.py
After execution, a file named quotes.csv will be created containing the scraped data.
📊 Output
The CSV file contains:
Quote text
Author name
Author profile link
This data can be used for analysis or further processing.
⚖️ Ethical Scraping
This project follows responsible scraping practices:
Uses a public demo website
Avoids excessive requests
Includes polite delays
Handles errors gracefully
🎯 Learning Objectives
This project helps you learn:
HTTP requests in Python
HTML parsing
Data extraction techniques
Error handling
Writing data to CSV files

Author
Kavya Mulimani
