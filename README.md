# dl-paper

Liu, Y. (2007). Fisher consistency of multicategory support vector machines. In Artificial intelligence and statistics (pp. 291-298). PMLR.

* keyword: fisher consistency, multicategory hinge loss, multicategory support vector machine
* summary: discuss four multi-class hinge loss, and only loss (b) is always fisher concsistent. Adding a constraint to loss (a), loss (c) and truncating loss (d) ensure their fisher consistency. 

Mikolov, T., Chen, K., Corrado, G., & Dean, J. (2013). Efficient estimation of word representations in vector space. arXiv preprint arXiv:1301.3781.

* keywords: word embedding, CBOW, skip-gram model, unsupervised learning
* summary: propose a two language models: continuous Bag-of-Words Model (CBOW) and skip-gram model to derive word embeddings.

Le, Q., & Mikolov, T. (2014). Distributed representations of sentences and documents. In International conference on machine learning (pp. 1188-1196). PMLR.

* keywords: paragraph embedding, unsupervised learning
* summary: each paragraph is assigned a paragraph vector (paragraph embedding) that is derived in an unsupervised manner, akin to the CBOW and skip-gram models.

Cheng, W., Hüllermeier, E., & Dembczynski, K. J. (2010). Bayes optimal multilabel classification via probabilistic classifier chains. In Proceedings of the 27th international conference on machine learning (ICML-10) (pp. 279-286).

* keywords: multi-label classification, Bayes optimal decisions
* summary: The authors present a theoretical demonstration that in multi-label classification, the Bayes optimal decisions may not rely on conditional label dependence. Specifically, for Hamming and rank loss, the Bayes optimal decisions solely hinge on the marginal distribution, while for subset 0-1 loss, the Bayes optimal decisions depend on the joint distribution.

Cai, T. T., Li, H., Liu, W., & Xie, J. (2016). Joint estimation of multiple high-dimensional precision matrices. Statistica Sinica, 26(2), 445.
* keywords: joint estimation, convergence rate
* summary: Jointly estimating multiple high-dimensional precision matrices leads to faster convergence rate (see Theorem 1).

Duan, Y., & Wang, K. (2022). Adaptive and robust multi-task learning. arXiv preprint arXiv:2202.05250.
* keywords: joint learning, multi-task learning (MTL)
* summary: propose a multi-task learning framework with $l_2$ norm, include vanilla, clustered and low-rank MTL (see Section 4).

Ramdas, A., Reddi, S. J., Póczos, B., Singh, A., & Wasserman, L. (2015). On the decreasing power of kernel and distance based nonparametric hypothesis tests in high dimensions. In Proceedings of the AAAI Conference on Artificial Intelligence (Vol. 29, No. 1).
* keywords: two-sample test, independent test, high dimension
* summary: point out a phenomenon that the power of two-sample test or independent test decreases as dimension increases. Notice that the all experiments are under so-called fair alternative. 

Lipton, Z., Wang, Y. X., & Smola, A. (2018). Detecting and correcting for label shift with black box predictors. In International conference on machine learning (pp. 3122-3130). PMLR.
* keywords: two-sample test, label shift
* summary: propose a framework for label shift with black box predictors. The most important findings are in Proposition 4: $p(y) = q(y)$ if and only if $p(f(x)) = q(f(x))$, and Proposition 2: consistency of the proposed importance weights.

Gretton, A., Smola, A., Huang, J., Schmittfull, M., Borgwardt, K., & Schölkopf, B. (2009). Covariate shift by kernel mean matching. Dataset shift in machine learning, 3(4), 5.
* keywords: covariate shift
* summary: propose a method for estimating importance, beta(x) = p(x)/q(x), using matching of kernel mean of distribution.

Muandet, K., Fukumizu, K., Sriperumbudur, B., & Schölkopf, B. (2017). Kernel mean embedding of distributions: A review and beyond. Foundations and Trends® in Machine Learning, 10(1-2), 1-141.
* keywords: distribution embedding, conditional distribution embedding
* summary: Chapter 3 introduces the kernel mean embedding for a distribution, and presents a theorem about how to transform the "distance" between distributions to the distance between two functions in RKHS. Chapter 4 introduces the embedding for a conditional distribution.

Mnih, A., & Salakhutdinov, R. R. (2007). Probabilistic matrix factorization. Advances in neural information processing systems, 20.
* keywords: probabilistic embedding, matrix factorization, recommender systems.
* summary: introduce a new framework of probabilistic matrix factorization for recommender systems, and show the importance of adding l2 penalty of embedding into objective function (greatest difference compared tso SVD-like matrix factorization method).

Manski, C. F., & Lerman, S. R. (1977). The estimation of choice probabilities from choice based samples. Econometrica: Journal of the Econometric Society, 1977-1988.
* keywords: importance weighting, weighted maximum likelihood estimation
* summary: This paper shows that importance weighting can also be applied to MLE framework when there exists covariate shift.

Bickel, S., Brückner, M., & Scheffer, T. (2007). Discriminative learning for differing training and test distributions. In Proceedings of the 24th international conference on Machine learning (pp. 81-88).
* keywords: covariate shift, logistic regression
* summary: introduce a new objective function for handling covariate shift, including two components: (1) consider a model seperating traning and testing samples; (2) weighted MLE, trying to maximize MLE on unlabeled testing data based on labeled training data.

Sugiyama, M., Nakajima, S., Kashima, H., Buenau, P., & Kawanabe, M. (2007). Direct importance estimation with model selection and its application to covariate shift adaptation. Advances in neural information processing systems, 20.
* keywords: covariate shift, KL divergence
* summary: use KL divergence to minimize testing distribution and weighted training distribution of x. Interestingly, the final solution is quite similar to that in kernel density estimaton. However, the proposed method works much better than KDE.

Guo, C., Pleiss, G., Sun, Y., & Weinberger, K. Q. (2017). On calibration of modern neural networks. In International conference on machine learning (pp. 1321-1330). PMLR.
* keywords: confidence calibration
* summary: this paper points out a phenomenon that modern neural networks are poorly calibrated. Experimental results show that temperature scaling in the most effective in confidence calibration.

Byrd, J., & Lipton, Z. (2019). What is the effect of importance weighting in deep learning?. In International conference on machine learning (pp. 872-881). PMLR.
* keywords: importance weighting, distribution shift
* summary: empirically point out that for those models capable of seperating all training samples, the final solution may not influenced by the density of samples.

Lipton, Z., Wang, Y. X., & Smola, A. (2018). Detecting and correcting for label shift with black box predictors. In International conference on machine learning (pp. 3122-3130). PMLR.
* keywords: label shift, conditonal shift, importance weighting
* use MMD to minimize the distribution of **features** x so as for correcting label shift, also discuss how to correcting conditional shift with the same idea.