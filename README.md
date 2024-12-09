# BeanCounter: A low-toxicity, large-scale, and open dataset of business-oriented text
<dic align="center">
[**Data**]()&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**Paper**]()
</div>

## What is BeanCounter?
BeanCounter is a public dataset consisting of more than 159B tokens extracted from businesses’ disclosures. These disclosures are originally published on the United States Securities and Exchange Commissions's (SEC) Electronic Data Gathering and Retrieval (EDGAR) system. To our knowledge, this is one of the largest datasets of business-oriented text. 

## Datasheet
Please see Datasheet.pdf for detailed information on dataset composition, collection process, distribution. maintenance etc.

## Supporting Datasets
This directory most contain datasets produced from the main BeanCounter dataset as a result of content analysis, pronoun prevalence, demographic descriptor prevalence and toxicity of content surrounding demographic descriptors. 

## Tables & plots
All tables and plots produced in the paper can be reproduced in the BeanCounter_tables_and_plots.ipynb notebook. 

## Toxicity and demographic analysis:
All programs responsible for producing analysis for demographic prevalence and toxicity analysis of text surrounding a demographic descriptor can be found in toxicity_and_demographic_analysis.ipynb.

## Model evaluation
Each task used for model evaluation is included as a separate notebook:
- Fin NER
- Financial Phrasebank
- RealToxicityPrompts
- SafeNLP
- Huggingface leaderboard (general LLM evaluations)

These tasks can be configured to evaluate various models in the respective notebooks. 

## Continually pretrained models
We continually pretrained Pythia-1.4B and Phi-1.5 on BeanCounter and the resulting models are in this directory. 

## Citing this work
'''text

'''
