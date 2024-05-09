# Thesis

For my senior thesis, I expanded on my past work, where I had found that fake news contained more emotion than real news, to additionally investigate the ties between emotions and reactions to fake/real news, and the tie between social media algorithms and fake news virality. 

One theory is that fake news utilizes more emotion in the article’s writing itself, defined as ‘publisher emotion’, in order to achieve emotional reactions from readers, defined as ‘social emotion’. This study investigates both sides of this relationship by first exploring whether fake news contains more emotional language, and second, investigating whether Twitter reactions to fake and real news demonstrate any difference in emotion. 

The second half of my study shifts from investigating the ties between emotion and fake news, to studying the tie between social media and fake news. My study is among one of the first to investigate the connection between social media algorithms and fake news; in particular, I analyzed how Reddit’s implementation of a suggested news feed algorithm correlated with fake news virality. 

Methods: 

To investigate the ties between emotions and reactions to fake/real news: 

1. Use a Multinomial Naive Bayes model to classify data --> Achieves high classification accuracy while having interpretable features (individual words)

2. Extract top 100 features related to each class --> Can indicate distinguishing factors between classes

3. Conduct sentiment and emotion analysis on top features to compare classes --> Use VADER and NRC Emotion Lexicon

4. Use this approach on fake news/real news (ISOT Fake News Dataset)  to study ‘publisher emotion’, and on Twitter reactions to fake/real news (2023 CIC TruthSeeker Dataset) to study ‘social emotion’

To investigate the tie between social media algorithms and fake news virality: 

1. Collected 100 most upvoted posts in r/politics from one month before and after Reddit implemented suggested-content

2. Train Neural Network on fake/real news (ISOT Fake News Dataset) 
(Achieves higher accuracy than Naive Bayes Model, and feature interpretability not relevant)

3. Use model to classify both datasets, and compare percentages of fake and real news

Results: 

1. Fake news contained equal or greater amounts of every emotion, and significantly more negative emotion, than real news; this result supports the belief that fake news contains more emotional language than real news. 

2. Reactions to real news contained equal or greater amounts of every emotion compared to reactions to fake news; this result challenged the belief that fake news incites greater emotion.

3. Implementing suggested content on news feeds correlated with a 30% increase in fake news virality in r/politics on Reddit, supporting the belief that social media algorithms increase the spread of fake news. 


Read my whole paper here: https://drive.google.com/file/d/1tmWwZNk_cSuZxEvmog-mqas1jUD9cFzI/view?usp=sharing 
