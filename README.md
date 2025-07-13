# 📊 WhatsApp Chat Analyzer

A Streamlit web application to analyze and visualize WhatsApp chat exports. Gain insights into user activity, message trends, word usage, emoji patterns, and more — all from your personal or group chats.

---

## 🚀 Features

- 📁 Upload `.txt` WhatsApp export (no media)
- 👤 Analyze individual user or entire group
- 🧮 Message, word, media, and link statistics
- 📆 Monthly and daily activity timelines
- 📊 Most active days, months, and hours
- 🔥 Heatmap of weekly activity
- 👑 Most active users (for group chats)
- ☁️ Word cloud of most frequent words
- 📈 Most common meaningful words (after Hinglish stopword removal)
- 😄 Emoji frequency analysis with pie chart

---

## 🛠️ Tech Stack

| Tool / Library   | Purpose |
|------------------|---------|
| **Streamlit**    | Frontend web app interface |
| **Pandas**       | Data manipulation and processing |
| **Matplotlib**   | Line, bar, and pie charts |
| **Seaborn**      | Heatmaps |
| **Regex (`re`)** | Parsing raw WhatsApp text |
| **WordCloud**    | Generating word clouds |
| **emoji**        | Extracting emojis |
| **urlextract**   | Extracting links from messages |

---

## 🧠 How It Works

1. **Upload File**: Select your exported WhatsApp chat `.txt` file.
2. **Preprocessing**: The app parses message timestamps, usernames, and message content using `regex` and `pandas`.
3. **User Selection**: Choose to analyze all users or focus on one.
4. **Insights**: View activity stats, visual charts, emoji usage, and word clouds.

---


## 📂 File Structure

📁 WhatsApp-Chat-Analyzer
├── App.py # Main Streamlit app
├── helper.py # Data processing functions
├── preprocessor.py # Raw text cleaning & parsing
├── stop_hinglish.txt # Custom stopword list
├── requirements.txt # Python dependencies
└── README.md # Project documentation

🙋‍♀️ Author
Made with ❤️ by Tanishka
If you like this project, give it a ⭐ and share it!