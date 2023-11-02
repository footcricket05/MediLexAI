# MediLexAI: Advanced Text Analytics for Healthcare Articles

## Description
Welcome to MediLexAI, where we delve into the realm of AI in healthcare articles, extracting valuable data and uncovering insightful analysis. Our project is designed to extract data from a curated list of URLs related to AI in healthcare, performing an in-depth data analysis on the text. Our analysis includes sentiment analysis and the computation of various linguistic variables, such as word count, sentence count, average sentence length, and the percentage of complex words.

## Dependencies
Before running MediLexAI, ensure you have the following dependencies installed:

1. `Python 3.x`
2. `pandas`
3. `nltk (Natural Language Toolkit)`
4. `newspaper3k`
5. `syllables`

You can install the required libraries using pip:
```
pip install pandas nltk newspaper3k syllables
```

## Installation
To set up the project, follow these steps:

1. Install Python: [Python Installation Guide](https://www.python.org/downloads/)
2. Install the required libraries using pip: `pip install pandas nltk newspaper3k syllables`
3. Download NLTK data: `import nltk nltk.download('punkt')`

## Usage
1. Place the input file "input.xlsx" in the same directory as the Python script.
2. Run the Python script: `Data Extraction and NLP.py`
3. The output file "output.csv" will be generated in the same directory.

## Notes
1. The input file should adhere to the structure specified in "Input.xlsx."
2. If any errors occur during data extraction or analysis, an error message will be displayed, and the script will continue to process the remaining URLs.
3. The output file will contain the computed variables and sentiment analysis scores for each URL in the input file.
4. Please note that the sentiment analysis scores are based on the VADER sentiment analysis tool and may not always perfectly reflect the sentiment of the article.

## Contributing
If you encounter issues or have suggestions for improvement, please consider creating a pull request or opening an issue.

## License
This project is licensed under the MIT License. See the License file for more details.
