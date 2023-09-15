# bnn
## Bayesian Neural Network Inference of Strong Gravitational Lenses
ovejero conducts hierarchical inference of strongly-lensed systems with Bayesian neural networks

[ovejero](https://github.com/swagnercarena/ovejero/tree/master)

[cobaya](https://github.com/CobayaSampler/cobaya/tree/master)


# Installation
Lenstronomy requires an additional fortran package (fastell) to run lens models with elliptical mass distributions. Thankfully, installing the package is fairly easy (although a fortran compiler is required).

```
$ git clone https://github.com/sibirrer/fastell4py.git <desired location>
$ cd <desired location>
$ python setup.py install --user
```

In the future, ovejero will be a pypi package. For now, it can be installed by cloning the git repo.

```
$ git clone https://github.com/swagnercarena/ovejero.git
$ cd overjero/
$ pip install -e . -r requirements.txt
```
