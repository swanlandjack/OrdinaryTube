# OrdinaryTube
A html script to allow users to look at different topic and search for the most watched Youtube.  Then use Gemini to summarize


# Ordinary Tube Search & AI Summary

A lightweight web application that searches for the most viewed YouTube videos on any topic and automatically generates AI-powered summaries.

## Features

- **Most Viewed Videos**: Find the top-viewed YouTube videos based on your search terms
- **Quick Prompt Bubbles**: Easily search popular news sources with one click (TVB News, CNBC, Bloomberg, BBC, etc.)
- **AI-Powered Summaries**: Automatic video summaries generated using Google's Gemini 2.0 Flash model
- **Time Range Filtering**: Filter results by time period (1 day to 1 year)
- **Multiple Language Support**: Automatic detection and summarization of Chinese content
- **Secure API Key Storage**: Safely store your API keys on your device
- **Mobile-Friendly**: Works on all devices including phones and tablets

## How to Use

1. **Enter Search Terms**: Type keywords or click on the quick prompt bubbles
2. **Set Time Range**: Choose how recent you want the videos to be
3. **Enter API Keys**: 
   - YouTube API Key from [Google Cloud Console](https://console.cloud.google.com/)
   - Gemini API Key from [Google AI Studio](https://aistudio.google.com/app/apikey) (optional for summaries)
4. **Search**: Click the Search button to find videos
5. **View Results**: Results are grouped by search term, showing the most viewed videos first
6. **Read Summaries**: AI-generated summaries appear under each video (if Gemini API is provided)

## API Keys

You'll need to provide your own API keys to use this application:

- **YouTube Data API v3**: Required for searching and retrieving video information
- **Gemini 2.0 Flash API**: Optional, enables AI-powered video summarization

The application securely stores your keys in your browser's local storage when you check "Remember API keys on this device."

## Limitations

- The free YouTube API has a daily quota limit
- Summary quality depends on available video metadata (no actual video transcription)

## Credits

Created by ordinaryjack

## License

[Add your preferred license here]
