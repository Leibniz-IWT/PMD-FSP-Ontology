# PMD-FSP-Ontology
Projekt Material Digital: Ontology for Flame Spray Pyrolysis

This repository serves as a demonstrator for an application ontology based on the [PMDco 2.0.8](https://github.com/materialdigital/core-ontology) core ontology for a semantically description of the Flame Spray Pyrolysis (FSP) process to generate nanoparticles. The process of ontologization requires a multistep proceeding and is described elsewhere (-> paper link). It is based on the usage of an Electronic Laboratory Notebook (ELN). To understand the required steps for the ontologization, the underlying files can be found in this repo. What is not given here are the microservices used to convert the data from the ELN via the API into SparQL entries due to security reasons (IT infrastructure information is inherently in the code), but their functionality is described in the paper.

## 00_FSP_ontology
This is the T-Box (Terminology Box) of the FSP ontology.

## 01_ELN_Template
Template for the eLabFTW ELN for FSP experiments; this template is closely related to the FSP ontology, see the [T-Box](#02_FSP_ontology).

## 02_query_test_ontodocker
For a test of SparQL queries, five exemplary A-Boxes (Assertion Box) from five individual FSP experiments are given as Turtle (ttl) files. They are related to the ELN entries which are exported as pdf files.

The ELN entries for "Flame 2" are all empty because only one single flame was used for the FSP.

After loading the A-Box files, SparQL queries can be performed. For example, uploading (i.e. inserting) all A-Boxes given here in the 'Triples'-field at the '1: Sample Data' part of the Web page of [Mad Sholten](https://madsholten.github.io/sparql-visualizer/) and inserting the SparQL query given in 'sparql_query.txt' yield the results of the formulated queries, see 'res_query.csv'.


