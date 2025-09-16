# YouTube Video Summarization

This project is a full-stack AI application that automatically converts YouTube videos into concise summaries. It's built with Streamlit and uses powerful AI models to transcribe and summarize video content.

-----

## Features

  - **End-to-End Automation:** Get a summary from a YouTube URL in minutes.
  - **Audio Transcription:** Utilizes **OpenAI's Whisper API** for highly accurate transcription of video audio.
  - **Advanced Summarization:** Employs an **LLM-based Haystack NLP pipeline** with the **Llama 3 model** to generate concise summaries.
  - **User-Friendly Interface:** The application is hosted on Streamlit, providing an intuitive and clean user experience.

-----

## Tech Stack

  - **Frontend:** Streamlit
  - **Backend/Core Logic:** Python
  - **Video Processing:** `pytube`
  - **Transcription:** OpenAI's Whisper API
  - **Summarization:** Haystack NLP Pipeline with Llama 3

-----

## How It Works

1.  **Input:** The user provides a YouTube video URL.
2.  **Download:** `pytube` downloads the audio from the video.
3.  **Transcription:** The audio is sent to **OpenAI's Whisper API** to be transcribed into text.
4.  **Summarization:** The text transcript is fed into a **Haystack NLP pipeline**.
5.  **Output:** The Llama 3 model processes the text and generates a concise summary, which is then displayed to the user.

