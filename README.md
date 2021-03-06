# MODEL1001150000: Pepke2010_Ca2_CaM_mCaMKII

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1001150000.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1001150000.git@20140916`

## Usage

Importing the model package.

`import MODEL1001150000 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This the full model from the article:  
**A dynamic model of interactions of Ca2+, calmodulin, and catalytic subunits of Ca2+/calmodulin-dependent protein kinase II.**   
Pepke S, Kinzer-Ursem T, Mihalas S, Kennedy MB. _PLoS Comput Biol_ 2010 Feb
12;6(2):e1000675. PMID:
[20168991](http://www.ncbi.nlm.nih.gov/pubmed/20168991) , doi:
[10.1371/journal.pcbi.1000675](http://dx.doi.org/10.1371/journal.pcbi.1000675)
;  
**Abstract:**   
During the acquisition of memories, influx of Ca2+ into the postsynaptic spine
through the pores of activated N-methyl-D-aspartate-type glutamate receptors
triggers processes that change the strength of excitatory synapses. The
pattern of Ca2+influx during the first few seconds of activity is interpreted
within the Ca2+-dependent signaling network such that synaptic strength is
eventually either potentiated or depressed. Many of the critical signaling
enzymes that control synaptic plasticity,including Ca2+/calmodulin-dependent
protein kinase II (CaMKII), are regulated by calmodulin, a small protein that
can bindup to 4 Ca2+ ions. As a first step toward clarifying how the
Ca2+-signaling network decides between potentiation or depression, we have
created a kinetic model of the interactions of Ca2+, calmodulin, and CaMKII
that represents our best understanding of the dynamics of these interactions
under conditions that resemble those in a postsynaptic spine. We constrained
parameters of the model from data in the literature, or from our own
measurements, and then predicted time courses of activation and
autophosphorylation of CaMKII under a variety of conditions. Simulations
showed that species of calmodulin with fewer than four bound Ca2+ play a
significant role in activation of CaMKII in the physiological
regime,supporting the notion that processing of Ca2+ signals in a spine
involves competition among target enzymes for binding to unsaturated species
of CaM in an environment in which the concentration of Ca2+ is fluctuating
rapidly. Indeed, we showed that dependence of activation on the frequency of
Ca2+ transients arises from the kinetics of interaction of fluctuating
Ca2+with calmodulin/CaMKII complexes. We used parameter sensitivity analysis
to identify which parameters will be most beneficial to measure more carefully
to improve the accuracy of predictions. This model provides a quantitative
base from which to build more complex dynamic models of postsynaptic signal
transduction during learning.

The nomenclature of the different Calmodulin forms in th emodel differs from
the description in the article. The C and N terminal Ca 2+ binding sites are
described by the numbers at each species name, with the first entry indicating
the number of Ca 2+ ions bound to the C and the second the ones bound on the N
terminal sites. In complexes with two CaM, the four numbers at the end
indicate _C_N_C_N.  
For example: CaM1N2C in the article is CaM_2_1 in the model, CaM4 is CaM_2_2
and KCaMcomplex_0_1_1_2 stands for CaMKII bound to CaM1C and CaM2N1C .

This is a Systems Biology Markup Language (SBML) file, originally generated by
MathSBML 2.9.0 [8-Oct-2008] 15-Jan-2010 13:13:32 (GMT-07:60). SBML is a form
of XML, and most XML files will not display properly in an internet browser.
To view the contents of an XML file use the "Page Source" or equivalent button
on you browser.

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not..  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


