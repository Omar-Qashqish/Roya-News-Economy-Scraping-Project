# Roya News Economy Scraping Project

This project contains a Python script designed to scrape economy-related articles from the Roya News website in both Arabic and English sections.

## 📂 Extracted Data Fields:
- **Title**: The article's headline.
- **Content**: A brief summary or the full text of the article.
- **Image**: Link to the article's image.
- **Link**: Direct link to the article page.
- ✅ The script also downloads each article's image and saves it into a local folder.


## 📄 Sections Targeted:
- Arabic Section: اقتصاد (Economy section)
- English Section: Economy

✅ The script only fetches articles published within the last **24 hours**, ensuring that the collected data is always fresh and relevant.

## 🛠️ Technologies Used
- Python
- Requests
- BeautifulSoup (bs4)
- Pandas
- pyodbc (for database connection)

## 🗂️ Output Formats
- Structured DataFrame
- Saved Excel File (`.xlsx`)
- Inserted records into SQL Server database

## 🚀 Current Status
- This project is actively maintained and will continue to be enhanced with better data cleaning, error handling, and automation.

---

> Feel free to use, modify, or integrate the script into your data pipelines!
