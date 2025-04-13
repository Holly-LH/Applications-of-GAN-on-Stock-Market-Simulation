# Applications-of-GAN-on-Stock-Market-Simulation

In this project, we explore GAN’s potential in simulating and
predicting stock market time series data. We apply the GAN model with Gated Recurrent Unit
(GRU) as the generator, Convolutional Neural Network (CNN) as the discriminator to predict
future prices, and the GAN model with Temporal Convolutional Network (TCN) structures as
both the generator and the discriminator to simulate historical prices. Our study shows that
the GAN model has the ability to approximate the distribution of historical returns and the
potential to perform better than the moving average model in stock price prediction. Extensive
experiments show that the model trained on one stock can be used to predict the prices of other
stocks, even when the companies are in different businesses. Meanwhile, our study also shows
that the GAN model does not capture autocorrelations well when simulating stock prices and is
very unstable when making future predictions.
