A recommender system aims to predict or filter preferences based on the user’s selections. Recommender systems are employed across diverse domains such as movies, music, news, books, research papers, search queries, social tags, and general products.
Recommender systems generate a list of suggestions using one of two methods.

**Collaborative Filtering:** Collaborative filtering methods create a model based on the user's previous activities (e.g.,). products bought or looked up by the user, along with comparable choices made by other users. The model is subsequently utilized to forecast items (or their ratings) that might capture users' interest.

**Content-based filtering:** This approach utilizes specific attributes of an item to suggest other items that share similar characteristics. Content-based filtering methods are totally based on a description of the item and a profile of the user’s preferences. It recommends items based on the user’s past preferences.

Let’s develop a basic recommendation system using Python and Pandas. 
Let’s focus on providing a basic recommendation system by suggesting items that are most similar to a particular item, in this case, movies. It just tells what movies/items are most similar to the user’s movie choice.
