# Deep Learning

---

### [LeCun et al. (2015)](https://doi.org/10.1038/nature14539)

##### Title: Deep learning

##### Authors: Yann LeCun, Yoshua Bengio & Geoffrey Hinton 

##### Abstract: 

* *Deep learning allows computational models that are composed of multiple processing layers to learn representations of data with multiple levels of abstraction.* 
* *These methods have dramatically improved the state-of-the-art in speech recognition, visual object recognition, object detection and many other domains such as drug discovery and genomics.* 
* *Deep learning discovers intricate structure in large data sets by using the backpropagation algorithm to indicate how a machine should change its internal parameters that are used to compute the representation in each layer from the representation in the previous layer.* 
* *Deep convolutional nets have brought about breakthroughs in processing images, video, speech and audio, whereas recurrent nets have shone light on sequential data such as text and speech.*

Honestly, I believe there is no better summary than the original abstract. The idea of multi-layer neural networks is not new. For a long period of time before 2012, neural-network-based methods weren't drawing much attention comparing to what the hype is now. The success of deep learning, I believe, has several key reasons: 1. huge well-labeled dataset; 2. enormous computing power; 3. better tools for implementation; 4. industry interests. Deep learning methods are undoubtedly and unreasonably out-performed any other methods in the areas of computer vision, natural language process and many others nowadays. This is now a positive feedback loop for accelerating related research. One of the top conference CVPR 2020 has been estimated to have over 10,000 submissions. I think there is a huge opportunity in using deep learning in biomedical data science. Having said that, there are pitfalls for deep learning methods. We haven't fully understood why this non-convex optimization driven approach can achieve such good generalization ability. And why deeper models often perform better? The theory of deep learning is largely incomplete. Initialization of network weights and hyperparameters can affect the performance of deep neural networks drastically. We should not be satisfied with the empirically good performance. And as the authors mentioned, there is still a long way to go with applying deep learning to unsupervised learning problems. 

---

### [Angermueller et al. (2016)](https://doi.org/10.15252/msb.20156651)

##### Title: Deep learning for computational biology

##### Authors: Christof Angermueller, Tanel Pärnamaa, Leopold Parts & Oliver Stegle

##### Abstract: 

*Technological advances in genomics and imaging have led to an explosion of molecular and cellular profiling data from large numbers of samples. This rapid increase in biological data dimension and acquisition rate is challenging conventional analysis strategies. Modern machine learning methods, such as deep learning, promise to leverage very large data sets for finding hidden structure within them, and for making accurate predictions. In this review, we discuss applications of this new breed of analysis approaches in regulatory genomics and cellular imaging. We provide background of what deep learning is, and the settings in which it can be successfully applied to derive biological insights. In addition to presenting specific applications and providing tips for practical use, we also highlight possible pitfalls and limitations to guide computational biologists when and how to make the most use of this new technology.*

I think this paper is really a good and comprehensive survey in applying deep learning to computational biology. It's more approachable and detailed with abundant references for the usage of deep learning methods. But the scope is narrowed in only treating deep learning a new tool. I think combining domain knowledge with deep learning can, in turn, catalyze the development of this method. 







 