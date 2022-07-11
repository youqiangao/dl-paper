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

* keywords: propose a model for paragragh vector with three stages: the unsupervised training to update paragraph vectors and word vectors with training data, the inference stage to derive paragraph vectors for testing data (word vectors keep fixing in this stage), and the last stage is to make label prediction with paragraph vectors and word vectors.