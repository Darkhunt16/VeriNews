# VeriNews

This project develops a machine learning model to classify news articles as fake or real, addressing the harmful effects of fake news on society. A diverse dataset of news articles was used for training and validation, ensuring robust results. The model's performance was evaluated using four different techniques for accuracy and reliability. The goal is to identify misinformation effectively and prevent its spread. This initiative supports maintaining information integrity in the digital era.

 **Logistic Regression**

## Project Overview

In the digital era, the rapid spread of information across online platforms has made fake news a pressing concern. This project utilizes machine learning algorithms to assess the authenticity of news articles, offering an effective solution to tackle misinformation.

## Dataset

We have used a labelled dataset containing news articles along with their corresponding labels (true or false). The dataset is divided into two classes:
- 1: Genuine news articles
- 0: Fake or fabricated news articles

The dataset is taken from Kaggle. [Link](https://www.kaggle.com/competitions/fake-news/data?select=train.csv)


## Usage

1. Clone this repository to your local machine:

```bash
git clone https://github.com/Darkhunt16/VeriNews.git
```

2. Navigate to the project directory:

```bash
cd VeriNews
```

3. Install the dependencies

```bash
pip install -r requirements.txt
```

4. Run the following command in your terminal

```bash
streamlit run app.py
```

4. Now you should be able to view the project at http://localhost:8501

## Results

In the provided textfield enter the news and hit enter to know whether the news is real or fake.

