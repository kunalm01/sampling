Comparing Sampling Techniques for 5 Machine Learning Models

Introduction
This project explores the effectiveness of different sampling techniques for creating a balanced dataset for a machine learning model. The dataset used is initially unbalanced, so random over-sampling and under-sampling techniques are used to create a balanced dataset. Five different sampling techniques are then applied to this balanced dataset, and the accuracies of the resulting samples are compared using five different machine learning models.

Sampling Techniques
The following five sampling techniques were used in this project:

Random Over Sampling: A basic sampling technique where each data point in the dataset has an equal probability of being selected in the sample.

Smote Sampling: SMOTE is an oversampling technique that generates synthetic samples from the minority class. It is used to obtain a synthetically class-balanced or nearly class-balanced training set, which is then used to train the classifier.

Adasyn Sampling: ADASYN is based on the idea of adaptively generating minority data samples according to their distributions: more synthetic data is generated for minority class samples that are harder to learn compared to those minority samples that are easier to learn.

Random Under Sampling: Class to perform random under-sampling. Under-sample the majority class(es) by randomly picking samples with or without replacement.

Tomek Links Sampling: The procedure for finding Tomek Links can be used to locate all cross-class nearest neighbors. If the examples in the minority class are held constant, the procedure can be used to find all of those examples in the majority class that are closest to the minority class, then removed.

Conclusion
It is recommended to use Tomek Links for this dataset, as it consistently gives the best performance across all models. However, other sampling techniques may be worth considering for different datasets or models.
