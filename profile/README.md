# Welcome to the EMMO Framework Repository
<p align="center">
  <a href="https://github.com/emmo-repo/EMMO">
    <img src="https://github.com/emmo-repo/EMMO/raw/master/doc/emmo-logo.png" alt="EMMO logo" width="120">
  </a>
</p>


The **EMMO** is the results of a **multidisciplinary effort** to develop a standard representational framework that is consistent with **scientific principles and methodologies**. It merges the efforts of physicists, engineers, materials scientists, analytical philosophers, information and communication scientists. 

The EMMO provides **framework for knowledge capture and interoperability** that is rooted on **applied sciences principles**. However, it's foundational approach makes it suitable for the usage in many other fields and qualifies it as a **top-level ontology**.

## The EMMO

The EMMO GitHub page provides the repositories hosting the **EMMO ontology** and its **alternative versions** that constitute the framework. More specifically it provides repositories for the following EMMO versions:
1. The **[EMMO](https://github.com/emmo-repo/EMMO)**, the main reference ontology repository, hosting the all the EMMO ontology modules from the top-level (i.e., mereocausality) down to the mid-level (i.e., the disciplines)

2. The **[HUME](https://emmo-repo.github.io/hume/hume.ttl)** (aka the HUMan readable EMMO), a full version of the EMMO where the UUID-based IRIs are replaced with human readable IRIs taken from the *skos:prefLabel* field. The HUME is generated automatically after every release of the EMMO.

3. The **[ELITE](https://github.com/emmo-repo/ELITE)** ontology: a subset of HUME that provides an entry-level EMMO based ontological framework, that can be easily expanded to the full HUME or EMMO in case of need.

You can find an introduction to the EMMO conceptualisation with examples in the [EMMO Wiki](https://github.com/emmo-repo/EMMO/wiki).

## Domain Ontologies

This GitHub page hosts also hosts all the official **EMMO domain ontologies** repositories, named using the following convention **domain-*[domain ontology name]***. 

If you want to create your domain ontology based on the EMMO, please follow the [Guidelines for EMMO Domain Ontologies Development](https://github.com/emmo-repo/.github/wiki/DomainOntologiesDevelopersGuidelines).

## Tools

**[EMMOntoPy](https://github.com/emmo-repo/EMMOntoPy)** is a Python package based on [Owlready2](https://pypi.org/project/Owlready2/), which provides a natural and intuitive representation of ontologies in Python. EMMOntoPy extends Owlready2 and adds additional functionality, like accessing entities by label, reasoning with FaCT++ and parsing logical expressions in Manchester syntax.  

EMMOntoPy was originally developed to work effectively with the EMMO and EMMO-based domain ontologies, but is usable with any other OWL ontology.

## Publications

A publication list of EMMO-related resources maintained by EMMC is availble [here](https://emmc.eu/emmo/).

