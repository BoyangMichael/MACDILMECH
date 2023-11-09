# MACDILMECH
Kinetic mechanisms for the combustion of toluene reference fuel with ethanol addition (TRFE). Funded by the ANR project MACDIL [ANR-15-CE22-0014](https://anr.fr/Projet-ANR-15-CE22-0014).


## Kinetic Details
Details of the mechanism is described in the main body and supplementary materials of [the following journal article](https://doi.org/10.1016/j.fuel.2022.124682).

```
Boyang Xu, Pascal Dievart, Mickael Matrat, Julian Garrec, Laurent Catoire.
An updated empirical correlation formalism for laminar flame speeds: Application to a TRFE gasoline surrogate in highly diluted conditions. 
Fuel 324 (2022): 124682.
https://doi.org/10.1016/j.fuel.2022.124682
```


## Files
This repository contains the following files in CHEMKIN format.

| File                   | Description   | 
| ---------------------- | ------------- |
| `MACDIL.chem`          | The MACDIL mechanism (593 species and 3698 reactions). It is reduced from the detailed model `MACDIL-detailed.chem`. Reduction procedure described in [this paper](https://doi.org/10.1016/j.fuel.2022.124682). |
| `MACDIL.therm`         | Thermodynamic database |
| `MACDIL.tran`          | Transport database |
| `MACDIL-detailed.chem` | The detailed mechanism (2339 species and 9440 reactions). |
| `MACDIL-syngas.chem`   | A detailed mechanism for syngas (H2/CO) combustion. |



## How to cite
Please cite the following article, whose bibtex entry is provided [here](citation.bib).

```
Boyang Xu, Pascal Dievart, Mickael Matrat, Julian Garrec, Laurent Catoire. An updated empirical correlation formalism for laminar flame speeds: Application to a TRFE gasoline surrogate in highly diluted conditions. Fuel 324 (2022): 124682. https://doi.org/10.1016/j.fuel.2022.124682
```
