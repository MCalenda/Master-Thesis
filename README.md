<div align = "center">

[![GitHub contributors](https://img.shields.io/github/contributors/MCalenda/Q-DELOREAN?style=for-the-badge)](https://GitHub.com/MCalenda/Q-DELOREAN/graphs/contributors)
[![GitHub issues](https://img.shields.io/github/issues/MCalenda/Q-DELOREAN?style=for-the-badge)](https://GitHub.com/MCalenda/Q-DELOREAN/issues)
[![GitHub forks](https://img.shields.io/github/forks/MCalenda/Q-DELOREAN?style=for-the-badge)](https://GitHub.com/MCalenda/Q-DELOREAN/fork)

# Exploring the Potential of Quantum NLP for Non-Functional Requirements Classification

</div>

## Introduction

Repository of the research study conducted for the *Software Engineering for Artificial Intelligence* course 2022-23 and for my Master Thesis.

Quantum Natural Language Processing (QNLP) is an emerging field that leverages quantum computing principles to process and analyze natural language text. This thesis delves into the potential of QNLP within the domain of Requirements Engineering, specifically focusing on the classification of non-functional requirements (NFRs). In our approach, we leverage the DisCoCat framework to capture both distributional and compositional aspects of meaning. The former suggests that words with similar meanings statistically exhibit similar distributions in text, while the latter explains the sentence meaning through the combination of the word composing it according to grammatical rules.

The QNLP pipeline involves preprocessing the requirements description, parsing each sentence into string diagram using the DisCoCat framework, and parameterizing the diagrams as tensor networks or quantum circuits respectively for classical and quantum experiments.

This study aims to assess the classification capabilities of the quantum approach and the comparison with shallow ML models. Furthermore, the study aims to explore the comparison with other compositional models that are not grammar-based in order to assess the relevance of grammar in this context.

The empirical study conducted demonstrates the effectiveness of the DisCoCat framework in accurately classifying NFRs, showing that the grammar was an added value in this particular scenario. The comparison with classical language models reveals that quantum approach outperforms traditional approaches such as TF-IDF Naive Bayes, while exhibiting similarities to Word2Vec, albeit with fewer parameters.

Overall, this research contributes to the understanding of QNLP's applicability in real-world scenarios and lays the foundation for future advancements in the field.

## Instructions

No installation is required, just open with Google Colab the notebooks in the `/notebooks` folder and everything will be ready to run experiments in a reproducible environment.

## Programming languages and technologies

<div align= "center">

![Python Badge](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff&style=for-the-badge)

![Lambeq Badge](https://img.shields.io/badge/Lambeq-2980B9?&style=for-the-badge)
![PyTorch Badge](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=fff&style=for-the-badge)

[![Dataset](https://img.shields.io/badge/Dataset%20-Promise-critical?style=for-the-badge)](https://zenodo.org/record/3309582)

</div>

## License

Distributed under the MIT License. See `LICENSE` for more information.
