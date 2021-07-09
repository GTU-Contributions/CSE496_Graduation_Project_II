# CSE496_Graduation_Project_II
Gebze Technical University

Graduation Project II - Spring 2018

Instructor: Assist. Prof. Burcu Yilmaz

Topic: Named Entity Recognition (NER) with Deep Learning

Abstract: Many words create certain impressions on the reader. With the help of these impressions the reader gains an insight about the words in a text via some entities. In NLP (Natural Language Processing), this process is called Named Entity Recognition (NER). A lot of named entities in the sentence like location, person, organization, time, money or date can be identified. One of the major problems in these operations are confusions about whether the word denotes the name of a location, a person or an organization, or whether an number stands for time, money or a date. This project implements neural network architectures both for word-level and character-level representations by using combination of Bi-LSTM, CNN and CRF. The architectures require no feature engineering or data preprocessing, thus making it applicable to a wide range of sequence labeling tasks. Models for English and Turkish are trained both in word and character level. The models are evaluated on two data sets for sequence labeling tasks – CoNLL2003 for English and Wikipedia dump datasets for English (EWNERTC) and Turkish (TWNERTC). The best obtained results for English for word-level and char-level are 96.41% accuracy, 83.80 F1 and 98.22% accuracy, 89.87 F1 respectively on CoNLL2003 dataset. The best obtained results for Turkish for word-level and char-level are 90.31% accuracy, 63.85 F1 and 90.98% accuracy, 67.33 F1 respectively on TWNERTC dataset.
