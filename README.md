# DA-401 Spotify Project

This project is part of my DA 401 senior seminar course. In this project, I attempt to find a sort of acoustic coherence between rock songs through time. This project uses the Spotify API to compile together my data. 

The data file contains all of the data that I used in the project. The sample.csv contains the random samples of data that I took, while the other data files are the larger pulls that I made specific to each genre, and are labeled as such. These data files are what were sampled to create sample.csv. 

The figures folder contains all of the figures in the paper. 

The Spotify R markdown file is the file in which the data was pulled, compiled, and sampled. This makes use of the Spotify API, under proper, fair use of it. 

The Spotify Analysis R markdown contains all of the methods that I implemented. This begins with the random teams modeling, followed by logistic regression, PCA, and KNN. Included as well is the acoustic coherence testing. 

The final file is the Spotify Analysis (no post punk) R markdown. This file is identical to the previous Spotify Analysis R markdown, however, this time post-punk has been removed as a genre in order to better test for genre coherence and granularity. 