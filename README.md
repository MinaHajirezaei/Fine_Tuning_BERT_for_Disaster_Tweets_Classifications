# Fine_Tuning_BERT_for_Disaster_Tweets_Classifications

In this model, one of the keras packages in Tensorflow called Ktrain is used to  help build, train, and deploy neural networks and other machine learning models. 
Inspired by ML framework extensions like fastai and ludwig, ktrain is designed to make deep learning and AI more accessible.

!pip install ktrain
import ktrain 
learner = ktrain.get_learner(model=model, train_data=(X_train, y_train), val_data=(X_test, y_test), batch_size=64)
