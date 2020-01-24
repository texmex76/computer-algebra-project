# CA Project: A Modular GCD Algorithm

## Documentation

The documentation of the project is in the `doc` folder. In particular, the paper is found in `doc/A_Modular_GCD_Algorithm.pdf` and the slides in `doc/Modular GCD Computations.pdf` or `doc/Modular GCD Computations.pptx`.

## Running the code

The code is implemented as [SageMath](https://www.sagemath.org/) Jupyter notebooks. SageMath has to be installed on the system to run the code. Executing this command will start the SageMath server:
```
sage -n jupyter
```

There are different notebooks for different tests and implementations:
* `notebooks/gcd_int.ipynb`: demonstration of the basic integer GCD algorithm
* `notebooks/gcd_int_mod.ipynb`: demonstration of the modular integer GCD algorithm
* `notebooks/gcd_int_functions.ipynb`: helper functions and implementations of the basic integer GCD algorithm and the modular integer GCD algorithm
* `notebooks/gcd_modm.ipynb`: demonstration of the GCD algorithm for polynomials
* `notebooks/GCD_MODm_functions.ipynb`: helper functions and implementation of the GCD algorithm for polynomials
