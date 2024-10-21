#🦜 LangChain: Summarize Text From YT or Website

This Streamlit application leverages LangChain and Groq's LLM API to summarize content from YouTube videos or websites. The app allows users to input a YouTube video URL or a generic website URL and get a concise 300-word summary of the content.

##🛠 Features

1.Summarizes content from YouTube videos or web pages.
2.Uses Groq's Gemma-7b-It language model API for generating summaries.
3.Validates the input URL before processing.
4.Streamlit-based UI for ease of use.

##🧰 Technologies Used

1.LangChain: Framework for building applications with LLMs.
2.Groq LLM: Chat-based LLM for generating summaries.
3.Streamlit: Web app framework for the user interface.
4.Python Validators: For URL validation.
5.YoutubeLoader & UnstructuredURLLoader: For loading content from YouTube videos or websites.

##📑 How It Works

1.The user provides a Groq API key and enters a valid YouTube or website URL.
2.The URL is validated, and the corresponding content is fetched using either YoutubeLoader or UnstructuredURLLoader.
3.The content is then summarized using a pre-defined prompt template via LangChain's summarization chain.
4.The result is displayed in the app.

##🔧 Setup and Installation

1.To run this project locally, follow these steps:
2.Clone the repository
3.Create a virtual environment
4.Install the required dependencies
5.Run the app

##🚀 Usage

1.Open the app in your browser (http://localhost:XXXX).
2.Enter your Groq API Key in the sidebar.
3.Input a YouTube URL or a website URL to summarize.
4.Click on Summarize the Content to get the summary.

##File Structure:

|-- app.py             # The main application code
|-- requirements.txt   # Required dependencies
|-- README.md          # Documentation

