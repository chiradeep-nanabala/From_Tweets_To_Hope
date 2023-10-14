# From_Tweets_to_Hope: A Data-Driven Approach to Supporting the Needy in America

In today's fast-paced world, social media, particularly Twitter, has evolved into a critical platform for sharing information and opinions. Twitter serves as a valuable source of data, especially in emergency situations where tweets can rapidly communicate crucial information. However, challenges such as limited audience reach and relevance can hinder the effectiveness of these tweets in reaching those who can provide assistance. Our project aims to tackle these challenges by utilizing data mining and sentiment analysis on Twitter data from selected U.S. states. We will leverage the Twitter API and analysis libraries such as Text Blob, VADER, and Flair to identify tweets expressing the need for help, charity, and support, with a focus on positive tweets to identify potential resources and volunteers.

# Data Collection & Pre-processing
## 1) Twitter API Connection
We harnessed the power of the Twitter API to collect tweets relevant to sentiment analysis. The Twitter API enables programmatic access to Twitter data, making it invaluable for various applications, including sentiment analysis. To access the Twitter API, we first created a developer account, applied for API access, and then used API endpoints to search for tweets based on specific search terms, often in the form of hashtags.

## 2) Data Collection and Filtering
Our data stream consisted of tweets either seeking or providing help. Twitter serves as a platform for charitable organizations and individuals to solicit donations or recruit volunteers. We collected tweets related to charitable giving, aiming to understand the causes people care about, the language and strategies used for fundraising, and how people express their requests for help or gratitude for donations. Keywords and hashtags related to charitable giving and help-seeking were used for this purpose, along with geo filters to ensure we collected tweets specifically from the United States.

## 3) Data Pre-processing
Data pre-processing is a critical step in text analysis. It involves cleaning and formatting the text to make it suitable for analysis. Our pre-processing steps included tokenization, retaining alphanumeric characters, removing stop words, lemmatization, special character removal, URL removal, and removing user mentions and hashtags. These steps ensured that the text data was in a format conducive to accurate sentiment analysis.

# Feature Extraction
## 1) Frequency Distribution
Frequency distribution, a fundamental concept in Natural Language Processing (NLP), involves analyzing word or linguistic element occurrences within a text or corpus. This analysis, often represented as a table or graph, reveals language usage patterns. Frequency distribution aids various NLP tasks like text classification and information retrieval by helping identify relevant features and ranking documents based on relevance.

## 2) Named Entity Recognition (NER)
Named Entity Recognition (NER), an NLP technique, identifies and extracts named entities such as names, organizations, locations, and monetary values from unstructured text data. NER finds applications in information extraction, sentiment analysis, and text classification. In our project, NER helps identify relevant entities in tweets related to the need for help, charity, and support in selected U.S. states.

## 3) Part-of-Speech (POS) Tagging
Part-of-speech (POS) tagging, a foundational NLP task, assigns grammatical tags to words in sentences, indicating their syntactic roles. Tags include parts of speech like nouns, verbs, adjectives, and adverbs. POS tagging plays a vital role in NLP applications, including machine translation, text-to-speech synthesis, sentiment analysis, and named entity recognition. Various techniques, from rule-based methods to deep learning models, can be employed for POS tagging.

# Sentiment Analysis
Sentiment analysis, a subset of NLP, discerns whether text conveys a positive, negative, or neutral sentiment. Also known as opinion mining or emotion AI, sentiment analysis tools interpret tone, meaning, and intentions behind text data. It finds widespread use in gauging public sentiment from sources such as reviews, surveys, web articles, and social media.

# Models and Methodologies Used
Our project employs various Python libraries and methods for sentiment analysis. Key approaches include:

1. TextBlob
2. VADER
3. Flair

# Results
## Sentiment Distribution of Needy
<img width="660" alt="image" src="https://github.com/ChiradeepNanabala/From_Tweets_to_Hope/assets/44319198/0c4d2c79-b663-4a56-89d0-fa90b74b7aa3">

## Sentiment Distribution of Donors
<img width="660" alt="image" src="https://github.com/ChiradeepNanabala/From_Tweets_to_Hope/assets/44319198/9d3038e3-210e-4cf4-87ae-3fd54d067682">

## Positive Tweets of Needy & Donor Groups for TextBlob, Vader, Flair
<img width="660" alt="image" src="https://github.com/ChiradeepNanabala/From_Tweets_to_Hope/assets/44319198/96451a19-9d9d-4c8b-8e7b-5e87e05fc4ab">

## Choropleth Map of Needy in USA
<img width="660" alt="image" src="https://github.com/ChiradeepNanabala/From_Tweets_to_Hope/assets/44319198/b4b42819-76c1-4c84-b8ac-8aae5fa9f471">

## Choropleth Map of Donors in USA
<img width="660" alt="image" src="https://github.com/ChiradeepNanabala/From_Tweets_to_Hope/assets/44319198/8223bbf2-f76f-4fac-a55e-513b9746242e">

## Examples of Extracted Tweets

<img width="660" alt="image" src="https://github.com/ChiradeepNanabala/From_Tweets_to_Hope/assets/44319198/34a143cb-f9b6-4933-ab96-7bb12895fd5b">

# Conclusion

## Project Impact
Our project harnesses the extensive Twitter ecosystem, spanning diverse categories, to efficiently gather and categorize tweets from individuals seeking assistance and compassionate volunteers. By establishing seamless connections, we bridge the divide between those in need and those ready to extend a helping hand. Through our platform, we cultivate a valuable network that nurtures meaningful collaborations and support.

## Enhancing Communication on Twitter
Our approach aims to make tweets more accessible and reliable, potentially elevating the overall positivity and helpfulness of interactions on Twitter. In the realm of social media, where negative tweets and misinformation often dominate discussions, our one-stop solution for improved tweet accessibility and reliability can counteract these negative trends. It promotes more constructive, collaborative exchanges on the platform.

## Elevating Sentiment Analysis
Moreover, our approach has the potential to enhance the accuracy and consistency of sentiment analysis. The improved accessibility and reliability of tweets can provide more dependable data for sentiment analysis algorithms. This project offers a promising avenue to elevate the quality of communication on Twitter and foster a more inclusive, engaged, and supportive community on the platform.


