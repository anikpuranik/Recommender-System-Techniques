# Recommender-System-Techniques
In very general way, Recommendation System are used for suggesting relevant items (like movie, song or books) to user.<br>

Techniques of Recommendation Systems: 
1. Average Weighted: We Find the item that has highest rating and is popular. This is simple, effective and very popular approach.
2. Content Based Filtering: Where one or more attributes of the item are considered and the item with same attribute with maximum popularity is recommended.
3. Collaborative Filtering: We find users with similar interest in the item and based on the users interest recommend the similar item.

Although we have 3 approaches, this can be combined to form a very good recommendation system. Services like Amazon uses all three recommendation system based on the category and purpose. As soon as you enter the page, you can see few recommendation that are popular and are highly rated. This uses <b>Average Weighted Recommendation.</b> When you search for a product, this recommendation <b>('Customers who bought this item also bought")</b> is shown. This comes under <b>Collaborative Filtering.</b> When you have searched for few products and your track interest is available, than <b>Contect Based Recommendation</b> is used <b>("Based on your interest")</b>

Here, we have used a Kaggle <a href="https://www.kaggle.com/tmdb/tmdb-movie-metadata">dataset</a> for movie recommendation using all the three techniques.
