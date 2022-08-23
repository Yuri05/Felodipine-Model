### 2.3.1 Absorption

The model parameter `Specific intestinal permeability` was was calculated by PK-Sim® and kept to that value since it was insensitive. The default solubility was assumed to be measured value in fasted state simulated intestinal fluid (see [Section 2.2.1](#221-in-vitro-and-physicochemical-data))

The dissolution of both immediate and extended-release tables was implemented via two Weibull dissolution tablets, and the dissolution kinetic parameters were optimized (see [Section 2.3.4](#234-automated-parameter-identification)).


### 2.3.2 Distribution

Felodipine is highly bound to proteins in plasma (see [Section 2.2.1](#221-in-vitro-and-physicochemical-data)). A value of 0.36% was used in this PBPK model for `Fraction unbound (plasma, reference value)`. 

An important parameter influencing the resulting volume of distribution is lipophilicity. The reported experimental logP values are in the range of 4 (see [Section 2.2.1](#221-in-vitro-and-physicochemical-data)) which served as a starting value. Finally, the model parameter `Lipophilicity` was optimized to match best clinical data (see also [Section 2.3.4](#234-automated-parameter-identification)).

After testing the available organ-plasma partition coefficient and cell permeability calculation methods built in PK-Sim, observed clinical data was best described by choosing the partition coefficient calculation by `Rodgers and Rowland` and cellular permeability calculation by `PK-Sim Standard`.


### 2.3.3 Metabolism and Elimination

Two metabolic pathways were implement into the model via Michaelis-Menten kinetics 

* CYP3A4
* unknown hepatic enzyme *via* unspecific hepatic clearance

The latter was preferred over renal clearance, since there is evidence that felodipine is fully metabolized and not found in urine ([Edgar 1987](#5-references)).
CYP3A5 was not implemented since the fraction metabolized appeared to be minor compared to CYP3A4.

The CYP3A4 expression profiles is based on high-sensitive real-time RT-PCR ([Nishimura 2003](#5-references)). Absolute tissue-specific expressions were obtained by considering the respective absolute concentration in the liver. The PK-Sim database provides a default value for CYP3A4 (compare [Rodrigues 1999](#5-references) and assume 40 mg protein per gram liver). 

The first model simulations showed that gut wall metabolism was underrepresented in the PBPK model. In order to increase gut wall metabolism, the “mucosa permeability on basolateral side” (jointly the model parameters in the mucosa: ``P (interstitial->intracellular)`` and ``P (intracellular->interstitial)``) was estimated. A decrease in this permeability may lead to higher gut wall concentrations and, in turn, to a higher gut wall elimination. This parameter was preferred over other parameters such as relative CYP3A4 expression or fraction unbound (fu) in the gut wall as it is technically not limited to a maximum value of 100%.


### 2.3.4 Automated Parameter Identification

This is the result of the final parameter identification for the base model:

| Model Parameter                                              | Optimized Value                                              | Unit      |
| ------------------------------------------------------------ | ------------------------------------------------------------ | --------- |
| `Lipophilicity`                                              | 4.51                                                         | Log Units |
| Basolateral mucosa permeability<br />(``P (interstitial->intracellular)``, ``P (intracellular->interstitial)``) |0.09       | cm/min    |
| `kcat` (CYP3A4)                                              | 204.70                                                       | 1/min     |
| `Dissolution time` (extended release tablet)                 | 286.95                                                       | min       |
| `Dissolution shape` (extended release tablet)                | 0.76                                                         |           |
| `Lag time` (extended release tablet)                         | 18.68                                                        | min       |
| `Tablet time delay factor` (extended release tablet)         | 0.07                                                         |           |
| `Dissolution time` (immediate release tablet)                | 46.50                                                        | min       |
| `Dissolution shape` (immediate release tablet)               | 0.89                                                         |           |