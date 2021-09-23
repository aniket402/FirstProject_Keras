# Exploring keras

Keras make a lot of things easier to us than tensorflow. In tensorflow, a lot of code was supposed to be written by us. We had to initialise the weights, write the forward and backward propagation code, then specify the cost function, create the optimiser, call minimize on it and then basically run a loop with specific batch size and call optimize multiple times. Keras basically simplifies the code and we are saved from writing a lot of redundant code. 

Keras requires a backend framework like tensorflow to run. So, we can say that keras is basically a layer over tf.

## Flow of code in keras

1. Create Model - We have used keras sequential model.
2. Add layers and define the architecture.
4. Compile
5. Fit
6. Evaluate 

      |Layer (type)|Units #|Activation function|
      |---|---|---|
      |dense_1(input)|30|--|
      |dense_2(hidden)|32|relu|
      |dense_3(hidden)|16|relu|
      |dense_4(output)|1|sigmoid|

## Result

### Loss/Accuracy vs Epoch

