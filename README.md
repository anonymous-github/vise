# Ontology-driven Event Type Classification in Images: Supplemental Material

This repository contains **supplemental material** for the **WACV 2021 submission 578**. 

Detailed information on the sampling strategy to gather event images, statistics for the training and testing datasets presented in Section 3.3, and results using different inference strategies (Section 4.2.3) are available in the [sub578_supplemental.pdf](sub578_supplemental.pdf). 

We also provide different versions of the *Visual Event Ontologies (VisE-O)* and the *Ontologies* of the benchmark datasets.

**USAGE:** After opening an *Ontology*, the *Leaf Event Nodes* (blue), *Branch Event Nodes* (orange), and *Root Node* (yellow) as well as their *Relations* are displayed. By clicking on a specific *Event Node* additional information such as the *Wikidata ID* and related child (*Incoming*) and parent (*Outgoing*) nodes are shown. In addition, the search bar can be used to directly access a specific *Event Node*.


## VisE-O: Visual Event Ontology

In Section 3.2 of the paper, we have presented several methods to create an *Ontology* for newsworthy event types. Statistics are presented in Table 1 of the paper. Different version of the *Ontology* can be explored using the following links:
- **Initial Ontology** (result of Section 3.2.2): [link](https://anonymous-github.github.io/VisE-O_initial/index.html)
- **Disambiguated Ontology** (result of Section 3.2.3): [link](https://anonymous-github.github.io/VisE-O_disambiguated/index.html)
- **Refined Ontology** (result of Section 3.2.4): [link](https://anonymous-github.github.io/VisE-O_refined/index.html)


## Benchmark Ontologies

In order to evaluate the presented ontology-diven approach on other benchmark datasets, we have manually linked classes of the *Web Images for Event Recognition (WIDER)*, *Social Event Dataset (SocEID)*, and the *Rare Event Dataset (RED)* to the *Wikidata* knowledge base according to Section 5.3.3. The resulting *Ontologies* for these datasets can be explored here:
- **WIDER Ontology**: [link](https://anonymous-github.github.io/WIDER/index.html)
- **SocEID Ontology**: [link](https://anonymous-github.github.io/SocEID/index.html)
- **RED Ontology**: [link](https://anonymous-github.github.io/RED/index.html)