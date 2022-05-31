# MS-Engage Recommender-System-Project

* **Movies Recommender System:** This part is focused around building two kinds of recommendation engines; namely the Simple Generic Recommender and the Content Based Filter.

* **Books Recommender System:** This part is focused around building two kinds of recommendation engines; namely the Simple Generic Recommender and the Collaborative Based Filter.

## Check out the live demo:[LIVE](https://recommend-books-movies.herokuapp.com/)

##  Concept learnings
* **Simple Recommender:** This system used overall TMDB Vote Count and Vote Averages to build Top Movies Charts, in general and for a specific genre. A simple popularity formula was used to calculate ratings on which the sorting was finally performed.
* **Content Based Recommender:** I built a content based engine; calculating cosine similarity.
operations done on the metadata of movies provided in dataset.
* **Collaborative Filtering:** Implemented this using user_id, book-title and user-ratings; to recommend books to users with similar tastes.
 
## Project Flow

<img src="https://github.com/RajshreeVats/recommendation-engine/blob/master/templates/My%20First%20Board%20(2).jpg">
<img src="https://github.com/RajshreeVats/recommendation-engine/blob/master/templates/My%20First%20Board.jpg">

### Approach 

The problem was divided into several steps:

1. **Data Collection:** Data for movies was collected from the TMDB website and through a script that queried for data from various TMDB Endpoints. Dataset for Books was collected from Kaggle website.
2. **Data Wrangling:** The datasets were uploaded to a dataframe and explored. Null values were filled in wherever appropriate and polluted values were discarded or wrangled.
3. **Recommendation Systems:** Four different recommendation systems were built using various ideas and algorithms such as IMDB's Weighted Rating, Content Based Filtering and Collaborative Filtering.
3. **Website:** Built using Flask web app framework for python.

## Final Results 
# Features Implemented
1. Recommends Top 50 books in trending 
2. Top 5 books recommended to user 
3. Recommends Popular picks in movies
4. Top 3 movies recommended to user
5. Synopsis of the movie 
6. Link to play the movie
7. User Ratings
 

# Tech Stack
<p align ="center">
  <code><img src="http://api.buttercms.com/static/images/tech_banners/Flask.716baf905d79.png" width="10%" /></code>
  <code><img src="https://www.digitaldesignjournal.com/wp-content/uploads/2018/07/Python-Programming-Wallpaper_1.jpg" width="10%" /></code>
  <code><img src="https://i1.wp.com/softwareengineeringdaily.com/wp-content/uploads/2018/07/jupyter-logo.png" width="10%"/></code>
 <code><img src="https://upload.wikimedia.org/wikipedia/commons/3/31/NumPy_logo_2020.svg" width="10%"/></code>
 <code><img src="https://en.wikipedia.org/wiki/Pandas_(software)#/media/File:Pandas_logo.svg" width = "10%"/></code>
 
### Deployed using :
 
  <code><img src="https://iconape.com/wp-content/files/us/67356/png/heroku-1.png" width="10%"/></code>
  <code><img src="https://img.icons8.com/color/64/000000/git.png" width="10%"/></code>
  <code><img src="https://img.icons8.com/color/64/000000/github.png" width="10%"/></code>



# How to get the API key?
Create an account in https://www.themoviedb.org/, click on the `API` link from the left hand sidebar in your account settings and fill all the details to apply for API key. If you are asked for the website URL, just give "NA" if you don't have one. You will see the API key in your `API` sidebar once your request is approved.

# How to run the project?
1. Clone or download this repository to your local machine.
2. Install all the libraries mentioned in the [requirements.txt] file with the command `pip install -r requirements.txt`
3. Get your API key from https://www.themoviedb.org/. (Refer the above section on how to get the API key)
4. Open your terminal/command prompt from your project directory and run the file `app.py` by executing the command `python app.py`.
5. Go to your browser and type `http://127.0.0.1:5000/` in the address bar.
6. That's it! 
