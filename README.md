# Vision Language Model for Dietary Analysis

## Overview

**Vision Language Model for Dietary Analysis** is a cutting-edge application that leverages Google's Gemini Pro Vision API to analyze images of food and provide detailed dietary information. The app uses an advanced Vision Language Model (VLM) to identify food items in an image, calculate their calorie content, and deliver a comprehensive nutritional breakdown.

## Features

- **Image-Based Food Analysis**: Upload an image of your meal, and the app will identify each food item.
- **Calorie Calculation**: The app calculates the total calorie intake based on the identified food items.
- **Detailed Nutritional Information**: Get a breakdown of calories per food item for better dietary management.
- **Streamlit Integration**: A user-friendly interface built with Streamlit for easy access and use.

## Technology Stack

- **Google Gemini Pro Vision API**: For food recognition and analysis.
- **Streamlit**: Web framework for building the app interface.
- **Python**: Core programming language used.
- **Pillow (PIL)**: For image handling and processing.
- **dotenv**: For environment variable management.

## Installation

### Prerequisites

- Python 3.7+
- Google Cloud API Key with access to Gemini Pro Vision API

### Setup

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/vision-language-model-dietary-analysis.git
    cd vision-language-model-dietary-analysis
    ```

2. Create and activate a virtual environment:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Set up your environment variables:
    - Create a `.env` file in the root directory.
    - Add your Google API key:
      ```env
      GOOGLE_API_KEY=your_google_api_key_here
      ```

## Usage

1. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```

2. Upload an image of a meal.
3. Enter any specific input prompt if needed.
4. Click "Tell me the total calories" to get a detailed analysis of the food items and their calorie content.

## Example Output

![Screenshot 2024-09-03 212712-Photoroom](https://github.com/user-attachments/assets/7e336cac-8be6-44a5-8282-0525f3879e96)
![Screenshot 2024-09-03 212632-Photoroom](https://github.com/user-attachments/assets/300a32eb-6df4-4bcc-a852-64ef8f0c4ab5)


## Contributing

Contributions are welcome! Please fork this repository, make your changes, and submit a pull request.

## Contact

For any inquiries or issues, please contact ayushkumawat2112@gmail.com.
