# Internshala Scraping Project

This project aims to scrape internship details from Internshala's website and store them in a structured format using Python. The script utilizes web scraping techniques with the BeautifulSoup library to extract internship details such as title, company name, location, start date, duration, stipend, and status.

## Prerequisites

Before running the script, make sure you have the following installed:

- Python 3.x
- Requests library (`pip install requests`)
- BeautifulSoup library (`pip install beautifulsoup4`)
- Pandas library (`pip install pandas`)

## Usage

1. Clone or download this repository to your local machine.
2. Navigate to the project directory.
3. Run the `internshala_scraper.py` script.

```
python internshala_scraper.py
```

4. The script will scrape internship details from Internshala's website and save them in a CSV file named `whole_Internshala_scraped2.csv`.

## Description

- The script starts by sending a request to Internshala's internship page.
- It parses the landing page to extract the total number of pages containing internship listings.
- It then iterates through each page, scrapes the internship details, and stores them in a dictionary.
- After scraping all pages, it converts the dictionary to a Pandas DataFrame.
- Finally, it exports the DataFrame to a CSV file for further analysis.

## Files

- `internshala_scraper.py`: The main Python script for scraping Internshala internship details.
- `whole_Internshala_scraped2.csv`: The CSV file containing the scraped internship data.
- `README.md`: This readme file providing information about the project.

## Notes

- The script may need adjustments if there are changes to Internshala's website layout or structure.
- Use responsibly and adhere to Internshala's terms of service and usage policy.
- For any issues or improvements, feel free to open an issue or submit a pull request.
