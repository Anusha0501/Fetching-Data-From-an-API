# Data Collection with APIs and Web Scraping in Python

This repository demonstrates two fundamental data acquisition techniques used in data science and analytics:

1. **Fetching Data from an API**
2. **Web Scraping Data from Websites**

These projects showcase how to collect, process, and store data using Python for further analysis and visualization.

---

# Project 1: Fetching Data From an API

This project demonstrates how to fetch data from The Movie Database (TMDb) API using Python. The script retrieves top-rated movie data, processes the results, and stores the data in a CSV file for further analysis.

## Steps Implemented

### 1. Import Required Libraries

* pandas for data manipulation and analysis
* requests for making HTTP requests to the API

### 2. API Request

* Connected to the TMDb API endpoint.
* Retrieved top-rated movie data using an API key.
* Handled pagination to fetch movie information across multiple pages.

### 3. Data Extraction and Processing

Extracted important movie attributes including:

* id
* title
* overview
* release_date
* popularity
* vote_average
* vote_count

The data from all pages was combined into a single DataFrame.

### 4. Error Handling

* Checked HTTP response status codes.
* Logged errors whenever a request failed.

### 5. Data Storage

* Stored the final processed dataset in a CSV file.
* Created a structured dataset suitable for analysis and visualization.

### Output

The script:

* Displays the first few rows of the dataset.
* Shows the dataset dimensions.
* Saves the final dataset as:

`movies.csv`

---

# Project 2: Web Scraping Using Python

This project demonstrates how to collect data directly from websites through web scraping techniques.

The notebook shows how to send requests to web pages, parse HTML content, extract useful information, and organize the data into a structured format for analysis.

## Steps Implemented

### 1. Sending Requests

* Connected to web pages using HTTP requests.
* Retrieved webpage content for analysis.

### 2. Parsing HTML

* Parsed HTML documents using Python libraries.
* Identified target elements and attributes containing useful information.

### 3. Data Extraction

* Extracted relevant information from webpages.
* Collected structured data from unstructured HTML sources.

### 4. Data Cleaning

* Removed unnecessary content.
* Standardized extracted information.
* Prepared data for analysis.

### 5. Data Storage

* Converted scraped information into structured tabular format.
* Stored data using Pandas DataFrames.

---

## Technologies Used

* Python
* Pandas
* Requests
* Jupyter Notebook
* BeautifulSoup (if applicable)

---

## Skills Demonstrated

### API Skills

* REST API Integration
* JSON Data Processing
* Pagination Handling
* HTTP Requests
* Data Collection Automation

### Web Scraping Skills

* HTML Parsing
* Website Data Extraction
* Data Cleaning
* Web Data Collection
* Structured Data Creation

### Data Analysis Skills

* Data Wrangling
* Data Manipulation
* CSV File Handling
* Pandas DataFrames
* Exploratory Data Preparation

---

## Repository Structure

```text
├── Fetching_Data_From_an_API.ipynb
├── fetching_data_from_an_api.py
├── web scraping.ipynb
├── movies.csv
└── README.md
```

---

## Requirements

Install the required packages:

```bash
pip install pandas requests beautifulsoup4
```

---

## How to Run

### API Project

1. Obtain a TMDb API key.
2. Replace the API key in the script.
3. Run:

```bash
python fetching_data_from_an_api.py
```

4. The output dataset will be saved as:

```text
movies.csv
```

### Web Scraping Project

1. Open the notebook:

```bash
web scraping.ipynb
```

2. Execute the notebook cells.
3. The extracted data will be processed and stored for analysis.

---

## Learning Outcomes

Through these projects, I learned:

* Working with real-world APIs
* Handling JSON responses
* Managing paginated data
* Extracting information from websites
* Parsing HTML documents
* Cleaning and preprocessing data
* Building structured datasets
* Using Python for automated data collection

---

## Important Notes

* Replace the API key with your own TMDb API key before running the API project.
* Respect website Terms of Service when performing web scraping.
* Follow robots.txt guidelines where applicable.
* These projects are intended for educational and learning purposes.

---

## Future Improvements

* Automate data pipelines.
* Store data in SQL databases.
* Build dashboards using Power BI or Tableau.
* Create data visualizations using Matplotlib and Seaborn.
* Deploy data collection workflows in the cloud.

---

## Author

**Anusha**

Aspiring Software Engineer | Data Enthusiast | Python Developer

GitHub: https://github.com/Anusha0501
