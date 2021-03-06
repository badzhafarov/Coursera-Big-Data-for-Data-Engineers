Homeworks:
* Week 5
  * [Music Recommender 1](https://github.com/badzhafarov/Coursera-Big-Data-for-Data-Engineers/blob/master/Big%20Data%20Analysis/recommender1.ipynb) - build the edges of the type “track-track”. To do it you will need to count the collaborative similarity between all the tracks: if a user has started listening to track B within 7 minutes after starting track A, then you should add 1 to the weight of the edge from vertex A to vertex B (initial weight is equal to 0).
  * [Music Recommender 2](https://github.com/badzhafarov/Coursera-Big-Data-for-Data-Engineers/blob/master/Big%20Data%20Analysis/recommender2.ipynb) - build the edges of the type “user-track”. Take the amount of times the track was listened by the user as the weight of the edge from the user’s vertex to the track’s vertex.
  * [Music Recommender 3](https://github.com/badzhafarov/Coursera-Big-Data-for-Data-Engineers/blob/master/Big%20Data%20Analysis/recommender3.ipynb) - build the edges of the type “user-artist”. Take the amount of times the user has listened to the artist’s tracks as the weight of the edge from the user’s vertex to the artist’s vertex.
  * [Music Recommender 4](https://github.com/badzhafarov/Coursera-Big-Data-for-Data-Engineers/blob/master/Big%20Data%20Analysis/recommender4.ipynb) - build the edges of the type “artist-track”. Take the amount of times the track HAS BEEN listened by all users as the weight of the edge from the artist’s vertex to the track’s vertex.

* Week 6
  * [BFS](https://github.com/badzhafarov/Coursera-Big-Data-for-Data-Engineers/blob/master/Big%20Data%20Analysis/BFS_spark_SQL.ipynb) - breadth-first search using the Dataframe API.
