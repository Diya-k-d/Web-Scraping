# RERA Project Details Web Scraper

## Overview

This project uses **Python and Selenium** to automatically scrape
promoter details from a RERA (Real Estate Regulatory Authority) website.

The script navigates through registered projects, opens the promoter
details page, and extracts important information such as promoter name,
GSTIN, PAN number, and permanent address.

The collected data is stored in a structured format for further
analysis.

------------------------------------------------------------------------

## Technologies Used

-   Python
-   Selenium
-   Pandas
-   Chrome WebDriver

------------------------------------------------------------------------

## Features

-   Automated navigation of project pages
-   Extraction of promoter details
-   Handles dynamic webpage elements
-   Uses explicit waits to ensure reliable scraping
-   Runs Chrome in headless mode

------------------------------------------------------------------------

## Data Extracted

The scraper collects the following fields:

-   Promoter Name
-   PAN Number
-   GSTIN Number
-   Permanent Address

------------------------------------------------------------------------

## How to Run the Project

1.  Install dependencies

```{=html}
<!-- -->
```
    pip install selenium pandas

2.  Download **ChromeDriver** compatible with your Chrome version.

3.  Update the ChromeDriver path in the script:

```{=html}
<!-- -->
```
    chrome_driver_path = "path_to_chromedriver"

4.  Run the script:

```{=html}
<!-- -->
```
    python webscrape.py

------------------------------------------------------------------------

## Output

The extracted data is saved into a **Pandas DataFrame** and can be
exported to CSV or Excel for further analysis.

------------------------------------------------------------------------

## Purpose

This project demonstrates **web automation and data extraction from
dynamic websites**, which is useful for building datasets for data
analysis and machine learning.
