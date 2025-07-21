# 🕷️ Web Scraping Projects using BeautifulSoup (PakWheels + Indeed)

This repository contains **two beginner-friendly web scraping scripts** written in **Python** using **BeautifulSoup** and **Requests** libraries.

### 🔍 Target Websites:
1. **PakWheels.com** – Car Listings Scraper  
2. **Indeed Pakistan (pk.indeed.com)** – Job Listings Scraper

> ⚠️ This is an educational project. Always respect website terms of service before scraping.

---


---

## 🚗 Project 1: PakWheels Web Scraper

### 🌐 URL: [https://www.pakwheels.com](https://www.pakwheels.com)

### 📌 What this script does:
- Sends an HTTP request to PakWheels homepage
- Parses the HTML using **BeautifulSoup**
- Tries to extract:
  - 🚙 Car Name
  - 💵 Price
  - 📍 Location
  - 🖼️ Image URL
  - 🔗 Car Link

### ⚠️ Current Problem:
PakWheels uses **Cloudflare security**, so the scraper is **blocked**.  
You’ll receive a message like:

> **"Sorry, you have been blocked."**  
> This website is using a security service to protect itself from online attacks.

✅ Workaround: Use **Selenium** or **ScraperAPI** for future improvement.

---

## 💼 Project 2: Indeed Pakistan Job Scraper

### 🌐 URL: [https://pk.indeed.com](https://pk.indeed.com)

### 📌 What this script does:
- Sends a request to the homepage or job search page
- Parses the HTML using **BeautifulSoup**
- Extracts job-related data:
  - 🧑‍💼 Job Title
  - 🏢 Company Name
  - 📍 Location
  - 📄 Summary (if available)
  - 🔗 Job URL

### ✅ Status: **Working Properly**  
The script fetches data and prints it or saves it as a CSV.

---

## 🔧 Technologies Used

- Python 3.x  
- BeautifulSoup  
- Requests  



