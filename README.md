# Product Recommendation System

A system to recommend products which are mostly similiar with viewing product

Description.csv is the Dataset for this system

Dataset columns - columns are item_id,name,description are as Product ID,Product Name,Product Description

ProductRecommend.ipynb - Identifies the similarities between the products. This correlation is further used to identify the similar products for the item being viewed

Recommendation System Steps 

    1.Preprocessing the dataset

    2.Convert each product description into vectors using TF-IDF

    2.The model recommends  similar product based on  description.

    3.Calculate the similarity between all the products using cosine similarity.
    
    4.Recommend top 3 products based on similarity score