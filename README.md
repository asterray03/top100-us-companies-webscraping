# 🏢 Web Scraping Fortune 100 U.S. Companies

This project demonstrates **web scraping with Python** to extract data about the **100 largest U.S. companies by revenue** from [Wikipedia](https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue).

The goal of this project is to:
- Practice using **BeautifulSoup** and **Requests** for web scraping.
- Clean and structure raw HTML table data into a tabular format with **Pandas**.
- Export the data into a **CSV file** for further analysis.

## 📊 Sample Output (Jupyter Notebook Screenshot)

Here’s a screenshot of the first few rows of the scraped data in VS Code:

![Scraped Data Screenshot](https://github.com/asterray03/top100-us-companies-webscraping/blob/main/Screenshot%202025-08-27%20023148.png)

---

## 📈 Data Preview

The scraped dataset contains the following columns:  

| Column | Description |
|--------|-------------|
| **Rank** | Company’s rank by revenue (1–100) |
| **Name** | Company name |
| **Industry** | Sector or industry |
| **Revenue (USD millions)** | Annual revenue (in millions of USD) |
| **Revenue growth** | YoY revenue growth (%) |
| **Employees** | Total employees |
| **Headquarters** | Company’s HQ location |

**Example rows:**

| Rank | Name                 | Industry                    | Revenue (USD millions) | Revenue growth | Employees  | Headquarters              |
|------|----------------------|-----------------------------|------------------------|----------------|------------|---------------------------|
| 1    | Walmart              | Retail                      | 648,125                | 6.0%           | 2,100,000  | Bentonville, Arkansas     |
| 2    | Amazon               | Retail and cloud computing  | 574,785                | 11.9%          | 1,525,000  | Seattle, Washington       |
| 3    | Apple                | Electronics industry        | 383,482                | –2.8%          | 161,000    | Cupertino, California     |

---
