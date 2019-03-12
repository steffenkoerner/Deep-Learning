## Welcome to Deep Learning

### Interesting Literature
- [Hackers Guide to Neural Networks](http://karpathy.github.io/neuralnets/)
- [Online Book Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/index.html)
- [Deep Learning Papers Reading Roadmap](https://github.com/floodsung/Deep-Learning-Papers-Reading-Roadmap)
- [Google Crash Course](https://developers.google.com/machine-learning/crash-course/fitter/graph)
- [Neural Network Playground](http://playground.tensorflow.org/#activation=tanh&batchSize=10&dataset=circle&regDataset=reg-plane&learningRate=0.03&regularizationRate=0&noise=0&networkShape=4,2&seed=0.30786&showTestData=false&discretize=false&percTrainData=50&x=true&y=true&xTimesY=false&xSquared=false&ySquared=false&cosX=false&sinX=false&cosY=false&sinY=false&collectStats=false&problem=classification&initZero=false&hideText=false)
- [Rules of Machine Learning](https://developers.google.com/machine-learning/guides/rules-of-ml/)
- [Free Udacity Course Deep Learning](https://eu.udacity.com/course/deep-learning--ud730?utm_medium=referral&utm_campaign=api)
- [Summary Backpropagation](https://google-developers.appspot.com/machine-learning/crash-course/backprop-scroll/)
- [Backpropagation intuitve](http://colah.github.io/posts/2015-08-Backprop/)
- [Backpropagation in detail](http://neuralnetworksanddeeplearning.com/chap2.html)
- [Github code for applying style to images](https://github.com/lengstrom/fast-style-transfer)


### Competitions
- [kaggle](https://www.kaggle.com/)






## Tensorflow

### Things to know
- **Computational Graph:** <br>
This graph consists of nodes which are specifing TensorFlow operations. The backend of TensorFlow is based on highly efficient C++ Code. Instead of sending each single operation to the backend, which includes overhead for switching back to python. The computational graph is send to the backend.

- **Session:**  <br> 
The connection to the backend is called session

- **Placeholder:**  <br>
A placeholder is a value that is guaranteed to be inputted if the program is run. For example the input is inserted into the placeholder values

- **Variable:**  <br>
It is a value that is within the computational graph. It can be used and even modified by the computation. In general the model parameter are variables. Before a variable can be used within a session it has to be initialized. This can be done for all variables at once. `sess.run(tf.global_variables_initializer())`


