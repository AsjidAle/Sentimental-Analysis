### Sentiment Analysis of Amazon Reviews for "Maus" Graphic Novel

This project performs sentiment analysis on Amazon reviews for the graphic novel "Maus" by Art Spiegelman. It scrapes the reviews from Amazon, analyzes the sentiment of each review using TextBlob, and visualizes the sentiment distribution.

#### Table of Contents
- [Features](#features)
- [Requirements](#requirements)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Sentiment Analysis Methodology](#sentiment-analysis-methodology)
- [Author](#author)

#### Features
- Scrapes Amazon reviews for the graphic novel "Maus" using web scraping techniques.
- Analyzes sentiment using TextBlob, classifying each review as positive, negative, or neutral.
- Visualizes the sentiment distribution with a bar chart.
- Provides insights into the overall sentiment of the reviews.

#### Requirements
- Python 3.x
- pandas
- requests
- BeautifulSoup
- textblob
- matplotlib

#### Getting Started
Clone this repository to your local machine:


#### Usage
- Run the `scrape_amazon_reviews.py` script to scrape Amazon reviews and perform sentiment analysis.
- Ensure that the CSV file containing the scraped reviews is named `amazon_reviews_maus.csv` and is saved in the same directory as the script.
- Execute the script using Python:
    ```bash
    python scrape_amazon_reviews.py
    ```

#### Sentiment Analysis Methodology
- The script utilizes the TextBlob library for sentiment analysis.
- Each review is classified as positive, negative, or neutral based on the polarity score obtained from TextBlob.
- The sentiment distribution is visualized using a bar chart.

#### Author
Asjid Ali  
Email: asjidale@gmail.com

Feel free to reach out for any questions or feedback.

---
