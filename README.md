# char-rnn-tf
Implementation of Vanilla **RNN for Character Level** prediction using TensorFlow from scratch.

The Character Level RNN uses as input both the current input and the output of the previous hidden layer to predict 
the next character in sequence. The outline of the implementation is broadly divided into the following categories

**Import required models**\
**Preparation of I/O data**
**Defining One-Hot encoding function**
**Defining Hyperparameters**
**Creating Tensor Placeholders**
**Initializing weights and biases**
**Specifying Activations, Output and Loss function**
**Specifying Optimizer**
**Gradient Clipping**
**Gradient Update**
**Session and run**
**Preparing inputs to RNN and Sampling**

**Result**
The output after every 500 iterations is set to be sampled.
As the iterations increase, the models gradually learns to learn the relations between characters,
position of white spaces grammar,syntax of sentences.
