# NLP_Projects

This repository stores my NLP related projects.

## NLP Classification: Sentiment Analysis Exercise:

- Summary:
Build a text classifier using the pretrained DistilBert (Deep Learning) published by HuggingFace.

- Dataset:
English Reddit comments with 27 labeled emotions and neutral

- Preprocessing:
  - translating emojis to text
  - utilize comments with evidence of strong agreement
  - The final data frame has a total of 53,425 documents (comments) with 23 (28 originally with 5 dropped) unique labels.
  
- Model:
  - LSTM Model
  - Transfer learning model: DistilBERT
  
 Summary:
 
 Both Transfer Learning models, based on DistilBERT, handled multi-label predictions better than LSTM model. LSTM performed decently on average, scoring ~30%, but did so by taking advantage of class imbalances, steadfastly predicting a ‘neutral’ sentiment. Neutral documents made up 28.3% of the instances in the dataset![image](https://user-images.githubusercontent.com/46760000/198363897-261a01b7-a1ee-499a-adab-e6f2a7335428.png)

  
  
