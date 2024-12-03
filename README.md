
# SentimentScope

**SentimentScope** is a web-based sentiment analysis application that allows users to input text and analyze the emotional tone of the content. The app provides a detailed sentiment breakdown, including positive, neutral, and negative sentiment scores, as well as an overall compound sentiment score. The application leverages machine learning techniques, including VADER Sentiment Analysis, to classify and evaluate text in real-time.

## Features

- **Sentiment Analysis**: Classifies input text as positive, neutral, or negative.
- **Real-Time Feedback**: Instant sentiment score output as you type or submit text.
- **Detailed Sentiment Metrics**: Provides sentiment scores for positive, neutral, and negative sentiment, along with a compound score.
- **Responsive Design**: Optimized for desktops, tablets, and mobile devices.
- **Interactive UI**: Easy-to-use form for text input with results displayed in a clear, table format.

## Technologies Used

- **Flask**: Python web framework for building the application.
- **VADER Sentiment Analysis**: Sentiment analysis tool for textual data.
- **Scikit-learn**: For TF-IDF text vectorization and machine learning-based sentiment analysis.
- **HTML/CSS/JavaScript**: For building the front-end interface.
- **Bootstrap**: For responsive design and layout.
- **Nltk**: Used for stopwords filtering in text preprocessing.

## Installation

Follow the steps below to set up **SentimentScope** on your local machine.

### 1. Clone the Repository


git clone https://github.com/geniusbj/SentimentScope.git
cd SentimentScope


### 2. Create a Virtual Environment (Optional but recommended)


python -m venv venv


### 3. Activate the Virtual Environment

- On **Windows**:

  .venv\Scripts\activate


- On **Mac/Linux**:

  source venv/bin/activate


### 4. Install Dependencies

Make sure you have `pip` installed and then run:


pip install -r requirements.txt


### 5. Run the Application

Once dependencies are installed, run the Flask app:


python app.py


The application will start, and you can visit **http://127.0.0.1:5000** in your browser to interact with **SentimentScope**.

## Usage

1. Enter text into the provided text area on the main page.
2. Submit the form to get a sentiment analysis of your text.
3. View the sentiment scores in the table, including:
   - **Positive**: Percentage of positive sentiment.
   - **Neutral**: Percentage of neutral sentiment.
   - **Negative**: Percentage of negative sentiment.
   - **Compound**: A single score that summarizes the overall sentiment of the text.

## Contributing

If you want to contribute to this project, feel free to fork the repository and submit pull requests.

## License

This project is open-source and available under the [MIT License](LICENSE).
