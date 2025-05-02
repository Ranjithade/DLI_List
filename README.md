# 🇨🇦 Designated Learning Institutions (DLI) List Scraper

A Python script that scrapes the official list of Designated Learning Institutions (DLIs) from the Government of Canada website and organizes the data by province/territory. Ideal for international students, immigration consultants, and anyone tracking eligible institutions for study permits.

## 📌 Features

- ✅ Scrapes DLI data for all provinces and territories
- 🏫 Captures key info: institution name, city, DLI number, and campus details
- 📍 Maintains province selection context from dynamic dropdown
- 📄 Outputs data as a structured table (e.g., HTML or CSV)
- 🔄 Can be scheduled for periodic updates

## 📁 Output

- An organized table of DLIs per province
- Downloadable formats supported (CSV, HTML)
- Province name included in each record for easy filtering

## 📸 Sample Output

| Province     | Institution Name                    | City         | DLI Number |
|--------------|-------------------------------------|--------------|------------|
| Ontario      | University of Toronto               | Toronto      | O19332746152 |
| British Columbia | University of British Columbia  | Vancouver    | O19330231062 |

## 🛠️ Technologies Used

- `requests` – fetch HTML content
- `BeautifulSoup` – parse HTML
- `selenium` – (optional) handle dynamic dropdowns
- `pandas` – for data organization and export

## 🚀 Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/dli-list-scraper.git
   cd dli-list-scraper


Install dependencies:

pip install -r requirements.txt
python dli_scraper.py

🌐 Data Source
All data is publicly available and sourced from:
Canada.ca - DLI List
