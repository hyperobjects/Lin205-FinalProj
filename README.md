# Random Sentence Generation
Final Project for Programmeringsteknik för lingvister [Programming Techniques for Linguists]  at Stockholms Universitet

<H1>Project Description:</h1>
Choose an author and download a couple of his or her books from Project Gutenberg. Next, extract this author’s word bigrams, i.e. all two-word sequences. For instance, in the sentecen "cats like eating fish" we have 3 bigrams: [("cats", "like"), ("like", "eating"), ("eating", "fish")]. Write a program which generates random sentences given your chosen author’s bigram model. Given a previous word w, it should choose randomly from the words which follow w in the bigram model.

<h3> Input:</h3>
Ebooks downloaded from Project Gutenberg 
<h3> Output:</h3>
Randomly generated sentence using the author’s bigram probabilities

<h2> Dependencies:</h2>

pip install -U nltk <br>
nltk.download() #download data <br>

pip install urllib<br>
