The general concept of building a PBPK model has previously been described by Kuepfer et al. ([Kuepfer 2016](#5-references)). Relevant information on anthropometric (height, weight) and physiological parameters (e.g. blood flows, organ volumes, binding protein concentrations, hematocrit, cardiac output) in adults was gathered from the literature and has been previously published ([Willmann 2007](#5-references)). The information was incorporated into PK-Sim® and was used as default values for the simulations in adults.

The applied activity and variability of plasma proteins and active processes that are integrated into PK-Sim® are described in the publicly available PK-Sim® Ontogeny Database Version 7.3 ([PK-Sim Ontogeny Database Version 7.3](#5-references)) or otherwise referenced for the specific process.


First, a mean model was built using clinical data from single dose and multiple doses studies with intravenous and oral administration of felodipine ([Edgar 1987](#5-references), [Bailey 1996](#5-references), [Gelal 2005](#5-references), [Bailey 2003](#5-references), [Goosen 2004](#5-references), [Jalava 1997](#5-references), [Blychert 1990](#5-references), [Lundahl 1998](#5-references), [Bailey 1995](#5-references), [Aberg 1997](#5-references), [Bailey 1993](#5-references), [Edgar 1992](#5-references), [Lundahl 1997](#5-references)). One DDI study ([Jalava 1997](#5-references)) was also used in the optimization to help the model describe DDI better. The mean PBPK model was developed using a typical male European individual. The relative tissue-specific expressions of enzymes predominantly being involved in the metabolism of felodipine (CYP3A4) were considered ([Meyer 2012](#5-references)).

A specific selected set of parameters (see below) was optimized using the Parameter Identification module provided in PK-Sim®. Structural model selection was mainly guided by visual inspection of the resulting description of data and biological plausibility.

Once the appropriate structural model was identified, dissolution kinetic parameters were optimized for immediate-release tablets. 

The model was then evaluated by simulating further clinical studies reporting pharmacokinetic concentration-time profiles of felodipine.

Details about input data (physicochemical, *in vitro* and clinical) can be found in [Section 2.2](#22-data).

Details about the structural model and its parameters can be found in [Section 2.3](#23-model-parameters-and-assumptions).

