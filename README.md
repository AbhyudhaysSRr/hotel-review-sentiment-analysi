# Hotel Review Sentiment Analysis System

## Overview
This project is a sentiment analysis system designed to evaluate hotel reviews and provide actionable insights for hotel owners. The system was developed using Python, NLTK, and Flask, incorporating advanced text preprocessing techniques and Support Vector Machines (SVM) to classify customer feedback into positive or negative sentiments. The analysis provides hotel management with valuable insights to improve customer experience based on feedback.

## Key Features
- **Text Preprocessing:** Tokenization, stop-word removal, stemming/lemmatization, and feature extraction using TF-IDF.
- **Sentiment Classification:** The use of Support Vector Machines (SVM) ensures effective classification of reviews into positive and negative categories.
- **Sarcasm Detection:** Addressed key challenges in sentiment analysis such as detecting sarcasm and complex emotions in text.
- **User-Friendly Interface:** Implemented using Flask, allowing hotel owners to input reviews and get real-time sentiment feedback.
- **Visualization:** The system provides visual representations such as confusion matrices and ROC curves for model performance analysis.
  
## System Requirements
To run this project, ensure you have the following installed:
- Python 3.x
- Flask
- NLTK
- Scikit-learn
- Matplotlib (for visualizations)

## Installation Guide
1. Clone this repository:
   ```bash
   git clone https://github.com/your-repository/hotel-review-sentiment-analysis.git
   ```
2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Flask app:
   ```bash
   python app.py
   ```
4. Open your browser and navigate to `http://127.0.0.1:5000` to access the sentiment analysis interface.

## Usage
- Input a hotel review in the text box provided on the web interface.
- Submit the review to receive the sentiment classification (positive or negative).
- Analyze visual metrics such as confusion matrix and ROC curves to understand model performance.

## Results
The sentiment analysis model achieved an **accuracy of 82%**, with visual metrics like the confusion matrix and ROC curve further demonstrating the model's capability to distinguish between positive and negative sentiments.

## Research Paper
This system is based on research published in the 2024 International Conference on Distributed Computing and Optimization Techniques (ICDCOT). The paper details the system’s design, development, and effectiveness in analyzing customer feedback for the hospitality industry.

- **Citation:**
  A. S. R, G. M. Aditya, A. K. Upadya, A. Naik, and U. P, "Customer Feedback and Sentiment Analysis for Hotel Services," 2024 International Conference on Distributed Computing and Optimization Techniques (ICDCOT), Bengaluru, India, 2024, pp. 1-6, doi: [10.1109/ICDCOT61034.2024.10516070](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10516070&isnumber=10515308).

## Future Work
- **Aspect-Based Sentiment Analysis:** Expand the system to identify specific aspects of hotel services (e.g., room quality, customer service) from the reviews.
- **Multilingual Support:** Incorporate support for sentiment analysis in multiple languages to cater to global hotels.
- **Enhanced Sarcasm Detection:** Improve sarcasm detection by leveraging advanced NLP techniques such as BERT or GPT-based models.
