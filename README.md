# **Crypto API  Scraper**  

## **Project Overview**
This project automates the extraction of cryptocurrency market data from a public API: https://coinmarketcap.com/api/ 
Each scrape includes a **timestamp column** to track when the data was last updated, making it useful for time-series analysis, monitoring trends, or building a historical dataset.  

### **Key Features**  
**Automated API Scraping** – Fetches real-time or historical crypto data.  
**Timestamp Tracking** – Adds a `last_updated` column to record scrape time.  
**Data Storage** – Saves results in **CSV, JSON** (configurable).    
**Scheduling Support** – Can be run manually or scheduled.  
