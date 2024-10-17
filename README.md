# AI Web Scraper

## Project Overview

This project is an **AI-powered web scraper** built using **Selenium**, **BeautifulSoup**, and **Streamlit**. The scraper automates the process of extracting web content, specifically focusing on the `<body>` of the webpage. It can also handle CAPTCHA challenges and provides a simple, interactive user interface through Streamlit.

The main goal of this project is to automate the collection and cleaning of website content, enabling users to easily scrape and review the core textual data from any website.

## Key Features

- **Automated Scraping**: Uses Selenium to navigate websites and extract HTML content.
- **CAPTCHA Handling**: Waits for CAPTCHA resolution if encountered during scraping.
- **DOM Parsing**: Extracts and cleans the body content of a webpage using BeautifulSoup.
- **Streamlit Interface**: Allows users to input a URL and view the scraped content via a user-friendly web interface.

## How It Works

1. **Input a URL**: Users provide a URL via the Streamlit app.
2. **Scraping the Website**: The script uses Selenium to open the browser, navigate to the website, and wait for any CAPTCHA challenges.
3. **Extracting Body Content**: The HTML content of the page is parsed, and the `<body>` section is extracted.
4. **Cleaning the Content**: Unnecessary tags like `<script>` and `<style>` are removed from the body content.
5. **Viewing Results**: The cleaned content is displayed in the Streamlit app.

## Technologies Used

- **Python**: The core programming language used for development.
- **Selenium**: For automating browser interaction and handling web scraping.
- **BeautifulSoup**: For parsing and cleaning the HTML content.
- **Streamlit**: To create an interactive user interface for scraping and displaying results.

## Usage
Enter the URL of the website you want to scrape into the Streamlit text input field.
Click the Scrape Site button.
The app will display the cleaned DOM content in the provided text area.

## Future Enhancements
Support for Pagination: Scraping content across multiple pages automatically.
Error Handling: More robust handling of CAPTCHA failures and page load errors.
Language Models: Integrating advanced AI models for better content extraction and summarization.

## Acknowledgement
Tech with Tim - https://youtu.be/Oo8-nEuDBkk?si=et16easZoZI0zPGQ
