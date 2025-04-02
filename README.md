# Selenium Web Scraping Project

## Overview
This repository contains two versions of a Selenium-based web scraping project. The first version focuses on setting up Selenium and testing it on Google, while the second version extracts football match data from the website **adamchoi.co.uk**.

## Versions
### 📌 Version 1: Selenium Setup & Google Test
- Install Selenium & ChromeDriver
- Verify installation by automating a simple Google search
- Basic Selenium commands (opening a website, finding elements, etc.)

### 📌 Version 2: Football Matches Scraper
- Navigate to the **adamchoi.co.uk** website
- Click on "All Matches"
- Extract match data (date, home team, score, away team)
- Save data to a CSV file

## Installation
### Step 1: Install Required Libraries
```bash
pip install selenium webdriver-manager pandas
```

### Step 2: Download & Set Up ChromeDriver
1. Check your **Chrome version**: Open Chrome → `chrome://settings/help`
2. Download the matching **ChromeDriver** from [here](https://googlechromelabs.github.io/chrome-for-testing/)
3. Extract it and add the path to **system PATH** (or specify it in your script)

### Step 3: Clone the Repository
```bash
git clone https://github.com/your-username/selenium-web-scraping.git
cd selenium-web-scraping
```

## Usage
### Running Version 1 (Google Test)
```bash
cd version1
jupyter notebook
# Open version1_google_test.ipynb and run the cells
```

### Running Version 2 (Football Matches Scraper)
```bash
cd version2
jupyter notebook
# Open version2_football_scraper.ipynb and run the cells
```

## Repository Structure
```
selenium-web-scraping/
│── version1/                   # Selenium setup & Google test
│   ├── version1_google_test.ipynb
│   └── requirements.txt
│
│── version2/                   # Football matches scraper
│   ├── version2_football_scraper.ipynb
│   ├── football_data.csv        # Extracted data
│   └── requirements.txt
│
│── README.md                   # Project documentation
└── .gitignore                   # Ignore unnecessary files
```

## Contact
For questions or improvements, feel free to **fork this repo** or contact me on [LinkedIn]www.linkedin.com/in/naina-singamsetti
 🚀

