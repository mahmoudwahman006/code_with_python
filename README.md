# Repo For Some Python Projects 

Welcome to this repository! 🎉 This repository contains multiple projects, each stored in its own file. Each project tackles a unique problem or demonstrates a specific concept. Below, you will find an overview of the projects and their contents.


![Mandelbrot Animation](https://upload.wikimedia.org/wikipedia/commons/2/21/Mandelbrot_sequence_new.gif)

---

## Table of Contents

1. [Project 1: Scraping an education website](#Scraping_an_education_website)
2. [Project 2: scraping_olx](#finish_scraping_olx)
3. [Project 3: scraping elqabbany](#scraping_elqabbany)
4. [Project 4: Download video on YouTube for scraping](#Download_video_on_YouTube)
5. [Project 5: Regular expression](#Regular_expression)
6. [Project 6: composite](#composite)
---

## Project 1: Scraping an education website

**File:** `Scraping an education website .ipynb`  
**Description:** 
**Web Scraper for CoreyMS Blog Videos and Articles**
This script scrapes data from the CoreyMS blog across multiple pages. It collects and displays the following details for each article:
Headlines: The titles of the blog posts.
Summaries: A brief summary or excerpt from each blog post.
YouTube Links: The embedded video links associated with the blog posts.

**Features:**
Scrapes data from up to 17 pages of the blog.
Utilizes requests to fetch webpage content and BeautifulSoup for HTML parsing.
Stores the scraped data into three lists: list_headline, list_summary, and list_headlink.
Outputs the collected data in a structured format, with each blog post's headline, summary, and video link printed together.

**Dependencies:**
Python modules: requests, BeautifulSoup4.
This script is designed for educational or personal use to practice web scraping techniques.

---

## Project 2: finish scraping olx

**File:** `finish scraping olx .ipynb`  
**Description:** 
**Web Scraper for OLX Vehicles Listings**
This Python script scrapes vehicle listings from the OLX Egypt website, extracting details from up to 30 pages. It collects and displays the following information for each listing:

Titles: Names of the listed vehicles.
Prices: The advertised prices.
Pictures: Direct links to the vehicle images.
Listing Links: URLs for individual listings on the website.
The script uses requests and BeautifulSoup for fetching and parsing webpage content.

---

## Project 3: scraping elqabbany

**File:** `scrapping ELqabbany_company for rokna.ipynb`  
**Description:** 
**Web Scraper for Kabbanifurniture.com (Rokna Collection)**
This Python script scrapes data from the "Rokna" collection page of the Kabbanifurniture website. It extracts and displays the following information for each item in the collection:

Names: Names of the furniture pieces.
Links: URLs leading to the detailed product pages.
Prices Before Discount: Original prices before applying discounts.
Prices After Discount: Current prices after discounts.
The script uses requests to fetch webpage content and BeautifulSoup to parse and extract structured data. It's ideal for learning or practicing web scraping techniques.

---


## Project 4: Download video on YouTube for scraping

**File:** `download  video by pytube.ipynb`  
**Description:** 

## Project 5: Regular expression

**File:** `read_file_and_use_RE.ipynb`  
**Description:** 
Regex-Based Data Extraction from Text File
This script processes a text file (task.txt) and extracts specific information using regular expressions. Below are the main functionalities:

Names Extraction:

Uses regex to extract full names consisting of three words (e.g., "First Middle Last").
Stores the names in list_name.
Phone Numbers Extraction:

Extracts Egyptian phone numbers starting with 010, 011, or 012 followed by eight digits.
Saves the phone numbers in list_phone_number.
Email Addresses Extraction:

Finds email addresses with the pattern username@domain.extension.
Adds the emails to list_mail.
Data Source:

Reads the content of task.txt into a single string for pattern matching.
This script is useful for extracting structured information from unstructured text files.


## Project 6: composite

**File:** `composite .ipynb`  
**Description:** 
**Composition Class Overview**
This Python class, composition, provides a framework for managing attributes and methods dynamically. It is designed to allow flexible manipulation of an object's data and behavior during runtime. Below is a summary of its key functionalities:

Attribute Management:
Add attributes using add_at(atname, atvalue).
Remove attributes with remove_at(atname).
Rename and update attributes



## How to Contribute

We welcome contributions to improve and expand this repository! Follow these steps:  
1. Fork the repository.  
2. Create a new branch for your changes.  
3. Commit your changes and push them to your branch.  
4. Create a pull request describing your updates.

Feel free to open issues for bugs, feature requests, or questions.

---

## License

You are free to use, modify, and distribute this repository, but please give proper credit.

---

### Contact

If you have any questions, feel free to reach out via email or open an issue.

Happy coding! 🚀
