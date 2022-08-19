# Felodipine-Model
Whole-body PBPK model of felodipine.

<a title="Felodipine" href="/wiki/File:Felodipine_structure.svg"><img width="220" alt="Felodipine structure.svg" src="//upload.wikimedia.org/wikipedia/commons/thumb/4/46/Felodipine_structure.svg/220px-Felodipine_structure.svg.png"></a>


This repository contains:

- a [PK-Sim snapshot (*.json) file](https://docs.open-systems-pharmacology.org/working-with-pk-sim/pk-sim-documentation/importing-exporting-project-data-models#exporting-project-to-snapshot-loading-project-from-snapshot) of the current PBPK model
- static content (e.g. text blocks, *.md files) as inputs for an evaluation plan
- an evaluation plan (evaluation-plan.json) to create an evaluation report using the snapshot and static text blocks to display the performance of the model

**The latest release of the snapshot of the model, the evaluation plan and the static content can be found [here](../../releases/latest).**

**The latest release of the PK-Sim project model file and the respective evaluation report can be found [here](https://github.com/Open-Systems-Pharmacology/OSP-PBPK-Model-Library/releases/latest).**



This felodipine model is intended to be used as victim drug in CYP3A4-mediated drug-drug interactions (DDI).

This whole-body PBPK model of felodipine has been  developed using in particular published pharmacokinetic clinical data by Edgar et al. 1987 [[1](#references)], Bailey et al. 1996 [[2](#references)], Gelal et al. 2005 [[3](#references)], Bailey et al. 2003 [[4](#references)], Goosen 2004 [[5](#references)], Jalava et al. 1997 [[6](#references)], Blychert et al. 1990 [[7](#references)], Lundahl et al. 1998 [[8](#references)], Bailey et al. 1995 [[9](#references)], Aberg et al. 1997 [[10](#references)], Bailey et al. 1993 [[11](#references)], Edgar et al. 1992 [[12](#references)], and Lundahl et al. 1997 [[13](#references)]. 
The model has then been evaluated simulating a large number of clinical studies and comparing with respective observed data. 


## Code of conduct
Everyone interacting in the Open Systems Pharmacology community (codebases, issue trackers, chat rooms, mailing lists etc...) is expected to follow the Open Systems Pharmacology [code of conduct](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODE_OF_CONDUCT.md#contributor-covenant-code-of-conduct).

## Contribution
We encourage contribution to the Open Systems Pharmacology community. Before getting started please read the [contribution guidelines](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CONTRIBUTING.md#ways-to-contribute). If you are contributing code, please be familiar with the [coding standard](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODING_STANDARDS.md#visual-studio-settings).

## License
The model code is distributed under the [GPLv2 License](https://github.com/Open-Systems-Pharmacology/Suite/blob/develop/LICENSE).

## References
[1] [Edgar B, Lundborg P, Regårdh CG. Clinical pharmacokinetics of felodipine. A summary. Drugs. (1987)](https://doi.org/10.2165/00003495-198700343-00005)

[2] [Bailey DG, Bend JR, Arnold JM, Tran LT, Spence JD. Erythromycin-felodipine interaction: magnitude, mechanism, and comparison with grapefruit juice. Clin Pharmacol Ther. (1996)](https://doi.org/10.1016/s0009-9236(96)90163-0)

[3] [Gelal A, Balkan D, Ozzeybek D, Kaplan YC, Gurler S, Guven H, et al. Effect of menthol on the pharmacokinetics and pharmacodynamics of felodipine in healthy subjects. Eur J Clin Pharmacol. (2005)](https://doi.org/10.1007/s00228-004-0847-8)

[4] [Bailey D. Bergamottin, lime juice, and red wine as inhibitors of cytochrome P450 3a4 activity: comparison with grapefruit juice. Clinical Pharmacology & Therapeutics. (2003)](https://doi.org/10.1016/s0009-9236(03)00051-1)

[5] [Goosen TC, Cillie D, Bailey DG, Yu C, He K, Hollenberg PF, et al. Bergamottin contribution to the grapefruit juice-felodipine interaction and disposition in humans. Clin Pharmacol Ther. (2004)](https://doi.org/10.1016/j.clpt.2004.08.019)

[6] [Jalava KM, Olkkola KT, Neuvonen PJ. Itraconazole greatly increases plasma concentrations and effects of felodipine. Clin Pharmacol Ther. (1997)](https://doi.org/10.1016/s0009-9236(97)90191-0)

[7] [Blychert E, Wingstrand K, Edgar B, Lidman K. Plasma concentration profiles and antihypertensive effect of conventional and extended-release felodipine tablets. Br J Clin Pharmacol. (1990)](https://doi.org/10.1111/j.1365-2125.1990.tb03600.x)

[8] [Lundahl JU, Regårdh CG, Edgar B, Johnsson G. The interaction effect of grapefruit juice is maximal after the first glass. Eur J Clin Pharmacol. (1998)](https://doi.org/10.1007/s002280050424)

[9] [Bailey DG, Arnold JM, Bend JR, Tran LT, Spence JD. Grapefruit juice-felodipine interaction: reproducibility and characterization with the extended release drug formulation. Br J Clin Pharmacol. (1995)](http://www.ncbi.nlm.nih.gov/pmc/articles/pmc1365172/)

[10] [Aberg J, Abrahamsson B, Grind M, Nyberg G, Olofsson B. Bioequivalence, pharmacokinetic and pharmacodynamic response to combined extended release formulations of felodipine and metoprolol in healthy volunteers. Eur J Clin Pharmacol. (1997)](https://doi.org/10.1007/s002280050321)

[11] [Bailey DG, Arnold JM, Munoz C, Spence JD. Grapefruit juice--felodipine interaction: mechanism, predictability, and effect of naringin. Clin Pharmacol Ther. (1993)](https://doi.org/10.1038/clpt.1993.84)

[12] [Edgar B, Bailey D, Bergstrand R, Johnsson G, Regårdh CG. Acute effects of drinking grapefruit juice on the pharmacokinetics and dynamics of felodipine--and its potential clinical relevance. Eur J Clin Pharmacol. (1992)](https://doi.org/10.1007/bf00266354)

[13] [Lundahl J, Regårdh CG, Edgar B, Johnsson G. Effects of grapefruit juice ingestion--pharmacokinetics and haemodynamics of intravenously and orally administered felodipine in healthy men. Eur J Clin Pharmacol. (1997)](https://doi.org/10.1007/s002280050263)





