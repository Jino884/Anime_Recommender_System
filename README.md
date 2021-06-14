# Data Science Project: Anime Recommender System
* Exploring the anime dataset to overview the amine charasteristic and featuring analysis.
* To create the collaborative filtering recommendation by Singular Values Decompostion, dimentional reduction technique, proposed to recommend the anime to each user.

## Code and Resources Used
__Python:__ 3.8.3                                                                                                                                  
__Coding Tools:__ Jupyter, Google Colab                                                                                       
__Package:__ pandas, numpy, matplotlib, seaborn, re, surprise, IPython.display                                                                                 
__Surprise Desktop:__ http://surpriselib.com/                                                                                                       
__Surprise Ducumentation:__ https://surprise.readthedocs.io/en/stable/                                                                        
__Surprise Github:__ https://github.com/NicolasHug/Surprise                                                            
__Anime Dataset:__ [Dataset](https://github.com/Jino884/Anime_Recommender_System/tree/main/Data) or https://www.kaggle.com/CooperUnion/anime-recommendations-database

## Data Cleaning
_Follow the coding_: [here](https://github.com/Jino884/Anime_Recommender_System/blob/main/Data_Cleaning.ipynb).                                       
An anime dataset (_anime.csv_) (for exploration)
* __genre__ -- fill null with the string "no detail".
* __type__ -- fill null with the string "etc".
* __episodes__ -- change value 1 to the string "movie"
* __rating__ -- fill na with 0 that represent no data

A rating dataset (_rating.csv_) (for creating the model)
* __rating__ -- Change the value -1 to 0


After cleaning data you will obtain anime_C.csv and rating_C.csv which are cleaned anime dataset and cleaned rating dataset respectively.

## EDA
_Follow the coding_: [here](https://github.com/Jino884/Anime_Recommender_System/blob/main/Data_Exploratory.ipynb).        

<img src="https://github.com/Jino884/Anime_Recommender_System/blob/main/types%20of%20anime.png" width="60%" height="50%">
