# EDA-Numbers-of-visitors-to-japan

# INTRODUCTION
From 2017 to 2023, Japan has witnessed a significant growth in the number of foreign visitors. Over this period, the country has become an increasingly popular destination for travelers from all around the world. With its unique blend of traditional culture and modern amenities, Japan offers a captivating experience that appeals to a wide range of interests. The introduction of e-passports and automated immigration gates at airports has significantly streamlined the arrival process and reduced waiting times. Regarding the types of visitors, there has been a diversification in the profile of foreigners visiting Japan. While Japan has long been popular among tourists from neighboring Asian countries, such as China and South Korea, there has been a noticeable increase in visitors from other regions as well. Travelers from North America, Europe, and Australia have shown growing interest in exploring the rich cultural heritage and natural beauty of Japan.

# About the dataset
I got the dataset from kaggle. https://www.kaggle.com/datasets/risakashiwabara/japannumber-of-visitors-to-japan/data

very many people are coming to japan, in this issue, I will show the number of people coming to Japan by month and by year, and also the number of people coming to Japan by Countries.

# Tool Used
Power BI (Power query, DAX)

# Data Preparation
## Data transformation
The data was already cleaned but there was errors for some data type columns

![transform](https://github.com/AdekunleOjo/EDA-Numbers-of-visitors-to-japan/assets/55541028/9b46e5bb-c9ea-4ac0-8f10-ee47150d67fc)

For the visitor's column, i changed the data type from text to Whole number because the the data type is numeric and i also changed the data type for the Year column to Whole number.

## Data modeling
I created another table called month to find the unique value for month to match each value in the Montly visiting Table

![month](https://github.com/AdekunleOjo/EDA-Numbers-of-visitors-to-japan/assets/55541028/8d4785cb-2263-4367-905d-54e335a5a83a)

And then I joined the tables together by the month column for each table using one to many relationship
![modeling](https://github.com/AdekunleOjo/EDA-Numbers-of-visitors-to-japan/assets/55541028/9dc82e93-bcea-4ff7-8090-dc9457684c34).

## Visualization and Dashboard
![japan](https://github.com/AdekunleOjo/EDA-Numbers-of-visitors-to-japan/assets/55541028/601b1ae5-492b-4b0c-a927-6a1d9303a8c1)

## Uncovered insights
- Averagely over 40,000 people are entering japan daily for (2017-2023)
- Over 100 million people have entered japan within the last 7 years
- China, South korea and Taiwan topped the chart as the most visited countries to japan with china having over 27 million travellers within the last 7 years
- January, April, and june are people's favourite months to visit japan, while september was recorded the lowest.
- Visitor arrivals to japan reduced drastically on 2020, i think this is due to the covid-virus outbreak, most places were lockdown around the world and travellers were restricted.

# Recommendation
- Averagely 40,000 people are entering japan daily, this shows how peaceful and accommodating japan is.
- Among the top 20 countries that visited japan within (2017-2023), i noticed that no african countries was there, japan can also consider this and make visa free to some african countries, this we promote africa-japan collaboration and as well africa-asia collaboration.
- Given the increasing popularity of Japan as a travel destination, it is advisable for foreigners to plan their trips well in advance. This includes booking accommodations, securing transportation, and researching popular attractions to make the most of their visit. 
- Before traveling to Japan, foreign visitors should make sure to check the specific visa requirements for their country of origin. Japan has implemented measures to ease visa restrictions for many nationalities, but it's essential to stay updated on any changes or specific documentation needed.
- Japan is known for its advanced technology, so foreigners should take advantage of it to enhance their travel experience. Utilize smartphone apps for navigating public transportation, translating signs, and discovering local attractions and restaurants.




