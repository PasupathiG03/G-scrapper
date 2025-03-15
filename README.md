G-Scrapper

Overview

G-Scrapper is a powerful web scraping tool designed to extract PDF, PPTX, and DOCX files from the web using Google search. It automates the process of finding and downloading document files for research, analysis, or data collection.

Features

🔍 Google Search Integration – Scrapes document files directly from search engine results.

📄 File Type Filtering – Extracts only PDF, PPTX, and DOCX files.

⚡ Automated Downloading – Saves files to a specified directory.

🚀 Fast & Efficient – Optimized for quick and accurate results.

🔧 Customizable Search Parameters – Allows fine-tuned search queries.

Installation

Prerequisites

Ensure you have the following installed:

Python 3.8+

pip (Python package manager)

Google Search API or Selenium (for automated searches)

Clone the Repository

git clone https://github.com/your-username/G-Scrapper.git
cd G-Scrapper

Install Dependencies

pip install -r requirements.txt

Usage

Basic Usage

Run the script to scrape document files:

python gscrapper.py --query "machine learning" --filetype pdf --limit 10

Command-Line Arguments

Argument

Description

Example

--query

Search query for Google

"data science tutorials"

--filetype

File type to scrape (pdf, pptx, docx)

pdf

--limit

Number of results to fetch

10

--output

Directory to save files

./downloads

Example

Scraping 5 PowerPoint presentations on deep learning:

python gscrapper.py --query "deep learning" --filetype pptx --limit 5

Configuration

Modify config.py to set default search parameters and file storage locations.

API-based scraping (if applicable) requires setting up API keys.

Dependencies

requests

beautifulsoup4

selenium

googlesearch-python

Install dependencies using:

pip install -r requirements.txt

Contributing

We welcome contributions! Feel free to:

Fork the repository

Create a new branch (git checkout -b feature-xyz)

Commit your changes (git commit -m "Added feature XYZ")

Push to your branch (git push origin feature-xyz)

Open a pull request

License

This project is licensed under the MIT License. See LICENSE for details.

Contact

📧 Email: your-email@example.com🐙 GitHub: your-username


