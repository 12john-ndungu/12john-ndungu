# Sentiment Analysis Flask Application

This project is a web application for sentiment analysis using Flask. The application predicts the sentiment (positive or negative) of a given text input using a pre-trained Logistic Regression model using data from twitter

 Features

- User-friendly web interface for text input
- Sentiment prediction (positive or negative)

## Installation

1. **Clone the repository**
    ```sh
    git clone https://github.com/your-username/sentiment-analysis-flask.git
    cd sentiment-analysis-flask
    ```

2. **Create and activate a virtual environment**
    ```sh
    python3 -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install dependencies**
    ```sh
    pip install -r requirements.txt
    ```

4. **Run the Flask application**
    ```sh
    python app.py
    ```

## Usage

- Open your browser and go to `http://127.0.0.1:5000/`
- Enter your text and click "Analyze" to get the sentiment prediction

## NOTE
Sign up for an account at ngrok
Get your authtoken from the ngrok dashboard
