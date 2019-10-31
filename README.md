# NLP-tutorial_psych-methods
NLP tutorial for the psych methods group at Columbia

# Installation

i) Clone or download this repository

ii) CD into the repoistory directory and run: pip install -r requirements.txt

iii) For the GloVe vector code, you will need to download this 1gb text file and add it to the repo: http://nlp.stanford.edu/data/glove.6B.zip


# How to run

There are 5 Jupyter Notebook tutorials that you can run through Anaconda Navigator:   https://docs.anaconda.com/anaconda/navigator/getting-started/

Each tutorial has independent code/variables, but the concepts build on each other so I recommend going through them in order. 


# Outline

## 1. NLTK (natural language toolkit) Basics

- Part-of-speech tagging
- Word lemmatization
- Extracting lexical frequencies
- Extracting word phonemes
- Counting syllables
- Rhyme generating with syntactic and syllabic constraints

## 2. Wikipedia text scraping and sentiment analyses

- Scrape text from wikipedia pages
- Use three different pretrained sentiment analyzers (vader, affin, sentistrength) to compare positive / negative sentiments of different pages

## 3. Reddit scraping

- Use pushshift.io API to scrape massive amounts of text from reddit using criteria such as keywords, date and time, subreddit, upvotes, etc.

## 4. GloVe vectors (semantic word embeddings)

- Import a dataset of GloVe vectors trained on Wikipedia text and compare the semantic representations of different words, wikipedia pages, and subreddits.
- Generate your own set of GloVe vectors with a new text corpus. 

## 5. Generating text with the GPT-2 transformer model

- Basic code to predict upcoming words using custom text prompts with GPT-2
