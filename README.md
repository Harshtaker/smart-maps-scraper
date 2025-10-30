# 🧠 Smart Maps Scraper

Smart Maps Scraper is an intelligent web scraping tool that extracts business **Name, Website, Email, and Phone** details directly from **Google Maps** — enhanced with **AI-assisted data cleaning** and a sleek **Streamlit interface**.

---

## ✨ Features

- 🗺️ **Scrape Google Maps** listings automatically  
- 🔍 **Search by city and business type** (e.g., "restaurants in Delhi")  
- 🌐 **Crawls business websites** to extract real emails & phone numbers  
- ⚡ **Multi-threaded scraping** for faster performance  
- 🧩 **Streamlit UI** for simple one-click operation  
- ⏹️ **Stop scraping anytime** using the built-in stop button  
- 📊 **Auto CSV Export** with all collected data  
- 🧠 **AI cleaning & filtering** (powered by OpenAI API, optional)

---

## 🧰 Tech Stack

| Component | Description |
|------------|-------------|
| **Python 3.12+** | Core programming language |
| **Selenium (Edge)** | For automated Google Maps interaction |
| **Requests + Regex** | For extracting emails and phone numbers |
| **ThreadPoolExecutor** | To crawl multiple sites in parallel |
| **Streamlit** | Interactive web UI |
| **dotenv** | For managing API keys securely |

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Harshtaker/smart-maps-scraper.git
cd smart-maps-scraper
2️⃣ Create a Virtual Environment
bash
Copy code
python -m venv .venv
.venv\Scripts\activate
3️⃣ Install Dependencies
bash
Copy code
pip install -r requirements.txt
4️⃣ Add Your OpenAI API Key
Create a .env file in the root folder:

bash
Copy code
OPENAI_API_KEY=your_api_key_here
🚀 Running the App
Run Streamlit Interface
bash
Copy code
streamlit run app.py
Once launched, open the provided local URL (usually http://localhost:8501) in your browser.

🧩 Usage Guide
Enter your City (e.g., Lucknow)
Enter a Business Keyword (e.g., marketing agencies, hospitals, software companies)
Choose how many businesses to scrape (up to 500)
Click “🚀 Start Scraping”
Wait for results and download the CSV file



⚠️ Notes
Only scrapes publicly available data.
Designed for educational and research purposes only.
Requires a stable internet connection and Microsoft Edge installed.

🧑‍💻 Developer
Harsh Shukla
🎓 B.Tech IT | Rajkiya Engineering College, Ambedkar Nagar
💼 Passionate about automation, AI tools, and full-stack development
📧 [harshshukla0303@gmail.com]

