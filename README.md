# MSc Thesis

**Title**: Exploiting a new probabilistic model: S2FA - Simple-Supervised Factor Analysis

2019 summer, FII, UAIC, Iasi, Romania

The **implementation** of the R package can be found [here](https://github.com/aciobanusebi/s2fa).

**Abstract**:

In machine learning, a classic **supervised-unsupervised pair** of algorithms is **Gaussian Joint Bayes-Expectation Maximization (EM) for Gaussian Mixture Model**. Starting from this, one can create an algorithm for **semi-supervised** learning and also other extensions. In this work, we started from an existing **unsupervised learning algorithm (EM for Factor Analysis)**, created its supervised version (**S2**) and exploited the properties of this new model. Two main extensions of S2 are: the semi-supervised (**S3**) case and the missing data (**MS3**) case. All the algorithms are derived starting from the (log-)likelihood of the (observed) data and using the **maximum likelihood principle**. The **S2** algorithms are trained using **closed-form formulas**, while **S3 and MS3** are trained using the **EM** algorithm. The S2 and S3 algorithms can also be vectorised. 

Apart from the **derivation of the algorithms**, we found **two significant links between the supervised counterpart of (unconstrained) Factor Analysis and (multi-output) Linear Regression**, and we present them here. Some **experiments** are also included.
