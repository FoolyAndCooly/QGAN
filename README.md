# QGAN for generating continuous distribution
This implementation is based on this article:

[Jonathan Romero and Alan Aspuru-Guzik. Variational quantum generators: Generative adversarial quantum machine learning for continuous distributions, 2019.](https://arxiv.org/abs/1901.00848)

The most important step is to encode classical information as the parameters of a variational quantum circuit, thus encoding it into a quantum state.

There is the circuit:

 <img src="https://github.com/FoolyAndCooly/QGAN/blob/main/readme/circuit.png" width = "400" height = "200" alt="图片名称" align=center />

This is the loss function of the generator and discriminator during my training process, as well as the KL divergence.

<img src="https://github.com/FoolyAndCooly/QGAN/blob/main/readme/train.png" width = "400" height = "300" alt="图片名称" align=center />

And this is the result:

 <img src="https://github.com/FoolyAndCooly/QGAN/blob/main/readme/res.png" width = "500" height = "200" alt="图片名称" align=center />

As you can see, it's not quite perfect and it may requires more training data and computational power support.
