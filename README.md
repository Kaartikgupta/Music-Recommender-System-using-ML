# Music-Recommender-System-using-ML
There are many companies which are working on daily basis to improve their Recommender System which they are using now like Youtube, Amazon, Netflix and many other such companies which are providing web services. In layman’s term, Recommender system is used to suggest something to the user. Recommender systems are today unavoidable in our daily online journeys.They are typically classified into Content-Based Filtering and Collaborative filtering.

I have made this recommender system using ### Collaborative Filtering

Collaborative algorithm uses “User Behavior” for recommending items. They exploit behavior of other users and items in terms of transaction history, ratings, selection and purchase information. Other users behavior and preferences over the items are used to recommend items to the new users. In this case, features of the items are not known.

The aim of this project is to:-
Build a collaborative filtering music recommeder system using the Million Song Dataset; a freely-available collection of audio features and metadata for a million contemporary popular music tracks.

## User-Based Collaborative Filtering
This is the simplest technique in collaborative filtering in which the recommender system finds the similar users to the active user (to whom we are trying to recommend a movie). A specific application of this is the user-based Nearest Neighbor algorithm. This algorithm needs two tasks:

1.Find the K-nearest neighbors (KNN) to the user a, using a similarity function w to measure the distance between each pair of users:


2.Predict the rating that user a will give to all items the k neighbors have consumed but a has not. We Look for the item j with the best predicted rating..
