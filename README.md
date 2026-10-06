# Evaluating Numeracy of Language Models as a Natural Language Inference Task

This repository contains the dataset and resources accompanying the paper:

    Evaluating Numeracy of Language Models as a Natural Language Inference Task
    Rahmad Mahendra, Damiano Spina, Lawrence Cavedon, and Karin Verspoor.
    Findings of the Association for Computational Linguistics: NAACL 2025.

## Overview

Recent advances in large language models (LLMs) have demonstrated strong performance on mathematical problem solving. However, numeracy extends beyond solving arithmetic problems. Language models also need to understand, compare, and interpret numerical information expressed in natural language.

This work introduces a benchmark for evaluating numeracy as a Natural Language Inference (NLI) task. The benchmark evaluates whether language models can correctly reason about numerical information in context and determine the relationship between a premise and a hypothesis.

We focus on three foundational numeracy skills:

    Arithmetic — reasoning about numerical operations and calculations.

    Number comparison — determining relationships between numerical quantities.

    Number normalization — understanding equivalent numerical expressions represented in different forms, such as 3 and three.

## Dataset


The benchmark is designed to distinguish numerical reasoning from general mathematical problem solving by embedding numerical information in natural-language contexts.
## Task Formulation

The dataset consists of NLI-style instances designed to test numeracy capabilities. Each instance contains a premise, a hypothesis, and an NLI label.

The labels represent the semantic relationship between the premise and hypothesis:
    
    entailment — The hypothesis follows from the premise.
    contradiction — The hypothesis conflicts with the premise.
    neutral — The hypothesis cannot be determined from the premise.


## Repository Structure

The repository is organized as follows:

    .
    ├── data/
    │   ├── number_representation_variation/
    │   │   ├── basic_arithmetic/
    │   │   ├── comparative_reasoning/
    │   │   ├── number_with_quantifier/
    │   ├── numeracy_nli/
    │   │   ├── basic_arithmetic/
    │   │   ├── number_comparison
    │   │   ├── number_normalization
    │   └── template_formula/
    ├── README.md
    ├── LICENSE


## Citation

If you use this dataset or benchmark in your research, please cite:

    @inproceedings{mahendra-etal-2025-evaluating,
    title = "Evaluating Numeracy of Language Models as a Natural Language Inference Task",
    author = "Mahendra, Rahmad and
              Spina, Damiano and
              Cavedon, Lawrence and
              Verspoor, Karin",
    editor = "Chiruzzo, Luis and
              Ritter, Alan and
              Wang, Lu",
    booktitle = "Findings of the Association for Computational Linguistics: NAACL 2025",
    month = apr,
    year = "2025",
    address = "Albuquerque, New Mexico",
    publisher = "Association for Computational Linguistics",
    pages = "8351--8376",
    doi = "10.18653/v1/2025.findings-naacl.467",
    url = "https://aclanthology.org/2025.findings-naacl.467/"
}


## License

Please refer to the LICENSE file for the terms under which the dataset and accompanying resources may be used.

If you use this dataset, please cite the paper above.


## Acknowledgements

This work was conducted by researchers from the School of Computing Technologies at RMIT University and the School of Computing and Information Systems at The University of Melbourne.

For questions, issues, or suggestions regarding the dataset, please open an issue in this repository.
