# Comparison of Julia and python in jupyter notebooks

Simple comparison of julia vs python.

Create the environment
```bash
conda create -n julia_python python=3.9
conda activate julia_python
conda install tensorflow pytorch numpy
pip install jupyterlab jupyter_nbextensions_configurator intel-openmp
```
using python 3.9, because there is no conda package ready yet for the 3.10

to add julia kernel, run
```julia
] add IJulia
using IJulia
```
(I'm using Julia 1.7.3)

start jupyter notebook
```bash
jupyter lab
```