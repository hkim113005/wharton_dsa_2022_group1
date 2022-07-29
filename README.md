# wharton_dsa_2022_group1
Wharton Global Youth Data Science Academy 2022 Group 1 Final Project

## Citations

Cjhutto. “CJHUTTO/Vadersentiment: Vader Sentiment Analysis. Vader (Valence Aware Dictionary and Sentiment Reasoner) Is a Lexicon and Rule-Based Sentiment Analysis Tool That Is Specifically Attuned to Sentiments Expressed in Social Media, and Works Well on Texts from Other Domains.” GitHub, https://github.com/cjhutto/vaderSentiment.

Dave, Dhruvil. “Billboard ‘The Hot 100’ Songs.” Kaggle, 9 Nov. 2021, https://www.kaggle.com/datasets/dhruvildave/billboard-the-hot-100-songs.

Silva, Mariana O. S. “MusicOSet An Enhanced Music Dataset for Music Data Mining.” MusicOSet - an Enhanced Music Dataset for Music Data Mining, https://marianaossilva.github.io/DSW2019/#downloads.


## Data Sources
In our project we utilized 4 main data sources. These included two data sets: one on the Billboard Hot 100 (the second citation) and one on artist popularity (the third citation). In addition, we did a lot of data scrapping from both Spotify and Genius.

## Packages
Throughout our project we used many algorithms and packages in R and Python. This included the Python packages Spotipy (https://spotipy.readthedocs.io/en/master/), lyricsgenius (https://lyricsgenius.readthedocs.io/en/master/reference.html), tensorflow, sklearn, pandas, numpy, pickle, tqdm, vaderSentiment, and other base Python packages. In R we utilized tidyverse, glmnet, xtable, data.table, and other packages.

## Data Files
In our data directory we have a sub-directory for the original datasets. In the main data directory there are many csv that represent different data we scraped through APIs. Our raw combined dataset is the "group1_hit_songs_dataset_raw1.csv" (the one without the number does not include the sentiment of lyrics). The main cleaned datasets we used were labeled "group1_hit_songs_dataset_ml_" followed by a number with the ".csv" extension. Number 2 is the cleaned and prepared data with the hitness as a boolean. Number 5 is the cleaned and prepared dataset with log scaling on tempo and popularity. Number 7 is the cleaned and prepared dataset with the maximum division scaling on tempo and popularity.

## Code
We programmed in Jupyter Notebook and Rmd files. The number explain the order in which we ran each script and the titles explain the goal of each script. Descriptive headers explain the programs in Python and each R chunk has a decriptive title as well.