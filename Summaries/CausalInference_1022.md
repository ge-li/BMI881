# Causal Inference

### [Pearl (2009)](http://doi.org/10.1214/09-SS057)

##### Title: Causal Inference in Statistics: An Overview

##### Author: Judea Pearl

In this paper, the author provided an overview of Causal Inference using Structural Causal Model (SCM). 

I agree with many parts of the paper, but I get lost starting from Section 3. For example, what's the "graphical rules" for writing down the covariance of any pair of observed variables in terms of path coefficients and covariances among the error terms? Why is it $Cov(X, Y) = \beta + Cov(U_Y, U_X) [eq. 4]$? Why not $\beta^2$? 

One concept shows repeatedly, the "golden rule": behind any causal conclusions there must be some causal assumption, untested in observational studies; "causal assumptions, in contrast, cannot be verified even in principle, unless one resorts to experimental control", which is the first mental barriers Pearl mentioned in Section 2.4. I'm pretty sure that I don't understand it. 

Things only start to make more sense when the first expression appears $Y_x(u)$. However, this paper is no way near a paper on mathematical causal inference. I'd really hope it's something like the Graduate Texts in Mathematics series, but it's not. Of course, another explanation is that due to my dumbness and time limitation I can't "get used to" the new notation and models introduced.  

With that being said, I absolutely agree with the first paragraph in Section 3. The new "theory" on causal inference must meet the 4 requirements. And I definitely want to be educated by such theory. But I think more work needs to be done in terms of presenting it in a more intuitive, concise, and rigorous way. 