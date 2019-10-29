# OHDSI

### [Madigan et al. (2013)](https://doi.org/10.1093/aje/kwt010)

##### Title: Evaluating the Impact of Database Heterogeneity on Observational Study Results

##### Author: Madigan et al.

Clinical studies that use observational databases (e.g. administrative claims data or electronic health records) to evaluate the effects of medical products have become commonplace. In this paper, the authors systematically studied heterogeneity among databases, holding other study methods constant, by exploring relative risk estimates for 53 drug-outcome pairs and 2 widely used study designs across 10 observational databases. Their findings showed that clinical studies that use observational databases can be sensitive to the choice of database. In fact, studies of the same drug effect could yield conflicting results ranging from statistically significant decreased risk to statistically significant increased risk.

I'm not surprised by the results. First of all, observational studies inherently suffer from many different potential biases and sources of variability ([Sources of Variation](https://www.healthknowledge.org.uk/public-health-textbook/research-methods/1a-epidemiology/sources-variation-measurement-control)). Methods like propensity score can be used to adjust for that only to some extent. For example, I think even if one uses the propensity score to help estimate the treatment effect, such an estimated effect only applies to the specific population. Here, such homogeneity doesn't exist among those databases. Secondly, this paper uses multiple testing although the results definitly cannot be solely explained by multiple testing. 53 * 2 * 10 ≈ 1000, given a 0.05 p-value threshold, it is still expected to have 50 false significant cases. With that being said, I totally agree with the authors that we should be extremely cautious when dealing with observational data, and more attention is needed to consider how the choice of data source may be affecting results. For giving any serious conclusions, Randomized Controlled Trials (RCT) is still the way to go. On the other hand, more studies are needed for observational data.

  