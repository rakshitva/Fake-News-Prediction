# Fake-News-Prediction
## 1. **Abstract**
The media industry is struggling with the widespread issue of fake news, which undermines public trust and journalistic integrity. Social media platforms enable misinformation to spread rapidly, leading to polarized opinions and potential legal risks.

To combat this, the media industry need advanced systems for real-time detection and verification of fake news. By implementing these mechanisms, media organizations can protect their reputation and ensure they are providing accurate, reliable information to their audiences.


The goal is to enhance public trust and support a more informed society by reducing the impact of fake news.

### a. Introduction

In today's digital age, the spread of misinformation, commonly known as fake news, has become a pervasive issue, undermining the integrity of journalistic organizations worldwide. The impact of fake news extends beyond politics, significantly affecting public health. In our exploration, we confront the pervasive influence of fake news, epitomized by [Donald Trump's election](https://misinforeview.hks.harvard.edu/article/twitter-flagged-donald-trumps-tweets-with-election-misinformation-they-continued-to-spread-both-on-and-off-the-platform/) claims. His dissemination of unfounded allegations of voter fraud not only ignited a storm of misinformation but also eroded trust in democratic institutions. As we delve deeper, we confront the urgent need to combat fake news' corrosive effects on truth and democracy. Researchers and policymakers are increasingly leveraging these tools to predict and mitigate the dissemination of fake news, enabling targeted interventions to combat its harmful effects.

## b) Problem Statement

### **What is the prevailing Circumstance?**

The proliferation of social media platforms and digital news outlets has facilitated the rapid dissemination of information, both accurate and false. This unprecedented accessibility to news sources has led to an alarming increase in the circulation of fake news, which poses significant risks to most news sectors and its stakeholders.

### **What problem is being addressed?**

The primary problem being addressed is the pervasive presence of fake news within the digital media landscape. Fake news undermines the credibility of the media industry as a reputable journalistic entity, erodes reader confidence, and contributes to the polarization of public opinion. Moreover, the dissemination of false information can have far-reaching consequences, including social unrest, political instability, and legal ramifications.

### ** Project Aim ?**

The project aims to develop and implement sophisticated systems for detecting and flagging fake news in real-time. By leveraging cutting-edge technologies such as natural language processing (NLP), machine learning (ML), and data analytics, the media industry intends to identify and verify the authenticity of news articles and sources. Additionally, the project will involve the establishment of rigorous editorial standards and fact-checking procedures to ensure the dissemination of accurate and reliable information to its audience. Through these initiatives, most News sector seeks to safeguard its reputation, enhance public trust, and uphold the principles of ethical journalism.



### c. Objectives

#### Main Objectives

- To implement robust fake news detection mechanisms capable of identifying and flagging misinformation in real-time, thereby safeguarding the integrity and credibility of most News sectors.

#### Specific Objectives

1. Develop a comprehensive dataset of labeled news articles, encompassing both genuine and fake content, to train and validate machine learning models for fake news detection.
2. Utilize natural language processing (NLP) techniques to extract relevant features from news articles, such as linguistic patterns, sentiment analysis, and lexical semantics.
3. Implement state-of-the-art machine learning algorithms, including supervised and unsupervised learning approaches, to classify news articles as genuine or fake based on extracted features.
4. Integrate the fake news detection system seamlessly into the News's content management workflow, enabling automated flagging and verification of potentially false information.
5. Conduct regular updates and improvements to the fake news detection system to adapt to evolving misinformation tactics and enhance its accuracy and reliability over time.


### d. Notebook Structure


i. Abstract <br>

ii. Data Understanding<br>

iii. Exploratory Data Analysis<br>

iv. Text Preprocessing<br>

v. Modeling<br>

vi. Evaluation<br>

vii. Limitation<br>

viii. Next Steps<br>

ix. Recommendation




### f. Metric of Success

- The performance of the model is evaluated based on achieving an accuracy of over 85%.


## 2. **Data Understanding**

The data used in this project was obtained from: [Kaggle](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset).

The dataset is divided into: Fake.csv and True.csv. Where the Fake.csv file contains: 23481 rows and 4 columns and the True.csv file contains: 21417 rows and 4 columns.

Each file contains news articles, distinguished by their authenticity. 'Fake.csv' contains fake news articles, while 'True.csv' contains genuine news articles.
