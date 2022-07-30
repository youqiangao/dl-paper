# dl-paper

Liu, Y. (2007), “Fisher Consistency of Multicategory Support Vector Machines,” in *Proceedings of the Eleventh International Conference on Artificial Intelligence and Statistics*, PMLR, pp. 291–298.

* keyword: fisher consistency, multicategory hinge loss, multicategory support vector machine
* summary: discuss four multi-class hinge loss, only loss (b) are always fisher concsistent. Adding a constraint to loss (a), loss (c) and truncating loss (d)  make them fisher consistent. 

Dorfer, M., Kelz, R., and Widmer, G. (2016), “Deep Linear Discriminant Analysis,” *arXiv:1511.04707 [cs]*.

* keywords: LDA, deep neural network
* summary: propose a LDA eigenvalue-based objective function and encode x through a deep neural nework f(.) to push the net to generate discriminative hidden representation H.

Mikolov, T., Chen, K., Corrado, G., and Dean, J. (2013), “Efficient estimation of word representations in vector space,” *arXiv preprint arXiv:1301.3781*.

* keywords: word embedding, CBOW, skip-gram model
* summary: propose a two language models: continuous Bag-of-Words Model (CBOW) and skip-gram model to derive word embeddings. It is different from NNLM in terms of the non-linear hidden layers is removed and future words are used for prediction.

Le, Q., and Mikolov, T. (2014), “Distributed representations of sentences and documents,” in *International conference on machine learning*, PMLR, pp. 1188–1196.

* keywords: paragraph vector
* summary: propose a model for paragragh vector with three stages: the unsupervised training to update paragraph vectors and word vectors with training data, the inference stage to derive paragraph vectors for testing data (word vectors keep fixing in this stage), and the last stage is to make label prediction with paragraph vectors and word vectors.

Ioffe, S., and Szegedy, C. (2015), “Batch normalization: Accelerating deep network training by reducing internal covariate shift,” in *International conference on machine learning*, PMLR, pp. 448–456.

* keywords: internal covariate shift
* summary: propose a batch normalization to address so-called internal covariate shift caused by saturating nonlinearities. Batch normalization enables training of models with saturating nonlinearties and much higher learning rate, and dramatically accererates the training of deep networks.

Grandvalet, Y., and Bengio, Y. (2006), “Entropy Regularization.”	

* keywords: entropy regularization, semi-supervised learning, unlabeled data
* summary: assume high conditional entropy for unlabeled data. They propose an entropy regularization to utilize unlabeled data in the training of model. Eqn. (9.5) states the empirical version of the conditional entropy. 

Lee, D.-H. (2013), “Pseudo-label: The simple and efficient semi-supervised learning method for deep neural networks,” in *Workshop on challenges in representation learning, ICML*, p. 896.

* keywords: pseudo labels, semi-supervised learning, unlabeled data
* summary: propose a method to use labeled data and unlabeled data simultaneously. Specifically, geneate pseudo labels for unlabels instances, and the rest is the same as usual supervised learning. It is equivalent to entropy regularization. 