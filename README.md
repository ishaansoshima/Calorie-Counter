# Calorie-Counter

# Gemini Health App

This is a Streamlit application that uses the Google Gemini Pro Vision API to analyze images of food and calculate the total calories. The app is designed to help users understand the nutritional content of their meals.

## Features

- Upload an image of food
- Calculate the total calories in the image
- Get details of each food item and its calories
- Modern and user-friendly UI/UX

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/gemini-health-app.git
```
2.Install the required packages:
```bash
pip install -r requirements.txt
```
3.Create a .env file in the root directory of the project and add your Google Gemini Pro Vision API key:
```bash
google_api_key=your_api_key_here
```
4.Run the Streamlit app:
```bash
streamlit run app.py
```
## Usage:
Upload an image of food using the file uploader in the sidebar.
Enter any additional input prompt in the text input field in the sidebar.
Click the "Calculate Calories" button.
The app will display the total calories and details of each food item in the main section.
