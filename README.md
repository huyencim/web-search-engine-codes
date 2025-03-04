# Search Engine Codes (Python)

## 📌 Project Overview

This project is a **simple search engine** that crawls web pages, extracts links, indexes content, and ranks pages using a simplified **PageRank algorithm**. It is implemented in Python.

## 🛠️ Features

✅ **Web Crawling:** Extracts links from web pages using `urllib.request`.
✅ **Indexing:** Stores words and their associated URLs.
✅ **Page Ranking:** Implements a simplified **PageRank** algorithm.

## 📂 Files in This Repository

- **Search\_engine\_codes.ipynb** – The main Python notebook containing the implementation.

## 🚀 How to Use

1. Clone this repository:
   ```bash
   git clone <repo_link>
   cd <repo_folder>
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Search_engine_codes.ipynb
   ```
3. Run all cells to crawl a website, index content, and compute page ranks.

## 📜 Code Explanation

### Web Crawling:

- **`getPage(url)`**: Fetches HTML content from a given URL.
- **`get_all_links(page)`**: Extracts all hyperlinks from the page.
- **`crawlWeb(seed_url)`**: Crawls the web starting from a seed URL, creating an index and a link graph.

### Page Ranking:

- **`computeRanks(graph)`**: Implements PageRank by iterating over pages and updating ranks based on inbound links.

## 📈 Example Output

When running `crawlWeb()`, the program will print:

```python
{'https://example.com/page1': 0.15, 'https://example.com/page2': 0.25, ...}
```

These values indicate the **importance of each page** based on its connections.

##

---

**📩 Feel free to reach out if you have any questions!**

