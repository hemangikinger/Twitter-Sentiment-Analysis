About this Competition

You are someone who is recently starting on NLP or has become a master ,irrespective of where you lie in the learning chain , I can bet you have worked on sentiment analysis and if not you will be going to, you just can't bypass it. Can You?. Sentiment analysis is for NLP 'what Happy Birthday to You' is for Guitar players Right? You start here

In case you are not aware about sentiment analysis here is a very good article : https://towardsdatascience.com/sentiment-analysis-concept-analysis-and-applications-6c94d6f58c17

Recently Kaggle Lauched a new competition admist the COVID-19 Scare , named Twitter Sentiment Extraction ,I know right its a twitter sentiment analysis competition,But kaggle never disappoints you,it could not have been this straightforward, afterall it has go on for two months.So what this competition asks for is not the sentiment scores but the part of the tweet (word or phrase) that reflects the sentiment., Interesting it isn't it? This competition is special,so if you want to level up your NLP skills , this competition is for you.

About the Notebook

!pip install gensim --upgrade
!pip install keras --upgrade
!pip install pandas --upgrade

![image-1](https://github.com/hemangikinger/Twitter-Sentiment-Analysis/blob/master/image-1.png)

![image-2](https://github.com/hemangikinger/Twitter-Sentiment-Analysis/blob/master/image-2.png)

![image-3](https://github.com/hemangikinger/Twitter-Sentiment-Analysis/blob/master/image-3.png)


Read Dataset
Dataset details

    target: the polarity of the tweet (0 = negative, 2 = neutral, 4 = positive)
    ids: The id of the tweet ( 2087)
    date: the date of the tweet (Sat May 16 23:58:44 UTC 2009)
    flag: The query (lyx). If there is no query, then this value is NO_QUERY.
    user: the user that tweeted (robotickilldozr)
    text: the text of the tweet (Lyx is cool)

![image-4](https://github.com/hemangikinger/Twitter-Sentiment-Analysis/blob/master/image-4.png)


Map target label to String

    0 -> NEGATIVE
    2 -> NEUTRAL
    4 -> POSITIVE

![image-5](https://github.com/hemangikinger/Twitter-Sentiment-Analysis/blob/master/image-5.png)

Pre-Process dataset

![image-6](https://github.com/hemangikinger/Twitter-Sentiment-Analysis/blob/master/image-6.png)

Split train and test

![image-7](https://github.com/hemangikinger/Twitter-Sentiment-Analysis/blob/master/image-7.png)

Word2Vec

![image-8](https://github.com/hemangikinger/Twitter-Sentiment-Analysis/blob/master/image-8.png)

![image-9](https://github.com/hemangikinger/Twitter-Sentiment-Analysis/blob/master/image-9.png)

![image-10](https://github.com/hemangikinger/Twitter-Sentiment-Analysis/blob/master/image-10.png)

Tokenize Text

![image-11](https://github.com/hemangikinger/Twitter-Sentiment-Analysis/blob/master/image-11.png)

Label Encoder

![image-12](https://github.com/hemangikinger/Twitter-Sentiment-Analysis/blob/master/image-12.png)

![image-13](https://github.com/hemangikinger/Twitter-Sentiment-Analysis/blob/master/image-13.png)

Embedding layer

![image-14](https://github.com/hemangikinger/Twitter-Sentiment-Analysis/blob/master/image-14.png)

Build Model

![image-15](https://github.com/hemangikinger/Twitter-Sentiment-Analysis/blob/master/image-15.png)

![image-16](https://github.com/hemangikinger/Twitter-Sentiment-Analysis/blob/master/image-16.png)


