# feature_selection
Introduction:
Feature selection is the process of selecting the features in the data which are most useful to the problem you are working on. For example, when training a classification or regression model, not all the features within the data may be useful or relevant to making a prediction. This can negatively impact the model in several ways:
•
Including features which aren’t relevant introduces more ‘noise’ into the data which can ultimately make it less accurate than a model trained on fewer features.
•
Having a high number of features (particularly if the number of instances in your training data is low) increases the risk of overfitting – this is known as the ‘curse of dimensionality’.
•
Also in a real-world setting, collecting the data itself may take time and effort. Identifying which features are relevant and only including those in the model could therefore make it easier and cheaper to collect the data needed to use the model.
•
Including more features increases the training time.
Some models are more sensitive than others. For example, K-Nearest Neighbours and Neural Networks can be very sensitive to irrelevant features, while logistic regression is sensitive to features which are highly correlated.
There are three main approaches to feature selection:
•
Filter methods use a statistical measure to rank the features contained within the data. Features not meeting a pre-set threshold can then be eliminated. Alternatively, the best K features can be selected.
MLDM Week 7 Workshop: Feature Selection & Class Imbalance
•
Wrapper methods treat feature selection as a search problem and use a model to evaluate the highest performing combination of features.
•
Embedded methods learn which features contribute most to the model accuracy as part of the model training process itself. In other words, embedded methods don’t require a separate feature selection step because this is performed as an integral part of the model training.
