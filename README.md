# AmbitionBox Top 500 Companies — Web Scraping & EDA

An end-to-end data analytics project using **Python Web Scraping, Regex, Pandas, Exploratory Data Analysis, and Excel Dashboarding** to analyse company information collected from AmbitionBox.

## Project Overview

This project collects company information from the AmbitionBox Top 500 Companies page and transforms the scraped web data into a structured dataset.

The project covers the complete analytics workflow:

**Web Scraping → Regex Extraction → Data Cleaning → EDA → Visualization → Dashboard → Business Insights**

After data cleaning and validation, **495 companies** were used for the final analysis.

## Objectives

- Scrape company information from AmbitionBox using Python.
- Extract useful information from raw web content using Regex.
- Clean and transform the scraped data into a structured dataset.
- Analyse company ratings, reviews, industries, and locations.
- Perform Exploratory Data Analysis (EDA).
- Create meaningful visualizations.
- Build an Excel Company Intelligence Dashboard.
- Generate business insights and recommendations.

## Technologies Used

- **Python**
- **Requests**
- **BeautifulSoup**
- **Regular Expressions (Regex)**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**
- **Microsoft Excel**

## Data Fields

The final dataset contains the following fields:

| Column | Description |
|---|---|
| Company Name | Name of the company |
| Raw Card Text | Original scraped company card text |
| Company Rating | Employee rating of the company |
| Reviews | Number of employee reviews |
| Industry | Industry or business sector |
| Location | Company location information |

## Web Scraping & Regex

### Web Scraping

The project uses:

**Requests → BeautifulSoup → Company Cards → Structured Data**

Requests was used to access the web pages, while BeautifulSoup was used to parse the HTML structure and identify company information.

### Regex Extraction

Regex was used to extract important information from the raw company card text, including:

- Company Rating
- Review Count

Industry and location information were also extracted and structured for analysis.

## Data Cleaning

The scraped data was cleaned using Pandas.

Major cleaning steps included:

- Removing duplicate company records.
- Converting company ratings into numeric values.
- Converting review counts such as `K`, `L`, and `M` into numeric values.
- Handling missing Industry and Location values.
- Standardizing text fields.
- Removing records without valid ratings or review counts.
- Excluding Company Size because reliable information was not available.
- Validating the final dataset.

## Exploratory Data Analysis

The analysis focused on:

- Company rating distribution.
- Top-rated companies.
- Most-reviewed companies.
- Industry representation.
- Location concentration.
- Average ratings by industry.
- Average ratings by location.
- Relationship between company ratings and review counts.

## Key Results

- **495 companies** were included in the final dataset.
- **6 data fields** were used for analysis.
- **Average Company Rating:** 3.78
- **Total Reviews:** approximately 6.63 million
- **Average Reviews per Company:** approximately 13,393
- **Rating Range:** 2.7 – 4.9

## Visualizations

The project includes the following visualizations:

1. Company Rating Distribution
2. Top 10 Companies by Rating
3. Top 10 Companies by Review Count
4. Rating vs Reviews
5. Top 10 Industries by Company Count
6. Industry Average Rating
7. Top 10 Company Locations
8. Location Average Rating

## Excel Dashboard

An Excel **Company Intelligence Dashboard** was created to provide a single view of the major project findings.

### Dashboard KPIs

- Total Companies: **495**
- Average Rating: **3.78**
- Total Reviews: **6.63M**
- Average Reviews: **13,393**

The dashboard also includes charts for company ratings, reviews, industries, and locations.

## Business Insights

The analysis provides insights into:

- Employee perception through company ratings.
- Employee feedback volume through review counts.
- Industry-level company concentration.
- Geographical concentration of companies.
- Differences in average ratings across industries and locations.
- Relationship between employee ratings and review volumes.

## Business Recommendations

- Companies should regularly monitor employee ratings and feedback.
- Organizations with lower ratings can investigate areas requiring workplace improvement.
- Companies can benchmark their employee ratings against industry peers.
- Review patterns can be analysed to understand employee expectations.
- Location-level comparisons can help identify regional differences.
- Regular analysis of employee feedback can support better employee engagement strategies.

## Project Structure

```text
AmbitionBox-Web-Scraping-EDA
│
├── 01_Notebook
│   └── AmbitionBox_Web_Scraping_Analysis.ipynb
│
├── 02_Raw_Data
│   └── AmbitionBox_Top_500_Raw_Data.csv
│
├── 03_Cleaned_Data
│   └── AmbitionBox_Top_500_Cleaned_Data.csv
│
├── 04_Visualizations
│   ├── company_rating_distribution.png
│   ├── top_10_rated_companies.png
│   ├── top_10_reviewed_companies.png
│   ├── rating_vs_reviews.png
│   ├── top_10_industries.png
│   ├── industry_average_rating.png
│   ├── top_10_company_locations.png
│   └── location_average_rating.png
│
├── 05_Dashboard
│   └── AmbitionBox_Company_Intelligence_Dashboard.xlsx
│
├── 06_Documentation
│   └── AmbitionBox_Web_Scraping_Project_Documentation.docx
│
└── 07_Presentation
    ├── AmbitionBox_Web_Scraping_Project_Presentation.pptx
    └── AmbitionBox_Web_Scraping_Presentation.mp4
```
## Author

### Madishetti Rakshitha

**B.Tech Graduate | Aspiring Data Analyst | Data Science Enthusiast**

**Skills:** Python • Web Scraping • Regex • Pandas • Excel

**LinkedIn:** [Madishetti Rakshitha](https://www.linkedin.com/in/madishetti-rakshitha-b1a332343)  
**GitHub:** [Rakshitha152003](https://github.com/Rakshitha152003)
