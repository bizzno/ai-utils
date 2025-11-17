# AI Utils

Collection of AI and machine learning utilities for text processing and classification.

## Features

- Text preprocessing and tokenization
- Sentiment analysis tools
- Named entity recognition (NER)
- Machine learning classifiers
- Natural language processing utilities
- Feature extraction for ML models

## Structure

```
src/
├── preprocessing/    - Text cleaning and tokenization
├── classification/   - ML classifiers and models
├── analysis/         - Sentiment and entity analysis
└── utils/            - Helper functions and utilities
```

## Installation

Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

Text preprocessing example:
```python
from src.preprocessing import TextProcessor

processor = TextProcessor()
clean_text = processor.clean(raw_text)
tokens = processor.tokenize(clean_text)
```

Classification example:
```python
from src.classification import Classifier

classifier = Classifier()
classifier.train(training_data)
result = classifier.predict(input_text)
```

## Requirements

- Python 3.6 or higher
- NumPy
- scikit-learn
- NLTK or spaCy

## License

MIT
