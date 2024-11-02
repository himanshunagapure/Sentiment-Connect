# Sentiment Connect

## Abstract
"Sentiment Connect" leverages the power of social media to analyze public sentiment regarding the New Education Policy (NEP) of India. By utilizing Twitter as a platform for data collection, this project addresses the challenges faced during the implementation of educational policies by understanding public opinions. The project employs sentiment analysis techniques on real-time Twitter data to generate insights into the public's feelings toward NEP.

## Table of Contents
- [Introduction](#introduction)
- [Project Objectives](#project-objectives)
- [Technologies Used](#technologies-used)
- [Modules](#modules)
- [Data Collection](#data-collection)
- [Data Visualization](#data-visualization)
- [Sentiment Analysis Models](#sentiment-analysis-models)
- [Power BI Dashboard](#power-bi-dashboard)
- [Research Paper](#research-paper)
- [License](#license)
- [Contact](#contact)

## Introduction
Social networking sites have become popular channels for communication, allowing users to express their opinions on various topics. The vast amount of data generated on platforms like Twitter has fueled research in sentiment analysis and opinion mining. This project utilizes the Twitter API to collect and analyze public sentiment related to the NEP of India, providing insights that can assist in effective policy implementation.

## Project Objectives
- To collect real-time Twitter data regarding the NEP of India.
- To preprocess and analyze the data for sentiment extraction.
- To visualize sentiments using various data visualization techniques.
- To develop and train sentiment analysis models to classify sentiments into positive, negative, or neutral.
- To summarize textual data related to the NEP.
- To provide a user-friendly interface for displaying results.

## Technologies Used
- Python
- Tweepy
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Power BI

## Modules
1. **Data Gathering**: Utilizes Tweepy to collect real-time Twitter data.
2. **Data Preprocessing and Analysis**: Cleans and processes data for analysis.
3. **Implementing Sentiment Analysis**: Analyzes sentiments using various models.
4. **Implementing Text Summarization**: Summarizes textual data for concise representation.
5. **Designing GUI and Generating Output**: Develops a graphical user interface to display results.
6. **Connection and Testing**: Connects all modules and performs testing to ensure functionality.

## Data Collection
Data is gathered using the Tweepy library, which interfaces with the Twitter API. The script collects tweets related to the NEP based on specific hashtags and keywords.
Obtained Twitter API credentials from the [Twitter Developer Portal](https://developer.twitter.com).

## Data Visualization
The project employs various visualization techniques to represent data insights, including:
- **Word Cloud**: Displays the most frequent words in the tweets.
- **Scatter Plot**: Visualizes sentiment scores.
- **Bar Plot**: Compares positive, negative, and neutral sentiments.

## Sentiment Analysis Models
Multiple machine learning models were tested for sentiment classification, including:
- **Linear Regression**
- **Bernoulli Naive Bayes**
- **Support Vector Machine (SVM)**
- **Random Forest**

The Random Forest provided the best performance for sentiment analysis.
![Accuracy](https://github.com/himanshunagapure/Sentiment-Connect/blob/main/img/accuracy.png)

## Power BI Dashboard
Below are images of the Power BI dashboard created for visualizing sentiment analysis results.

![Dashboard Image 1](https://github.com/himanshunagapure/Sentiment-Connect/blob/main/img/dashboard%202020.png)

![Dashboard Image 2](https://github.com/himanshunagapure/Sentiment-Connect/blob/main/img/dashboard%202021.png)

![Dashboard Image 3](https://github.com/himanshunagapure/Sentiment-Connect/blob/main/img/Dashboard%202022.png)

## Research Paper
For more in-depth insights and methodologies used in this project, you can refer to the research paper [here](https://journal.ijprse.com/index.php/ijprse/article/view/551).

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact
For any inquiries or feedback, please contact:
- **Name**: Himanshu
- **Email**: himunagapure114@gmail.com
