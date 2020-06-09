# Movie Recommendation System

An end-to-end Hplywood Movie Recommendation System deployed on Heroku platform using Python language and Flask web framework.

Check out the web link for demo: https://movie-recommendor.herokuapp.com/

## File Description:

[Procfile](Procfile) - This is to declare the process types in the app. It specifies the commands to be executed when the app is run on the server. This file is necessary for Heroku platform.

[app.yaml](app.yaml) - Here, it is used to define the runtime environment. Use it if you're deploying on GCP.

[requirements.txt](requirements.txt) - It is important to include all the libraries used in the code and their acceptable version(s). 

[preprocessing.ipynb](preprocessing.ipynb) - This is for exploratory purposes and preprocess the [movie_metadata](movie_metadata.csv) file to [data](data.csv) file.

[create.py](create.py) - It contains the same preprocessing steps as in ipynb file above so that it can be used in the app environment.

[main.py](main.py) - This is the main file from where the application is run.

#### All the code files contains relevant comments explaining the steps.

## Dataset:

The dataset was taken from [this kaggle link](https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset). This data contains metadata for 5000 Hollywood movies. 



