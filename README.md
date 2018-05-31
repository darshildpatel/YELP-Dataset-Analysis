## Big Data Analysis and Visualization
Gathering useful insights from the Dataset using interactive tool **Apache Zeppelin**. This tool provides an integrated platform to have a Web-based notebook that enables data-driven, interactive data analytics and collaborative documents with SQL, Scala etc. 
I am running zeppelin locally on docker by following these [instructions](https://github.com/dylanmei/docker-zeppelin). I pulled all the JSON files into HDFS for easy access.

### About the Yelp Dataset
- 4.1M reviews and 947K tips by 1M users for 144K businesses
- 1.1M business attributes, e.g., hours, parking availability, ambience.
- Aggregated check-ins over time for each of the 125K businesses
- 200,000 pictures from the included businesses

### Analysis on Zeppelin
- Summarize the number of reviews by US city, by business category.
- Rank all cities by # of stars descending, for each category
- What is the average rank (# stars) for businesses within 15 km of Edinburgh Castle, Scotland, by type of business (category)? 
- Rank reviewers in Q3 by their number of reviews. For the top 10 reviewers, show their average number of stars, by category.
- For the top 10 and bottom 10 category Food businesses in Q3, (in terms of stars), summarize star rating for reviews in January through May only.
