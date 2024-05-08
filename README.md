# NLP LLMs in Health Sciences

## Abstract

In the field of medical research, Clinical Trial Reports play a pivotal role in providing essential information to evaluate patient condition, safety, and the effectiveness of new treatments. However, the sheer volume and complexity of these reports present significant challenges for medical professionals tasked with careful interpretation. Recent advancements in Artificial Intelligence, particularly in Natural Language Processing (NLP), offer promising solutions to these challenges. This project focuses on analyzing summaries of CTRs related to breast cancer treatments.

## Introduction and Problem Statement

State-of-the-art NLP techniques offer promising solutions to these challenges. Advanced models, such as BERT, have shown remarkable capabilities in understanding and processing complex textual data. These models can effectively capture intricate patterns and dependencies within clinical text, enabling comprehensive analysis and information extraction.

Despite these advancements, there remain significant hurdles to overcome. Ensuring the accuracy and consistency of extracted information, particularly in the context of clinical data, remains a key challenge.

This project focuses on analyzing summaries of CTRs related to breast cancer treatments. Each of these Clinical Trial Reports contains essential information including Eligibility criteria, Intervention, Results, and Adverse effects, crucial for informed decision-making. The main task is to perform textual entailment, labeling the given statements either as Entailment or Contradiction based on the veracity of the statements.

The challenge here is to effectively extract and understand important information from CTRs. This is made difficult because these reports often include details about different groups of patients who received different treatments or had different characteristics at the start of the study. Also, it is important to make sure that the information we extract is correct and consistent.

To address these challenges, our project aims to leverage NLP techniques to develop an advanced model capable of comprehensively analyzing CTRs related to breast cancer treatments. Additionally, the model will assess statements generated from the report summaries, determining their truthfulness even when faced with intentional textual modifications.

The ultimate goal of this project is to refine AI's consistency in understanding an extensive amount of clinical data and making logical deductions. This refinement will help Artificial Intelligence become a valuable asset for medical professionals, aiding them in making informed decisions about patient care.

## Repository Contents

This repository contains Jupyter Notebook files for various NLP tasks using Large Language Models (LLMs) in the field of Health Sciences.

### Cloning the Repository

To clone this repository, you can use the following command:


git clone https://github.com/D-Siri/NLP-LLM-s-in-Health-Sciences.git


### Running Jupyter Notebooks

Once you have cloned the repository, navigate to the directory containing the Jupyter Notebook files. You can then run the notebooks using Jupyter Notebook or JupyterLab.

1. First, make sure you have Jupyter Notebook installed. You can install it using pip:
   
pip install notebook

2. Navigate to the directory containing the notebook files
   
3. Launch Jupyter Notebook
   
4. This will open Jupyter Notebook in your default web browser. You can then navigate to the desired notebook file (NLP_Baseline_Bert.ipynb) and click on it to open and run the notebook.

### Notebook Descriptions

- **NLP_Baseline_Bert.ipynb:** Baseline implementation of a BERT model for NLP tasks.
- **NLP_BertLarge.ipynb:** Exploration of a larger BERT model for NLP tasks.
- **NLP_Clinical Bert_Augmentation.ipynb:** Demonstration of augmentation techniques applied to a Clinical BERT model.
- **NLP_Clinical Bert_Neural Classifier.ipynb:** Implementation of a Neural Classifier using a Clinical BERT model.
- **NLP_clinicalbert_Q:A Prompt.ipynb:** Focus on a Q&A prompt approach using a Clinical BERT model.




