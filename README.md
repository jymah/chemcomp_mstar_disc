# chemcomp

Modeling the chemical composition of gas giants by accretion of pebbles, planetesimals and gas.

**docs: [WIKI](https://chemcomp.readthedocs.io/en/latest/ "wiki")**

## install:
clone project:

`git clone https://github.com/AaronDavidSchneider/chemcomp.git`

move into directory:

`cd chemcomp`

Install conda environment:

`conda create -n chemcomp numpy "astropy>=4.0" scipy matplotlib pyyaml jupyter parse h5py pip pytables`

Install a development version `chemcomp`:

`pip install -e .`

or install from pypi

``pip install chemcomp``

Adjust paths in `chemcomp/helper/main_helper` if you need different directories for output and config.

## Publications
### Original Publications

-   [Schneider & Bitsch (2021a)](https://ui.adsabs.harvard.edu/abs/2021A&A...654A..71S)</br>
    How drifting and evaporating pebbles shape giant planets. I. Heavy element content and atmospheric C/O

-   [Schneider & Bitsch (2021b)](https://ui.adsabs.harvard.edu/abs/2021A&A...654A..72SS)</br>
    How drifting and evaporating pebbles shape giant planets. II. Volatiles and refractories in atmospheres

-   [Bitsch, Schneider & Kreidberg (2022)](https://ui.adsabs.harvard.edu/abs/2022A&A...665A.138B)</br>
    How drifting and evaporating pebbles shape giant planets. III. The formation of WASP-77A b and $\tau$ Boötis b

Please cite [Schneider & Bitsch(2021a)](https://ui.adsabs.harvard.edu/abs/2021A&A...654A..71S), if you use `chemcomp` in your work.

### Publications using `chemcomp`

-   [Bitsch et al. (2021)](https://ui.adsabs.harvard.edu/abs/2021A&A...649L...5B)</br>
    Dry or water world? How the water contents of inner sub-Neptunes constrain giant planet formation and the location of the water ice line

-   [Hühn & Bitsch (2023)](https://ui.adsabs.harvard.edu/abs/2023A&A...676A..87H)</br>
    How accretion of planet-forming disks influences stellar abundances

-   [Bitsch & Mah (2023)](https://ui.adsabs.harvard.edu/abs/2023arXiv230900509B)</br>
    Enriching inner discs and giant planets with heavy elements

-   [Mah & Bitsch (2023a)](https://ui.adsabs.harvard.edu/abs/2023A&A...673A..17M)</br>
    Forming super-Mercuries: Role of stellar abundances

-   [Mah & Bitsch (2023b)](https://ui.adsabs.harvard.edu/abs/2023A&A...677L...7M)</br>
    Close-in ice lines and the super-stellar C/O ratio in discs around very low-mass stars

-   [Savvidou & Bitsch (2023)](https://ui.adsabs.harvard.edu/abs/2023arXiv230903807S)</br>
    How to make giant planets via pebble accretion

-   [Danti, Bitsch & Mah (2023)](https://ui.adsabs.harvard.edu/abs/2023arXiv231002886D)</br>
    Composition of giant planets: the roles of pebbles and planetesimals

-   [Chatziastros, Bitsch & Schneider (2023)](https://ui.adsabs.harvard.edu/abs/2023arXiv231012797C)</br>
    Constraining the formation history of the HAT-P-11 system by atmospheric abundances

And several more in preperation (last updated: 22.11.2023)


## Thanks:
- I would like to thank Bertram Bitsch for his enormous support during the development of this code and for continuing to use the code together with his students.
- I would like to thank Cornelis Dullemond for providing the solver which (in adapted version) is used to solve the gas viscous disk equation and dust transport equation.
- I would like to thank everyone, who has already used chemcomp in their work and has contributed in fixing small bugs.
