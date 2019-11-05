# Boosting and Bagging

### [Buhlmann & Hothorn (2007)](https://doi.org/10.1214/07-STS242)

##### Title: Boosting Algorithms: Regularization, Prediction and Model Fitting

##### Authors: Peter Bühlmann & Torsten Hothorn

In this paper, the authors present an in-depth survey on the boosting method along with a dedicated R package **mboost**. Boosting is an ensemble method for improving the predictive performance of a base procedure that produces a function estimate, e.g., decision trees. This is done by iteratively reweight the data based on the prediction error. For a higher-level view, the boosting method can be really regarded as a special case of functional gradient descent (FGD), where we try to estimate a real-valued function that minimizes some kind of loss function. Different combinations of the loss function and base procedures can result in different boosting algorithms. Boosting method also has a wide range of applications such as variable selection and survival analysis. The authors also demonstrate these applications using the **mboost** package.

I think this paper is a very comprehensive statistical review of the boosting method. In fact, I prefer the functional gradient descent (FGD) term over boosting, because FGD exactly describes what "boosting" is really trying to do, and gives a unified view of a bracket of such methods. And for any problem involves optimization, gradient descent is such an important and almost always applicable idea. I like the formality and rigourousness in this paper, although I can't absorb them all nor do I have the intention to. Because I think the intuition behind boosting, even the implementation is quite straight forward. I will definitely refer to this paper if I encounter related research problems that can use this type of method.