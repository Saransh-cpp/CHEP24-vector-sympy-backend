# A new SymPy backend for vector: uniting experimental and theoretical physicists

[![Poster](https://img.shields.io/badge/CHEP24-poster-blue?logo=github&logoColor=white&color=blue)](https://indi.to/zTs5b)
[![Proceeding](https://img.shields.io/badge/CHEP24-proceedings-blue?logo=github&logoColor=white&color=blue)](/CHEP24_proceeding.pdf)

Vector is a Python library for 2D, 3D, and Lorentz vectors, especially arrays of vectors, to solve common physics problems in a NumPy-like way. Vector currently supports creating pure Python Object, NumPy arrays, and Awkward arrays of vectors. The Object and Awkward backends are implemented in Numba to leverage JIT-compiled vector calculations. Furthermore, vector also supports JAX and Dask operations on Awkward arrays of vectors.

We introduce a new SymPy backend in vector to allow symbolic computations on high energy physics vectors. Along with experimental physicists using vector for numerical computations, the SymPy backend will enable theoretical physicists to utilize the library for symbolic computations. Since the SymPy vector classes and their momentum equivalents operate on SymPy expressions, all of the standard SymPy methods and functions work on the vectors, vector coordinates, and the results of operations carried out on vectors. Moreover, vector’s SymPy backend will create a stronger connection between software used by experimentalists and software used by theorists.

This talk will introduce vector and its backends to the users and funnel down to the SymPy backend. Finally, vector’s SymPy backend is relatively new; hence, we aim to collect suggestions and recommendations from both theoretical and experimental physicists.

## Stuck somewhere? Reach out!

- If something is not working the way it should, or if you want to request a new feature, create a [new issue](https://github.com/scikit-hep/vector/issues) on GitHub.
- To discuss something related to vector, use the [discussions](https://github.com/scikit-hep/vector/discussions/) tab on GitHub or vector’s gitter ([Scikit-HEP/vector](https://gitter.im/Scikit-HEP/vector)) chat room.
- Have a look at vector's [changelog](https://vector.readthedocs.io/en/latest/#changes-in-vector-s-api) to stay up-to-date!

## Cite vector

If you use `vector` in your work, please cite it using the following metadata -

```bib
@software{Schreiner_vector,
author = {Schreiner, Henry and Pivarski, Jim and Chopra, Saransh},
doi = {10.5281/zenodo.5942082},
license = {BSD-3-Clause},
title = {{vector}},
url = {https://github.com/scikit-hep/vector}
}
```
