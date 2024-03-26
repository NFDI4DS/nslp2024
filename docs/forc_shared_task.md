---
layout: default
title: FoRC shared task
nav_order: 5
---

# FoRC: Field of Research Classification of Scholarly Publications

A core application of NSLP is classifying scientific articles for their respective field of research (FoR). While some repositories already use a classification system, these are often limited either in terms of the used taxonomy or in terms of the classification model. The Field of Research Classification (FoRC) shared task involves two subtasks. Participants can sign up for **one or both** subtasks. Automated evaluations of submitted systems are done through the Codalab platform.

**[Subtask I: Single-label multi-class FoR classification of general scholarly papers.](https://codalab.lisn.upsaclay.fr/competitions/16684)** Participants will develop classifiers that take (a subset of) the available metadata of articles as input and output one of 123 predefined hierarchical classes from the ORKG taxonomy of research fields. Classifiers will be trained and tested using a dataset of 59,500 English scientific papers constructed by fetching metadata from ORKG (CC BY-SA 4.0) and arXiv (CC0 1.0). The following metadata fields are available: title, authors, abstract, DOI, URL to the full paper (if available and based on license), publisher, publication month, and year. Systems will be evaluated using accuracy as well as macro, micro, and weighted scores of recall, precision, and F1. 

**[Subtask II: Fine-grained multi-label classification of Computational Linguistics scholarly papers.](https://codalab.lisn.upsaclay.fr/competitions/16712)** Participants will design classification systems based on a corpus of ca.~1500 English scholarly articles in Computational Linguistics (CL), collected from the ACL Anthology (CC BY 4.0) and annotated according to a novel hierarchical taxonomy consisting of 170 core CL (sub-)topics. Metadata fields include ACL Anthology ID, title, abstract, author(s), URL to the full text, publisher, publication year and month, proceedings title, DOI, and venue. As a multi-label hierarchical classification problem, this subtask will be evaluated by computing micro and macro precison, recall, F1-score.

**Organisers**

* Georg Rehm (Deutsches Forschungszentrum für Künstliche Intelligenz, Germany)
* Ekaterina Borisova (Deutsches Forschungszentrum für Künstliche Intelligenz, Germany)
* Raia Abu Ahmad (Deutsches Forschungszentrum für Künstliche Intelligenz, Germany)

**Contact**

* georg.rehm@dfki.de
* ekaterina.borisova@dfki.de
* raia.abu_ahmad@dfki.de

**Important dates**

* Release of training data: **January 2, 2024**
* Release of testing data: **January 10, 2024**
* Deadline for system submissions: ~~**February 22, 2024**~~ **February 29, 2024**
* Paper submission deadline: ~~**March 7, 2024**~~ **March 14, 2024**
* Notification of acceptance: **April 4, 2024**
* Camera-ready submission: **April 18, 2024**
* Workshop: **<span style="color: red;">May 27 2024</span> (date confirmed)**


