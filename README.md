# chemcomp
Modeling the chemical composition of gas giants by accretion of pebbles, planetesimals and gas.

## Usage:
If you use this code in your work and found it useful, please cite [Schneider & Bitsch (2021a)](https://ui.adsabs.harvard.edu/abs/2021A&A...654A..71S)

## install:
clone project:

`git clone https://github.com/AaronDavidSchneider/chemcomp.git`

move into directory:

`cd chemcomp`

Install conda environment:

`conda create -n chemcomp numpy "astropy>=4.0" scipy matplotlib pyyaml jupyter parse h5py pip pytables`

Install `chemcomp`:

`pip install -e .`

Adjust paths in `chemcomp/helper/main_helper` if you need different directories for output and config.

## Thanks:
- I would like to thank Bertram Bitsch for his enormous support during the development of this code and for continuing to use the code together with his students.
- I would like to thank Cornelis Dullemond for providing the solver which (in adapted version) is used to solve the gas viscous disk equation and dust transport equation.
- I would like to thank everyone, who has already used chemcomp in their work and has contributed in fixing small bugs.

## Help:
Check the [WIKI](https://chemcomp.readthedocs.io/en/latest/ "wiki")
