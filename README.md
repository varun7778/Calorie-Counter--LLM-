# Calorie Counter App

This application utilizes Google AI's Gemini Pro Vision API to estimate the total calories and provide a breakdown of individual food items with their estimated calorie counts from a provided image.

Model Used: 'gemini-pro-vision'

## Prerequisites

- Python 3.10 or later
- Installed libraries:
    - streamlit
    - google-generativeai
    - python-dotenv
    - langchain
    - PyPDF2
    - chromadb
    - pdf2image
    - faiss-cpu
    - langchain-google-genai
  
- A Google API key with access to the Gemini Pro Vision API

## Setup

1. Create a .env file in the same directory as the Python script and add the following line:

   ```
   GOOGLE_API_KEY=YOUR_API_KEY
   ```

   Replace `YOUR_API_KEY` with the actual Google API key.

2. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

## Running the App

1. Navigate to the directory containing the Python script in your terminal.
2. Execute the following command to start the Streamlit app:

   ```bash
   streamlit run app.py
   ```

## Using the App

1. **Upload an image:** Click the "Choose an image..." button and select a food image in JPG, JPEG, or PNG format.
2. **Enter an optional prompt:** If desired, provide additional context in the "Input Prompt" field.
3. **Click "Total calories" button:** The app will process the image, communicate with the Gemini Pro Vision API, and display the estimated total calories and a breakdown of individual food items with their calorie counts.

## Preview
![alt text](https://github.com/varun7778/Calorie-Counter-LLM/blob/9281c4e8a29f59a403d3303a1c4958318bbb5f90/img/1.png)

![alt text](https://github.com/varun7778/Calorie-Counter-LLM/blob/9281c4e8a29f59a403d3303a1c4958318bbb5f90/img/2.png)
