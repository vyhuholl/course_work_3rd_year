Курсовая работа "Автоматическое обнаружение слов русского языка с короткой историей (на материале газетных текстов последнего десятилетия)". </br>
*Course work "Automatic recognition of Russian words with a short history (on a newspaper texts of a passed 15 years)".* </br>

* news_crowler.ipynb -- a program which downloads a large corpus of newspaper articles from different sources. </br>
The resulting corpus is located here (as texts.pkl): </br>
https://drive.google.com/open?id=1I-R4mPcYgjYFkyzNyWazOoikBtSSOxPV </br>
* most_frequent.ipynb -- a program which writes the list of 1000 most frequent Russian words to most_frequent.txt.
* inverted_indexer.ipynb -- a program which computes an inverted index of the corpus. For every word in the corpus (excluding stopwords, most frequent Russian words, numerals, named entities and non-alphabetic strings of characters) a list of dates for every occurrence of a word in the corpus is computed. </br>
The resulting index is located here: </br>
https://drive.google.com/open?id=1ffqsJfb_UE0s5qGwtQxKj1Ni5rMRF6jg
* A library used for neural named entity recognition sometimes gives false-negative results. An example of bad NER is located at bad_ner_example.ipynb.
* results.ipynb contains: </br>
1. A function, which plots a (smoothed plot) of word occurrences in the corpus.
2. A code that finds all words which first occurred in 2002 or later and last occurred in 2017 or later Words with less than 5 occurences in corpus and words which have their own page in Wikipedia (most likely named entities falsely marked as non-named entities) were excluded. The resulting list of words is located at results.csv </br>
Occurrence plots for words are located here: </br>
https://drive.google.com/open?id=1FAF-BNCHkLaKK3qOH22GEjcMR0g-n8-y
# References:
Source for the list of 1000 most frequent Russian words: http://dict.ruslang.ru/freq.php </br>
Library used for named entity recognition: https://github.com/deepmipt/ner
