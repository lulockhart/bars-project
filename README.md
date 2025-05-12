# 🍸 Bars.com Venue Scraper

This project automated the discovery and classification of alcohol-serving venues in U.S. cities using Google Search scraping. It was developed for **Bars.com**, a company that partners with upscale casual venues to deliver promotional offers powered by survey data and POS integrations.

> 🔒 **Note:** Due to NDA restrictions, `.ipynb` notebooks and full datasets are not included in this repository.

---

## 🧠 Project Background

Bars.com needed a scalable method to identify suitable venues in target cities (e.g., Boulder, Dallas, Fort Worth). Manual venue outreach was inefficient, so I developed a Python-based scraping pipeline to:
- Automate discovery via search queries (e.g., "restaurants near [city]")
- Scrape business details from Google
- Detect if the venue serves alcohol
- Prepare data for enrichment and outreach

---

## 🛠️ Tools Used

- **Python** (Selenium, Pandas)
- **Google Business Panel** scraping
- **Regex + DOM inspection** for alcohol detection
- **Jupyter Notebooks**
- **Manual validation** + Excel cleanup

---

## 🔍 Key Features

- Automated search and scrape from Google’s business cards
- Checked “Offerings” section to detect terms like “Alcohol,” “Cocktails,” “Hard liquor”
- Cleaned and exported a list of qualified venues
- Included logic for fallback scraping when primary elements were missing

---

## ⚙️ Project Outcomes

- Dramatically reduced time to identify high-fit venues
- Produced clean lists with venue name, address, and alcohol flag
- Provided foundational data for Bars.com’s venue acquisition pipeline
- Ready to scale to new regions with minimal code changes

---

## 🧭 Future Work

- Add Google Maps API fallback for addresses or coordinates
- Integrate pricing, ratings, and category filters
- Develop a UI to select cities and export results
- Expand to Yelp or OpenTable scraping if needed

---

Created for **Bars.com** as part of a portfolio project  
**Author:** Luke Lockhart
