# YouTube Video Summarizer

A Python application that summarizes YouTube videos based on user-provided links using OpenAI's GPT-3.5 Turbo model.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Demo](#demo)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project aims to simplify the process of summarizing YouTube videos. Users can provide a YouTube video link and a question, and the application will generate a summary of the video based on the provided input. The summarization process leverages the YouTube transcript and OpenAI's GPT-3.5 Turbo model for generating concise summaries.

## Features

- Extracts video transcripts from YouTube videos.
- Utilizes OpenAI's GPT-3.5 Turbo model for natural language summarization.
- Provides a user-friendly Gradio interface for easy interaction.

## Prerequisites

Before you get started, make sure you have the following prerequisites:

- Python 3.x
- Required Python packages: `openai`, `gradio`, and `youtube_transcript_api`
- An OpenAI API key (you can sign up for an API key on the [OpenAI website](https://beta.openai.com/signup/))

## Installation

1. Clone the GitHub repository:

   ```bash
   git clone https://github.com/abhaypancholi/YouTube-Video-Summarizer.git
   ```

2. Install the required Python packages:

   ```bash
   pip install openai gradio youtube_transcript_api
   ```

3. Set up your OpenAI API key:
   
   - Sign up for an API key at [OpenAI](https://beta.openai.com/signup/).
   - Replace `'your-api-key-here'` in the `openai.api_key` assignment with your actual API key in the `Summarizer` class.

## Usage

1. Run the application using the Gradio interface:

   ```bash
   python your_script.py
   ```

2. Access the interface in your web browser at `http://localhost:7860`.

3. Provide the YouTube video URL and your question.

4. Click the "Summarize" button to receive the video summary.

## Demo

You can access a live demo of the YouTube Video Summarizer [here](https://yourdemo.com).

## Contributing

Contributions are welcome! If you would like to improve this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Create a pull request.

## Contact
If you have any doubts feel free to connect with me on [LinkedIn](www.linkedin.com/in/abhaypancholi).
