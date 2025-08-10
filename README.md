# Amazon Reviews Sentiment Analysis

This project analyzes Amazon product reviews using OpenAI's GPT model to extract:
- Sentiment analysis
- Emotion detection
- Product aspects
- Brand identification

## Setup

1. Clone the repository
```bash
git clone <repository-url>
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Create a `constants.py` file with your OpenAI API key:
```python
OPENAI_API_KEY = "your-api-key-here"
```

4. Place your review dataset in the `Data/` folder as `reviews_100.csv`

## Usage

Run the analysis:
```bash
python review_sentiment_new.py
```

The analyzed results will be saved in `Data/reviews_100_analyzed.csv`