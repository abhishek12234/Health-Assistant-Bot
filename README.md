# Gemini Health App

A Streamlit-based Health Management application that utilizes Google Gemini Pro Vision API to analyze uploaded images of food items and calculate their total calorie content. The app prompts the user to upload an image of food, and it returns a detailed breakdown of calorie intake for each food item in the image.

## Features
- Upload an image of food items in `jpg`, `jpeg`, or `png` formats.
- Uses Google Gemini Pro Vision API to recognize food items and calculate their calorie intake.
- Provides a detailed nutritional breakdown of each food item in the image.

## How It Works
1. The user inputs a prompt and uploads an image of food.
2. The application sends the image to Google Gemini Pro Vision API.
3. The API processes the image, recognizes the food items, and calculates the total calories.
4. The results are displayed in a structured format with calorie details for each food item.

## Requirements

Before running the app, ensure you have the following installed:

- Python 3.x
- Streamlit
- Google Gemini Pro Vision API (generativeai)
- Pillow (for image processing)
- python-dotenv (for environment variable management)

You can install the required libraries by running:

```bash
pip install streamlit Pillow python-dotenv google-generativeai
