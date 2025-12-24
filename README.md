🛒 Product Sentiment Analyzer & Review Dashboard

A web-based application that automatically collects product reviews from e-commerce platforms, analyzes customer sentiment using NLP techniques, and presents insights through an interactive dashboard.

📌 Overview

The Product Sentiment Analyzer helps users understand customer opinions by converting raw product reviews into Positive, Neutral, and Negative sentiments.
It saves time, reduces manual effort, and supports better decision-making for customers and businesses.

✨ Features

🕷️ Automated Review Scraping: Collects product reviews dynamically using Selenium

🧹 Data Cleaning: Removes noise like special characters and stopwords

💬 Sentiment Analysis: Classifies reviews as Positive, Neutral, or Negative using NLP

📊 Interactive Dashboard: Visual representation using charts and graphs

🔍 Product Search: Search and analyze reviews for specific products

💾 Data Storage: Stores processed data securely in a database

⚡ Fast Insights: Real-time sentiment trends and summaries

🧰 Tech Stack
Frontend

HTML

CSS

JavaScript

Chart.js / Plotly

Backend

Python

Flask / Django

Web Scraping

Selenium

BeautifulSoup

NLP & Data Processing

Pandas

NLTK / TextBlob / VADER

Database

SQLite / MySQL / MongoDB

Tools

VS Code

Chrome WebDriver

Git & GitHub

🚀 Workflow (Flow Explanation)

User enters the product name

System scrapes product reviews from e-commerce sites

Collected reviews are cleaned and preprocessed

Sentiment analysis is performed on each review

Results are stored in the database

Dashboard generates visual insights

Sentiment results are displayed to the user

🛠️ Installation & Setup
1. Clone the Repository
git clone <repo-url>
cd product-sentiment-analyzer

2. Install Dependencies
pip install -r requirements.txt

3. Setup WebDriver

Download Chrome WebDriver

Add it to system PATH

4. Run the Application
python app.py


Access the application at:
👉 http://localhost:5000

📂 Project Structure
product-sentiment-analyzer/
├── frontend/
│   ├── templates/          # HTML files
│   ├── static/
│   │   ├── css/            # Stylesheets
│   │   └── js/             # JavaScript files
├── backend/
│   ├── scraper.py          # Web scraping logic
│   ├── sentiment.py        # NLP sentiment analysis
│   ├── database.py         # Database operations
│   └── app.py              # Flask/Django app
├── data/
│   └── reviews.db          # Stored review data
├── requirements.txt
└── README.md

📊 Dashboard Output

Sentiment Distribution (Pie Chart)

Review Count (Bar Chart)

Overall Product Rating Trend

✅ Advantages

Saves time and manual effort

Accurate sentiment classification

Easy-to-understand visual insights

Useful for customers, sellers, and researchers

Scalable for multiple products and platforms

🌍 Applications

E-commerce product analysis

Customer feedback evaluation

Market research

Competitive product comparison

Business decision support

🔮 Future Enhancements

 Multi-platform scraping (Amazon, Flipkart, etc.)

 Aspect-based sentiment analysis

 User login and product comparison

 Export reports as PDF/CSV

 AI-powered recommendation system

🤝 Contributing

Contributions are welcome!
Feel free to fork the repository, open issues, or submit pull requests.

📜 License

MIT License – See the LICENSE file for details.

🙌 Credits

Built with ❤️ using Python, NLP, and Web Technologies.
