# Analysing Climate Change with Machine Learning
![Climate Change](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQowmMZNQOtHnOWDSkilSu6JtGrZBGcYk4zj3XzC0iI6LyW0_Yj&s)

## Data Summary
The data contains temperature readings for a vast date range, from 1750 to 2015. This dataset specifically covers the global temperature combined, rather than solely the sea or land temperature. This was chosen because of the amount of comparitive analysis available on global combined temperature rather than the other two options in isolation.

## Problem Statement
Devastating environmental damage will only increase as the climate continues to change. It is (generally) proven that the climate is changing for the worse, but that isn't the main problem that was addressed with this piece of analysis. In this analysis, I wanted to be able to train a machine learning model that would tell us what the average temperature will be in 10, 50 or 100 years' time, so that we can map these temperatures back to the devastating effects of even a small amount of average temperature change.

## Solution
I have used machine learning in the form of a simple linear regression to analyse this dataset and have trained the model to enable us to use it to predict the average combined temperature for any given year. This is a supervised form of machine learning, meaning that I trained it on the data we have available to us and based off of that data, the model has learnt how to predict the temperature for future dates.
