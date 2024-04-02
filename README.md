# **AutoGPT Creator App**

This is a personal project that consist of the usage of streamlit and langchain to create an agent that perfomr multiple tasks at a single time given a prompt. 
In this example, the agent creates a youtube video title for the prompt inserted at the beggining and then it creates a script for the video.
This project is built in pyton using streamlit as the web app framework and langchain to get the llm.

## Usage

To run the application:
1. Set your api key (openAI/HuggingFace) in the .env file: `API_KEY_NAME=<YOUR_API_KEY>`
2. Import it in the app.py file: `api_key = os.getenv('API_KEY_NAME')`
3. In the terminal, write the command to start the application: `streamlit run app.py`
4. In the browser of your choice, go to: http://localhost:8501