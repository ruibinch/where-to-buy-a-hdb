# Where to buy a HDB flat

The HDB resale price data from 1990-2018 is analysed and used to predict the trend of housing prices for different regions of Singapore in the future.
Then, a decision can be made on which is the most profitable region for a purchase of a HDB flat.

Overview:
- Singapore is divided into 6 regions - Far North, North, North East, East, West, Far West
- For each region, the average price per sqm for the past 28 years is obtained and plotted in a `price per sqm` vs `quarter` graph
- An <b>RNN utilising LSTM neurons</b> is trained using the existing dataset and subsequently used for time-series forecasting to predict the
future housing prices in that region

<br>

Potential future improvements:
- Further tweaking of the neural network
  - Utilising callbacks (e.g. early stopping)
  - Optimising the choice of hyperparameters (batch size, number of neurons, number of epochs)
- Utilise a sliding window for train-test split

<br>
<hr>

This project was developed for the Machine Learning Driven Data Science course organised by NUS-ISS.
