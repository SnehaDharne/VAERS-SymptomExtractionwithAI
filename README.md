# VAERS Adverse Event Analysis: A Hybrid Approach with LLMs and Statistical Modeling

This repository contains code and analysis for a project investigating adverse events following vaccination using the Vaccine Adverse Event Reporting System (VAERS) dataset. This project explores a novel hybrid approach, combining the power of Large Language Models (LLMs) like Gemini 1.5 Flash for symptom extraction with traditional statistical methods for temporal and associative analysis. The goal is to enhance the accuracy and scalability of vaccine safety monitoring by leveraging the strengths of both LLMs and statistical models.

## Key Features and Contributions:

* **Hybrid Model:** A framework integrating LLMs for unstructured text processing with statistical models for temporal and associative analysis of VAERS symptom data.
* **Symptom Extraction Comparison:** Evaluation and comparison of Named Entity Recognition (NER) based methods and LLM-based approaches for symptom extraction, focusing on accuracy, scalability, and computational efficiency.
* **Enhanced Data Processing:** Addressing challenges in handling medical abbreviations and synonyms through preprocessing techniques and custom dictionaries.
* **Comprehensive Analysis:** Bridging research gaps by combining LLMs' text understanding capabilities with statistical models' robustness for association rule mining.
* **Temporal Analysis:** Investigating symptom progression over time using Kendall's Tau, Longest Common Subsequence (LCS), and Dynamic Time Warping (DTW).
* **Associative Analysis:** Uncovering patterns of co-occurring symptoms using the Apriori algorithm and comparing results against LLM-based pattern discovery.
* **Comparative Evaluation:** Rigorous evaluation of NER and LLM-based approaches against a manually annotated baseline and the VAERSSYMPTOMS dataset.

## Project Structure:

The repository includes:

* **Data:** Preprocessed VAERS data used in the analysis.
* **Notebooks:** Jupyter notebooks documenting the analysis process and results.
* **Report:** Visualizations and reports summarizing the findings.
* **Documentation:** This README file providing an overview of the project.

## Methodology:

The project follows a structured approach:

1. **Data Preprocessing:** Cleaning and preparing the VAERS dataset, including handling medical abbreviations and synonyms.
2. **Symptom Extraction:** Comparing NER-based and LLM-based methods for extracting symptoms from VAERS narratives.
3. **Temporal Analysis:** Analyzing symptom progression over time using statistical methods and comparing NER and LLM results.
4. **Associative Analysis:** Identifying co-occurring symptoms using the Apriori algorithm and comparing NER and LLM results against a benchmark dataset.
5. **Evaluation:** Rigorous evaluation of both approaches using established metrics.

## Results and Conclusions:

The project demonstrates the potential of LLMs to improve symptom extraction and enhance the analysis of VAERS data. The hybrid approach offers a promising direction for vaccine safety research, combining the strengths of LLMs and statistical methods. The repository provides detailed results and insights into the comparative performance of NER and LLM-based approaches.

## Dependencies:
* Python 3.x
* spaCy
* MedSpaCy
* scikit-learn
* pandas
* numpy
