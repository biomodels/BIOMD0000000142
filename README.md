# BIOMD0000000142: model_0000001

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000142.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000142.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000142 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**Which model to use for cortical spiking neurons?**   
Izhikevich EM. _IEEE Trans Neural Netw._ 2004 Sep;15(5):1063-70.
[15484883](http://www.ncbi.nlm.nih.gov/pubmed/15484883) ,  
**Abstract:**   
We discuss the biological plausibility and computational efficiency of some of
the most useful models of spiking and bursting neurons. We compare their
applicability to large-scale simulations of cortical neural networks.

The model is according to the paper _Which Model to Use for Cortical Spiking
Neurons?_ Figure1(H) Class 2 excitable has been reproduced by MathSBML. The
ODE and the parameters values are taken from the a paper _Simple Model of
Spiking Neurons_ The original format of the models are encoded in the MATLAB
format existed in the ModelDB with Accession number 39948

Figure1 are the simulation results of the same model with different choices of
parameters and different stimulus function or events.a=0.2; b=0.26; c=-65;
d=0; V=-64; u=b*V;

This model originates from BioModels Database: A Database of Annotated
Published Models. It is copyright (c) 2005-2010 The BioModels Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html) .  
To cite BioModels Database, please use [Le Novère N., Bornstein B., Broicher
A., Courtot M., Donizelli M., Dharuri H., Li L., Sauro H., Schilstra M.,
Shapiro B., Snoep J.L., Hucka M. (2006) BioModels Database: A Free,
Centralized Database of Curated, Published, Quantitative Kinetic Models of
Biochemical and Cellular Systems Nucleic Acids Res., 34: D689-D691.](http://ww
w.pubmedcentral.nih.gov/articlerender.fcgi?tool=pubmed&pubmedid=16381960)


