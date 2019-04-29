# Book-Recommendation-Engine

Dataset collected from Project Gutenberg.

Steps:

1. Tokenize and Stem the extracted text.

2. Create a dictionary from the stemmed words.

3. Using Gensim, create a new bag of words model using the previously made dictionary.

4. Convert BoW model into dataframe and sort occurences.

5. Generate tf-idf model using Gensim

6. Using cosine similarity determine the distance between different texts , create a similarity matrix.

7. Using clustering to visualize groups of similar books using scipy.cluster





