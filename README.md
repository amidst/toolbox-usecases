# Use Cases of the AMIDST Toolbox.

This is a secondary repository to the [AMIDST toolbox repository](https://github.com/amidst/toolbox). 

This repository contains the code of relevant use-cases of the AMIDST Toolbox. These contributions do not add a specific functionality to the toolbox. They can be seen as examples of how this toolbox can be used. This category might include contributions related to student projects, research papers, industry applications, etc. 

The AMIDST core team will not supervise the quality of the contributions, this is responsibility of the contributors. They will be integrated as independent Maven modules. For futher information about how to contribute to AMIDST use the following [link](http://amidst.github.io/toolbox/ContributingToAMIDST.html).


Ath this moment in time it includes the code of the following scientific papers:

* Hanen Borchani et. **Modeling concept drift: A probabilistic graphical model based approach**. Proceedings of the Fourteenth International Symposium on Intelligent Data Analysis (IDA 2015). Saint-Etienne, France.

> **Abstract**: An often used approach for detecting and adapting to con- cept drift when doing classification is to treat the data as i.i.d. and use changes in classification accuracy as an indication of concept drift. In this paper, we take a different perspective and propose a framework, based on probabilistic graphical models, that explicitly represents concept drift using latent variables. To ensure efficient inference and learning, we re- sort to a variational Bayes inference scheme. As a proof of concept, we demonstrate and analyze the proposed framework using synthetic data sets as well as a real financial data set from a Spanish bank.

* Hanen Borchani et. **Dynamic Bayesian modeling for risk prediction in credit operations**. Proceedings of the 13th Scandinavian Conference on Artificial Intelligence (SCAI 2015). Halmstad, Sweden. 

> **Abstract**: In this paper we perform an exploratory analysis of a financial data set from a Spanish bank. 
Our goal is to do risk prediction in credit operations, and as data is collected continuously and reported on a monthly basis, this gives rise to a streaming data classification problem. Our analysis reveals some practical problems that have not previously been thoroughly analyzed in the context of streaming data analysis: the class labels are not immediately available and the relevant predictive features and entities under study (in this case the set of customers) may vary over time. In order to address these problems, we propose to use a dynamic classifier with a wrapper feature subset selection to find relevant features at different time steps. The proposed model is a special case of a more general framework that can also accommodate more expressive models  containing latent variables as well as more sophisticated feature selection schemes.

* Antonio Salmerón et al. **Parallel importance sampling in conditional linear Gaussian networks**. In Conferencia de la Asociación Española para la Inteligencia Artificial (CAEPIA 2015), volume in press, 2015.

> **Abstract**: In this paper we analyse the problem of probabilistic infer- ence in CLG networks when evidence comes in streams. In such situa- tions, fast and scalable algorithms, able to provide accurate responses in a short time are required. We consider the instantiation of variational inference and importance sampling, two well known tools for probabilis- tic inference, to the CLG case. The experimental results over synthetic networks show how a parallel version importance sampling, and more precisely evidence weighting, is a promising scheme, as it is accurate and scales up with respect to available computing resources.
