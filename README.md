# Clustering probability measures in the Wasserstein space
Final thesis for bachelor's degree in mathematical engineering (Politecnico di Milano, A. Y. 2023/24), supervised by prof. M. Beraha. 

Authors: [Pietro Masini](https://github.com/pietromas), [Maria Chiara Menicucci](https://github.com/mariachiaramnc).

Our main reference is ["An invitation to statistics in Wasserstein space"](https://link.springer.com/book/10.1007/978-3-030-38438-8) by V. M. Panaretos and Y. Zemel.

## Abstract
In this thesis we tackle the problem of clustering probability measures in the
Wasserstein space. After presenting the necessary background in optimal
transport and defining the Wasserstein distance, we introduce the problem
of clustering and review two major algorithms used in clustering Euclidean
data: K-Means and Expectation-Maximization. Then we show how they can
be modified for the purpose of clustering probability measures, focusing on
proposing a novel algorithm which extends the EM algorithm to the case
of measures. We implement such extensions in Python and compare their
performances on simulated datasets, ascertaining that EM performs better
than K-Means.
