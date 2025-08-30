# 🎥 YouTube Video Analyzer

> **CSUF 2024 Spring Hackathon Project**  
> An intelligent YouTube video analysis platform that transcribes, summarizes, and analyzes video content with sentiment analysis capabilities.

## 🌟 Features

- 🗣️➡️📄 **Transcribe YouTube Videos**: Automatically convert spoken content into text using advanced speech recognition
- ✍️ **Summarize Transcripts**: Generate concise, intelligent summaries of long video transcripts
- 😊😐😢 **Sentiment Analysis**: Analyze the emotional tone of video comments (positive, neutral, negative)
- 📊📈 **Metadata Display**: Comprehensive video statistics including views, likes, channel information, and comment metrics
- 🎛️ **Interactive Dashboard**: Beautiful, user-friendly interface built with **Streamlit** for seamless interaction and data visualization

## 🚀 Demo
\

## 🛠️ Tech Stack

- **Frontend**: Streamlit
- **Backend**: Python
- **APIs**: YouTube Data API, Speech Recognition APIs
- **ML/NLP**: Natural Language Processing libraries for sentiment analysis and summarization
- **Data Processing**: Pandas, NumPy

## 📋 Prerequisites

Before you begin, ensure you have the following installed:
- Python 3.8 or higher
- pip (Python package manager)
- YouTube Data API key (from Google Cloud Console)

## ⚡ Quick Start

### 1. Clone the Repository
```bash
git clone <repository-url>
cd Topiks
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Set Up API Keys
Create a `.env` file in the root directory and add your API keys:
```env
YOUTUBE_API_KEY=your_youtube_api_key_here
OPENAI_API_KEY=your_openai_api_key_here  # Optional: for enhanced summarization
```

### 4. Run the Application
```bash
streamlit run app.py
```

### 5. Open Your Browser
Navigate to `http://localhost:8501` to start analyzing YouTube videos!

## 🎯 How to Use

1. **Enter YouTube URL**: Paste any YouTube video URL into the input field
2. **Analyze**: Click the analyze button to start processing
3. **View Results**: 
   - See the auto-generated transcript
   - Read the AI-powered summary
   - Explore comment sentiment analysis
   - Check detailed video metadata
4. **Export**: Download results for further analysis


## 🔧 Configuration

### API Setup
1. **YouTube Data API**:
   - Go to [Google Cloud Console](https://console.cloud.google.com/)
   - Enable YouTube Data API v3
   - Create credentials and get your API key

2. **Optional APIs**:
   - OpenAI API for enhanced summarization
   - Additional speech recognition services


##  Hackathon Details

- **Category**: AI/ML Application
- **Theme**: Intelligent Content Analysis


