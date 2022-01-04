# Amazon_Vine_Analysis

## Overview
Since your work with Jennifer on the SellBy project was so successful, you’ve been tasked with another, larger project: analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project, you’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. You’ll need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, you’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.

## Resources
Software: Google Colab Notebook, PostgreSQL 12.8, pgAdmin 4, AWS

## Results
![Vine_Review](https://user-images.githubusercontent.com/83085800/148006042-84d4740c-601c-4489-bc35-bc38c97c9c12.png)

## Summary
41.60% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is 53.01%. This describes a negative bias for reviews in the Vine program.
