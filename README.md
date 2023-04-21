# A neuro-fuzzy approach for classifier selection in credit scoring

Credit risk is a part of financial risk and its assessment is the most important decision for financial institute prosperity, so in literature plenty of credit scoring theories were introduced. A cooperative Neuro-Fuzzy model is proposed for clients’ classification between solvents and insolvents. In a phase, an Artificial Neural Network (ANN) produces evaluation metric scores for 3 ANN topologies (1, 2, 3 Hidden Layer ANN) using 4 tuning hyperparameter techniques, and in a parallel phase evaluation metrics hierarchy are derived from expert’s view via Fuzzy AHP model. Combining two phases, a Technique for Order Preference by Similarity to Ideal Solution (TOPSIS) model provides the optimal neural network topology. The proposed method innovation lies on intervention of financial expert’s aspect and institute’s policy in a data-driven model without output reasoning, with an upper aim to manipulate the tremendous force of Neural Networks. In this paper, suggested model was applied on 3 datasets and its results were discussed in order to reveal its utility. The conclusion lies on the fact that human opinion through Fuzzy AHP, is crucial when ANN models generate similar performance metric outputs and generally, it could be used as a validation manner on decisions based on ANN outputs.

### Methodology

	The first phase represents an initial approach of creation three artificial neural networks with different topologies (1, 2 and 3 Layers). Specifically, for a start, dataset should be cleaned and prepared for algorithms application. As duplicate rows and columns as constant and quasi constant variables are removed, missing values and outliers are detected and handled, target variable transformed to has a balance quantity and categorical variables are encoded. In the second stage, for each of three models, four tuning techniques are applied and model which dominates in more evaluation metrics is chosen as the best. In the end, the output of this phase and input for the next one is a table with models’ performance metrics for three neural networks models.

	In the second phase is introduced human aspect through expert’s knowledge. A Fuzzy Analytic Hierarchy Process (FAHP) Is applied and takes into account preferences of four different experts with diverse ranking significance of evaluation metrics for model selection. As a result, normalized non-fuzzy scores of each metric are produced and it would be used as inputs in the next phase.  

	Finally, both performance metrics of three neural networks and weights of FAHP, are inputs in a selection model using Technique for Order of Preference by Similarity to Ideal Solution (TOPSIS). As the output of the above descripted process is the selection of the most robust model base on expert view for credit risk assessment.



![image](https://user-images.githubusercontent.com/65331575/233630334-a6b85aee-5f21-4e51-809c-4f94c83f3a3a.png)
