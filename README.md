# Phase-4-NLP-Project
![Google Apple](https://github.com/MuchiriKinyua/Phase-4-NLP-Project/assets/113877377/92e62fe7-1a89-473a-b0dc-bab30bdf02d1)
(1. Business Understanding)[#1.-Business-Understanding] </br>
1.1 Problem Statement </br>
1.2 Main Objective </br>
1.3 Specific Objectives </br>
2. Notebook structure </br>
3. Data Understanding </br>
4. Data Modelling </br>
5. Evaluation </br>
6. Recommendations </br>
7. Conclusions </br
(8. Challenges)[#8.-Challenges]
# 1. Business Understanding
In the competitive landscape of today's market, establishing a profound connection between products or services and the emotions of the target audience is a strategic imperative. Emotional branding offers the potential to cultivate brand loyalty, trust, and differentiation. </br>
To harness the power of emotional branding, businesses must accurately gauge public sentiment towards their offerings, ensuring that the emotional connection aligns with their brand vision. By analyzing various sources of customer feedback, such as social media posts, sentiment analysis can determine whether the sentiment of the feedback is positive, negative, or neutral. </br>
Employing sentiment analysis can lead to data-driven decisions, improving overall performance and reputation, and resulting in increased profitability and success. </ br>
## 1.1 Problem Statement
Emotional branding, a strategy centered on evoking specific emotions in customers, has become a critical driver of brand loyalty and differentiation. Establishing a deep emotional connection between brands and consumers is essential. </br>
However, the challenge lies in accurately assessing and aligning a brand's emotional resonance with customer sentiment in real-time. To address this challenge, this project seeks to develop a sentiment analysis solution that deciphers the emotions expressed in tweets related to Apple and Google products. </br>
The aim to equip businesses shareholders with actionable insights to strategically employ emotional branding and strengthen their brand-consumer relationships. The ultimate goal is to empower organizations to enhance customer loyalty, trust, and competitiveness by aligning their products with the emotions of their target audience. 
## 1.2 Main Objective
To use Natural Language processing to build models which can rate a sentiment on Google and Apple based on tweets.
## 1.3 Specific Objectives
a. To use both NLP and deep learning models to classify tweets into positive, neutral and negative. </br>
b. To visualize sentiment analysis, gain insights from them hence evaluate model performances to conlude informed decisions. </br>
c. Understanding and preprocessing dataset of tweets related to google and apple products.
# 2. Notebook structure
1. Business Understanding
1.1 Business Description
1.2 Problem Statement
1.3 Main Objective
1.4 Specific Objectives
2. Notebook structure
3. Data Understanding
4. Data Modelling
5. Evaluation
6. Recommendations
7. Conclusions
8. Challenges
# 3. Data Understanding
tweet_text - It contains information about the text
emotion_in_tweet_is_directed_at - It contains information about the brand
i.e;
Apple
iPhone
Android App
Google Android
iPad or iPhone App
Other Apple product or service
Other Google product or service
is_there_an_emotion_directed_at_a_brand_or_product (will be used as the target) - It contains information about the emotion towards a given brand
i.e;
I can't tell
Positive emotion
Negative emotion
No emotion toward brand or product
# 4. Data Modelling
Textplob results:
positive    4457
neutral     3799
negative     815
![Sentiment analysis](https://github.com/MuchiriKinyua/Phase-4-NLP-Project/assets/113877377/44831d8b-e1c0-4458-b9fc-3bbebd857590)
# 5. Evaluation
Although the most frequent words for both positive and negative are focused on technology (sxsw), products (apple, iphone), and social media activities (mention, rt(retweet)), their is some differences. </br>
Frequent positive words (which are not in the list of negative words): great and good shows satisfactory and positive sentiments. Frequent negative words (which are not in the list of positive words): quot (argument) and think shows unsatisfactory. </br>
But the BIGGEST INDICATOR here is that there are 4457 positive tweets and 815 tweets. This shows that most tweets expressed favour or satisfactory in the products. Negative ones although at the minority shows that some twitter users were critical about the products. </br>
An accuracy of 68% shows 68% of the models predictions were made correctly.
# 6. Recommendations
The stakeholders should: </br>
Leverage sentiment analysis models. They should improve the areas which lead to negative sentiments by identifying specific issues mentioned in the negative sentiment tweets and priotize their resolution. </br>
Uphold positive ones. They should identify the positive tweets and feedback and capitalize on them hence use them to make progress. </br>
Brand promotion. Share positive sentiment and customer success stories on twitter and marketing channels to bolster brand awareness and trust. </br>
# 7. Conclusions
Celebrate Positive Interactions: Positive sentiment tweets often mention words like great and good. Brands should acknowledge and celebrate these positive interactions. Sharing such experiences can build brand loyalty and trust. </br>
Improve Communication: The analysis reveals that clear and effective communication is essential. Customers often express negative sentiments when they feel uninformed or frustrated. Brands should focus on enhancing their communication strategies. </br>
Enhance Customer Service: in the CrowdFlower brands and products sentiment analysis, customer service plays a pivotal role. Addressing customer service concerns mentioned in tweets can significantly improve overall sentiment. Prompt and helpful responses can turn negative sentiment into positive experiences. </br>
# 8. Challenges
a. Data is way limited. Datasets should be diverse. </br>
b. Quite a challenge developing NLP Models that accuately align tweets with specific emotions. </br>
c. Scaling the solution for sentiment analysis and still maintain brand alignment with evolving emotions. </br>
