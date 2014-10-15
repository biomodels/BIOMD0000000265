# BIOMD0000000265: Conradie2010_RPControl_CellCycle

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000265.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000265.git@20140916`


# Model Notes


This model is from the article:  
** Restriction point control of the mammalian cell cycle via the cyclin E/Cdk2:p27 complex. **   
Conradie R, Bruggeman FJ, Ciliberto A, Csikász-Nagy A, Novák B, Westerhoff HV,
Snoep JL _FEBS J._2010 Jan; 277(2): 357-67
[20015233](http://www.ncbi.nlm.nih.gov/pubmed/20015233),  
**Abstract:**   
Numerous top-down kinetic models have been constructed to describe the cell
cycle. These models have typically been constructed, validated and analyzed
using model species (molecular intermediates and proteins) and phenotypic
observations, and therefore do not focus on the individual model processes
(reaction steps). We have developed a method to: (a) quantify the importance
of each of the reaction steps in a kinetic model for the positioning of a
switch point [i.e. the restriction point (RP)]; (b) relate this control of
reaction steps to their effects on molecular species, using sensitivity and
co-control analysis; and thereby (c) go beyond a correlation towards a causal
relationship between molecular species and effects. The method is generic and
can be applied to responses of any type, but is most useful for the analysis
of dynamic and emergent responses such as switch points in the cell cycle. The
strength of the analysis is illustrated for an existing mammalian cell cycle
model focusing on the RP [Novak B, Tyson J (2004) J Theor Biol230, 563-579].
The reactions in the model with the highest RP control were those involved in:
(a) the interplay between retinoblastoma protein and E2F transcription factor;
(b) those synthesizing the delayed response genes and cyclin D/Cdk4 in
response to growth signals; (c) the E2F-dependent cyclin E/Cdk2 synthesis
reaction; as well as (d) p27 formation reactions. Nine of the 23 intermediates
were shown to have a good correlation between their concentration control and
RP control. Sensitivity and co-control analysis indicated that the strongest
control of the RP is mediated via the cyclin E/Cdk2:p27 complex concentration.
Any perturbation of the RP could be related to a change in the concentration
of this complex; apparent effects of other molecular species were indirect and
always worked through cyclin E/Cdk2:p27, indicating a causal relationship
between this complex and the positioning of the RP.

The rate constants presented in the paper have units [per tenth of an hour]
and have been changed here to [per hour] (e.g. k16 = 0.25 not 0.025); for
further confirmation of the correctness of this change, see the original model
(Novak, J Theor Biol 2004 230:563).


