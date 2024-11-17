# Amazon_product_price_webscraping
Amazon Data Web Scraping This project is a Python-based web scraping script designed to extract product details from Amazon search result pages. Using the BeautifulSoup library, the script collects product titles, prices, ratings, reviews, and availability information, and saves the data into a structured CSV file for further analysis.

Features
Efficient Data Extraction: Scrapes essential product details from Amazon, including:
Product Title
Price
Rating
Number of Reviews
Availability Status
Dynamic Scraping: Automatically handles multiple product links found on a search result page.
Clean Data Storage: Outputs the scraped data into a well-structured CSV file for easy access and analysis.
Technologies Used
Python: For the main script and logic.
Libraries:
requests: To make HTTP requests to Amazon pages.
BeautifulSoup (from bs4): To parse and extract data from the HTML content.
pandas: For data organization and exporting to CSV.
numpy: For handling missing or invalid data.
Requirements
Python 3.6 or higher
Libraries listed in requirements.txt:
plaintext
Copy code
numpy
pandas
requests
beautifulsoup4
Usage
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/amazon-web-scraping.git
cd amazon-web-scraping
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Replace the HEADERS['User-Agent'] placeholder in the script with your browser's User-Agent string.

Run the script:

bash
Copy code
python Webscraping.ipynb
The scraped data will be saved as amazon_data.csv in the project directory.

Limitations
Bot Detection: Amazon has strong anti-scraping mechanisms. If blocked, consider using browser automation tools like Selenium or proxy services.
Dynamic Content: JavaScript-rendered content may not be fully scraped; using headless browsers can address this issue.
Rate Limits: Ensure compliance with Amazon's Terms of Service by adhering to ethical scraping practices.
License
This project is licensed under the MIT License. See the LICENSE file for more information.

Disclaimer
This project is for educational purposes only. Ensure compliance with Amazon's terms and conditions when using this tool.
