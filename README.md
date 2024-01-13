# Gemini-Image-Analyzer

This application uses Google's Generative AI to analyze images and generate responses based on the input prompt. The application is built using Streamlit, a popular framework for building machine learning and data science web apps.

# Getting Started

This project is a Streamlit web application that utilizes Google's Generative AI to analyze images and generate responses based on the input prompt. It's designed to be easy to set up and run locally.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have installed Python 3.8+
- You have installed pip, which is a package manager for Python. Most Python installations come with pip preinstalled. If not, you can download it from the [official website](https://pip.pypa.io/en/stable/installation/).

## Installing Dependencies

To install the necessary dependencies, open your terminal and navigate to the directory where you cloned this repository. Then, run the following command:

```
pip install -r requirements.txt

```
# Setting Up Environment Variables

This application uses environment variables to store sensitive information such as API keys. To set these up, create a `.env` file in the root directory of the project and add your Google API key like so:

```
GOOGLE_API_KEY=your_google_api_key_here
```
# Running the Application

To run the application, navigate to the directory containing the script and run the following command:

```
streamlit run app.py
```
Replace app.py with the name of your Python script. This will start the Streamlit server and open the application in your default web browser.

Now, you should be able to interact with the application through your web browser. Simply enter your input prompt, upload an image, and click on "Tell me about the image" to generate a response based on the input image and prompt.
