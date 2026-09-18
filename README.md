# 🕸️ Naukrigulf Web Scraper - Data Engineering Project

<p align="center">
  <img src="data_scraping.jpg" alt="Data Scraping" width="100%">
</p>

## 📌 Project Overview
This project is an automated web scraping pipeline built to extract job listings from [Naukrigulf](https://www.naukrigulf.com/). It specifically targets "Data Engineer" job postings, navigates through multiple pages automatically, and extracts key details for each job. The scraped data is then processed and exported into a structured CSV file for further analysis.

## 🚀 Features
- **Automated Navigation:** Uses Selenium WebDriver to automatically search for jobs and navigate through multiple pagination links.
- **Bypass Automation Detection:** Implements custom Chrome options to avoid basic bot detection mechanisms.
- **Data Extraction:** Accurately scrapes:
  - Job Title
  - Company Name
  - Location
  - Required Experience
  - Job Description
- **Data Structuring:** Utilizes Pandas to transform raw scraped data into a clean, tabular DataFrame.
- **CSV Export:** Saves the final dataset locally as a `.csv` file.

## 🛠️ Technologies & Libraries Used
- **Python 3.x**
- **Selenium** (Web Automation & Scraping)
- **Pandas** (Data Manipulation & Structuring)
- **Time** (Execution delays for page loading)

## 📂 Notebook Structure
The project is structured into clear, logical steps within the Jupyter environment:
1. **Imports And Options:** Setting up Selenium WebDriver, Chrome options, and importing Pandas.
2. **Scraping Code:** The core logic for launching the browser, searching, looping through pages, and extracting elements.
3. **Show Results:** Displaying the extracted data within a Pandas DataFrame to ensure accuracy.
4. **Export the output to a CSV file:** Saving the DataFrame for future use.

## ⚙️ How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/Abdelfattah011/Data_Scraping_project.git
   ```
2. Install the required dependencies:
   ```bash
   pip install selenium pandas
   ```
3. Ensure you have the Chrome WebDriver installed and compatible with your current Google Chrome version.
   
5. Run the Jupyter Notebook or Python script.   

👨‍💻 Author
Abdelfattah Ahmed Abdelfattah
Data Engineer
