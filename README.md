# EDA-Numbers-of-visitors-to-japan

## INTRODUCTION
From 2017 to 2023, Japan has witnessed a significant growth in the number of foreign visitors. Over this period, the country has become an increasingly popular destination for travelers from all around the world. With its unique blend of traditional culture and modern amenities, Japan offers a captivating experience that appeals to a wide range of interests. In recent years, the Japanese government has actively promoted tourism, aiming to attract 40 million foreign visitors by 2020, an ambitious goal that was eventually achieved. This successful campaign, combined with the country's hosting of major international events such as the Rugby World Cup in 2019 and the Summer Olympics in 2021, has further boosted Japan's reputation as a must-visit destination. During this period, Japan has made great strides in facilitating travel for foreign visitors, including loosening visa restrictions and implementing user-friendly technologies to enhance the overall travel experience. The introduction of e-passports and automated immigration gates at airports has significantly streamlined the arrival process and reduced waiting times. Regarding the types of visitors, there has been a diversification in the profile of foreigners visiting Japan. While Japan has long been popular among tourists from neighboring Asian countries, such as China and South Korea, there has been a noticeable increase in visitors from other regions as well. Travelers from North America, Europe, and Australia have shown growing interest in exploring the rich cultural heritage and natural beauty of Japan.

## About the dataset
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
i created another table called month to find the unique value for month to match each value in the Montly visisting Table


