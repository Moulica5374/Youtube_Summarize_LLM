# YouTube Transcript Summarizer using LangChain and LLaMA 3.1

This project is a real-time web application that summarizes YouTube video transcripts. It uses LangChain to interface with the Together.AI API, running Meta LLaMA 3.1 (8B Instruct Turbo) for accurate summarization.

## Features

- Extracts subtitles directly from YouTube videos using the youtube-transcript-api
- Summarizes the transcript using LangChain and LLaMA 3.1 hosted by Together.AI
- Provides a clear summary and five key points from the video
- Simple and accessible web interface built with Gradio

## Tech Stack

Component            | Technology Used
---------------------|-------------------------
Frontend             | Gradio
Backend              | Python, LangChain, LangChain-Together
Language Model       | Meta-LLaMA 3.1 via Together.AI
Transcript Extraction| youtube-transcript-api
Orchestration        | LLMChain and PromptTemplate from LangChain
Deployment           | Localhost or Hugging Face Spaces

## Setup Instructions
pip install gradio langchain langchain-together youtube-transcript-api

api = "your_actual_together_api_key"

export TOGETHER_AI_API_KEY="your_actual_together_api_key"

Sample Input
YouTube URL:
https://www.youtube.com/watch?v=5MgBikgcWnY

Output
Concise summary of the video's purpose

Five clearly extracted key points

Credits
youtube-transcript-api

Together.AI

LangChain

Meta LLaMA 3.1

