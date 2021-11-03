# movie-recommender-system-tmdb-dataset

# there are three recomender sysytems
1. content based system
2. collabaratry filtering system
3. Hybrid system

we are using the A content based movie recommender system using cosine similarity
Content-based filtering approaches uses a series of discrete characteristics of an item in order to recommend additional items with similar properties. Content-based filtering methods are totally based on a description of the item and a profile of the user’s preferences. It recommends items based on the user’s past preferences.

# Stages 
1. preprocessing
2. model building
3. website
4. deoploy

# preprocessing
1. merge the datast on the bases of the title
2. selecting the some columns from overall dataset movie_id, title, overview, genres, keywords, cast, overview
3. removing the spaces form the columns 
4. creting the tag columns 
5. creating the new dataframe including the movie_id , title , tags
6. applying the poster stemmer on the dataset 
7. feature extraction
8. converting array 
9. checking for cosine similarity


# creating the website 
using the streamlit we creating the the website for the movie recomendation sysytem 

# Deploy the website 
The created the website is deployed on the heroku and link is given below.

# Link : [https://movies-recomendation-system.herokuapp.com/]
