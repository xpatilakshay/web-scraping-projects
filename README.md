# Web Scraping Projects

A collection of beginner-to-intermediate web scraping projects using Python, BeautifulSoup, Requests, and Pandas. These projects extract structured data from websites and save it into CSV files for analysis.

---

## Projects

### 1. Quotes Scraper
- **Website:** [quotes.toscrape.com](http://quotes.toscrape.com/)
- **Description:** Scrapes quotes, authors, and first tags from the website.  
- **Output:** `quotes_dataset.csv`  
- **Tech:** Python, Requests, BeautifulSoup, Pandas  
- **Concepts Learned:** HTML parsing, CSS selectors, extracting text/attributes, storing in CSV.

### 2. IMDb Movie Scraper
- **Website:** [IMDb Top 250](https://www.imdb.com/chart/top/)
- **Description:** Scrapes top 250 movies along with their rank, title, year, and rating.  
- **Output:** `imdb_movies.csv`  
- **Tech:** Python, Requests, BeautifulSoup, Pandas  
- **Concepts Learned:** HTML parsing, extracting structured data, working with lists, storing results in CSV.

### 3. Books Scraper
- **Website:** [books.toscrape.com](https://books.toscrape.com/)
- **Description:** Scrapes book titles, prices, and availability from all pages of the site.  
- **Output:** `books.csv`  
- **Tech:** Python, Requests, BeautifulSoup, Pandas  
- **Concepts Learned:** Pagination handling, HTML parsing, extracting structured data, saving results to CSV.

---

## How to Run

### Install required packages:
```bash
pip install requests beautifulsoup4 pandas
```

### Quotes Scraper
1. Navigate to the project folder:
```bash
cd web-scraping-projects/quotes_scraper
```
