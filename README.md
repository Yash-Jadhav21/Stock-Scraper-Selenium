Stock Scraper (Selenium + Pandas)

A Selenium-based scraper that extracts Most Active Stock data from financial websites,
processes it using Pandas, and exports it to Excel for further analysis.

---------------------------------------------------
Features
---------------------------------------------------
- Automates navigation to Trending Tickers → Most Active stocks
- Extracts stock data:
  - Name
  - Symbol
  - Price
  - Change
  - Volume
  - Market Cap
  - PE Ratio
- Cleans and transforms raw scraped data into a structured DataFrame
- Saves results as Excel (.xlsx) file

---------------------------------------------------
Requirements
---------------------------------------------------
Install dependencies with:
    pip install -r requirements.txt

---------------------------------------------------
Usage
---------------------------------------------------
1. Clone this repository:
   git clone https://github.com/your-username/stock-scraper-selenium.git
   cd stock-scraper-selenium

2. Run the script:
   python scraper.py

3. The output file will be saved as:
   temp.xlsx

---------------------------------------------------
Notes
---------------------------------------------------
- This scraper uses Selenium WebDriver (Chrome by default).
- Make sure you have ChromeDriver installed and available in your PATH.
- You can modify the clean_and_save_data() function to change the output filename.
