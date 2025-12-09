1. Introduction

Text preprocessing is the first and most important step in Natural Language Processing (NLP).
Raw text usually contains noise such as punctuation, stopwords, inconsistent casing, and irrelevant symbols.
Preprocessing helps convert this raw, unstructured text into a clean and structured form suitable for further NLP tasks such as tokenization, stemming, and machine learning models.

2. Objectives

The main objectives of this lab are:

To understand the importance of text preprocessing.

To learn various preprocessing techniques.

To apply operations such as:

Lowercasing

Tokenization

Stopword removal

Stemming and Lemmatization

Removing punctuation

Removing numbers and special characters

3. Preprocessing Techniques
3.1 Lowercasing

Converts all characters in text to lowercase.
Example:
"The CAT is Running" → "the cat is running"

3.2 Tokenization

Splits the sentence into individual words or meaningful units (tokens).
Example:
"NLP is fun." → ["NLP", "is", "fun"]

3.3 Removing Punctuation

Deletes characters such as: .,!?;:"'()[]{}…
Example:
"Hello!! How are you?" → "Hello How are you"

3.4 Removing Numbers

Gets rid of digits in the text.
Example:
"I have 2 dogs" → "I have dogs"

3.5 Removing Stopwords

Stopwords are common words like is, the, a, an, are, which add little meaning.
Example:
"the cat is on the table" → "cat table"

3.6 Stemming

Reduces words to their root form by cutting suffixes.
Example:
"playing", "played" → "play"

3.7 Lemmatization

Reduces words to their dictionary form (lemma).
Example:
"better" → "good"
