# sentimental_analysis_on_amazon_reviews
This project aims to conduct sentiment analysis on Amazon reviews using the VADER tool ,  the goal is to analyze the polarity of sentiments expressed in customer reviews, thereby providing valuable insights into product reception and customer satisfaction levels.

## Installation

Make sure you have Python-3 Installed in your computer , You can download the Latest version of `python` from [official website](https://www.python.org/)

## Prerequisites
To conduct sentiment analysis on a dataset you need to have some modules installed in your computer, To Install the required Python modules run the following command in your command prompt or terminal:

```bash
  pip install pandas sklearn nltk seaborn
```
## Downloading data
You can download the dataset required by clicking the below link:-

[dataset](https://drive.google.com/file/d/1XRa6vCsSTFy7z6Sr0t_plBDwjKtsWzNF/view?usp=drive_link)

## Downloading some modules in NLTK 
You have to download some NLTK modules in order to execute the python script , they are `words` , `averaged perceptron tagger` , `vader-lexicon`  and `maxent_ne_chunker`
- words :- The nltk library has a dataset called `words`.The ‘words’ dataset contains a list of about 236,000 English words. here we use it to access a list of English words
- averaged perceptron tagger :- It is a type of `part-of-speech` (POS) tagger that uses the averaged perceptron algorithm to predict the most likely POS tag for a given word.
- maxent_ne_chunker :- It is a type of named entity chunker that uses the maximum entropy framework to identify and classify named entities in a text.
To download them use the below syntax :-
```bash
nltk.download('words')
nltk.download('averaged perceptron tagger')
nltk.download('vader-lexicon')
nltk.download('maxent_ne_chunker')
```

Vader :- VADER (Valence Aware Dictionary and sEntiment Reasoner) is a lexicon and rule-based sentiment analysis tool that is specifically attuned to sentiments expressed in social media
VADER not only tells about the Positivity and Negativity score but also tells us about how positive or negative a sentiment is.

## Cloning this repository 
Clone this repository using the command:
```bash
git clone https://github.com/Sreelakshmiperanla/sentimental_analysis_on_amazon_reviews.git
```
Once you have downloaded the files, open the `command prompt` or `terminal` and navigate to the directory where the files are located.

## Executing or running Python Scripts in Different Environments

### Command prompt or terminal
Run the following command to train the model:
```bash
python sentiment_analysis.py
```

### using a text editor
You can use a text editor like VS Code to write and run your Python code. You need to install the Python extension for VS Code and then select the Python interpreter from the status bar
You can then use the `Run Python` File in Terminal command from the Command Palette or the right-click menu to `run` your Python file

After the training is complete, the `accuracy score`, `confusion matrix`, and `classification report` will be printed on the console.

## Built Using 

- [Python](https://www.python.org/)
- [Scikit-Learn (sklearn)](https://scikit-learn.org/stable/)
- [Pandas](https://pandas.pydata.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [nltk](https://www.nltk.org/)
- [Transformers](https://pypi.org/project/transformers/)
