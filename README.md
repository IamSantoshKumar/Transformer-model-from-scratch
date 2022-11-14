# Transformer-model-from-scratch

A Transformer is a model architecture that eschews recurrence and instead relies entirely on an attention mechanism to draw global dependencies between input and output. Before Transformers, the dominant sequence transduction models were based on complex recurrent or convolutional neural networks that include an encoder and a decoder. The Transformer also employs an encoder and decoder, but removing recurrence in favor of attention mechanisms allows for significantly more parallelization than methods like RNNs and CNNs.

I have created this notebook to understand how things are working internally in transformer and its implementations. this is very basic implementation only(Encoder)


Paper: https://paperswithcode.com/method/transformer

![alt text](https://production-media.paperswithcode.com/methods/new_ModalNet-21.jpg)
