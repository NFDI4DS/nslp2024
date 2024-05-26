---
layout: default
title: SOMD shared task
nav_order: 6
---

# SOMD: Software Mention Detection in Scholarly Publications

Software are important parts of the scientific process and should therefore recognized as first class citizen of research.
Research Knowledge Graphs have recently been adopted to provide bibliographic data at scale that could be populated by automatic extraction of software mentions.
Given the scale and heterogeneity of software citations, robust methods are required to detect and disambiguate mentions of software and related metadata. 
The **SO**ftware **M**ention **D**etection in Scholarly Publications (SOMD) task will utilise the [SoMeSci](https://data.gesis.org/somesci/) - Software mentions in Science - corpus. 
Participants can sign up for **one or more** subtasks. Automated evaluations of submitted systems are done through the Codalab platform.

**[Subtask I: Software mention recognition.](https://codalab.lisn.upsaclay.fr/competitions/16935)** Software mentions shall be recognised from individual sentences. At the same time, software mentions shall be classified according to their mention type, e.g., mention, usage, or creation and the software type, e.g., application, programming environment, or package.
Participants will develop classifiers that take individual sentences from the different subsets of SoMeSci and output mentions of software further classified into their type of software and mention.
Submissions will be evaluated by F1-Score based on exact matches.

**[Subtask II: Additional information.](https://codalab.lisn.upsaclay.fr/competitions/16936)** For each software mention, additional information according to the SoMeSci schema shall be recognised from the sentence. 
This includes information such as version, URL, and developer.
Participants will develop classifiers that take sentences with software mentions and identify all additional information within the sentence.
As in Subtask I, submissions will be evaluated by F1-Score based on exact matches.

**[Subtask III: Relation classification.](https://codalab.lisn.upsaclay.fr/competitions/16937)** For each software mention, relations to other recognised entities shall be classified. This includes versions and developers, but also URLs or host applications for plugins. The evaluation will be based on exact matches rather than partial matches. F1-Score will be used as a performance metric for all subtasks.


**Organisers**

* Stefan Dietze (GESIS Leibniz Institut für Sozialwissenschaften, Cologne & Heinrich-Heine-University Düsseldorf, Germany)
* Frank Krüger (Wismar University of Applied Sciences, Germany)
* Saurav Karmarkar (GESIS Leibniz Institut für Sozialwissenschaften, Cologne Germany)

**Contact**

* stefan.dietze@gesis.org
* frank.krueger@hs-wismar.de
* saurav.karmakar@gesis.org

**Important dates**

* Release of training and test data: **January 10, 2024**
* Deadline for system submissions: ~~**February 22, 2024**~~ **February 29, 2024**
* Paper submission deadline: ~~**March 7, 2024**~~ **March 14, 2024**
* Notification of acceptance: **April 4, 2024**
* Camera-ready submission: **April 18, 2024**
* Workshop: **<span>May 27 2024</span> (date confirmed)**
