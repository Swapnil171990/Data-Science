# Data-Science
Mutual information is a measure of dependence or “mutual dependence” between two random variables(x and y).
It measures the amount of information obtained about one variable through observing the other variable. In other words, it determines how much we can know about one variable by understanding another—it’s a little bit like correlation, but mutual information is more general.
In machine learning, mutual information measures how much information the presence/absence of a feature contributes to making the correct prediction on Y.
Mutual information (MI)between two random variables is a non-negative value, which measures the dependency between the variables. It is equal to zero if and only if two random variables are independent, and higher values mean higher dependency.
The mutual information between two random variables X and Y can be stated formally as follows:

I(X ; Y) = H(X) – H(X | Y)

Where I(X ; Y) is the mutual information for X and Y,
H(X) is the entropy for X and H(X | Y) is the conditional entropy for X given Y.
Mutual information is a measure of dependence or “mutual dependence” between two random variables. As such, the measure is symmetrical, meaning that I(X ; Y) = I(Y ; X).

Relation between 'Information Gain' and 'Mutual Information'

Mutual Information and Information Gain are the same thing, although the context or usage of the measure often gives rise to the different names.

For example:

Effect of Transforms to a Dataset (decision trees): Information Gain.
Dependence Between Variables (feature selection): Mutual Information.
Notice the similarity in the way that the mutual information is calculated and the way that information gain is calculated; they are equivalent:

I(X ; Y) = H(X) – H(X | Y)

and

IG(S, a) = H(S) – H(S | a)

Mutual information is sometimes used as a synonym for information gain. Technically, they calculate the same quantity if applied to the same data.
Feature Selection for Classification Problem using Mutual Information(MI)
