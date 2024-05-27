## NLP-Disaster-Tweets
### Overview
This is a Kaggle mini-project for DTSA 551 - Introduction to Deep Learning, focusing on text classification. I utilized models from the Recurrent Neural Network (RNN) family, a choice informed by the inherent sequential nature of tweets. In tweets, each word depends on the preceding ones to convey meaning, and understanding the context necessitates considering the order of the words within the sequence.

### The implemented models include:
* Stacked LSTM
* Bi-directional LSTM with attention
* Universal Sentence Encoder, a pre-trained model developed by Google Research
* RoBERTa, a pre-trained model developed by Facebook AI, that builds upon BERT by addressing some of its limitations and incorporating additional training techniques.
* RoBERTa, trained on tweets that incorporate 'keyword' and 'location' information.
* RandomForestClassifier fitted to our meta-features data (polarity, subjectivity, number of words, number of characters and number of sentences).

### RoBERTa
![Best_model_roberta_chart](https://github.com/WellyWong/NLP-Disaster-Tweets/assets/70742141/abf97751-b4bf-426c-8aa7-0d212e021e07)
Figure 1: RoBERTa training history

![kaggle_leaderboard_roberta](https://github.com/WellyWong/NLP-Disaster-Tweets/assets/70742141/3ee1bc0f-a81b-4f01-b0e9-91e08d29a823)
Figure 2: Kaggle Leader board for the best model in this project
