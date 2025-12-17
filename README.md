# Wikipedia Table Scraper (Python)

This project demonstrates how unstructured web data can be transformed into a clean, analysis-ready dataset using Python.

Rather than focusing on scraping itself, the main goal of this project is to show **data acquisition and preparation**, which is a critical first step in data science and AI workflows.

---

## Why this project exists

Many real-world AI and data projects do not start with clean datasets.
They start with:
- Wikipedia tables
- Public documentation
- Semi-structured web pages
- Inconsistent or noisy data sources

This mini project simulates a common real-world scenario:
> Extracting structured data from a public web source and preparing it for analysis or machine learning pipelines.

---

## What it does

- Sends an HTTP request to a Wikipedia page (with a proper User-Agent)
- Parses HTML tables using BeautifulSoup
- Extracts a comparison table into a pandas DataFrame
- Exports the cleaned data as a CSV file

---

## Output

The final output is a structured CSV file:


## Why this project exists

Many real-world data and AI projects do not start with clean, ready-to-use datasets.

They usually start with:
- Public documentation (Wikipedia, manuals, specs)
- Semi-structured HTML tables
- Inconsistent or noisy web data

This mini project demonstrates a common real-world workflow:
> Extracting structured data from a public web source and preparing it for analysis or machine learning pipelines.

The resulting dataset can be used for:
- Exploratory data analysis (EDA)
- Feature engineering experiments
- Benchmarking cloud providers
- Prototyping data ingestion pipelines

