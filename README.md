# Twitter Analysis
This repository contains a Jupyter Notebook for analyzing Twitter data. The notebook demonstrates how to extract, process, and visualize tweets using various Python libraries.

## Overview

The notebook performs the following tasks:
1. **Twitter API Authentication**: Sets up authentication to access Twitter's API using Tweepy.
2. **Data Extraction**: Fetches tweets from a specified user (e.g., `realDonaldTrump`).
3. **Data Processing**: Processes the extracted tweets, including filtering and cleaning.
4. **Sentiment Analysis**: Analyzes the sentiment of tweets using the NLTK library's SentimentIntensityAnalyzer.
5. **Data Visualization**: Visualizes the data using Matplotlib, including histograms and line plots.

## Libraries Used

- **Tweepy**: For accessing the Twitter API.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Matplotlib**: For data visualization.
- **NLTK**: For natural language processing and sentiment analysis.

## Key Features

- **Twitter API Authentication**: Securely connects to Twitter's API to fetch tweets.
- **Sentiment Analysis**: Uses NLTK's SentimentIntensityAnalyzer to determine the sentiment of tweets.
- **Data Visualization**: Creates histograms of tweet likes and sentiment scores, and plots the daily average sentiment.

## Getting Started

1. **Clone the repository**:
    ```bash
    git clone https://github.com/cizodevahm/Twitter_Analysis_NLTK.git
    cd Twitter_Analysis_NLTK
    ```

2. **Install the required libraries**:
    ```bash
    pip install tweepy pandas numpy matplotlib nltk
    ```

3. **Run the Jupyter Notebook**:
    ```bash
    jupyter notebook Twitter-Notebook.ipynb
    ```

## Usage

- **Fetch Tweets**: Modify the `screen_name` parameter in the notebook to fetch tweets from a different user.
- **Analyze Sentiment**: Run the cells to perform sentiment analysis on the fetched tweets.
- **Visualize Data**: Generate visualizations to understand the sentiment trends in the tweets.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
