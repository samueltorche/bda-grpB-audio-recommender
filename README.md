# bda-grpB-audio-recommender
Project for MSE BDA course - Group B - Recommending Music and the Audioscrobbler Data Set

# Summary
The goal is to implement a music recommendation system. It uses a dataset published by Audioscrobbler. Audioscrobbler was the first music recommendation system for last.fm, one of the first Internet streaming radio sites, founded in 2002. It contains listeners’ plays of artists’ songs.

# Analysis questions
1. Peut-on obtenir des résultats intéressants en utilisant des technique de Market Basket Analysis telles que les règles d'association ?
2. Peut-on déduire les genres des musiques à l'aide d'un clustering des utilisateurs et leurs écoutes ?
3. Est-il possible de recommander non pas des artistes mais d'autres utilisateurs qui partagent les même goût avec ALS ?

# Documentation
The project documentation is in the pdf file: BDA_grpB_rapport.pdf

# Content
MBA_audioscrobbler.json contains the notebook for the first analysis question

KMEANS-MUSIC-genre.json contains the notebook for the second analysis question

????.json contains the notebook for the third analysis question

download_data.sh script to download audioscrobbler data

# Data download
Execute script download_data.sh

Take content of extracted folder profiledata_06-May-2005 (except readme) and put in data folder in zeppelin.

Data was too big to be hosted on GitHub.

# References
[1] Sandy Ryza, Uri Laserson, Sean Owen, Josh Wills Advanced Analytics with Spark O'Reilly May 2017
