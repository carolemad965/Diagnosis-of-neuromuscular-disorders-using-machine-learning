# Diagnosis-of-neuromuscular-disorders-using-machine-learning
# What is Neuromuscular Disorders?
1-Neuromuscular disorders (NMD) NMDs are genetic inherited diseases.
2-NMDs are mostly caused by mutations.
3-Early diagnosis is essential for gene therapy to help patients live a normal life
4-Traditional physiotherapy tests can only indicate the presence of a problem
5-Genetic testing is how we can specify the type of NMD That's why NMD is more of a bioinformatics problem.
# Problem
1-NMD patients in Egypt suffer from the lack of interest in the terms of treatment, scientific research and awareness of the diseases.
2-When someone is diagnosed with one of these disorders,they usually get their treatment abroad with very high prices (may reach millions of dollars).This happens due to the unavailability of the treatment in Egypt.

3-According to the statistics of the World Health
Organization, the prevalence rate of muscular
dystrophy is one in every 3 thousand people.
4-This means that Egypt has between 700 thousand to
one million cases of this dreaded disease.
The spread of Consanguineous marriage, whether in
the Delta governorates, or in Upper Egypt, results in
these high rates.
# Our Solution
1-As bioinformaticans , our contribution lies in using our skills in data analysis and our knowledge of machine learning.
2-We develop a classification model that diagnose NMD types and subtypes.
3-This model will be deployed in a web application.
4-The web application contains other services that works in the favor of researchers and NMD patients.
# Methodology
1-Django:as the framework for developing our web application.
2-HTML, CSS, Java Script and React :for the frontend
3-Python Sklearn on Colab and TensorFlow :for developing the machine learning tool
# Our Dataset
We are using a gene expression dataset collected from GSE3307.
These data would help us develop a reliable model to classify between
types of NMD and healthy class.
The dataset has and 22,645 features and 121 samples which were divided
into various classes.
# Machine learning model
1-GA is used for feature selection.
2-RFE-LR is used afterwards to then
recursively eliminate the least important
features.
3-LR is used for training the ML model.
4-SKF is used for cross-validation






