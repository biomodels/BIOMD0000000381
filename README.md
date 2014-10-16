# BIOMD0000000381: Maree2006_DuCa_Type1DiabetesModel

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000381.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000381.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000381 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
** Modelling the onset of Type 1 diabetes: can impaired macrophage phagocytosis make the difference between health and disease? **   
Maree AF, Kublik R, Finegood DT, Edelstein-Keshet L._Philos Transact A Math
Phys Eng Sci._2006 May 15;364(1842):1267-82. [
16608707](http://www.ncbi.nlm.nih.gov/pubmed/16608707),  
**Abstract:**   
A wave of apoptosis (programmed cell death) occurs normally in pancreatic
beta-cells of newborn mice. We previously showed that macrophages from non-
obese diabetic (NOD) mice become activated more slowly and engulf apoptotic
cells at a lower rate than macrophages from control (Balb/c) mice. It has been
hypothesized that this low clearance could result in secondary necrosis,
escalating inflammation and self-antigen presentation that later triggers
autoimmune, Type 1 diabetes (T1D). We here investigate whether this hypothesis
could offer a reasonable and parsimonious explanation for onset of T1D in NOD
mice. We quantify variants of the Copenhagen model (Freiesleben De Blasio et
al. 1999 Diabetes 48, 1677), based on parameters from NOD and Balb/c
experimental data. We show that the original Copenhagen model fails to explain
observed phenomena within a reasonable range of parameter values, predicting
an unrealistic all-or-none disease occurrence for both strains. However, if we
take into account that, in general, activated macrophages produce harmful
cytokines only when engulfing necrotic (but not apoptotic) cells, then the
revised model becomes qualitatively and quantitatively reasonable. Further, we
show that known differences between NOD and Balb/c mouse macrophage kinetics
are large enough to account for the fact that an apoptotic wave can trigger
escalating inflammatory response in NOD, but not Balb/c mice. In Balb/c mice,
macrophages clear the apoptotic wave so efficiently, that chronic inflammation
is prevented.

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html).  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


