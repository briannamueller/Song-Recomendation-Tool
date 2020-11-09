# Song Recommendation Tool

#### Using the Spotify API, I have created the funtion *recommend_songs()* that allows a user to get song recommendations based on other artists and songs they enjoy.
- Input for the artist argument should be in list format. Ex: ['Justin Bieber, 'Drake', 'Beyonce'...]
- Input for the songs arguments should be a dictionary of tracks and the track artists. Ex: {'thank u, next':'Ariana Grande', 'Watermelon Sugar':'Harry Styles'...}
- The desired number of recommended songs in increments of 20 can be specified with the num_songs argument. The default is 20 songs. 
- The number of artist inputs + the number of song inputs can not exceed 5.

#### Once the user is satisfied with their recommended tracks, they can use the function *create_playlist()* which takes the dataframe of recommended songs as input and creates a Spotify playlist - All done within Python.
- The funtion requires a user ID which can be found on your Spotify profile page. Select the three dots that appear below your profile picture, select 'Share' and then 'Copy Spotify URI'. 
- The arguments 'playlist_name' and 'df' must also be specified.

*See the notebook Song_Recommendation_Function for full documentation.*

<br><br><p align="center">
  <img width="997" alt="Screen Shot 2020-11-08 at 1 06 57 PM" src="https://user-images.githubusercontent.com/54564733/98481919-67dfed80-21c3-11eb-96c1-aab322bb5bca.png">
</p>

<br><br><img width="996" alt="Screen Shot 2020-11-08 at 7 17 53 PM" src="https://user-images.githubusercontent.com/54564733/98490448-29642600-21f7-11eb-8fec-45db21926df7.png"><br>

<p align="center">
  <img width="615" alt="Screen Shot 2020-11-07 at 9 59 48 PM" src="https://user-images.githubusercontent.com/54564733/98481920-6c0c0b00-21c3-11eb-9823-c892f518cf0a.png">
</p>
