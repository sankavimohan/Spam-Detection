# Spam Detection Web Application

## Overview

This is a simple Spam Detection web application built using **Python, Scikit-learn, and Streamlit**. The application classifies messages as either **Spam** or **Not Spam** using a **Naïve Bayes classifier** trained on a dataset of labeled messages.

## Technologies Used

- **Python**: Programming language used for development
- **Pandas**: Data manipulation and preprocessing
- **Scikit-learn**: Machine learning library for feature extraction and classification
- **Streamlit**: Web framework for building interactive applications

## Features

- Load and clean a spam dataset
- Convert text messages into numerical features using **CountVectorizer**
- Train a **Multinomial Naïve Bayes** model to classify messages
- Provide a simple **Streamlit-based UI** for users to enter messages and check if they are spam

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/sankavimohan/Spam-Detection.git
   ```
2. Run the application:
   ```sh
   streamlit run spamDetection.py
   ```

## File Structure

```
spam-detection-app/
│-- spamDetection.py   # Main application file
│-- spam.csv           # Dataset (Make sure this file is present)
│-- README.md          # Documentation
```

## Usage

1. Open the web application in your browser after running the Streamlit server.
2. Enter a message into the input field.
3. Click **Validate**, and the app will predict if the message is spam or not.

## Example Output

```
Input: "You have won a free lottery! Click here to claim."
Prediction: Spam
```
