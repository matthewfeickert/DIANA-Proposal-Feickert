# [DIANA Fellow](http://diana-hep.org/pages/fellows.html) proposal for Matthew Feickert: A study of data flow graph frameworks for statistical models in particle physics

[![DOI](https://zenodo.org/badge/83797541.svg)](https://zenodo.org/badge/latestdoi/83797541)

## Abstract

The statistical software used for the last several years in particle physics is facing scalability challenges. In addition to processing speed, which is being addressed with GPU-based fitting approaches, we also face memory limitations as the combined statistical models grow in size. Thus, it is critical to investigate more distributed models for these computations.

The rapid development of software libraries for numerical computations through data flow graphs (e.g., [TensorFlow](https://www.tensorflow.org/) and [Theano](http://deeplearning.net/software/theano/)) has led to a fundamental change of paradigm in machine learning software. While originally developed for the purpose of deep learning research, these libraries are general enough to be applicable in a wide variety of other domains, including particle physics statistical models. Under the mentorship of [Gilles Louppe](https://glouppe.github.io/) and [Vince Croft](https://www.nikhef.nl/~vcroft/), [Matthew Feickert](http://www.matthewfeickert.com/) will investigate the pros and cons of implementing the statistical models used in particle physics with a different computational graph framework. In particular, we will assess their capabilities and limits, and determine how those frameworks would scale in terms of data and model parallelism.
