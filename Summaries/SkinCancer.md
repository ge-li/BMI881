# Skin Cancer

### [Wang et al. (2019)](https://doi.org/10.1001/jamadermatol.2019.2335)

##### Title: Assessment of Deep Learning Using Nonimaging Information and Sequential Medical Records to Develop a Prediction Model for Nonmelanoma Skin Cancer

##### Authors: Wang et al. 

In this paper, the authors built a deep learning-based model using nonimaging information and sequential medical records to develop a prediction model for nonmelanoma skin cancer. A total of 1829 patients with nonmelanoma skin cancer as their first diagnosed cancer and 7665 random controls without cancer were included in the analysis. They fed EMRs as image-like matrices into a customed build CNN as input and trained the model using 5-fold cross-validation, achieving an AUROC of 0.894 (SD = 0.007).  By further adapting a stepwise elimination procedure, they were able to identify and order important features contributing to the prediction of the disease using this model.

I do believe this paper has its merits. The authors are creative to build a deep learning model on EMR data for predicting skin cancers. I know it's where the hypes are now. I don't think there are major flaws in their design. But I've also anticipated the intermediate performance of deep learning models compared to what deep learning has achieved in computer vision and natural language processing tasks. I conjecture that the predictive power from the EMR data is limited to some extent. It's an easy-to-read paper. It provided some insights on what are the important risk factors for skin cancer. But methodologically, it is quite conventional.