### Multi-task feature learning

This is a method for learning multiple tasks simultaneously, assuming that they share a set of common latent features. It is based on regularizing the spectrum of the matrix of tasks. Regularization with the trace norm is a special case of this framework. Among the diverse applications of multi-task learning, one example is the personalized recommendation of products to consumers. 

The methodology is presented in detail in the papers
[Multi-Task Feature Learning](http://ttic.uchicago.edu/~argyriou/papers/nips06_online.pdf),
[Convex Multi-Task Feature Learning](http://ttic.uchicago.edu/~argyriou/papers/mtl_feat.pdf)
and 
[A Spectral Regularization Framework for Multi-Task Structure Learning](http://ttic.uchicago.edu/~argyriou/papers/spectral_mtl.pdf).

The school data comes from [H. Goldstein, Multilevel Modelling of Survey Data, 1991](http://www.bristol.ac.uk/media-library/sites/cmm/migrated/documents/multilevel-modelling-of-survey-data.pdf).

Note that it is possible to use the method with a nonlinear kernel instead of explicit features. It suffices to run the code on the Gram matrix after a preprocessing with a Gram-Schmidt or Cholesky decomposition (see [Convex Multi-Task Feature Learning](http://ttic.uchicago.edu/~argyriou/papers/mtl_feat.pdf)).


