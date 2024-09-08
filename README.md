# Data Schema and Dataset (Semantics4MPC) 

This is the companion code of the information model proposed in the manuscript entitled with **"Enabling scalable MPC design for building HVAC systems using semantic data modelling"**, under submission to the journal of [Automation in Construction](https://www.sciencedirect.com/journal/automation-in-construction). Preprinit is available [here](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4875326).

## Purpose of the project

The proposed data schema is a research prototype, which is built upon openly-available ontologies, in order to support more scalable Model Predictive Control (MPC) algorithm configuration and deployment. The data schema is developed for and published as part of the paper publication. The designed schema is populated with one real office building data located in the Bosch Research Campus in Renningen, Germany. 

## Overview
[Extensions](./Extensions/): the proposed (extended) schema for MPC algorithm, building topology, flow energy system and properties, based on the openly available ontologies.

[Alignment](./Alignment/): the proposed alignment ontologies between [Flow System Ontology](https://github.com/alikucukavci/FSO/)(FSO) and [Distribution Element Ontology](https://pi.pauwel.be/voc/distributionelement/index-en.html)(MEP).

[Dependency](./Dependency/): the dependent openly available ontologies with specific version during the development.

[SHACL](./SHACL/):the 29 SHACL constraints for components in the heating system and ventilation system respectively.

[Dataset](./Dataset/): the Resource-Description-Framework (RDF) graph of the studied Bosch office building in Turtle format.

[SPARQL](./Sparql/): the SPARQL queries used in the study, which includes:
- [Query for thermal and geometric information](./Sparql/Building_and_Geometry.sparql)
- [Query for the data points and properties related to the dampers](./Sparql/Damper.sparql)
- [Query for the data points and properties related to the reheat coil](./Sparql/ReheatCoil.sparql)
- [Query for data points and design properties of the radiator](./Sparql/Radiator.sparql)
- [Query for the deployed MPC algorithm](./Sparql/Control.sparql)
- [Adding the supply and return air temperature as the control input and outputs](./Sparql//Supply_Return_Air_Temp.sparql)

## License

This work (the proposed extension [Schema](./Extensions/), the sample [Dataset](./Dataset/), the [alignments](./Alignment/) made to the ontologies used in the research project, the designed [SHACL shapes](./SHACL/) as well as the sample [SPARQL queries](./Sparql/)) is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
See the
[LICENSE](LICENSE) file for details.

