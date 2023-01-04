# Machine-Learning-Algorithm
This repository consists of the machine learning algorithm developing from scratch which are a part of the FIT5201 assignments (All of the code in jupyter notebooks is produce with R coding language).
These are all algorithms including the following:
1. KNN regression
2. KNN regression with k-fold cross-validation
3. Bootstrap with KNN regression
4. Ridge regression on SGD and BGD
5. Multicalss Perceptron
6. Bayasian Classifier vs Logistic Regression
7. Expectation-Maximization (EM) on document clustering
8. Neural Network vs Perceptron
9. Self-Taught Learning Encoder

Summary on the development of algorithms:
- KNN Regression: Using KNN to find the mean of the calculation of regression objective(loss) function of all the data point
- Ridge Regression with SGD and BGD: Using SGD and BGD algorithm on L2 (ridge) regression which is a regression with additional
term lambda*weight square to shrinkiage some unnecessary weight of some variables.
- Multiclass Perceptron: The perceptron which require a change in weight for each variable based on the number of correct prediction and incorrect prediction 
for multiple class target variables the weight will be add and update if the prediction is correct while the incorrect one will be decreased.
- Bayesian Classifier: Using Bayesian probability to find the maximum likelihood and predict the target classes
- Logistic Regression: Using the sigmoid function along with SGD to find the point where the loss is minimised.
- EM algorithm for document clustering: Identify an Expect value for the latent variable in the document and maximise the value to minimised the loss after making a document clustering
- Neural Network: Creating a feed-forward and back-progpagration of the regression
- Self-Taught Encoder: Identify a pattern which need for the classification task using the Encoder.
