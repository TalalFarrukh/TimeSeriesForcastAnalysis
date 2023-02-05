# TimeSeriesForcastAnalysis

Hey everyone! Let me give you a little overview of this small project right here. So the task here is that we have the Date, Latitude and Longitude as our data.
What we need to do is peform binning and the values of the bins are the mean of the latitude and longitude values on the points inside the bin. I managed to achieve this
with the help of geopandas where I was able to create a grid of regular squares and then assign points to each square and calculate their aggregate values.

The next part is to create or let's say, train a ML/ANN model to predict latitude and longitude values based on only the dates given.
The model I used was Long Short-Term Memory networks or also known as LSTM networks. It is part of Neural Networks, specifically, Recurrent Neural Networks (RNN).
I used hyperparameter training in order to find the appropiate parameters to train this complex model. Finally after a lot of training and tunings, my model was ready.

It's not the best model that is out there. It has its flaws since there has only been one factor (Date) that has contributed to the prediction capabilities of the model.

The data and the code has been provided in this repo. Feel free to check it out!
