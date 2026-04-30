# SimpleWebScraperTool
A simple Python web scraping tool that extracts webpage title, paragraphs, text, anchor tags, and links using requests and BeautifulSoup. It processes any given URL and saves structured output into a text file, making it ideal for beginners and quick data extraction tasks.

🌐 Web Scraping Tool using Python

A simple and efficient Python-based web scraping tool that extracts useful information from any webpage, including titles, paragraphs, links, and formatted HTML content.

---

📌 Features

* Extracts webpage title
* Collects all paragraph tags
* Retrieves the first paragraph element
* Extracts all visible text from the webpage
* Collects all anchor tags 
* Extracts all links from anchor tags
* Outputs formatted (prettified) HTML
* Saves all results into a file (output.txt)

---

🛠️ Technologies Used

* Python 3
* requests – for fetching web pages
* BeautifulSoup (bs4) – for parsing HTML

---

📂 Project Structure
```
web-scraper/
│── scraper.py
│── output.txt
│── README.txt
```
---

⚙️ Installation

1. Clone the Repository
```sh
git clone https://github.com/subhankar505s/SimpleWebScraperTool.git
cd SimpleWebScraperTool
```
2. Create Virtual Environment (Optional but Recommended)
```sh
python -m venv venv
```
Activate it:

Windows:
```sh
venv\Scripts\activate
```
Linux/Mac:
```sh
source venv/bin/activate
```
3. Install Dependencies
```sh
pip install requests
pip install html5lib
pip install bs4
```
---

🚀 How to Run
```sh
python scraper.py
```
Then enter any URL when prompted:

Enter or Paste the URL to Crawl:
``` https://example.com ```

---

📄 Output

The extracted data will be saved in:

output.txt

It includes:

* Title of the webpage
* All paragraphs
* First paragraph element
* All text content
* All anchor tags
* Extracted links
* Prettified HTML

---

⚠️ Error Handling

* Handles invalid URLs
* Displays errors if the request fails
* Prevents crashing using try-except

---

🧠 Notes

* Make sure the URL includes http:// or https://
* Some websites may block scraping (use responsibly)
* Links extracted may be relative

---

⚡ Future Improvements

* Add support for relative URL handling
* Export data in JSON/CSV format
* Add GUI or web interface
* Implement multi-page crawling

---

👨‍💻 Author

Subhankar Mohanta

---

📜 License

This project is open-source and available under the MIT License.
