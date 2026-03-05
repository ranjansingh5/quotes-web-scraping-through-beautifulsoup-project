# 📜 Quotes Web Scraper (Python + BeautifulSoup)

## 📌 Project Overview

This project is a simple web scraping application built using **Python**, **Requests**, **BeautifulSoup**, and **Pandas**.

The script scrapes quotes from the website: https://quotes.toscrape.com


It extracts:

* Quote text
* Author name
* Tags associated with each quote

  The collected data is stored in a CSV file for further analysis.

---

## 🔗 Table of Contents

- [Features](features)
- [Technologies Used](technologies-used)
- [Project Structure](project-structure)
- [How It Works](how-it-works)
- [Learning Outcome](learning-outcomes)
- [Author](author)

---       

## 🚀 Features

* Scrapes multiple pages (1–10)
* Extracts structured data from HTML
* Cleans text using `.strip()`
* Stores data in a Pandas DataFrame
* Exports results to a CSV file

---

## 🛠️ Technologies Used

* Python 
* requests
* beautifulsoup
* pandas

---

## 📂 Project Structure

```
quotes_scraping.ipynb 
quotes_info.csv
README.md
```

---

## ⚙️ How It Works

1. Sends HTTP requests to each page (1 to 10)
2. Parses HTML content using BeautifulSoup
3. Finds all quote containers (`div.quote`)
4. Extracts:

   * Quote text (`span.text`)
   * Author name (`small.author`)
   * Tags (`a.tag`)
5. Stores data inside a list of dictionaries
6. Converts the list into a Pandas DataFrame
7. Exports the DataFrame to `quotes_info.csv`

---



---

## 📊 Output

The generated CSV file contains:

| Quotes | Author | Tags |
| ------ | ------ | ---- |

Example:

| “Life is what happens...” | John Lennon | life, inspirational |

---

## 🎯 Learning Outcome

By completing this project, you will understand:

* How HTTP requests work
* How to parse HTML structure
* How to extract structured data
* How to store scraped data in CSV format
* Basic data handling with Pandas

---

## 🧑‍💻 Author

**Author:** Ranjan Singh

**Project Type:** Web Scraping Project

**Language:** Python


