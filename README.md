# Mail Scraper
Google Maps Business Info and Email Scraper (Client Project)

## Introduction
This project, developed for a client, is designed to scrape business information from Google Maps and subsequently extract email addresses from the websites of these businesses. It is divided into two main parts:

1. **Google Maps Scraper**: Utilizes the [Zubdata/Google-Maps-Scraper](https://github.com/Zubdata/Google-Maps-Scraper) repository to scrape business information from Google Maps without using the official API.
2. **Email Scraper**: A custom Python script (`sites_to_mail.py`) that first identifies contact pages on the business websites obtained from Google Maps and then scrapes email addresses from these pages.

The project efficiently combines these two steps to provide a comprehensive solution for gathering business contact information.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Dependencies](#dependencies)
- [Configuration](#configuration)
- [Examples](#examples)
- [Troubleshooting](#troubleshooting)

## Installation
### Google Maps Scraper
Follow the installation instructions provided in the [Zubdata/Google-Maps-Scraper](https://github.com/Zubdata/Google-Maps-Scraper) repository.

### Email Scraper
1. Ensure Python is installed on your system.
2. Install the required Python packages:

   ```bash
   pip install selenium webdriver-manager
   ```

## Usage
### Running the Google Maps Scraper
Refer to the usage instructions in the [Zubdata/Google-Maps-Scraper](https://github.com/Zubdata/Google-Maps-Scraper) repository.

### Running the Email Scraper
Execute the `sites_to_mail.py` script with Python:

```bash
python sites_to_mail.py
```

## Features
- Scrapes business information from Google Maps.
- Extracts email addresses from business websites.
- Automated web scraping using Selenium.

## Dependencies
- Python
- Selenium
- WebDriver-Manager
- [Zubdata/Google-Maps-Scraper](https://github.com/Zubdata/Google-Maps-Scraper) repository.

## Configuration
No additional configuration is required for the `sites_to_mail.py` script. Make sure to follow the configuration steps for the Google Maps Scraper as mentioned in its repository.

## Examples
An example of using the `sites_to_mail.py` script would be:

```bash
python sites_to_mail.py
```

This will run the script and begin scraping emails from the provided URLs.

## Troubleshooting
For issues related to the Google Maps Scraper, refer to its respective repository. For the Email Scraper, ensure all dependencies are properly installed and Python is correctly set up on your system.