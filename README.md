# 📰 EXPRESS60 - News Summarizer App

Express60 is a Flask-based web application that helps users quickly grasp the essence of any news article. It fetches news based on keywords and provides both direct links to read and AI-generated summaries.

 🚀 Features

- 🔍 Search news by topic or keyword.
- 📖 Extract full text from news article URLs.
- 🧠 Summarize articles using NLP techniques (manual algorithm, not just built-in summarizer).
- 🌗 Light & Dark theme toggle.
- 📱 Responsive design for mobile and desktop.
- ❌ Handles empty or failed requests gracefully.

💡 How it Works

1. User searches for a topic (e.g., "science").
2. NewsAPI fetches the top related news.
3. Each article has options:
   - "Read More" opens the original source.
   - "Summary" sends the article to Flask backend for summarization.
4. The summary is created using:
   - Tokenization
   - Stopword removal
   - Frequency-based scoring
   - Extractive summarization via sentence ranking

🛠 Tech Stack

Frontend  
- HTML, CSS (with media queries for responsiveness)  
- Vanilla JavaScript  
- FontAwesome for icons  

Backend 
- Python with Flask  
- `newspaper3k` for article scraping  
- `NLTK` for tokenization  
- Custom summarization logic (not built-in)

📦 Installation

1. Clone the repository
   
   git clone https://github.com/your-username/Express60.git
   cd Express60

2. Install Python dependencies
pip install flask newspaper3k nltk

3.Add your NewsAPI key
const CONFIG = {
    API_KEY: "YOUR_NEWS_API_KEY"
}
4. RUN : python app.py

Contributing:

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

Please feel free to contact : kamathamrutha27@gmail.com

Thank you!!!!!



