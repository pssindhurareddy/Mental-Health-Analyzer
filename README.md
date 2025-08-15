# Mental-Health-Analyzer
Mental Health Sentiment Analyzer

This project is a Python and Streamlit-based application that analyzes user-written text to detect emotions and map them to mental health indicators such as depression, anxiety, and stress.
It uses the pre-trained Hugging Face model bhadresh-savani/distilbert-base-uncased-emotion.
No API key is required.

## Installation

### Clone the repository:

git clone https://github.com/yourusername/mental-health-analyzer.git
cd mental-health-analyzer


### Create and activate a virtual environment:

python -m venv venv
# Windows
venv\Scripts\activate
# Mac/Linux
source venv/bin/activate


### Install dependencies:

pip install torch==2.1.0 transformers==4.40.0 streamlit nltk

### Usage

### Run the application:

streamlit run mental_health_app.py


Enter any text into the text box and click Analyze to see detected emotions and related mental health indicators.

### Example

### Input:

I feel so tired and hopeless lately. Nothing excites me anymore.


### Output:

Sadness: 0.72
Depression: High
Anxiety: Normal
Stress: Normal

# Disclaimer

This tool is intended for educational purposes only. It is not a medical diagnostic tool. For any mental health concerns, please consult a qualified professional.
