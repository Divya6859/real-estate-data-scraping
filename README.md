# MagicBricks 1BHK Rental Listings Scraper

Automated extraction of 1BHK rental property listings from **MagicBricks** using Python and BeautifulSoup.

## Tech Stack
- Python
- Libraries: `requests`, `BeautifulSoup4`
- CSV module for structured data storage

## Project Overview
This project scrapes rental property data from MagicBricks, including:
- Price
- Carpet Area
- Furnished Status
- Tenant Type
- Number of Bathrooms
- Listing Status

The data is saved in a structured CSV file, ready for analysis.

## Workflow
1. Send HTTP requests to MagicBricks listings with proper headers.
2. Parse HTML and extract relevant property details.
3. Structure and save the extracted data into a CSV file.

## Highlights
- Automated data collection from MagicBricks listings
- Cleaned and structured dataset ready for analysis
- Enables exploration of real estate trends and pricing patterns

## How to Run
1. Clone this repository:
```bash
git clone https://github.com/Divya6859/magicbricks-scraper.git
cd magicbricks-scraper

pip install -r requirements.txt
python scripts/WebScrap_RealEstateData.py

See the included notebook for data exploration: `notebook/RealEstateData.ipynb`
