The Buzzfeed news dataset comprises a complete sample of news published in Facebook from 9 news agencies over a week close to the 2016 U.S. election from September 19 to 23 and September 26 and 27. Every post and the linked article were fact-checked claim-by-claim by 5 BuzzFeed journalists. There are two datsets of Buzzfeed news one dataset of fake news and another dataset of real news in the form of csv files, each have 91 observations and 12 features/variables.

The Buzzfeed news dataset consists of two datasets which has following main features:

id: the id assigned to the news article webpage Real if the article is real or fake if reported fake.

title : It refers to the headline that aims to catch the attention of readers and relates well to the major of the news topic.

text : Text refers to the body of the article, it elaborates the details of news story. Usually there is a major claim which shaped the angle of the publisher and is specifically highlighted and elaborated upon.

source: It indicates the author or publisher of the news article.

images: It is an important part of body content of news article, which provides visual cues to frame the story.

movies: It is also an important part of news article, a link to video or a movie clip included in a article, also provides visual cues to frame the story.
The two main features we care about are the source of the fake news and the language used in the fake news. In particular, we are interested in finding sources who published fake news and finding words which are more associated with one category than other. For finding the sources, we compare the proporation of the fake news reported by a particular news source and for finding the category associated words, we perform chi square test on the text of title and body of the articles.

This project is divided into two parts: (1) Exploratory Data Analysis (2) Classification The goal of second part is to build a classifer that can detect fakenews. We use three different classifiers to classify documents into real/fake news categories.

Here We have used LSTM and Bidirectional LSTM algorithm for model building and finding the accuracy for each.
