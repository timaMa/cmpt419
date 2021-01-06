# CMPT419-Project-by-Triple-A <img src="https://github.com/infinitusposs/CMPT419-Project-by-Triple-A/blob/master/LOGO.jpg" width="64">

## Poster
![image](https://github.com/infinitusposs/CMPT419-Project-by-Triple-A/blob/master/Poster/Triple%20A%20poster.jpg)

## Introduction
In recent years, deep learning has developed rapidly. More and more researchers
have applied deep learning to different fields, like data analysis, predictions. In
terms of predictions, many neural networks, which are an important part of deep
learning, have been used in predicting stock price. In this project, we will focus
on predicting the revenue of companies. We test and compare the performances
of Recurrent Neural Network (RNN) and Multilayer Perceptron (MLP) and try to
figure out a better neural network for predicting the revenue of companies. The
result indicates that MLP is a better neural network for making predictions on the
revenue of companies in the next quarter.

## Multi-layer Perceptron
![image](https://github.com/infinitusposs/CMPT419-Project-by-Triple-A/blob/master/Neural%20network%20models/MLP.jpg)

## Recurrent Neural Network
![image](https://github.com/infinitusposs/CMPT419-Project-by-Triple-A/blob/master/Neural%20network%20models/RNN.png)

## Dataset 
[Apple Financial Report.csv](https://github.com/infinitusposs/CMPT419-Project-by-Triple-A/blob/master/Dataset/Apple%20Financial%20Report.csv)

## Result
### MLP
![image](https://github.com/infinitusposs/CMPT419-Project-by-Triple-A/blob/master/Result/MLP.png)
### RNN
![image](https://github.com/infinitusposs/CMPT419-Project-by-Triple-A/blob/master/Result/RNN.png)

## Conclusion
RNN performs better on stock market prediction because the price highly depends on the previous
days. However, regarding the revenue of companies, the revenue highly depends on the decision
they make in the quarter. This is also because we changed the dataset so that whether new products
come out has been directly connected to the revenue of the corresponding quarter.
In conclusion, Multilayer Perceptron neural network is a better choice for forecasting companies’
profits.

## Future work
So far, many neural networks have been used in stock price prediction, such as Long Short-Term
Memory (LSTM) and Convolutional Neural Network (CNN). And for predicting stock prices, CNN
is the best choice and both LSTM and RNN have better performances than MLP since stock prices
heavily depend on the price of the previous days.
For the future work, we are going to test the performances of more neural networks like LSTM.
Since LSTM is a special type RNN, we expect that LSTM will have a similar performance as RNN.
Also, CNN is another choice for this project. We assume CNN will have the best performance on
market profit forecasting since it did well in stock forecasting and it does not depend on the previous
data.

## References
[1] Najafabadi, M. M., Villanustre, F., Khoshgoftaar, T. M., Seliya, N., Wald, R., & Muharemagic, E. (2015).
Deep learning applications and challenges in big data analytics. Journal of Big Data, 2(1), 1. <br />
[2] Vaisla, K. S., & Bhatt, A. K. (2010). An analysis of the performance of artificial neural network technique
for stock market forecasting. International Journal on Computer Science and Engineering, 2(6), 2104-2109. <br />
[3] Hiransha, M., Gopalakrishnan, E. A., Menon, V. K., & Soman, K. P. (2018). NSE stock market prediction
using deep-learning models. Procedia computer science, 132, 1351-1362.
