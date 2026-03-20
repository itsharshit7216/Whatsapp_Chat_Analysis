# WhatsApp Chat Analyzer 📊📱

A comprehensive Streamlit web application to analyze and visualize your exported WhatsApp chat data. Gain insights into your texting habits, identify the most active group members, and view activity trends over time!

## 🌟 Features

- **Overall Statistics:** At-a-glance view of total messages, total word count, media shared, and links sent.
- **Activity Timelines:** View message volume across daily and monthly timelines.
- **Activity Maps:** Heatmaps and bar charts to figure out your most active days of the week and months of the year.
- **Busiest Users:** (For groups) See who messages the most with beautiful visualizations and data tables.
- **Word Clouds & Most Common Words:** Discover the most frequently used words by you and your friends, automatically excluding common stop words.
- **Emoji Analysis:** Detailed breakdown and pie chart distribution of the emojis shared in the chat.

## 🚀 Installation & Local Setup

### Prerequisites

Ensure you have Python installed on your system. 

### 1. Download or Clone the project

Navigate to the project directory containing `app.py`.

### 2. Install dependencies

Install the required Python packages using pip:
```bash
pip install -r requirements.txt
```

### 3. Run the application

Start the server using Streamlit:
```bash
python -m streamlit run app.py
```
After executing this command, your default web browser should automatically open and navigate to `http://localhost:8501`.

## 🛠️ How to Export your WhatsApp Chat

1. Open the WhatsApp chat you want to analyze on your phone.
2. Tap the **three dots** in the top right corner > **More** > **Export chat**.
3. Choose **Without Media**.
4. Save the generated `.txt` file to your computer.
5. Upload the `.txt` file using the sidebar in the Streamlit app!

## 📦 Built With

- [Streamlit](https://streamlit.io/) - Web framework
- [Pandas](https://pandas.pydata.org/) - Data manipulation
- [Matplotlib](https://matplotlib.org/) & [Seaborn](https://seaborn.pydata.org/) - Data visualization
- [WordCloud](https://github.com/amueller/word_cloud) - Word cloud generation
- [urlextract](https://github.com/lipoja/URLExtract) - URL extraction
- [emoji](https://pypi.org/project/emoji/) - Emoji parsing

---
*Original Demo Link: [wca-campusx.herokuapp.com](https://wca-campusx.herokuapp.com/) (Service availability may vary)*
