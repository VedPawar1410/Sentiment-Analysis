Sentiment Analysis Web Application
This repository contains a web application that performs sentiment analysis on text input, predicting whether the sentiment is positive or negative. The application is built using Flask (Python), and the machine learning model used is a Logistic Regression model trained on sentiment-labeled data.

Features
A simple web interface for entering text (such as a review or a sentence).
Sentiment prediction displayed instantly upon form submission.
Deployed with Flask, styled with HTML, CSS, and basic JavaScript.
Sentiment prediction is based on a pre-trained model using Scikit-learn.

Installation
Clone the repository:
git clone https://github.com/username/sentiment-analysis-app.git
cd sentiment-analysis-app

Install the required dependencies:
pip install -r requirements.txt

Run the Flask app:
python app.py
Open a browser and navigate to http://127.0.0.1:5000/ to use the application.

File Structure
app.py: The main backend script, handling the sentiment prediction.
templates/: Contains the HTML templates (index.html, result.html).
static/: Contains CSS files for styling.
model.pkl: Pre-trained logistic regression model for sentiment prediction.
vectorizer.pkl: The TF-IDF vectorizer used for text transformation.

Usage
Launch the Flask server.
Open the web application in your browser.
Enter a sentence or review in the input box.
Click on the 'Predict' button to see whether the sentiment is positive or negative.

Future Improvements
Option to upload bulk text data for batch sentiment analysis.
More detailed analysis, including neutral sentiment detection.
Improved UI/UX for better user interaction.

License


Contributions
Feel free to submit pull requests or raise issues to improve the project.
