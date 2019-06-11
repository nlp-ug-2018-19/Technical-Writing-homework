# Sentiment Analysis Tool
#### Kinga Straszkiewicz
##### June 2019



## Introduction
Sentiment analysis is the automated process of understanding an opinion about a given subject from written or spoken language.

Also known as opinion mining or emotion AI, it refers to the use of natural language processing, text analysis, computational linguistics, and biometrics to systematically identify, extract, and study affective states and subjective information.

Sentiment analysis is widely applied to voice of the customer materials such as reviews and survey responses, online and social media, and healthcare materials for applications that range from marketing to customer service to clinical medicine.

## Description
Sentiment Analysis Tool is a software designed for sentiment analysis, involving statistical examination of a given text.

### Features:
* The analysis of overall sentiment of the text
* Providing the number of positive and negative words in the text, including stopwords
* Providing the number of positive and negative words in the text without stopwords
* Ratio of the positive/negative sentences to the whole text
* The frequency of appearance of positive and negative words
* The statistical analysis of occurrence of the sentiment words
* Sentiment analysis on the basis of sentences containing a keyword
* Viewing the data both as text and graphs

### Setup
The script of this tool is written in Python 3, so it is vital to have on the computer a program capable of processing this programming language.
**The programme also requires the installation of three Python modules**:
* re
* matplotlib.pyplot
* collections

For the Sentiment Analysis Tool to work properly, you need to download a few additional files:
* ._txt_ file with the first text meant for analysis
* ._txt_ file with the second text meant for analysis
* ._txt_ file with the list of positive words
* ._txt_ file with the list of negative words
* ._txt_ file with the list of stopwords

They all have to be located in the same folder as the programme.

To run, download a zip file:

https://github.com/kingastraszkiewicz/Project-Sentiment-Analysis/blob/master/Projekt.zip


## User Guide
After launching the tool, there appears the Menu displaying the contents of the programme and the numbers, which are ascribed to the options.
The first thing that you have to do is to pick one of the two texts meant for analysis.

![alt text](https://github.com/kingastraszkiewicz/Project-Sentiment-Analysis/blob/master/2019-06-10_17h49_01.png)

When the text is chosen, enter the number corresponding to one of the functions and press **ENTER**.

![alt text](https://github.com/kingastraszkiewicz/Project-Sentiment-Analysis/blob/master/2019-06-10_18h18_50.png)

### Functions
**1.** **_SENTIMENT ANALYSIS with stopwords_**

Press 1 to see the number of positive and negative words in a given text.
After analysing the text, the programme provides information whether the text is positive, negative, or neutral.

![alt text](https://github.com/kingastraszkiewicz/Project-Sentiment-Analysis/blob/master/2019-06-10_18h20_25.png)

1 also leads you to a pie chart on the occurrence of positive/negative words.

![alt text](https://github.com/kingastraszkiewicz/Project-Sentiment-Analysis/blob/master/sem_a.png)

**2.** **_SENTIMENT ANALYSIS without stopwords_**

Press 2 to see the number of positive and negative words in a given text **involving** stopwords.
After analysing the text, the programme provides information whether the text is positive, negative, or neutral.

![alt text](https://github.com/kingastraszkiewicz/Project-Sentiment-Analysis/blob/master/2019-06-10_18h21_05.png)

2 also leads you to a pie chart on the occurrence of positive/negative words with stopwords.

![alt text](https://github.com/kingastraszkiewicz/Project-Sentiment-Analysis/blob/master/sem_a_ws.png)

**3.** **_MOST FREQUENT positive/negative words_**

Press 3 to see two lists.
The first list contains the positive words which appear in the text, along with the frequency of their occurrence.

![alt text](https://github.com/kingastraszkiewicz/Project-Sentiment-Analysis/blob/master/2019-06-10_18h31_37.png)

The list is accompanied by a suitable column chart.

![alt text](https://github.com/kingastraszkiewicz/Project-Sentiment-Analysis/blob/master/poz.png)

The second list contains the negative words which appear in the text, along with the frequency of their occurrence.

![alt text](https://github.com/kingastraszkiewicz/Project-Sentiment-Analysis/blob/master/2019-06-10_23h10_50.png)

The list is accompanied by a suitable column chart.

![alt text](https://github.com/kingastraszkiewicz/Project-Sentiment-Analysis/blob/master/neg.png)

**4.** **_PERCENTAGE of positive/negative/neutral words/stop words_**

Press 4 to see the list with the number of occurrences of positive words, negative words, neutral words, and stop words.
There is also an information about the percent ratio of positive and negative words to the whole text

![alt text](https://github.com/kingastraszkiewicz/Project-Sentiment-Analysis/blob/master/2019-06-10_23h16_31.png)

The list is accompanied by a pie chart illustrating the data.

![alt text](https://github.com/kingastraszkiewicz/Project-Sentiment-Analysis/blob/master/per.png)

**5.** **_SENTIMENT ANALYSIS based on keywords_**

Press 5 to see two lists. One contains the source text divided on sentences and the other one contains all of the words in the text separated.

![alt text](https://github.com/kingastraszkiewicz/Project-Sentiment-Analysis/blob/master/2019-06-10_20h16_07.png)

Then, you have to write a key word. What follows is the list of sentences in which that keyword appears and the number of those sentences.
You also have an information about the number of positive and negative words in those sentences and the statistical analysis of the sentiment in those sentences.

![alt text](https://github.com/kingastraszkiewicz/Project-Sentiment-Analysis/blob/master/2019-06-10_21h23_16.png)

Additionally, the list is accompanied by a pie chart presenting statistical information.

![alt text](https://github.com/kingastraszkiewicz/Project-Sentiment-Analysis/blob/master/key.png)

##Altering Files
If you want the files containing lists of positive and negative words to be more accurate, you may add or remove words from them.

### Adding Elements to the Lists
To add word to the list:
* open the file:  _positive_words.txt_, _negative_words.txt_ or _stopwords.txt_
* according to the alphabetical order, add the word to the list
* save changes

### Removing Elements from the Lists
To eliminate a word from the list:
* open the file:  _positive_words.txt_, _negative_words.txt_ or _stopwords.txt_
* find the word you want to delete and remove it from the list
* save changes
