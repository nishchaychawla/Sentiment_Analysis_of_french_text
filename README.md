# Sentiment_Analysis_of_[ftragedy](https://www.kaggle.com/sharkcpn/french-tragedies/data)
Sentiment analysis of ftragedy dataset using tidytext and [French Expanded Emotion Lexicon](http://advanse.lirmm.fr/feel.php)

Sentiment analysis can be done in many ways but here I have primarily used tidytext package of R to calculate the total positive and negative words used in each text document.

The general idea is to compare the words from the standard lexicon(like FEEL) to evaluate the characteristics of each word and summing them up accordingly. Sentiment is often framed as a binary distinction (positive vs. negative), but it can also be a more fine-grained, like identifying the specific emotion an author is expressing (like fear, joy or anger).
The code creates a data frame at the end which have the polarity and count for each type of word. Many positive words and few negative words indicates positive sentiment (Polarity), while many negative words and few positive words indicates negative sentiment(Polarity).

### About Dataset
The data set contains 59 txt files in [zip folder](https://www.kaggle.com/sharkcpn/french-tragedies/data) in french language.

