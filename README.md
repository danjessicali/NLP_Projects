# NLP_Projects

This repository stores my NLP related projects.

## NLP Classification: Sentiment Analysis Exercise:

### Summary:
Build a text classifier using the pretrained DistilBert (Deep Learning) published by HuggingFace.

### Dataset:
English Reddit comments with 27 labeled emotions and neutral

### Preprocessing:
  - translating emojis to text
  - utilize comments with evidence of strong agreement
  - The final data frame has a total of 53,425 documents (comments) with 23 (28 originally with 5 dropped) unique labels.
  
### Model:
  - LSTM Model
  - Transfer learning model: DistilBERT
  
### Result:
 
 Both Transfer Learning models, based on DistilBERT, handled multi-label predictions better than LSTM model. LSTM performed decently on average, scoring ~30%, but did so by taking advantage of class imbalances, steadfastly predicting a ‘neutral’ sentiment. Neutral documents made up 28.3% of the instances in the dataset.

  
  
## Kickstarter Text Mining Project
### Overview

Kickstarter is an American public-benefit corporation based in Brooklyn, New York, that maintains a global crowd funding platform focused on creativity.  The company's stated mission is to "help bring creative projects to life". 

Kickstarter has reportedly received almost $6 billion in pledges from 20 million backers to fund more than 200,000 creative projects, such as films, music, stage shows, comics, journalism, video games, technology and food-related projects.

For this assignment, I am asking you to analyze the descriptions of kickstarter projects to identify commonalities of successful (and unsuccessful projects) using the text mining techniques we covered in the past two lectures. 

### Data

The dataset for this assignment is taken from [webroboto.io ‘s repository](https://webrobots.io/kickstarter-datasets/). They developed a scrapper robot that crawls all Kickstarter projects monthly since 2009. I noticed that the most recent crawls appear to be incomplete, so we will take data from the last complete crawl on 2021-05-17.

To simplify your task, I have downloaded the files and partially cleaned the scraped data. In particular, I converted several JSON columns, corrected some obvious data issues, and removed some variables that are not of interest (or missing frequently), and removed some duplicated project entries. I have also  subsetted the data to only contain projects with locations set to the United States (to have only English language and USD denominated projects). Some data issues surely remain, so please adjust as you find it necessary to complete the analysis. 

The data is contained in the file `kickstarter_projects_2021_05.csv` and contains about 131k projects and about 20 variables.


### Tasks Completed:
- Identifying Successful Projects
- Cleaning the Text and Word Cloud
- Simplicity as a virtue
- Sentimental Analysis
