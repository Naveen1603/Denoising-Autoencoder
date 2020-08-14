# Denoising Autoencoder

An autoencoder is a type of artificial neural network used to learn efficient data codings in an unsupervised manner. The aim of an autoencoder is to learn a representation (encoding) for a set of data, typically for dimensionality reduction, by training the network to ignore signal “noise”.

Denoising autoencoder is a stochastic extension to classic autoencoder , that is we force the model to learn reconstruction of input given its noisy version. A stochastic corruption process randomly sets some of the inputs to zero, forcing denoising autoencoder to predict missing(corrupted) values for randomly selected subsets of missing patterns.

![Denoising Autoencoder](Pics/autoencoder.png  "Denoising Autoencoder")

### Input and Output image samples


![Pic1](Pics/pic1.PNG "pic1")


![Pic2](Pics/pic2.PNG "pic2")


![Pic3](Pics/pic4.PNG "pic3")


![Pic4](Pics/pic3.PNG "pic4")


![Pic5](Pics/pic5.PNG "pic5")

![Pic6](Pics/pic6.PNG "Pic6")
