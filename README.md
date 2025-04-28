📱 WhatsApp Chat Analyzer

A Streamlit web app that analyzes your WhatsApp chat history to generate insights, statistics, and visualizations like word clouds, emoji analysis, most active users, and timeline activity!

🚀 Features

📊 Basic Statistics: Total messages, words, media files shared, and links.

🗓️ Timelines: Monthly and daily message frequency charts.

🏆 Most Active Users: Shows who chats the most in group chats.

☁️ Word Cloud: Most frequently used words.

📚 Common Words Analysis: Top 20 most used words (ignoring stop words).

😂 Emoji Analysis: Most used emojis and emoji distribution.

📆 Activity Maps: User activity by day and month.

🔥 Weekly Heatmap: Visualizes the busiest hours across the week.

🛠️ Tech Stack

Python 3

Streamlit — Web UI

Pandas — Data manipulation

Matplotlib & Seaborn — Data visualization

WordCloud — Generate word clouds

URLExtract — Extract URLs from chat data

Emoji — Analyze emoji usage

🧩 Project Structure

.
├── app.py            # Main Streamlit app
├── helper.py         # Analysis helper functions
├── preprocessor.py   # Preprocess raw WhatsApp data
├── stop_hinglish.txt # Custom stop words (Hindi + English)
├── Procfile          # For deploying on Heroku
├── setup.sh          # Streamlit server setup for Heroku

📥 How to Run Locally

Clone the Repository

git clone https://github.com/YOUR_USERNAME/whatsapp-chat-analyzer.git
cd whatsapp-chat-analyzer

Install Requirements

pip install -r requirements.txt

(You might need to create a requirements.txt if not already — I can help generate one too!)

Run the Streamlit App

streamlit run app.py

Upload your WhatsApp chat file (.txt) from sidebar and explore the analytics!

🧹 How to Export WhatsApp Chat

Open WhatsApp → Chat you want to export → More → Export Chat → Without Media → Save as .txt file.

🚀 Deploy to Heroku

This project is ready for deployment on Heroku:

Procfile and setup.sh are included!

Just create a Heroku app and push your code!

📸 Screenshots

Feature

Example

Top Statistics

📊 Total messages, words

Word Cloud

☁️ Visualization of top words

Emoji Analysis

😂 Top used emojis

Weekly Activity Heatmap

🔥 Hourly activity heatmap

🙏 Acknowledgements

Inspired by WhatsApp data and the amazing Streamlit community.

Thanks to all open-source library contributors!

📜 License

This project is licensed under the MIT License — free for personal and commercial use.

🔥 Let's Connect!

If you like this project, don't forget to ⭐️ star the repository!

✅ Done!
