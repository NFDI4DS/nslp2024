---
layout: default
title: Shared tasks
nav_order: 5
---

# Shared tasks

Two shared tasks are organised at the NSLP workshop. Both include several subtasks. Participants can sign up for one or more (sub-)tasks. Automated evaluations of submitted systems are done through the Codalab platform.

**Task 1. FoRC: Field of Research Classification of Scholarly Publications**

A core application of NSLP is classifying scientific articles for their respective field of research (FoR). While some repositories already use a classification system, these are often limited either in terms of the used taxonomy or in terms of the classification model. The Field of Research Classification (FoRC) shared task involves two subtasks.

**Subtask I: Single-label multi-class FoR classification of general scholarly papers.** Participants will develop classifiers that take (a subset of) the available metadata of articles as input and output one of 123 predefined hierarchical classes from the ORKG taxonomy of research fields. Classifiers will be trained and tested using a dataset of 59,500 English scientific papers constructed by fetching metadata from ORKG (CC BY-SA 4.0) and arXiv (CC0 1.0). The following metadata fields are available: title, authors, abstract, DOI, URL to the full paper (if available and based on license), publisher, publication month, and year. Systems will be evaluated using accuracy as well as macro, micro, and weighted scores of recall, precision, and F1. 

**Subtask II: Fine-grained multi-label classification of Computational Linguistics scholarly papers.** Participants will design classification systems based on a corpus of ca.~1500 English scholarly articles in Computational Linguistics (CL), collected from the ACL Anthology (CC BY 4.0) and annotated according to a novel hierarchical taxonomy consisting of 170 core CL (sub-)topics. Metadata fields include ACL Anthology ID, title, abstract, author(s), URL to the full text, publisher, publication year and month, proceedings title, DOI, and venue. As a multi-label hierarchical classification problem, this subtask will be evaluated by computing coverage error, label ranking average precision, and ranking loss scores.

**Organisers**

* Georg Rehm (Deutsches Forschungszentrum für Künstliche Intelligenz, Germany)
* Ekaterina Borisova (Deutsches Forschungszentrum für Künstliche Intelligenz, Germany)
* Raia Abu Ahmad (Deutsches Forschungszentrum für Künstliche Intelligenz, Germany)

**Contact**


**Task 2. SOMD: Software Mention Detection in Scholarly Publications**

Given the scale and heterogeneity of software citations, robust methods are required to detect and disambiguate mentions of software and related metadata. The Software Mention Detection in Scholarly Publications (SOMD) task will utilise the SoMeSci corpus. We produced novel test data with software mentions and related metadata in articles from multiple research fields. Four subtasks are planned:

**Subtask I: Software mention recognition.** Software mentions shall be recognised from individual sentences. At the same time, software mentions shall be classified according to their mention type, e.g., mention, usage, or creation and the software type, e.g., application, programming environment, or package. and plugin or package. **Subtask II: Additional information.** For each software mention, additional information according to the SoMeSci schema shall be recognised from the sentence. **Subtask III: Relation classification.** For each software mention, relations to other recognised entities shall be classified. This includes versions and developers, but also URLs or host applications for plugins. The evaluation will be based on exact matches rather than partial matches. FScore will be used as a performance metric for all subtasks.

**Organisers**

* Stefan Dietze (GESIS Leibniz Institut für Sozialwissenschaften, Cologne & Heinrich-Heine-University Düsseldorf, Germany)
* Frank Krüger (Wismar University of Applied Sciences, Germany)
* Saurav Karmarkar (GESIS Leibniz Institut für Sozialwissenschaften, Cologne Germany)

**Contact**

**Important dates (applicable to both shared tasks)**

* Release of training data: **January 2nd, 2024**
* Release of testing data: **January 10th, 2024**
* Deadline for system submissions: **February 22nd, 2024**
* Paper submission deadline: **March 7, 2024**
* Notification of acceptance: **April 4, 2024**
* Camera-ready submission: **April 18, 2024**
* Workshop: **Either May 26 or May 27, 2024 (tbc)**
