# Product_review
Problem Statement: Product Review Clustering and Recommendation

Background:
In the era of e-commerce, understanding customer feedback is crucial for businesses to enhance their products and services. However, with an overwhelming amount of reviews, it becomes challenging to extract meaningful insights and provide personalized recommendations to customers. Your task is to develop a machine learning solution that clusters product reviews based on their content and recommends similar products to customers.

Dataset:
You are provided with a dataset containing product reviews. Each review is accompanied by the following attributes:

asin: Unique identifier for the product.
sentence: The text of the review.
helpful: A metric indicating the helpfulness of the review.
main_image_url: URL of the main image associated with the product.
product_title: Title of the product.

Objective of model 

Clustering techniques to cluster product reviews based on the content of the reviews. Each cluster  represent reviews that are semantically similar.
Developling  a recommendation system that suggests similar products to a given product based on the clustering results. When a user provides the title of a product, the system should recommend other products that belong to the same cluster as the given product.
