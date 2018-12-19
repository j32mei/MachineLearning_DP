# Machine Learning: Design Project
# Johnson Mei and Aulon Ibrahimi
# Song Recommendations
  This repository provides code that utilizes classifiers of machine learning to determine a recommended song or playlist based on the       given song/track along with the dataset.
  
  The problem we are trying to tackle is the issue that arises when a music playlist is so overly played that just the sound of the songs begins to bother you or even bring down your mood. Thus, our attempt to provide a music playlist consisting of songs that are similar in aduio features with the current track being listened to.
  
  Approach: Using the Top Spotify Tracks of 2017 dataset which consists of audio features like danceability, energy, and valence, basically the vibe of the song, we determined which of these attributes were of most important and mapped it in a n-th dimensional array. Using this array, we implement k-means clustering to place all the songs into clusters based around the centroids of each feature. Given the current track, we returned a playlist of songs that were in the same cluster.
  
  Evaluation: Based off of our knowledge of the songs within the dataset, we believed it returned an appropriate playlist and unfortunately, we do not have some numerical representation of how good the recommended playlist is. Some shortcomings of our approach was our limited dataset which only consisted about 100 songs which probably gives us the bare minimum in terms of a recommendation. 
  
  Future Work: Work with multiple and larger datasets to create the ultimate music listening experience. Implement a system in which user can give direct feedback, maybe a like or dislike, to adjust the playlist accordingly because everyone has there own music preferences.
  
