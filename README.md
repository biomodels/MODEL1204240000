# MODEL1204240000: Model_1

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1204240000.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1204240000.git@20140916`

## Usage

Importing the model package.

`import MODEL1204240000 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This model is from the article:  
**Microarray data can predict diurnal changes of starch content in the picoalga Ostreococcus.**   
Sorokina O, Corellou F, Dauvillée D, Sorokin A, Goryanin I, Ball S, Bouget FY,
Millar AJ _BMC Systems Biology_ 2011, 5:36
[21352558](http://www.ncbi.nlm.nih.gov/pubmed/21352558) ,  
**Abstract:**   
BACKGROUND: The storage of photosynthetic carbohydrate products such as starch
is subject to complex regulation, effected at both transcriptional and post-
translational levels. The relevant genes in plants show pronounced daily
regulation. Their temporal RNA expression profiles, however, do not predict
the dynamics of metabolite levels, due to the divergence of enzyme activity
from the RNA profiles.Unicellular phytoplankton retains the complexity of
plant carbohydrate metabolism, and recent transcriptomic profiling suggests a
major input of transcriptional regulation. RESULTS: We used a quasi-steady-
state, constraint-based modelling approach to infer the dynamics of starch
content during the 12 h light/12 h dark cycle in the model alga Ostreococcus
tauri. Measured RNA expression datasets from microarray analysis were
integrated with a detailed stoichiometric reconstruction of starch metabolism
in O. tauri in order to predict the optimal flux distribution and the dynamics
of the starch content in the light/dark cycle. The predicted starch profile
was validated by experimental data over the 24 h cycle. The main genetic
regulatory targets within the pathway were predicted by in silico analysis.
CONCLUSIONS: A single-reaction description of starch production is not able to
account for the observed variability of diurnal activity profiles of starch-
related enzymes. We developed a detailed reaction model of starch metabolism,
which, to our knowledge, is the first attempt to describe this polysaccharide
polymerization while preserving the mass balance relationships. Our model and
method demonstrate the utility of a quasi-steady-state approach for inferring
dynamic metabolic information in O. tauri directly from time-series gene
expression data.

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not.

To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


