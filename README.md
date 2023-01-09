# MusicRecommender

Utilizes a dataset of 25000+ songs and their features to perform song clustering and popularity prediction

Clustering is done using K-means clustering and DBScan clustering. 

Popularity prediction is done with a decision tree classifier. The classifier can predict a song's popularity with about 70% accuracy. 

**Deatures used by the decision tree classifier:** 
- danceability
- energy
- key
- loudness
- speechiness
- acousticness
- liveness
- valence
- tempo
- duration_ms

**Features in the data:**
- Artist Name
- Track Name
- Popularity
- Genres
- Playlist
- danceability
- energy
- key
- loudness
- mode
- speechiness
- acousticness
- instrumentalness
- liveness
- valence
- tempo
- id
- uri
- track_href
- analysis_url
- duration_ms
- time_signature
