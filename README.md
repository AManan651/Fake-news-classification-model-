
## FAKE NEWS

![App Screenshot](https://storage.googleapis.com/kaggle-datasets-images/2093157/3477477/14e58fb27c107a83225fa0b25a1a29f7/dataset-cover.jpg?t=2022-04-17-12-59-20)

FAKE NEWS CLASSIFICATION MACHINE LEARNING MODEL

The information provided describes the **WELFake** dataset, which is designed for training and evaluating machine learning models to detect fake news. Here's a breakdown of the key points:

### Overview of the WELFake Dataset:
- **Size and Composition**:
  - The dataset contains a total of **72,134 news articles**.
  - Out of these, **35,028 are labeled as real news** and **37,106 as fake news**.
  - The dataset was created by merging four popular news datasets: **Kaggle, McIntire, Reuters, and BuzzFeed Political**.

- **Purpose**:
  - The goal of merging these datasets is to prevent overfitting in classifiers (machine learning models) and to provide a larger, more diverse set of text data for better model training.

- **Dataset Structure**:
  - The dataset is organized into a CSV file with four columns:
    1. **Serial Number**: An index starting from 0.
    2. **Title**: The headline or title of the news article.
    3. **Text**: The full content of the news article.
    4. **Label**: The label indicating whether the news is fake (`0`) or real (`1`).

- **Data Anomaly**:
  - The CSV file contains **78,098 entries**. However, only **72,134 entries** are actually accessed in the data frame, suggesting that there may be **5,964 entries** that are either duplicates, corrupted, or otherwise excluded during data processing.

### Implications for Machine Learning:
- **Diversity and Generalization**:
  - By combining data from multiple sources, the dataset aims to enhance the generalization capability of machine learning models, making them more robust to different writing styles and topics.
  
- **Class Balance**:
  - The dataset has a relatively balanced distribution of real and fake news, which is important for training classifiers that can accurately distinguish between the two classes.

- **Data Cleaning**:
  - The discrepancy between the number of entries in the CSV file and the data frame suggests that some cleaning or preprocessing has been done. It's essential to ensure that the remaining data is of high quality and representative.

This dataset is a valuable resource for developing and testing algorithms designed to detect fake news, which is an increasingly important task in today's information landscape. 
HERE IS THE LINK OF DATASET:- 
(https://www.kaggle.com/datasets/saurabhshahane/fake-news-classification/data)



## FAQ

#### Question 1: What is WordCloud?

Answer 1: 
A word cloud (also known as a tag cloud) is a visual representation of text data, where the importance or frequency of words is indicated by their size. In a word cloud, more frequent or important words appear larger and bolder, while less significant words appear smaller.
Example:
If you created a word cloud from a collection of news articles about technology, words like "AI," "machine learning," "data," and "innovation" might appear larger and more prominent, indicating that these are frequently mentioned terms in the articles.

Word clouds are a simple yet powerful way to visually represent the significance of words in a text dataset, making them a popular tool in data analysis and visualization.

#### Question 2: What is word_tokenize?

Answer 2: 
"word_tokenize" is a function used in natural language processing (NLP) to split a string of text into individual words or tokens. Tokenization is the process of breaking down text into smaller units, which can be words, phrases, or even characters, depending on the application.

#### Question 3: How can any one run it?

Answer 3:
>>>i) 1st download the data file (https://github.com/AManan651/Fake-news-classification-model-/blob/main/WELFake_Dataset%20link.docx).
ii) Upload it on colab. 
iii) RUN Time will be GPU or CPU.
iv) Connect WIFI and enjoy.
## Acknowledgements

 - [Rashedul Alam Shakil](https://github.com/rashakil-ds)
 - [Awesome Readme Templates](https://readme.so/editor)
 


