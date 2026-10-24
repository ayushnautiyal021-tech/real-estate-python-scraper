# Real Estate Web Scraper & Lead Extractor

An automated Python-based web scraper designed to extract real estate listings and lead details, structured cleanly into Excel (`.xlsx`) format.

## Features
- **Data Extraction**: Extracts property details including Property Name, Location, Price, Area (SqFt), Property Type, and Verification Status.
- **Automated Structuring**: Processes raw scraped data and organizes it into well-structured tabular formats.
- **Excel Export**: Exports cleaned lead data directly into Excel files using Pandas/OpenPyXL.

## Tech Stack
- **Language**: Python 3
- **Libraries**: Requests, BeautifulSoup4 / Playwright, Pandas, OpenPyXL

## Output Sample
The extracted leads are saved in `real_estate_extracted_leads.xlsx`.

### Columns Included:
1. `Property Name`
2. `Location`
3. `Price`
4. `Area (SqFt)`
5. `Property Type`
6. `Status`

## How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/ayushnautiyal021-tech/real-estate-python-scraper.git](https://github.com/ayushnautiyal021-tech/real-estate-python-scraper.git)
