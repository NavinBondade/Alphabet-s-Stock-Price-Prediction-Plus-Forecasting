# Forecasting of Alphabet's Stock Prices Using Long Short-Term Memory (LSTM) Networks
<p align="center">
<a href="https://nbviewer.jupyter.org/github/NavinBondade/Forecasting-The-Alphabets-Stock-Price-For-Next-Upcoming-60-Days/blob/main/Alphabet%27s%20Stock%20Price%20%20Prediction%20Plus%20Forecasting/NoteBook/Alphabet%27s_Stock_Price_Prediction_With_LSTM_.ipynb" target="_blank">
  <img align="center"  src="https://github.com/NavinBondade/Distinguishing-Fake-And-Real-News-With-Deep-Learning/blob/main/Graphs/button_if-github-fails-to-load-the-notebook-click-here%20(4).png?raw=true"/>
</a>
</p>
<img src="https://cdn.business2community.com/wp-content/uploads/2015/08/alphabet-logo-970-80-150x150.jpg.jpg" alt="Alphabet" width="900" height="500">
<p>Alphabet Inc., established in 2015 through a restructuring of Google, is now the parent company of Google and several former subsidiaries. As a global leader in the tech industry, Alphabet has reached significant milestones, including becoming the fourth U.S. company to surpass a $1 trillion market value in 2020. Traded on NASDAQ under the ticker symbol "GOOG," Alphabet continues to be one of the most profitable companies, offering substantial returns for investors.

To tackle the challenge of predicting Alphabet’s stock prices, I developed a deep learning model trained on historical stock data. Using advanced techniques like Recurrent Neural Networks (RNN) with Long Short-Term Memory (LSTM) units, the model excels in forecasting, offering a 60-day prediction with an impressive R2 score of 0.97. This accuracy helps investors gain valuable insights into market trends, enabling them to make more informed and strategic investment decisions.
</p>
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
<p>At the core of this model lies a sophisticated architecture built upon three Long Short-Term Memory (LSTM) layers, which have proven highly effective in capturing and learning long-term dependencies, particularly suited for stock price prediction and forecasting. LSTM’s ability to retain information over extended sequences makes it an ideal choice for financial time-series data, where patterns and trends unfold gradually over time. The LSTM layers are followed by three fully connected (dense) layers, which are responsible for decision-making tasks, translating the learned patterns into precise predictions.

The model was trained over 40 epochs, ensuring thorough learning of the stock price data. To optimize the model’s performance, the Adam optimizer was employed, known for its efficiency in handling sparse gradients and adapting learning rates. The mean squared error (MSE) function was used as the loss function, as it effectively measures prediction accuracy by penalizing larger errors more heavily. The training process used a batch size of 30, balancing computational efficiency and gradient stability. The dataset utilized for training was sourced from finance.yahoo.com, providing a comprehensive and reliable collection of Alphabet’s historical stock data, essential for building an accurate and robust predictive model.</p>
<h2>Model Training</h2>
<img src="https://github.com/NavinBondade/Alphabet-s-Stock-Price-Prediction-Plus-Forecasting/blob/main/Alphabet's%20Stock%20Price%20%20Prediction%20Plus%20Forecasting/Graphs/loss.png" width="450" height="300">
<p>After training, the model demonstrated remarkable convergence, as evident in the loss graph. The plot shows a sharp decline in the loss during the initial epochs, followed by a steady decrease as the model continues to learn, eventually reaching a minimal loss value of 0.0012. This low loss indicates the model's high level of accuracy in its predictions, with the mean squared error (MSE) consistently reducing as the model refines its ability to predict Alphabet’s stock prices.

The early rapid decrease in loss highlights how effectively the model learned from the data during the initial stages of training, while the subsequent flattening of the curve demonstrates that the model has achieved stability and is no longer overfitting or underfitting. The final result of a 0.0012 loss reinforces the model's robustness and reliability in stock price forecasting, providing investors with highly precise predictions for future market trends.</p>
<h2>Model Prediction</h2>
<img src="https://github.com/NavinBondade/Alphabet-s-Stock-Price-Prediction-Plus-Forecasting/blob/main/Alphabet's%20Stock%20Price%20%20Prediction%20Plus%20Forecasting/Graphs/Alphabet's%20Stock%20Price%20(Open)%20Prediction.png" alt="tomato" width="800" height="400">
<p>The model’s performance is illustrated in the graph, which compares the original stock figures with the predicted stock figures. As seen, the predicted values closely follow the actual stock price trends, demonstrating the model’s high accuracy. The minimal deviation between the two lines reflects the model’s capability in capturing the underlying patterns of Alphabet’s stock price movements.

Quantitatively, the model achieved an exceptional Root Mean Squared Error (RMSE) of 48.83, which indicates a small error margin between the predicted and actual stock prices. Additionally, the model’s R² score of 0.97 underscores its high predictive accuracy, explaining 97% of the variance in the stock price data. This performance highlights the model’s reliability and effectiveness in forecasting stock prices, offering investors precise insights into future market behaviors.</b></p>
<h2>Conclusion</h2>
<p>In this project, I have created an LSTM-based deep learning architecture that cable of telling Alphabets stock price for the upcoming next 60 days with an MSE of 48.83 and RMSE of 0.97.</p>
