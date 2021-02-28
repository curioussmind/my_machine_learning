## Generalization, Overfitting and Underfitting
Our goal in supervised learning is to build model on the training data so that we can make accurate predictions on unseen data; our model is able to generalize from the training set to the test set. In general, we want to build a model that is able to generalize as well as possible. 
Our model is good if the training and test set have enough in common. 

### Overfitting and Underfitting
When we build a complex model that does well on the training set but does not generalize to new data. So how can we avoid overfitting? by restrict ourselves to building a very simple model. But if we use a very simple model another issue arise. Too simple model does not capture the variation in our training set very well and it is called ***underfitting***