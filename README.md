# Final Project Ironhack Dec2021
## Fake News Detector

### Objective
Train and test a model that can **detect if a given news article is reliable or not**

### Dataset
Training data is from kaggle and contains **20,800 news articles in 5 columns** (id, title, author, text, label[1=unreliable and 0=reliable]) → the classes are balanced

Data also contains a test file with 5,200 articles excluding the label

### Method
Using NLP preprocessing to make text available for categorization models and compare the results. I will optimize the models by using Tdidf Vectors. Model comparison between Random Forest, XGBoost and Passife-Aggressive-Classifier.

### [Presentation](https://docs.google.com/presentation/d/1BKkF5vzqV0-g8fqMU1b1yNI0Zyoza8hi7aSkewgBUXU/edit?usp=sharing "Final_Projekt Presentation")