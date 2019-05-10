Курсовая работа "Автоматическое обнаружение слов русского языка с короткой историей (на материале газетных текстов последнего десятилетия)". </br>
*Course work "Automatic recognition of Russian words with a short history (on a newspaper texts of a passed 15 years)".* </br>

* news_crowler.ipynb -- a program which downloads a large corpus of newspaper articles from different sources. </br>
The resulting corpus is located here (as texts.pkl): https://drive.google.com/open?id=1I-R4mPcYgjYFkyzNyWazOoikBtSSOxPV . </br>
* most_frequent.ipynb -- a program which writes the list of 1000 most frequent Russian words to most_frequent.txt.
* inverted_indexer.ipynb -- a program which computes an inverted index of the corpus. For every word in the corpus (excluding stopwords, most frequent Russian words, numerals, named entities and non-alphabetic strings of characters) a list of dates for every occurence of a word in the corpus is computed.
# References:
Source for the list of 1000 most frequent Russian words: http://dict.ruslang.ru/freq.php . </br>
Library used for named entity recognition: https://github.com/deepmipt/ner .
