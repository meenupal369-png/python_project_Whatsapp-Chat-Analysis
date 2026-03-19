# python_project_Whatsapp-Chat-Analysis
💬 WhatsApp Chat Analysis
# 🌟 Overview

This project implements an interactive WhatsApp chat analysis system that provides meaningful insights from exported chat data. The system processes raw chat text files and transforms them into structured data for analysis.

The dashboard is built using Streamlit, allowing users to upload their chat file and instantly visualize statistics such as message count, activity trends, most active users, common words, and emoji usage.

# ✨ Features

Chat Data Processing: Converts raw WhatsApp chat text into structured format using preprocessing techniques

User-wise Analysis: Analyze chat statistics for individual users or overall group

Interactive Dashboard: Built with Streamlit for real-time interaction

Text Analysis: Identifies most common words by removing stop words (including Hinglish)

Emoji Analysis: Tracks most frequently used emojis

# Activity Tracking:

Daily and monthly message trends

Most active days and months

Heatmap for user activity by time

Media & Link Insights: Counts shared media files and links

# 💾 Data Source

The system works with:

WhatsApp Chat Export (.txt file):
Contains raw chat data including:

Messages

User names

Timestamps

Media and links

# stop_hinglish.txt:
Custom stop words list used to clean text data for better analysis

# 🛠️ Technologies Used

Python

Pandas (Data Processing)

Streamlit (Web App Framework)

Matplotlib & Seaborn (Data Visualization)

Regex (Text Parsing)

URLExtract (Link Extraction)

Emoji Library (Emoji Analysis)

# 📊 Key Functionalities

Displays key chat statistics:

📩 Total messages

📝 Total words

📎 Media shared

🔗 Links shared

Identifies:

👤 Most active users

🔤 Most common words

😀 Emoji usage patterns

Generates:

📈 Monthly & daily timelines

📊 Bar charts for user activity

🥧 Emoji distribution charts

🔥 Heatmaps for activity patterns

Provides user-friendly interface with file upload and dynamic filtering
