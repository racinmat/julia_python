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

mutagenesis examples taken from:
https://nbviewer.org/github/CTUAvastLab/JsonGrinder.jl/blob/gh-pages/v2.3.1/examples/mutagenesis_python.ipynb
https://nbviewer.org/github/CTUAvastLab/JsonGrinder.jl/blob/gh-pages/v2.3.1/examples/mutagenesis.ipynb

presentation: https://docs.google.com/presentation/d/17iJz3msb9cYPzNDW2RMl1ZY-U9kPS9j58vtXX__yt3U/edit?usp=sharing
