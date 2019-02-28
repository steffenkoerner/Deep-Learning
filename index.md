## Welcome to Deep Learning

### Interesting Literature
- [Hackers Guide to Neural Networks](http://karpathy.github.io/neuralnets/)
- [Online Book Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/index.html)
- [Deep Learning Papers Reading Roadmap](https://github.com/floodsung/Deep-Learning-Papers-Reading-Roadmap)
- [Google Crash Course](https://developers.google.com/machine-learning/crash-course/fitter/graph)
- [Neural Network Playground](http://playground.tensorflow.org/#activation=tanh&batchSize=10&dataset=circle&regDataset=reg-plane&learningRate=0.03&regularizationRate=0&noise=0&networkShape=4,2&seed=0.30786&showTestData=false&discretize=false&percTrainData=50&x=true&y=true&xTimesY=false&xSquared=false&ySquared=false&cosX=false&sinX=false&cosY=false&sinY=false&collectStats=false&problem=classification&initZero=false&hideText=false)
- [Rules of Machine Learning](https://developers.google.com/machine-learning/guides/rules-of-ml/)







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









You can use the [editor on GitHub](https://github.com/steffenkoerner/Deep-Learning/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/steffenkoerner/Deep-Learning/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
