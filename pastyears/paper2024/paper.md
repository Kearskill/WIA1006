QUESTION 1<br>
a)<br>
Overfitting is very common in Machine Learning. Decision Tree is also possible to be overfitted.
Overfitting occurs when a model learns the training data too well, capturing noise or random
fluctuations in the data rather than the underlying pattern. In decision trees, overfitting can lead
to overly complex trees that perform well on the training data but generalize poorly to unseen data.
<br>

Give TWO (2) solutions or approaches that can be used to avoid or solve this overfitting problem
in the Decision Tree. [2 marks]




b) <br>
Entropy is a measure of disorder or uncertainty in a system. In information theory, it is often used
to quantify the amount of information contained in a message or a random variable. Let's consider
a simple biased coin flip. Suppose we have a coin that is biased, such that the probability of
landing heads is p =0.6 and the probability of landing tails is the opposite q.

i) Calculate the probability of landing tails q. [1 mark]

ii) Calculate the entropy (S), given the formula for entropy is: [4 marks]<br>
![pic](figure001.png)

iii) Explain what it means by the value you calculated above. [1 mark]<br>

c) <br>
ID3 (Iterative Dichotomiser 3) is a popular algorithm used for building decision trees, which are a
type of predictive model used in machine learning. The algorithm was developed by Ross Quinlan
in 1979.<br> Describe TWO (2) important characteristics of ID3. [2 marks]

QUESTION 2<br>
Consider a Genetic Algorithm (GA) being used to solve a simple optimization problem of
maximizing a function, where x is a real number in the range [0, 6]. Assume a population size of
10, a crossover probability of 0.8, and a mutation probability of 0.1.

a)<br>
Describe the initialization process in the GA and explain how it generates the initial population. [2 marks]

b)<br>
What is the fitness function for this problem and explain how it evaluates the quality of solutions. [2 marks]

c)<br>
Describe the process of selection, crossover, and mutation using the example above. [3 marks]

d)<br>
State THREE (3) termination criteria that could be used to stop the GA. [3 marks]


QUESTION 3<br>
You are visiting town A in country Z. In this town, the parents in the community are encouraging
their children to read by paying them according to the hours they spend reading books. The
amount of pay varies depending on the parent. You've made some data collection by doing a
quick survey of 10 parents and how much they pay their children to read. The data is given below
in Table 1. In the dataset below, X (hours spent reading) is the feature vector and y (pay in $) are
the target output.

Table 1. The number of hours reading and its payment.<br>
![Table 1](figure002.png)

a)<br>
Calculate the covariance Cov(X, Y). The formula for computing the covariance between variable
x and y is given as follows.
![Formula](figure003.png)

Where X₁ is the ith sample of feature X, X is the mean of feature X, n is the total number of
samples in the dataset. [5 marks]

b)<br>
What is the difference between correlation and covariance?Give an example using two variables
X and Y. Why are we calculating covariance instead of correlation for PCA? [3 marks]

c)<br>
The eigenvalues for this problem has been calculated and is given as  
![Eigenvalues](figure004.png)

Which eigenvalues are more important and why? [2 marks]


QUESTION 4<br>
John has the information of 4 houses, i.e. size in thousand square feet, number of rooms and
price in million Ringgit Malaysia, and presented in the table below:
![Table](figure005.png)

John assumes that the houses can be grouped into 2 clusters, P and Q, using K-Means algorithm
with Euclidean distance. Apart from this, he also assumes the initial cluster centers are (1, 1, 1)
and (3, 3, 3) respectively.

a) <br>
What is the value of K for this case? [1 mark]

b) <br>
With the assumptions made by John, determine the houses that belong to both the clusters.
Present your answer in a table form. [3 marks]

c) <br>
Based on the assumption of John, where are the next cluster centers? [2 marks]

d) <br>
Instead of using K-Means clustering, Caine suggests using a bottom-up (agglomerative)
hierarchical clustering. To be more precise, Caine wants to perform a single-linkage clustering by considering Euclidean distance between objects.

Help Caine to find 2 clusters using the algorithm described above. [4 marks]


QUESTION 5<br>
Explain what is the Reinforcement Learning paradigm? Explain each of the key components of
reinforcement learning (RL) below. For each of the components give an example of the
components in the context of financial trading. [10 marks]

a) Agent

b) Environment

c) Action

d) States

e) Rewards

f) Policy