
# Project Summary

[Medium Article Here](https://medium.com/mlearning-ai/american-sign-language-alphabet-recognition-ec286915df12)

The goal was to create a Machine Learning based, Live American Sign language recognition system.

The dataset we used was derived from kaggle, consisting of 87,000 images. We used 70% of the dataset to train the model we created and the other 30% was used for testing.

We pretrained a ResNet50 model, then used learn.lr_find function from the FastAI library to find the best learning rate. Once the learning rate was optimized our accuracy was 99.98%

As far as the live component goes, we used OpenCV to create our real-time prediction system.

The model we built did have some error, which were due to the dataset we used form kaggle. Distance and lighting were specifically areas that we could improve, which would be fixed by having a dataset that presented ASL language hand gestures in a variety of settings and distances.

To explore this concept in the future, we would try to build upon our model so that it could recognize ASL words and even their associated sentiments. This would blend the concepts of convolutional neural networks with natural language processing. 

All in all I worked with a loveley team, and we built a pretty awesome model!

Teammates:
[Qinwen Zhou](https://www.linkedin.com/in/qinwen-zhou-957844141/), 
[Marshall Wurangian](https://www.linkedin.com/in/marshall-wurangian/), 
[Hao He](https://www.linkedin.com/in/haohe1113/), 
[Matthew Ruffner](https://www.linkedin.com/in/matthew-ruffner-data-analytics/), 
[Dian Zhao](https://www.linkedin.com/in/dian-zhao/), 
[Andrew Han](https://www.linkedin.com/in/uknowandy93/)
