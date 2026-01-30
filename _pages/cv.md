---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **M.S. in Data Science**, KTH Royal Institute of Technology & UR1-ISITC, 2020-2022
  * KTH GPA: 4.7/5.0 (A)
  * UR1-ISITC GPA: 15.0/20 (Bien)
  * Key Coursework: Machine Learning (A), Machine Learning II (A), Programming for Data Science (A), Data Mining (A), Cloud for Big Data (A)
  * Locations: Stockholm, Sweden & Rennes, France

* **B.S. in Artificial Intelligence & B.Eng. in Financial Engineering**, University of Electronic Science and Technology of China (UESTC), 2016-2020
  * GPA: 3.62/4.0
  * Key Coursework: Computer Vision and Pattern Recognition (4.0), Distributed Parallel Computing (4.0), Data Mining and Big Data Analysis (4.0), Advanced Programming (4.0), Financial Econometrics (4.0)
  * Location: Chengdu, China

Work Experience
======
* **September 2022 - Present: NLP Research Engineer**
  * Ontology Engineering Group, Universidad Politécnica de Madrid
  * Location: Madrid, Spain
  * Duties include:
    * Developing production-ready RAG pipelines for specialized domains (solar chemistry, ontology engineering)
    * Integrating LLMs with knowledge graphs and structured representations
    * Constructing evaluation frameworks and benchmarks for LLM applications
    * Building graph neural network architectures for software understanding
  * Supervisor: Oscar Corcho

* **March 2022 - September 2022: Research Intern**
  * Ontology Engineering Group, Universidad Politécnica de Madrid
  * Location: Madrid, Spain
  * Project: Software Understanding using Graph Neural Networks
  * Duties included:
    * Constructing datasets of 6,000+ open-source repositories
    * Implementing GNN models for software similarity detection
    * Developing evaluation metrics for graph-based software analysis

* **May 2016 - 2020: Co-Founder & Barber**
  * Lucky Barbershop & Lucky.Inc
  * Location: Chengdu, China
  * Duties included:
    * Introduced barber culture to China and developed first chain barbershop brand
    * Designed product line blending Western barber culture with Chinese aesthetics
    * Developed OAO (Online and Offline) business strategy with international partnerships

Research Projects
======

**SolarChem Project: LLM-Based QA RAG Pipeline** (2023-Present)
* Developed production RAG pipeline for solar chemistry expert review system
* Implemented multiple retrieval strategies (semantic chunking, re-ranking) and RAG methods (NaiveRAG, FactRAG, GraphRAG)
* Constructed benchmark with 500+ expert annotations from 100 academic papers
* Built web interface focusing on explainability and domain expert usability
* Extracted and integrated information from 700+ academic papers

**INESData Project: LLMs for Ontology Engineering** (2022-Present)
* Designed ontology engineering tasks specifically for LLMs (ISWC'24 publication)
* Mapped LLM capabilities to LOT (Learning, Ontology, Text) methodology
* Built comprehensive benchmark including text2triples, triples2ontology, query generation
* Constructed 4 gold-standard ontologies with multi-perspective evaluation metrics
* Focus on semantic consistency and structural knowledge representation

**SoftSim Project: GNN for Software Understanding** (2022-2023)
* Constructed dataset of 6,000+ GitHub repositories in multiple data formats
* Implemented SOTA GNN models (SimGNN, GMN, GCN) for software tasks
* Designed downstream tasks: software similarity, classification
* Defined numerical similarity metrics for quantitative graph learning evaluation
* Explored graph pooling architectures and multi-format representations

Skills
======
* **Programming Languages**: Python 3.x, SQL, CUDA, Shell/Bash
* **ML/DL Frameworks**: PyTorch, TensorFlow, Keras, Scikit-Learn, Transformers
* **Data Science**: NumPy, Pandas, Jupyter, Matplotlib, Seaborn
* **Technologies**: Docker, Unix/Linux, Git, RAG Systems, Knowledge Graphs
* **Specializations**: 
  * Natural Language Processing
  * Large Language Models (LLMs)
  * Graph Neural Networks (GNNs)
  * Retrieval-Augmented Generation (RAG)
  * Ontology Engineering
  * Explainable AI
  * Model Fine-tuning (LoRA, QLoRA)

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Awards & Honors
======
* **National Scholarship**, 2017 & 2018, University of Electronic Science and Technology of China
* **ASC Second Prize**, 2019, Asia Supercomputer Community
* **Excellent Graduate Award**, 2020, University of Electronic Science and Technology of China

Languages
======
* **Chinese**: Native
* **English**: Fluent (Professional working proficiency)
* **Spanish**: Intermediate (Working in Madrid)
