# YouTube Audio Download and Transcription Script

This script downloads audio from YouTube videos, transcribes it using OpenAI's Whisper model, and saves the transcriptions to a CSV file. It supports **bulk processing**, allowing multiple videos to be downloaded and transcribed concurrently for faster results.

## How to Use

You can run this script in **Google Colab** or in any **local Python environment**.

### Requirements

#### 1. Input CSV
Prepare a CSV file named `video_data.csv` with the following structure:
- **link**: YouTube video URLs
- **title**: Titles of the videos

Example:
```csv
link,title
https://www.youtube.com/watch?v=example,Example Video Title
