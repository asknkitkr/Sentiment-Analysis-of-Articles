# Sentiment Analysis of Articles

Sentiment Analysis is the use of Natural Language Processing, Text Analysis, Computational Linguistics and biometrics to systematically identify, extract, quantify and study affective states and subjective information.

The project deals with the analysis of articles that are scrapped from the link: https://asknkitkr.github.io/article/
The articles are send analyzed and it returns the Polarity of the article content as per condition:
```python
if Polarity > 0.1: 
  return "Positive"
if Polarity < 0: 
  return "Negative"
if Polarity <= 0.1 and Polarity >= -0.1: 
  return "Neutral"
```

## Libraries used in the project
- beautifulsoup4
- requests
- urllib3
- textblob
- colorama
- prettytable

## Installation
```bash
pip install -r requirements.txt
```

After installing all the required packages, open **main2.py**

## Contributors
- Ankit Kumar - https://github.com/asknkitkr
- Tushar Lohani - https://github.com/Tusharlohani
- Sakshi Kumari - https://github.com/sakshi413

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
