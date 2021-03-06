### General

* [MLE in Python](http://nbviewer.jupyter.org/github/VHRanger/MLE-tutorial/blob/master/Implementing%20and%20vectorizing%20a%20Maximum%20Likelihood%20model%20with%20scipy--1.ipynb) from QuantEcon: shows the correct way to calculate sd, t-stats and p-value from the Inverse Hessian; up-to-date and reliable automatic differentiation; and vectorization trips that can speed up MLE calculation.
* More generally, [QuantEcon Gallery](https://quantecon.org/gallery) contains useful examples for fitting economic models, esp. dynamic models. Examples are biased towards macro side but methods are useful in general.



### Links to useful modules:

* [Using API](http://docs.python-requests.org/en/master/user/quickstart/#make-a-request)
* [Regular expressions](https://docs.python.org/3/howto/regex.html#regex-howto)
* [Scraping](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
* [Working with SQLite3](https://docs.python.org/3.6/library/sqlite3.html)

### Fast sparse regression (e.g. High-dim FE)
* [FastReg](https://github.com/iamlemec/fastreg)

### Structural Models

* [BLP in Python](https://pypi.org/project/pyblp/), and [best practices for using it](https://chrisconlon.github.io/site/pyblp.pdf)

### ML 

* Bayesian deep learning: [PYSGMCMC](https://github.com/MFreidank/pysgmcmc) and [Edward](http://edwardlib.org/)
* [Deep IV](https://github.com/jhartford/DeepIV)
* [Variational Inference](https://github.com/blei-lab)
* [MSR's EconML package](https://econml.azurewebsites.net/). [This link](https://econml.azurewebsites.net/spec/comparison.html) compares the properties (types of treatment effect suited) of the popular causal ML estimators included in their package; useful to check before use. 
* [Uber's CausalML package](https://github.com/uber/causalml). Note: though "causal" is in the package name, the models themselves are not built for inference. For inference, use their learners in conjunction with DML. 
