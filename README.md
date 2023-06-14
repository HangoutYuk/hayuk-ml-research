# HangoutYuk Machine Learning Research

HangoutYuk! (or HaYuk!) is the solution to easily planning hangout events with your friends and family. This application recommends the best hangout places based on the closest distance to the user and predictions from a machine learning model. The machine learning model used is sentiment analysis to predict the negative or positive sentiment of a place to be considered as a hangout spot. Sentiments are based on comments about the specific hangout place. These comments are obtained from the reviews of the place available on Google Maps.

## Our ML Model

| Information     | Value                                                                           |
| --------------- | ------------------------------------------------------------------------------- |
| Model Structure | TextVectorization - Embedding - LSTM - Dense(ReLu) - Dense(Sigmoid)             |
| Model Input     | List of strings, uncased (lower string), alphabetic (word only)                 |
| Model Output    | Sigmoid values [0..1] where 0 is negative sentiment and 1 is positive sentiment |

## Dataset Sources

1. [Restaurant Reviews](https://www.kaggle.com/datasets/vigneshwarsofficial/reviews)
2. [Cafe Reviews](https://www.kaggle.com/datasets/sripaadsrinivasan/yelp-coffee-reviews)
3. Google Maps API

## Dataset Visualization

![Dataset Visualization](./images/wordcloud.png)

## ML Documentation

1. Looking for Sentiment Analysis Dataset on Kaggle
2. Collecting data automatically from Google Maps API
3. Creating endpoint Machine Learning for Cloud Computing
4. Divide the data in ratio of 50 (train), 30 (validation), and 20 (test)
5. Preprocessing text data and tuning hyperparameter
6. Building model using TensorFlow for Sentiment Analysis
7. Conduct Machine Learning model training with 735 train steps
8. Evaluate the machine learning model
9. Testing real data using random comments on Google Maps
10. Save model into Saved Model Format

## Our Machine Learning Team Members

| Bangkit ID  | Name                      | University                       | Contact                                                                     |
| ----------- | ------------------------- | -------------------------------- | --------------------------------------------------------------------------- |
| M360DSX3692 | Adri Firmansya Sofyan     | Universitas Telkom               | [Linkedin](https://www.linkedin.com/in/adri-firmansya-sofyan-9215b2271/)    |
| M309DSX0159 | Muhammad Rafi Valliansyah | Universitas Pendidikan Indonesia | [Linkedin](https://www.linkedin.com/in/muhammad-rafi-valliansyah-47677882/) |
| M169DSY2157 | Sania Rizka Ramadhani     | Universitas Gadjah Mada          | [Linkedin](https://www.linkedin.com/in/saniarizka/)                         |

> _So einfach ist es schon, wie kannst du es nicht schaffen?_
