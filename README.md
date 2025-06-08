# 📚 Book Scraper with Puppeteer

This project is a simple web scraper built using [Puppeteer](https://pptr.dev/) that extracts book details from [Books to Scrape](https://books.toscrape.com/) — a website built for practicing web scraping.

## 🚀 Features

- Scrapes multiple pages (up to 10 by default)
- Extracts:
  - Title
  - Price
  - Stock Availability
  - Star Rating
  - Product Link
- Stores scraped data in a `books.json` file
- Uses headless browser automation

## 📦 Technologies Used

- [Node.js](https://nodejs.org/)
- [Puppeteer](https://pptr.dev/)
- [fs (File System)](https://nodejs.org/api/fs.html)

## 📁 Project Structure

├── books.json # Output file containing scraped book data
├── index.js # Main scraping script
├── package.json
└── README.md # Project documentation

## ⚙️ Setup & Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/eabhishek24/puppeteer-scrapeBooks.git
   cd puppeteer-scrapeBooks

## 🚀 Usage
Run the scraper using Node.js:
npm install

## 📤 Output
After execution, the script generates a books.json file with structured data like this:
Each book includes:

![image](https://github.com/user-attachments/assets/a6847fd8-e3fa-4548-a9ae-6b40beaf7bb0)

## MongoDB document

![image](https://github.com/user-attachments/assets/8b855967-9a82-432a-8b4b-9b49d76d35ea)

## 📝 Notes
The scraper is configured to fetch 10 pages. You can modify the maxPages variable in index.js to scrape more or fewer pages.

This scraper is for educational/demo purposes only. Always check a site's robots.txt before scraping.


