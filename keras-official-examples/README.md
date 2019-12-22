# keras-official-examples

https://github.com/keras-team/keras/tree/master/examples

## Table of Contents

### Vision models examples

- mnist_mlp.py: Trains a simple deep multi-layer perceptron on the MNIST dataset.

- mnist_cnn.py Trains a simple convnet on the MNIST dataset.

- cifar10_cnn.py: Trains a simple deep CNN on the CIFAR10 small images dataset.

- conv_lstm.py: Demonstrates the use of a convolutional LSTM network.

- mnist_hierarchical_rnn.py: Trains a Hierarchical RNN (HRNN) to classify MNIST digits.

- mnist_transfer_cnn.py: Transfer learning toy example on the MNIST dataset.

- mnist_denoising_autoencoder.py: Trains a denoising autoencoder on the MNIST dataset.

### Text & sequences examples

- addition_rnn.py: Implementation of sequence to sequence learning for performing addition of two numbers (as strings).

- babi_rnn.py: Trains a two-branch recurrent network on the bAbI dataset for reading comprehension.

- babi_memnn.py: Trains a memory network on the bAbI dataset for reading comprehension.

- imdb_bidirectional_lstm.py: Trains a Bidirectional LSTM on the IMDB sentiment classification task.

- imdb_cnn.py: Demonstrates the use of Convolution1D for text classification.

- imdb_cnn_lstm.py: Trains a convolutional stack followed by a recurrent stack network on the IMDB sentiment classification task.

- imdb_fasttext.py: Trains a FastText model on the IMDB sentiment classification task.

- imdb_lstm.py: Trains an LSTM model on the IMDB sentiment classification task.

- lstm_stateful.py: Demonstrates how to use stateful RNNs to model long sequences efficiently.

- lstm_seq2seq.py: Trains a basic character-level sequence-to-sequence model.

- lstm_seq2seq_restore.py: Restores a character-level sequence to sequence model from disk (saved by lstm_seq2seq.py) and uses it to generate predictions.

- pretrained_word_embeddings.py: Loads pre-trained word embeddings (GloVe embeddings) into a frozen Keras Embedding layer, and uses it to train a text classification model on the 20 Newsgroup dataset.

- reuters_mlp.py: Trains and evaluate a simple MLP on the Reuters newswire topic classification task.

- cnn_seq2seq.py: Sequence-to-sequence example in Keras (character-level).

### Generative models examples

- lstm_text_generation.py: Generates text from Nietzsche's writings.

- conv_filter_visualization.py: Visualization of the filters of VGG16, via gradient ascent in input space.

- variational_autoencoder.py: Demonstrates how to build a variational autoencoder.

- variational_autoencoder_deconv.py: Demonstrates how to build a variational autoencoder with Keras using deconvolution layers.

- class_activation_maps.py

### Examples demonstrating specific Keras functionality

- antirectifier.py Demonstrates how to write custom layers for Keras.

- mnist_sklearn_wrapper.py: Demonstrates how to use the sklearn wrapper.

- mnist_irnn.py: Reproduction of the IRNN experiment with pixel-by-pixel sequential MNIST in "A Simple Way to Initialize Recurrent Networks of Rectified Linear Units" by Le et al.

- reuters_mlp_relu_vs_selu.py: Compares self-normalizing MLPs with regular MLPs.
