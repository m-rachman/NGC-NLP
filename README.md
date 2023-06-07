## Problem

Cleaning textual data in the 'Artikel' column of the given dataframe by removing stopwords, numeric, symbolic, and meaningless words.

## Objective

Preprocess the textual data in the 'Artikel' column to obtain a cleaned version of the text, where stopwords, numeric, symbolic, and meaningless words have been removed. The objective is to make the text more meaningful and suitable for further analysis or natural language processing tasks.

## Hints

1. Utilize the NLTK library for text preprocessing tasks like tokenization and removing stopwords.
2. Tokenize the words in each article using the `word_tokenize()` function from NLTK.
3. Download the list of stopwords using `nltk.download('stopwords')` and access them using `stopwords.words('indonesian')`.
4. Use list comprehension to filter out words that are numeric, symbolic, or stopwords from the tokenized words.
5. Check if a word consists only of alphabetic characters using the `isalpha()` method.
6. Convert the cleaned tokens back to a string using the `join()` method.
7. Drop the unnecessary columns from the dataframe using the `drop()` method.

By following these steps, you will be able to clean the textual data in the dataframe and obtain a new column with cleaned text.
