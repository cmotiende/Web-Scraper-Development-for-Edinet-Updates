# Web-Scraper-Development-for-Edinet-Updates
# Edinet Filings Scraper

A Python-based prototype that scrapes shareholder filings from the [Edinet website](https://disclosure2.edinet-fsa.go.jp/week0020.aspx) using an entity code. This tool is designed to extract daily updates and prepare them for translation, summary, and email reporting.

---

## 🔧 Features

- Accepts an **EDINET entity code** (e.g., `E00045`)
- Scrapes relevant links and document titles from the Edinet filings page
- Saves results into a clean, CSV format
- Modular and ready to be extended with:
  - Japanese-to-English translation
  - Auto-summary generation
  - Email automation for daily delivery

---

## 📁 Output

- A `.csv` file containing:
  - Filing title
  - Filing URL

Example: `edinet_filings_E00045.csv`

---

## 🚀 Usage

### 1. Clone the repository
```bash
git clone https://github.com/your-username/edinet-scraper.git
cd edinet-scraper
