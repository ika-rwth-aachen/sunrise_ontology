# SUNRISE Ontology

An ontology defining Operational Design Domain (ODD) and scenario-related concepts within the SUNRISE project, published via GitHub Pages.

**Ontology IRI:** `https://ika-rwth-aachen.github.io/sunrise_ontology/ontology`  
**Namespace:** `https://ika-rwth-aachen.github.io/sunrise_ontology/ontology#`  
**Latest Version IRI:** `https://ika-rwth-aachen.github.io/sunrise_ontology/ontology/1.0`

---

## Table of Contents
- [Overview](#overview)
- [How to use](#how-to-use)
- [Serializations](#serializations)
- [Versioning](#versioning)
- [Citing](#citing)
- [Project structure](#project-structure)
- [License](#license)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)

---

> [!IMPORTANT]
> The project is open-sourced and maintained by the [**Institute for Automotive Engineering (ika) at RWTH Aachen University**](https://www.ika.rwth-aachen.de/).
> We cover a wide variety of research topics within our [*Vehicle Intelligence & Automated Driving*](https://www.ika.rwth-aachen.de/en/competences/fields-of-research/vehicle-intelligence-automated-driving.html) domain.
> If you would like to learn more about how we can support your automated driving or robotics efforts, feel free to reach out to us!
> :email: ***opensource@ika.rwth-aachen.de***

## Overview
The SUNRISE Ontology formalizes key concepts and relationships related to ODDs and scenarios within the SUNRISE project. It is aligned with the taxonomies defined in ISO 34503 and ISO 34504, ensuring compatibility with international standards for scenario-based testing and verification.

The ontology models dynamic entities, environmental conditions, and scenery elements along with their respective attributes. It also captures exposure metrics and scenario metadata, providing a structured foundation for representing and exchanging information in simulation and testing contexts.

- **Ontology IRI:** <https://ika-rwth-aachen.github.io/sunrise_ontology/ontology>
- **Namespace:** <https://ika-rwth-aachen.github.io/sunrise_ontology/ontology#>

## How to use

### Import in Protégé (or any OWL/RDF tool)
- **Via IRI:** `https://ika-rwth-aachen.github.io/sunrise_ontology/ontology`
- **Or download a file** from [docs/](./docs/) and open locally.

### Programmatic use (Python / rdflib)
```python
from rdflib import Graph
G = Graph().parse("https://ika-rwth-aachen.github.io/sunrise_ontology/ontology.ttl", format="turtle")
```

---

## Serializations
- **Turtle:** [docs/ontology.ttl](./docs/ontology.ttl)
- **RDF/XML:** [docs/ontology.rdf](./docs/ontology.rdf)
- **JSON-LD:** [docs/ontology.jsonld](./docs/ontology.jsonld)

> Note: GitHub Pages does not perform HTTP content negotiation. Separate files are provided per format.

---

## Versioning
- **Latest Ontology IRI:** `https://ika-rwth-aachen.github.io/sunrise_ontology/ontology`
- **Latest Version IRI:** `https://ika-rwth-aachen.github.io/sunrise_ontology/ontology/1.0`

Archived versions live under [`docs/versions/`](./docs/versions/):

- **1.0** — 2025-10-16  
  - [TTL](./docs/versions/1.0/ontology.ttl) • [RDF/XML](./docs/versions/1.0/ontology.rdf) • [JSON-LD](./docs/versions/1.0/ontology.jsonld)

> When releasing a new version, update `owl:versionIRI` and `owl:versionInfo` in the ontology header, regenerate all serializations, and copy them to a new folder under `docs/versions/`.

---

## Citing
If you use this ontology, please cite the following project deliverable:

> Beckmann, J., Zhang, X., de Gelder, E., van Hassel, E., Nieto, M., Ben Nejma, G., & Grabowski, M. (2025).  
> **D5.2 – Harmonised descriptions for content of CCAM safety assessment data framework.**  
> *SUNRISE – Safety assUraNce fRamework for connected, automated mobIlity SystEms.*  
> Horizon Europe Research and Innovation Action, Grant Agreement No. 101069573.

---

## Project structure
```
docs/
├─ ontology.ttl         # Latest Turtle
├─ ontology.rdf         # Latest RDF/XML
├─ ontology.jsonld      # Latest JSON-LD
├─ index.html           # Human-readable landing page
└─ versions/
   └─ 1.0/
      ├─ ontology.ttl
      ├─ ontology.rdf
      └─ ontology.jsonld
```

---

## License
This ontology is licensed under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) license.

Developed within the **SUNRISE Project**, funded by the European Union under grant agreement no. 101069573.

---

## Contact
Maintainer: <jobst.beckmann@ika.rwth-aachen.de>  
GitHub: <https://github.com/ika-rwth-aachen/sunrise_ontology>


## Acknowledgements

This package is developed as part of the [SUNRISE project](https://https://ccam-sunrise-project.eu/).

<img src="docs/media/sunrise_logo.jpg" alt="SUNRISE Logo" width="400"/><br/>

Funded by the European Union. Views and opinions expressed are however those of the author(s) only and do not necessarily reflect those of the European Union or European Climate, Infrastructure and Environment Executive Agency (CINEA). Neither the European Union nor the granting authority can be held responsible for them. 

<img src="docs/media/eu_logo.png" alt="EU Flag" width="400"/><br/>

