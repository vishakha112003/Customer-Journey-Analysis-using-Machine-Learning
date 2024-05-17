# Customer Journey Mapping Analytics using Machine Learning 

![](/images/souledtstore.jpg)

Customer journey mapping is the process of creating a visual representation of a customer's interactions with a brand, product, or service. The customer journey map is a tool to visualize the experience of interacting with our brand from the customer's point of view. This map is critical because it forces us to look at how the customers actually experience our brand versus how we think they do. A customer journey map is a visual depiction of the stages customers go through when interacting with a company -- from buying products online to accessing customer service on the phone to airing grievances on social media.

This is a project that involves customer journey analysis for a famous clothing brand startup named The Souled Store to predict at what journey stage the customer tends to leave his/her journey with the company and understand their customer buying behaviour. 

The objective of this project is to:

•	predict customer behaviours

•	identify churn risk

•	analyze the effectiveness of different marketing channels and strategies to allocate resources more efficiently

•	improve customer service interactions

•	utilize Machine Learning Algorithms to predict when a customer tends to end their journey with the brand based on past behaviour

## Customer Journey Stages

•	Awareness: Customer learns about the product or service. The customer may leave the journey here without buying the product or service

•	Consideration: Customer evaluates the product against other options. This also comes under pre-purchase stage.

•	Purchase: Customer buys the product or subscribes to the service.

•	Retention: Customer uses the product or service regularly. This also includes posting reviews about the product or service.

•	Advocacy: Customer recommends the product to others. This includes giving referrals to others.

## Data Collection 

In this project, I collaborated with a friend who is a UX researcher and she was already working on her project to understand customer buying behaviour and new features that can be added to their app and website which can boost their business growth. She conducted in-person surveys and surveys through Google Forms to understand how customers were interacting with their products and understand their journey.  Some of the questions were multiple choice based and some of them needed custom answers. Some of the questions were:

•	Have you heard about The Souled Store? If Yes, are you a new customer or an old customer? 

•	How did you hear about The Souled Store?

•	Through which touchpoint did you the interact with The Souled Store? 

•	What was the clothing section?(Men,Women,Kids)

•	If Yes, when was the last month in which you interacted with their product?

•	What product category did you made an interaction with?

•	Did you purchase any product? If yes, did you post any review or gave a referall afterwards. If no, what was the last action that you made?

•	What was the ongoing sales campaign in which you interacted with the product?

•	How satisfied were you with your experience of interaction with the product?

These were few of the questions in her surveys that helped her to understand each of the customer’s journey with The Souled Store. She conducted surveys of around 400 people but only approx 250 had ever hear about The Souled Store.

I separated the data into two excel sheets - one for the customer journey data and the other is the product data for those customers who have purchased the product

## Data Integration and Cleaning

Now based on these surveys, I took the data from her surveys and incorporated it in an excel sheet and I further cleaned the data as needed. 

The two data files were merged using joins and data cleaning was done to handle missing values, duplicates, changing data types, dropping unnecessary columns etc.

## Exploratory Data Analysis

 The cleaned data was saved into a separate file for further analysis. First preliminary examination of the data was done and some necessary features were also added. Then using matplotlib and seaborn, data visualization was done to get insights from the data. Different charts were made to understand customer behaviour, how they are interacting and their experience with the brand analyze the data. At the end, insights derived from the data were written to be more clear about what the data says.

 ## Customer Journey Stage Prediction
 
 Next, I used Logistic Regression to predict at what journey stage the customer tends to end their journey wih the brand based on historical data.

 ## Power BI dashboard

 ![](/images/Dashboard%201.png)
 
 Finally, I made a Power Bi dashboard to get a overview about the entire data, understand the sales and purchase, analyzed different marketing strategies and at the end, I prepared a summary to understand what all changes can be implemented to understand business growth.
 


 ####  This project was done only for learning purposes.


