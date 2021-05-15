# Alphabet-s-Stock-Price-Prediction-Plus-Forecasting
<img src="https://cdn.business2community.com/wp-content/uploads/2015/08/alphabet-logo-970-80-150x150.jpg.jpg" alt="Alphabet" width="900" height="500">
<p>Alphabet Inc. is an American multinational conglomerate. It was created through a restructuring of Google in 2015, and became the parent company of Google and several former Google subsidiaries. In 2020, Alphabet became the fourth US company to reach a $1 trillion market value. It is a publicly listed company on NASDAQ as GOOG. 
</p>
<p>Alphabet is one of the most profitable companies, and the investors have ripped a lot of money from it by investing in its share. Stock price prediction is a trick and cumbersome task, that's why I have created a deep learning model that has extensively trained on Alphabet's stock price data to predict the stock value and <b>give forecasting  of next 60 days with an R2 score of 0.97</b>.</p>
<h2>Libraries Used</h2>
<ul>
  <li>Tensorflow</li>
  <li>Keras</li>
  <li>Numpy</li>
  <li>Pandas </li>
  <li>Matplotlib</li>
  <li>Numpy</li>
  <li>Sklearn</li>
</ul> 
<h2>Data Visualization</h2>
<img src="https://github.com/NavinBondade/Alphabet-s-Stock-Price-Prediction-Plus-Forecasting/blob/main/Alphabet's%20Stock%20Price%20%20Prediction%20Plus%20Forecasting/Graphs/Alphabet's%20Stock%20Price%20(Open).png" width="800" height="400">
<h2>Model Detail</h2>
<p>
The model at its core uses three Long Short-Term Memory (LSTM) which has proven quite effective for learning long-term dependence for stock price prediction and forecasting, and three dense layers for decision-making tasks. The model is trained for 40 epochs and uses adam as an optimizer and mean squared error as the loss function. The batch size was 30 during the training process. The dataset on which model trained was downloaded from finance.yahoo.com.</p>
<h2>Model Training</h2>
<img src="https://github.com/NavinBondade/Alphabet-s-Stock-Price-Prediction-Plus-Forecasting/blob/main/Alphabet's%20Stock%20Price%20%20Prediction%20Plus%20Forecasting/Graphs/loss.png" width="450" height="300">
<p>After training the model has shown loss: 0.0012</p>
<h2>Model Prediction</h2>
<img src="https://github.com/NavinBondade/Alphabet-s-Stock-Price-Prediction-Plus-Forecasting/blob/main/Alphabet's%20Stock%20Price%20%20Prediction%20Plus%20Forecasting/Graphs/Alphabet's%20Stock%20Price%20(Open)%20Prediction.png" alt="tomato" width="800" height="400">
<p>The model has predicted the stock price value quite accurately <b>the root mean squares error of the model was just 48.83, and the R2 score was 0.97</b></p>
<h2>Conclusion</h2>
<p>In this project, I have created an LSTM based deep learning architecture that cable of telling Alphabets stock price for the upcoming next 60 days with an MSE of 48.83 and RMSE of 0.97.</p>
