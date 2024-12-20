# PMD-FSP-Ontology
Projekt Material Digital: Ontology for Flame Spray Pyrolysis

This repository serves as a demonstrator for an application ontology based on the PMDco 2.0.7 (https://github.com/materialdigital/core-ontology) for a semantically description of the Flame Spray Pyrolysis (FSP) process to generate tailored nanoparticles. The process of ontologization requires a multistep proceeding and is described elsewhere (-> paper link). It is based on the usage of an Electronic Laboratory Notebook (ELN). To understand these steps, the underlying files can be found in this repo. What is not given here are the microservices used to convert the data from the ELN into SparQL entries due to security reasons (IT infrastructure information is inherently in the code), but their functionality is described in the paper.

## 00_ELN_Template
Template for the eLabFTW ELN for the FSP experiments; this template is closely related to the FSP ontology, i.e. the T-Box.

## 01_query_test
For a test of SparQL queries, five exemplary A-Boxes (Assertion Box) from five individual FSP experiments are given as a Turtle (ttl) file. 

The ELN entries for "Flame 2" are empty because only one single flame was used for the FSP.

## 02_FSP_ontology
This is the T-Box (Terminology Box) of the FSP ontology.
