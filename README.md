# Bias_lexica

Task Summary:
1. Scrape a dataset from any english newspaper with atleast 1000 articles and should be no older than 2017.
2. Write a program in Python which takes the dataset and calculates the 1000 most likely bias words for any 10 bias words of choice.
3. Then use word embeddings to calculate the 100 most similar words to each of those words.
4. Print out the cosine distances of each word to all its most similar words. 
 
 
 Result Description:
 1. Fetch the news articles from "https://timesofindia.indiatimes.com/", "https://edition.cnn.com/" using the defined functions. 
 2. Extract the news headlines from the articles.
 3. Pre-process the text using defined functions.
 4. Extract the 100 similar words for each defined biased word using word2vec model. 
 5. For each biased word, the extracted similar words along with their cosine distances will be saved in a csv file.
 
 Program Execution:
 From PyCharm or Spyder, run the file main.py or execute the command python main.py from the terminal. 
