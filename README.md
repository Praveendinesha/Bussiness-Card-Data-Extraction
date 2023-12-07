# **Bussiness Card Data Extraction**
---

This project focuses on extracting information from business cards using EasyOCR for text recognition and SQLite for storing and querying the extracted data.

## Overview
Business cards contain valuable information such as names, addresses, emails, and more. This project aims to extract structured data from images of business cards, making it easier to manage and utilize this information.

## Features
* **Text Extraction:** Utilizes EasyOCR library to extract text from business card images.
* **Data Storage:** Uses SQLite to save and query the extracted data.
* **Data Structuring:** Organizes extracted information into a structured format for easy access.

## Installation
**Requirements**
* Python 3.7 or higher
* EasyOCR library
* SQLite
* Pandas
* Matplotlib
* cv2

## Installation Steps
**Clone this repository:**
[Business-Card-Data-Extraction-Repository](https://github.com/praveendinesha/business-card-data-extraction)

## Install dependencies:
pip install -r requirements.txt

## Data Extraction:
1.Place business card images in the images directory.

2.Run the extraction script:
  python BizCardX_main.py

## Data Storage and Querying:
* The extracted data will be saved in the SQLite database (card_data.db).
* Use SQL queries to retrieve specific information from the database.

## Contributing
Contributions are welcome! Feel free to open issues or pull requests for any enhancements, bug fixes, or suggestions.
