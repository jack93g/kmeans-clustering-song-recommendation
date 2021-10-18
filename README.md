# **kmeans-clustering-song-recommendation**


<img src ="https://blog.global.fujitsu.com/fgb/wp-content/uploads/sites/3/2021/01/Zz0zNWU5ODJmMGUyMDUxMWVhYjMyYzBhYzcxZWQyN-scaled.jpg"> <br />

The purpose of this project is to write a python function which takes a song as a user input and then recommends a similar song based on the audio features of the song. To do this we will use the spotify api to save a playlist of around 5000 songs with their audio features (such as danceability, loudness etc) as a pandas dataframe. Then we will fit the kmeans algorithm to the dataframe to create clusters of songs. <br />
 
Finally we will write a function that takes a song as a user input and checks if the song is already in the playlist dataframe. If it is, the function will recommend a different song from the same cluster. If the song isn't already in the playlist, the function will grab the audio features of the song from the spotify api and then based on these features our kmeans model will predict which cluster the song should belong to and then recommend the user another song from this cluster.

