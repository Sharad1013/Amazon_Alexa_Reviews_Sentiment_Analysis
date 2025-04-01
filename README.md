# Amazon Alexa Reviews Sentiment Analysis

Sentiment analysis of 3,150 Amazon Alexa reviews using NLTK's VADER to analyze customer satisfaction through both numerical ratings and text-based sentiment analysis.

## Overview

This project analyzes customer reviews of Amazon Alexa products to understand customer sentiment and satisfaction levels. It combines numerical ratings with text-based sentiment analysis to provide a comprehensive view of customer feedback.

## Features

- Sentiment analysis of verified reviews using NLTK's VADER
- Visualization of rating distribution
- Analysis of positive, negative, and neutral sentiments
- Overall sentiment classification
- Interactive data visualization

## Technologies Used

- Python
- Pandas
- NLTK (VADER)
- Matplotlib

## Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/Amazon_Alexa_Reviews_Sentiment_Analysis.git
```

2. Install required packages
```bash
pip install pandas nltk matplotlib seaborn
```

3. Download NLTK data
```python
import nltk
nltk.download('vader_lexicon')
```

## Usage

1. Run the Jupyter notebook
```bash
jupyter notebook amazon_alexa.ipynb
```

2. The notebook will:
   - Load and preprocess the data
   - Perform sentiment analysis
   - Generate visualizations
   - Display sentiment results

## Results

- Average Rating: 4.46/5
- Sentiment Distribution:
  - Positive: 1,035.46
  - Neutral: 1,936.74
  - Negative: 96.80

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Dataset source: [Add your dataset source]
- NLTK VADER sentiment analyzer
