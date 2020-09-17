# PGA-Tour-Predictor

## Description
I'm interested in creating a machine learning model that can predict the percentage chance that a PGA Tour player will have at winning a specific tournament. This is still a work in progress, but the features will be a number of statistics related to each player (e.g. driving distance, driving accuracy, SG: putting, etc.) as well as the course that they play for each tournament.

I initially plan to use year-end stastical ranks as inputs to the model for right now. In the future, I foresee it being advantageous to utilize a more dynamic feature set of current stastical ranks preceding the tournament in question.

## Project Status
Currently, I have scraped pgatour.com for the desired year-end statistics from 2015 to 2020 and saved as csv files in 'HTML Data/'. I'm working towards obtaining past tournament results for the years 2015 to 2020 and building out my initial train/test datasets from there. I'll then likely run these through a custom PyTorch neural network model using gradient descent and a TBD criterion/optimizer.
