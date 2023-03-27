# fb-sentiment
Using FaceBook posts to predict user's sentiment. Based on that the system could offer relevant emojis.

This model be expanded by adding some methods of context processing (e.g. not only look at the post itself, but also consider the last 5 post/comments of the user).
In order to build a reaction (recommendation) system we can use machine learning algorithms such as collaborative filtering or content-based filtering. 
Collaborative filtering uses the behavior of similar users to make recommendations, while content-based filtering uses features of the post to make suggestions. 
A hybrid approach that combines both techniques could be used to improve the accuracy of the model.

To evaluate the effect of the model on user engagement, we can use A/B testing to compare the engagement levels of users who receive the smart reaction suggestions with those who do not. 
The metrics used to measure engagement could include the number of reactions, comments, and shares.

To improve our existing model further, it is essential to perform dimensionality reduction using techniques like PCA.

The other thing is that there is a real possiblity to use API of external NLP service such as ChatGPT which is a large language model 
and can guess and suggest reactions quite reliably. Then it's a matter of implementation of such API and price/performance ratio.
