# **kmeans-clustering-song-recommendation**


<img src ="https://blog.global.fujitsu.com/fgb/wp-content/uploads/sites/3/2021/01/Zz0zNWU5ODJmMGUyMDUxMWVhYjMyYzBhYzcxZWQyN-scaled.jpg"> <br />

# **workflow**

- The purpose of this project is to write a python function which takes a song as a user input and then recommends a similar song based on the audio features of the song. 
- To do this we will use the spotify api to save a playlist of around 5000 songs with their audio features (such as danceability, loudness etc) as a pandas dataframe. 
- Then we will take a song as user input and use the kmeans algorithm to recommend the user a similar song.

# **libraries**

- [Pandas](https://pandas.pydata.org/docs/)
- [Spotipy](http://spotipy.readthedocs.io)
- [Sklearn](https://scikit-learn.org/stable/)
