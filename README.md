# Data Extraction and NLP 

## Description
This project involves extracting data from a list of URLs related to AI in healthcare articles and performing data analysis on the extracted text. The analysis includes sentiment analysis, computation of various variables such as word count, sentence count, average sentence length, percentage of complex words, and more.

## Dependencies
1. `Python 3.x`

2. `pandas`

3. `nltk (Natural Language Toolkit)`

4. `newspaper3k`

5. `syllables`

## Installation
1. Install Python: [`Python Installation Guide`](https://www.python.org/downloads/)

2. Install the required libraries using pip:
```
pip install pandas nltk newspaper3k syllables
```

3. Download NLTK data:
```
import nltk
nltk.download('punkt')
```

## Usage
1. Place the input file "input.xlsx" in the same directory as the Python script.

2. Run the Python script:
```
Data Extraction and NLP.py
```

3. The output file "output.csv" will be generated in the same directory.

## Notes
1. The input file should follow the structure specified in "Input.xlsx".

2. If any error occurs during data extraction or analysis, an error message will be displayed, and the script will continue to process the remaining URLs.

3. The output file will contain the computed variables and sentiment analysis scores for each URL in the input file.

4. Please note that the sentiment analysis scores are based on the VADER sentiment analysis tool and may not always perfectly reflect the sentiment of the article.

## Contributing
If you find any issues or have any suggestions for improvement, feel free to create a pull request or open an issue.

## License
This project is licensed under the `MIT License` - see the License file for details.
