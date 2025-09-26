# MagicBricks 1BHK Rental Listings Scraper

Automated extraction of 1BHK rental property listings from MagicBricks using Python and BeautifulSoup.

## Tech Stack
- Python
- Requests, BeautifulSoup4
- CSV module

## Project Overview
This project scrapes rental property data from MagicBricks, including Price, Carpet Area, Furnished status, Tenant type, Bathroom, and Status, and stores it in a structured CSV file for analysis.

## Workflow
- Sent HTTP requests to MagicBricks listings with proper headers
- Parsed HTML and extracted relevant property details
- Structured and saved the extracted data into a CSV file

## Highlights
- Automated data collection from MagicBricks listings
- Cleaned and structured dataset ready for analysis
- Enabled exploration of real estate trends and pricing patterns

## How to Run
Clone this repository:

```bash
git clone https://github.com/Divya6859/magicbricks-scraper.git
cd magicbricks-scraper

pip install -r requirements.txt
python scripts/magicbricks_scraper.py

