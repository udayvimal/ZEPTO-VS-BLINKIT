# ZEPTO-VS-BLINKIT
🛒 Blinkit vs Zepto Platform Analysis – Data Generation, Scraping & Business Intelligence
📌 Overview
This project presents a complete business intelligence and market comparison analysis between India’s top quick-commerce grocery platforms – Zepto and Blinkit.

We simulate real-world data using the Faker library for orders and also scrape actual category-wise product data from Blinkit & Zepto using Selenium + BeautifulSoup.

Key deliverables:

✅ Web scraping code for live product/category data

✅ Synthetic order-level dataset with ~10K records

✅ Tableau dashboards for category dominance, delivery time, value split, etc.

✅ Business insights and comparison presented in PowerPoint

✅ All data transformation in Jupyter Notebook

✅ GitHub repository with code, data & outputs

🗂️ Project Structure
kotlin
Copy
Edit
📁 grocery-platform-analysis
├── 📄 README.md
├── 📁 notebooks/
│   TABLEAU PUBLIC LINK -
├── 📁 scripts/
│   └── web_scraper_blinkit_zepto.py
├── 📁 tableau/
│   ├── zepto_vs_blinkit.twbx
│   └── tableau_public_links.txt
├── 📁 ppt/
│   └── Blinkit_vs_Zepto_Analysis_Presentation.pptx
🧪 1. Data Generation
Using Python’s Faker library, we generated a simulated e-commerce order dataset that mimics Blinkit and Zepto platforms.

Key Features:

order_id, order_date, order_time

city, store_id, product_category

order_value, discount_amount, net_order_value

delivery_time_min, platform, payment_method

Script used:
notebooks/data_generation.ipynb

🔍 2. Web Scraping
We built a Python script using Selenium and BeautifulSoup to extract live product category data from:

🌐 https://www.zepto.app/

🌐 https://www.blinkit.com/

Scraped Data Includes:

Product title

Category (Snacks, Dairy, Beverages, etc.)

Subcategory

Price

Platform name

Script used:
scripts/web_scraper_blinkit_zepto.py

✅ CSV output used in Tableau & PowerPoint.

📊 3. Exploratory Data Analysis
Performed in Jupyter using Pandas, Seaborn, and Matplotlib.

Insights Uncovered:

Platform-wise delivery performance

Payment method preferences

High-performing product categories

Avg. discount trends per platform

Notebook:
notebooks/exploratory_analysis.ipynb

📈 4. Tableau Dashboards
Created 6+ insightful dashboards using Tableau Public:

Dashboard	Description
🧾 Order Distribution	Platform-wise order frequency by category
📦 Category Leadership	Zepto vs Blinkit – product category strengths
⏱ Delivery Time Analysis	Avg. delivery duration by platform
💳 Payment Methods	UPI vs COD vs Cards comparison
🏷 Discount vs Net Value	Platform pricing strategy overview
🏆 Overall Winner	Final strategic analysis from user perspective

🔗 Tableau Public Link:
🌐 View Dashboards on Tableau

🖼 5. Business Insights Report (PowerPoint)
Presentation file:
ppt/Blinkit_vs_Zepto_Analysis_Presentation.pptx

Includes:

Project Intro & Goals

Data source explanation (Faker + Web Scraped)

Key visual dashboards from Tableau

Strategic insights in business-friendly format

Platform comparison table (who’s winning where)

Suggestions for both platforms

🧠 Key Insights Summary
Category	Zepto	Blinkit
Dairy, Vegetables, Beverages	✅ Strong	⚠️ Weak
Snacks, Fruits, Frozen, Household	⚠️ Weak	✅ Strong
Delivery Speed	⚡ Fast	🚚 Slightly Slower
Average Discount	High	Moderate
User Friction	Users split orders	Same
Opportunity	Push snack bundles	Improve daily staples
Winner?	Groceries & essentials	Quick buys & treats

💡 How to Run Locally
Clone this repo:

bash
Copy
Edit
git clone https://github.com/udayvimal/grocery-platform-analysis.git
cd grocery-platform-analysis
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run data generator:

bash
Copy
Edit
jupyter notebook notebooks/data_generation.ipynb
Run scraper (requires ChromeDriver):

bash
Copy
Edit
python scripts/web_scraper_blinkit_zepto.py
Explore dashboards:

Open Tableau file in tableau/zepto_vs_blinkit.twbx
OR

Visit Tableau Public link.

🔗 Links
📈 Tableau PUBLIC LINK SHEETS: 

📎 PowerPoint Report: Download from repo

📂 Datasets Used: See data/ folder

📜 Analysis Notebook: notebooks/exploratory_analysis.ipynb

👨‍💻 Author
Uday Vimal
📬 LinkedIn
🎓 Data Analyst | BI Developer | Python + SQL + Tableau Enthusiast
