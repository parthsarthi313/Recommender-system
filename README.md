# Recommender-system
- This is an application which provides recommendations based on user input
![Screenshot 2021-08-30 214707](https://user-images.githubusercontent.com/77001772/131371307-32162c97-ce6e-4ff4-86fa-ec6d14323ae2.png)
[![Conda Latest Release](https://anaconda.org/conda-forge/pandas/badges/version.svg)](https://anaconda.org/anaconda/pandas/)
[![Website shields.io](https://img.shields.io/website-up-down-green-red/http/shields.io.svg)](http://shields.io/)<br>
[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)
## About the Code
- The application is fully developed using python and its libraries like numpy,pandas and sklearn.
- Vectorisation of Movies is done and each movie is converted to a vector of 5000 dimension.
- At the end, Cosine Similarity is applied to recommend the closest similar vector based on actor/genre/title etc.
- Code is written in simple language with pandas dataframe and numpy methods.
## How does the application work
#### The Application is pretty simple to use. Just write the name of the movie, you want to get recommended, 5 movies closely resembling to it will be shown.
#### Link to the demo:-
https://movie-recomm31.herokuapp.com/
## How to run the code and deploy using Heroku
- First install the metadata for movies and credits from the given link:-
https://www.kaggle.com/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv
- Download numpy,pandas,pickle and streamlit.
- run the ipynb in the virtual environment, You will get movies_list.pkl,similarity.pkl.
- run the command "streamlit run app.py" to get the website on your local system.
### To deploy the website on Heroku
- Create an app on Heroku.
- Add all the files in staging area, commit them, then add the command "git push heroku master" to run on server.
