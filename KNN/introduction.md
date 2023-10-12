# Introduction


The classification framework involves a two-step process: 

1) an inductive step for constructing a classification model from data
2) a deductive step for applying the model to test examples. 

Decision tree and rule-based classifiers are examples of eager 
learners because they are designed to learn a model that maps the input attributes 
to the class label as soon as the training data becomes available. 
An opposite strategy would be to delay the process of modeling the training data
until it is needed to classify the test instances. 
Techniques that employ this strategy are known as lazy learners. 

An example of a lazy learner is the **Rote classifier**, which memorizes 
the entire training data and performs classification only if the attributes 
of a test instance match one of the training examples exactly. An obvious 
drawback of this approach is that some test instances may not be classified 
because they do not match any training example.