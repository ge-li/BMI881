# Two Cultures

### [Breiman (2001)](https://doi.org/10.1214/ss/1009213726)

##### Title: Statistical Modeling: The Two Cultures

##### Author: Leo Breiman

In this paper, the author discussed the two cultures of statistical modeling, *i.e.*, data modeling culture and algorithmic modeling culture. The data modeling culture starts with assuming a stochastic data model for the inside of the black box, then evaluate the models using goodness-of-fit tests and residual examination. Whereas the algorithmic model considers the data generating process complex and unknown. With fewer concerns and assumptions on the data generating process, it thrives to algorithmically fit the predictor x to response y, and use predictive accuracy for model evaluation. At the time the paper was written, the data modeling culture was the majority. The author then used examples to contrast these two cultures, showed many weaknesses of data modeling while highlighting the power of algorithmic modeling. The author urged that we need to move away from exclusive dependence on data models and adopt a more diverse set of tools.

My comments:

* We've already seen this shifting of paradigm for after around two decades from the paper been published. In many problems containing a huge amount of data, and the main objective is to predict, the algorithmic modeling culture thrives. 
* I do think sometimes in statistics research, people tend to exhaustively develop methods. Joke: statisticians are model-fitting monkeys. Neural nets or AutoML are auto-model fitting monkeys, cheaper and better.
* I think modern data science emphasize both in accuracy and interpretability. People are now trying hard to understand why deep neural nets work so well.
* Some problems contain large random effects. Definitive problems vs ambiguity. The best way to evaluate different models is to see how much interpretable variance it can "explain". An example of the interpretable variance would be heritability in the population genetics setting. But again, you can't eliminate such large random effects in many cases. The author focus on trashing data models a lot. However, with large random effects, how can random forest give a plausible confidence interval of their prediction? (resampling maybe)
* I think the best practice is to use proper models for different problems. There is no all-purpose model. One clear example is that we don't want to use algorithmic models in Randomized Control Trials, where the effect of a treatment, is significant or not, can be well-addressed by regression models. We don't need fancy machine learning models to answer the question.
* A lot of the examples in the paper where data model (regression) fails, comes from the analysis of observational data. The sex discrimination case could be an example of Simpson's Paradox. Also in the Bupa liver data, the random forest model identified two clusters within class 2, which indicates there might be unidentified confounding factors in vanilla regression models.