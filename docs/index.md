---
layout: project
title: "Adapting Code LLMs to Domain-specific Languages via Synthethic Instruction Generation and Reinforcement Learning with AI Feedback in Low-resource Settings"
project:
  authors:
    - name: "Vedad Misirlic"
      url: "https://scholar.google.com/citations?user=aPbffSMAAAAJ&hl=en"
    - name: "Kevin Innerebner"
      url: "https://tugraz.elsevierpure.com/en/persons/kevin-innerebner/"
    - name: "Gerald Stieglbauer"
      url: "https://orcid.org/0009-0001-4367-2718"
    - name: "Elisabeth Lex"
      url: "https://elisabethlex.info/"
  institution: "Graz University of Technology and AVL List GmbH"
  conference: "CIKM '26"

  links:
    - label: Proceedings
      icon: ai ai-acm
      url: "https://doi.org/10.1145/3799682.3839250"
    - label: Paper
      icon: fas fa-file-pdf
      url: "https://dl.acm.org/doi/pdf/10.1145/3799682.3839250"

  abstract: "Large Language Models (LLMs) have significantly advanced automatic code generation in mainstream, high-resource, general-purpose programming languages. These models are trained on large instruction-code datasets with executable test environments, which can benchmark the performance of the outputs. However, they typically underperform on low-resource, proprietary Domain Specific Languages (DSLs) due to limited training data. In this work, we introduce a fully automated, two-stage training pipeline for adapting coding LLMs to low-resource and proprietary DSL scenarios. Stage 1 performs supervised fine-tuning (SFT) using multi granular instructions synthesized directly from raw code and comments. Stage 2 conducts Reinforcement Learning with AI Feedback (RLAIF) by generating new instructions, and subsequently Direct Preference Optimization (DPO) by choosing a preferred output. We evaluate our approach using parser success, similarity and fidelity metrics, complemented with walkthrough studies. Our results suggest that this fully automated, two-stage pipeline can enable effective adaptation of LLMs to low-resource and proprietary DSL settings under realistic data and evaluation constraints."
  bibtex: |
    @inproceedings{misirlic2026adapting,
      author = {Misirlic, Vedad and Innerebner, Kevin and Stieglbauer, Gerald and Lex, Elisabeth},
      title = {Adapting Code {LLMs} to Domain-specific Languages via Synthethic Instruction Generation and Reinforcement Learning with {AI} Feedback in Low-resource Settings},
      booktitle = {Proceedings of the 35th {ACM} International Conference on Information and Knowledge Management},
      series = {CIKM '26},
      year = {2026},
      address = {Rome, Italy},
      publisher = {ACM},
      doi = {10.1145/3799682.3839250},
      url = {https://doi.org/10.1145/3799682.3839250},
      isbn = {979-8-4007-2539-5},
      pages = {9481--9483},
      numpages = {3}
    }
---
