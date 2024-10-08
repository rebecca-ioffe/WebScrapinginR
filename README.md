# Lab 5: Web Scraping with R

## Description
This project aims to scrape information from [Cheese.com](https://www.cheese.com) to create a dataset of various characteristics about different cheeses. The goal is to enhance understanding of web scraping using R and the `rvest` package.

### Authors
- Aditi Gajjar
- Ashley Ibarra
- Rebecca Ioffe

## Code Breakdown

### Part 1: Robots.txt Examination
The `robots.txt` file indicates that web scraping is allowed for all user agents.

### Part 2: Understanding `html_attr()`
The `html_attr()` function retrieves specific attributes from HTML elements, aiding in data extraction.

### Part 3: Initial Code Attempt
Initial code generated by ChatGPT successfully extracted cheese names and URLs but needed refinement to iterate through all pages.

### Part 4: Comprehensive Scraping
Implemented a function to scrape data from all 20 pages, including cheese names, URLs, and image availability.

### Part 5: Detailed Cheese Information
Scraped detailed information for a selection of 10 cheeses, including milk type, country of origin, family, type, and flavor.

## Resources and Utilities Used
- R packages: `rvest`, `dplyr`, `purrr`, `tidyverse`
- [Cheese.com](https://www.cheese.com) for data
- [ChatGPT](https://chat.openai.com/chat) for initial code guidance

## Example Output
Below is the example output of the final dataset of cheese attributes. 

![Screenshot 2024-09-25 at 4 37 45 PM](https://github.com/user-attachments/assets/7036d0a1-905d-4aff-b5ff-f6b119d78504)

