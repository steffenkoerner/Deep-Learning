## Welcome to Deep Learning

### Interesting Literature
- [Hackers Guide to Neural Networks](http://karpathy.github.io/neuralnets/)
- [Online Book Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/index.html)
- [Deep Learning Papers Reading Roadmap](https://github.com/floodsung/Deep-Learning-Papers-Reading-Roadmap)
- [Google Crash Course](https://developers.google.com/machine-learning/crash-course/fitter/graph)
- [Neural Network Playground](http://playground.tensorflow.org/#activation=tanh&batchSize=10&dataset=circle&regDataset=reg-plane&learningRate=0.03&regularizationRate=0&noise=0&networkShape=4,2&seed=0.30786&showTestData=false&discretize=false&percTrainData=50&x=true&y=true&xTimesY=false&xSquared=false&ySquared=false&cosX=false&sinX=false&cosY=false&sinY=false&collectStats=false&problem=classification&initZero=false&hideText=false)
- [Rules of Machine Learning](https://developers.google.com/machine-learning/guides/rules-of-ml/)
- [Free Udacity Course Deep Learning](https://eu.udacity.com/course/deep-learning--ud730?utm_medium=referral&utm_campaign=api)
- [Github code for applying style to images](https://github.com/lengstrom/fast-style-transfer)

#### Backpropagation
- [Summary Backpropagation](https://google-developers.appspot.com/machine-learning/crash-course/backprop-scroll/)
- [Backpropagation intuitve](http://colah.github.io/posts/2015-08-Backprop/)
- [Backpropagation in detail](http://neuralnetworksanddeeplearning.com/chap2.html)
- [Karpathy - Yes, you should understand backpropagation](https://medium.com/@karpathy/yes-you-should-understand-backprop-e2f06eab496b)
- [CS231n Winter 2016 Lecture 4 Backpropagation](https://www.youtube.com/watch?v=59Hbtz7XgjM)


### Competitions
- [kaggle](https://www.kaggle.com/)

### Games
- [Flappy Bird(Github)](https://github.com/yenchenlin/DeepLearningFlappyBird)

### Machine Learning Projects
- [30 Amazing Machine Learning Projects](https://medium.mybridge.co/30-amazing-machine-learning-projects-for-the-past-year-v-2018-b853b8621ac7)
### Interview Machine Learning
- [What I am learned from AI interviews](https://blog.usejournal.com/what-i-learned-from-interviewing-at-multiple-ai-companies-and-start-ups-a9620415e4cc)


### Other Links
- [10 Operating System Concepts to know](https://medium.com/cracking-the-data-science-interview/the-10-operating-system-concepts-software-developers-need-to-remember-480d0734d710)

### Concept a ML Engineer must know
* Supervised Learning
* Unsupervised Learning
* Reinforcement Learning
* Backpropagation
* Gradient Decent, Stochastic Gradient Descent
  * Local Minima
  * Momentum
* Neural Network, CNN, RNN
* Regularization (L1, L2, Dropout)

* Vanishing Gradient
* Activation Function (Sigmoid, Relu,...)
* Learning Rate


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


